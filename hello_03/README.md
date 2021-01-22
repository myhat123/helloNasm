内存
====

https://zhuanlan.zhihu.com/p/23722940

$ nasm -f elf danteng.asm -o danteng.o
$ gcc -m32 danteng.o -o danteng
$ ./danteng ; echo $?