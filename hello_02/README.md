寄存器
=====

https://zhuanlan.zhihu.com/p/23639191

```sh
$ nasm -f elf nmb.asm -o nmb.o
$ gcc -m32 nmb.o -o nmb
$ ./nmb ; echo $?
```