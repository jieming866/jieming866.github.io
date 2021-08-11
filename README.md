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

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/jieming866/jieming866.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
