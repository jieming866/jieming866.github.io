# Welcome to My Pages

## System Calls in 32-bit Linux
- To make a system call in 32-bit Linux, place the system call number in eax, then its arguments, in order, in ebx, ecx, edx, esi, edi, and ebp, then invoke int 0x80.
- Some system calls return information, usually in eax.
- All registers are saved across the system call.

## System Calls in 64-bit Linux
- To make a system call in 64-bit Linux, place the system call number in rax, then its arguments, in order, in rdi, rsi, rdx, r10, r8, and r9, then invoke syscall.
- Some system calls return information, usually in rax. A value in the range between -4095 and -1 indicates an error, it is -errno.
- The system call destroys rcx and r11 but others registers are saved across the system call.
- Full details are in Section A.2.1 of the The [AMD64 ABI](http://www.x86-64.org/documentation/abi.pdf).

## linux assembly resources
- [Linux Assembly](http://asm.sourceforge.net/)
- [X86 Opcode and Instruction Reference is](http://ref.x86asm.net/)

## github acc
- [github.global.ssl.fastly.net](http://github.global.ssl.fastly.net.ipaddress.com/#ipinfo)
- [github.com](https://github.com.ipaddress.com/#ipinfo)
