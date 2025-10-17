# Project-1

test line. Did this work?


1.Which program is fastest? Is it always the fastest?

Generally the fastest program will be alloca because it allocates memory the fastest just on the stack. 

2.Which program is slowest? Is it always the slowest?

The slowest will generally be new and malloc because they handle more bookkeeping and are more on the heap. 

3.Was there a trend in program execution time based on the size of data in each Node? If so, what, and why?

The time increases as the bytes on the nodes increase because they mean more memory, taking more time.

4.Was there a trend in program execution time based on the length of the block chain?

Growth feels linear, as nodes increase time increases just as much.

5.Consider heap breaks, what's noticeable? Does increasing the stack size affect the heap? Speculate on any similarities and differences in programs?

Heap breaks were more noticeable on malloc and new but increasing stack size i do not think will affect the heap because alloc mainly uses the stack and not the heap anyways. 

6.Considering either the malloc.cpp or alloca.cpp versions of the program, generate a diagram showing two Nodes. Include in the diagram
the relationship of the head, tail, and Node next pointers.
show the size (in bytes) and structure of a Node that allocated six bytes of data
include the bytes pointer, and indicate using an arrow which byte in the allocated memory it points to.

Head —--> node1
		Info
		Next (nude 2)
		Size

Tail   → node 2
		Info
		next (null)
		Size

7.There's an overhead to allocating memory, initializing it, and eventually processing (in our case, hashing it). For each program, were any of these tasks the same? Which one(s) were different?

The same across all programs was:  allocate memory, hash data
And different was:  stack/head data allocation, bookkeeping 

8.As the size of data in a Node increases, does the significance of allocating the node increase or decrease?

I think it will stay the same, maybe a small increase because there is more data but because everything else stays the same I do not think it will affect the process or anything. 




