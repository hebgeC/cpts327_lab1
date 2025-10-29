# cpts327_lab1
lab 1: buffer overflow attack


gcc -m32 -O0 -fno-omit-frame-pointer -z execstack \
-fno-stack-protector -no-pie -o stack-L1 stack-L1.c
