# Bootloader

## Operating Systems Assignment-3
(Group No.-32)
Sneha Sinha: 2016098
Ritu Kumari: 2016078

### To run the code 
    nasm -f bin main.asm -o boot && qemu-system-x86_64 -fda boot

### Description Of Code
    1. We are switching directly to the long mode (64-bit and protected) from the real mode (16-bit).
    2. It also checks whether the CPU supports long mode or not. 
    3. Displays "Hello World" and CR3 register contents.
