环境
====

https://zhuanlan.zhihu.com/p/23618489

> $ sudo apt-get install gcc nasm gcc-multilib

示例
====

```asm
global main

main:
    mov eax, 0
    ret
```

> $ nasm -f elf first.asm -o first.o
> $ gcc -m32 first.o -o first

> $ ./first ; echo $?

gcc -o hello hello.c