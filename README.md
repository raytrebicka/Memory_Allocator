# Memory_Allocator

This is a memory allocator implementation utilizing sbrk and mmap written in C to run on CentOS 7.4. The header malloc.h ensures that
the custom functions are being used instead of the system ones. The implementation of malloc, calloc, and free are written in mymalloc.c.
