# README Memory Allocator

**Important understandings**

1. What is Virtual Memory?

Virtual Memory is an operating system technique that extends a computer's physical RAM by using storage space (HDD or SSD) as temporary memory.

enabling multitasking and preventing the system from crashing when the RAM is fully utilized.

2. What is heap?

when allocating memory dynamically, it gets stored in the heap. Needs to be freed manually.

3. What is stack?

local variables inside a function get stored on the stack and get freed automatically when exiting the function.

4. What is page?

paging, divides the memory inti small fixed-sized blocks called pages.

5. What is memory fragmentation?

**Important system calls**

1. sbrk()

2. brk()

3. mmap()

4. munmap()

