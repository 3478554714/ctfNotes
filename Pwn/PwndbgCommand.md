###  1. **基础信息查看**

| 命令               | 作用                                                         |
| ------------------ | ------------------------------------------------------------ |
| `context` 或 `ctx` | 显示当前上下文：寄存器、反汇编代码、栈、代码段（可自定义显示内容） |
| `regs`             | 显示所有寄存器的值（比 GDB 默认更清晰）                      |
| `stack [n]`        | 查看栈顶开始的 `n` 行（默认 10 行），自动解析指针/字符串     |
| `vmmap`            | 查看进程的内存映射（包括栈、堆、libc、binary 等段的地址范围和权限） |

------

###  2. **内存与地址操作**

| 命令                       | 作用                                                         |
| -------------------------- | ------------------------------------------------------------ |
| `telescope <addr> [count]` | 从 `<addr>` 开始“望远镜”式查看内存，自动解析为地址、字符串、整数等（类似 `x/10gx` 但更智能） |
| `hexdump <addr> [size]`    | 以十六进制+ASCII格式打印内存内容                             |
| `dereference <addr>`       | 解引用指针（查看该地址指向的内容）                           |
| `search -t string "flag"`  | 在内存中搜索字符串 `"flag"`（支持 `-t` 指定类型：string, bytes, dword 等） |
| `find_fake_fast <addr>`    | （堆题专用）查找可能的 fake fastbin chunk                    |

------

###  3. **堆（Heap）调试（需 libc 调试符号或正确加载）**

| 命令           | 作用                                                         |
| -------------- | ------------------------------------------------------------ |
| `heap`         | 显示当前堆的所有 chunks（需 glibc 调试信息）                 |
| `heap chunks`  | 列出所有分配的 chunk                                         |
| `heap bins`    | 查看 fastbins / unsorted bin / small bins / large bins 的状态 |
| `malloc_stats` | 显示 malloc 统计信息（glibc 内部）                           |
| `arena`        | 显示当前 malloc arena 信息                                   |

> 💡 若无调试符号，可配合 `patchelf --set-interpreter ...` + `LD_PRELOAD=./libc.so` 加载带符号的 libc。

------

###  4. **ROP / 栈溢出辅助**

| 命令                | 作用                                                       |
| ------------------- | ---------------------------------------------------------- |
| `rop`               | 自动搜索 binary 中的 ROP gadgets（需安装 ROPgadget）       |
| `cyclic <length>`   | 生成 De Bruijn 序列（用于确定偏移）                        |
| `cyclic -l <value>` | 根据覆盖的 EIP/RIP 值计算偏移（如 `cyclic -l 0x61616168`） |
| `canary`            | 显示当前栈 canary 值（如果存在）                           |

------

###  5. **断点与执行控制**

| 命令                          | 作用                                                         |
| ----------------------------- | ------------------------------------------------------------ |
| `start`                       | 启动程序并自动停在main函数开头                               |
| `run/r`                       | 正常启动程序，通常在打好断点后运行                           |
| `continue/c`                  | 程序继续执行到下一断点或程序结束                             |
| `break *0x401234/b *0x401234` | 在指定地址下断点                                             |
| `next/n`                      | 单步跳过（C语言），让程序继续执行一句C语言后停止，碰见函数省略 |
| `ni`                          | 单步跳过（汇编语言），让程序继续执行一段汇编语句后停止，碰见函数省略 |
| `step/s`                      | 单步进入（C语言），其余同`next/n`，但其碰见函数会进入函数内部继续调试 |
| `si`                          | 单步进入（汇编），其余同`step/s`                             |
| `finish/fini`                 | 执行完当前函数并返回                                         |
| `quit/q`                      | 退出gdb                                                      |
| `nextcall` / `nextjmp`        | 单步到下一个 call / jmp 指令                                 |
| `stepuntilasm "mov rdi"`      | 单步直到遇到匹配的汇编指令                                   |

------

###  6. **ELF / 二进制信息**

| 命令       | 作用                                                         |
| ---------- | ------------------------------------------------------------ |
| `elf`      | 显示 ELF 文件的基本信息（入口点、节区等）                    |
| `got`      | 显示 GOT 表内容（可用于泄露 libc 地址）                      |
| `plt`      | 显示 PLT 表（函数桩）                                        |
| `checksec` | 显示二进制的安全保护机制（NX, PIE, Canary, RELRO 等）← **极其常用！** |

------

### 🔄 7. **其他实用命令**

| 命令            | 作用                                 |
| --------------- | ------------------------------------ |
| `argc` / `argv` | 查看 main 函数的参数                 |
| `env`           | 查看环境变量                         |
| `errno`         | 查看当前 errno 值                    |
| `procinfo`      | 显示进程信息（PID、父进程等）        |
| `aslr`          | 查看 ASLR 是否启用（Linux 内核级别） |

------

### ✅ CTF 调试典型流程示例

```shell
gdb ./vuln
pwndbg> checksec          # 看保护
pwndbg> break main        # 下断点
pwndbg> run               # 运行
pwndbg> vmmap             # 看内存布局
pwndbg> telescope $rsp 20 # 看栈
pwndbg> cyclic 100        # 生成 pattern
# （输入后 crash）
pwndbg> cyclic -l $rip    # 计算偏移
pwndbg> got               # 看 GOT 泄露点
pwndbg> search -t string "/bin/sh"  # 找字符串
```

------

### 💡 小技巧

- 使用 `config` 可自定义 `context` 显示内容（如只显示 regs + disasm）。
- `pwndbg` 支持 Python 脚本扩展，可在 `.gdbinit` 中配置常用设置。
- 在远程调试时，配合 `gef` 或 `pwntools.gdb.debug()` 更高效。