### 1. **RELRO: Partial RELRO**

####  什么是 GOT？

程序调用外部函数（如 `printf`, `puts`）时，会通过 **GOT 表（Global Offset Table）** 查找真实地址。GOT 表在程序运行时是可以被修改的（为了支持动态链接）。

####  Partial RELRO 的问题：

- 程序启动后，**GOT 表仍然可写**。
- 如果你能**覆盖 GOT 表中的某个函数指针**（比如把 `puts` 的地址改成 `system`），下次调用 `puts("hello")` 就会变成 `system("hello")`！

####  CTF 利用思路：

- 常见技巧：

  GOT hijacking

  - 例如：你发现程序最后会调用 `exit()`，而 `exit` 在 GOT 中。
  - 你通过溢出把 `exit` 的 GOT 条目改成 `main` 或 `system` 的地址，就能劫持控制流。

####  如何防御？

- Full RELRO：程序一启动就把 GOT 锁成只读 → 无法修改。
- 你的输出是 **Partial RELRO** → **可以改 GOT！这是好消息！**

------

### 2. **Stack: No canary found**

####  什么是 Stack Canary？

想象你在栈上放了一个“警报器”（canary）。如果发生缓冲区溢出，攻击者要覆盖返回地址，就必须先覆盖这个 canary。程序在函数返回前会检查它是否被改动，如果变了就直接 crash，阻止攻击。

####  No canary found 的含义：

- **完全没有这个警报器**
- 意味着可以直接通过栈溢出覆盖返回地址，跳转到任意地方

####  CTF 利用思路：

- 经典栈溢出直接可用

  ```c++
  char buf[114];
  gets(buf); // 若读取字符串长度大于114，会直接导致栈溢出
  /* 安全写法：
  if(strlen(buf) <= 114) gets(buf);
  */
  ```

  输入 72 个字符 + 8 字节返回地址，就能控制 RIP（x64）或 EIP（x86）。

####  防御方式：

- 编译加 `-fstack-protector`
- 你的程序没开 → **非常利于初学者！**

------

### 3. **NX: NX enabled**

####  什么是 NX（No-eXecute）？

- 栈（stack）和堆（heap）上的数据**不能当作代码执行**。
- 以前老式漏洞可以直接往栈里写 `shellcode`（一小段机器码），然后跳过去执行。
- 现在不行了！栈是 “rwx” 中的 “rw-”，没有 “x”（execute）权限。

####  对你的影响：

- **不能直接执行 shellcode**
- 必须用程序里已有的代码片段来拼凑攻击 → 这就是 **ROP（Return-Oriented Programming）**

####  CTF 利用思路：

- 找程序里的 `gadgets`（以 `ret` 结尾的小指令块）
- 把它们串起来，最终调用 `system("/bin/sh")`
- 因为你的程序 **没有 PIE**（见下一条），地址是固定的，ROP 很容易！

>  总结：NX 开了不是坏事，只是逼你用 ROP —— 这是 Pwn 的核心技能！

------

### 4. **PIE: No PIE (0x3fe000)**

####  什么是 PIE？

- PIE = Position Independent Executable
- 开启后，程序每次运行的基地址都不同（配合 ASLR）
- 攻击者不知道 `main`、`system`、gadgets 在哪 → ROP 变难

####  No PIE 的含义：

- **程序加载地址固定！**
- 比如你的程序总是从 `0x3fe000` 开始
- 所有函数、字符串、gadgets 的地址都是**确定的**！

####  CTF 利用思路：

- 你可以用 `objdump -d ./vuln` 或 `ROPgadget --binary ./vuln` 直接拿到 gadget 地址
- 写 exp 时直接硬编码地址，不用泄露内存

>  对新手极其友好！不用处理地址随机化问题。

------

##  综合分析：这个程序对 Pwn 新手非常友好！

| 保护机制   | 状态    | 对你的影响                         |
| ---------- | ------- | ---------------------------------- |
| **RELRO**  | Partial | ✅ 可以改 GOT 表（备用方案）        |
| **Canary** | 关闭    | ✅ 直接栈溢出，无需绕过             |
| **NX**     | 开启    | ⚠️ 不能执行 shellcode，但可以用 ROP |
| **PIE**    | 关闭    | ✅ 所有地址固定，ROP 极其简单       |

### 🛠 你大概率可以这样利用：

1. 找到栈溢出点（比如 `gets`, `read` 读太多）

2. 计算偏移量（覆盖到返回地址）

3. 用 ROP 调用

  ```shell
system("/bin/sh")
  ```
  
   - 因为没开 PIE，`system` 和 `/bin/sh` 字符串地址可以直接从程序或 libc 中找到

4. 如果懒得搞 ROP，也可以试试改 GOT（比如把 `puts` 改成 `system`）

------

##  学习建议

1. **先学栈溢出基础**
   - 理解栈帧结构（return address, saved rbp）
   - 用 `gdb` + `gef` 或 `pwndbg` 调试
2. **练习无保护程序**
   - 先做 `No Canary, No NX, No PIE` 的题
   - 再过渡到 `NX enabled, No PIE`（就是你现在的情况）
3. **学习 ROP**
   - 用 `ROPgadget` 工具找 gadgets
   - 学会调用 `system("/bin/sh")` 或 `execve`
4. **工具推荐**
   - `checksec`：看保护
   - `gdb` + `gef`：调试
   - `pwntools`（Python 库）：写 exp 脚本

------

## 🧪 举个简单例子（伪代码）

假设程序如下：
```c++
#include <stdio.h>
void vuln() {
    char buf[64];
    read(0, buf, 200); // 溢出！
}
int main() { vuln(); }
```

你用 `checksec` 得到的就是你提供的结果。

**Exploit 思路：**

1. 找到 `system` 地址（比如 `0x401230`）

2. 找到 `/bin/sh` 字符串地址（比如 `0x402000`）

3. 构造 payload：

   text

   编辑

   ```
   [64字节填充] + [8字节rbp] + [system_addr] + [fake_ret] + [/bin/sh_addr]
   ```

4. 发送 payload，拿到 shell！