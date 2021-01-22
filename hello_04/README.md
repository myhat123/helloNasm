c语言和汇编
=========

https://zhuanlan.zhihu.com/p/23779935

gcc -m32 hello.c -o hello
./hello; echo $?

test01.asm
==========
global main

main:
    mov eax, 0
    ret

section .data

x    dw    0
y    dw    0
z    dw    0

test01.c
========
int x, y, z;

int main() {
    return 0;
}

以上两个代码相同