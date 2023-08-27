# XV6

# XV6-modified
Several modfication to XV-6 are done, each task represents a particular aspect of OS kernel, like memory management, scheduler, shell behaviour, etc. See each task detailed reports for better understanding

# Tasks and introductions
* Assignment-0 : Studying the boot order and memory flow in XV6 modules (Bootasm.S, Bootblock.asm) by debugging the code and changing the address values. Basics like how memory stack(RAM) is configured and partitions etc.

* Assignment-1 : This is about how to add a Custom User program and system calls in XV6.
* 
* Assignment-2A : Here we added some curson operations in shell like left/right arrow function(which also includes editing) and shell history option which can be accessed using up and down arrow(Circular loop implementation, O(1) operation). Here we understand how shell handles consoles at different layers and buffers.

* Assignment-2B : Here we customize XV6 scheduler with various policies - FCFS, Round Robin, DML, SML. We understand how the processes are activated, the process struct's parameters and process related system calls like myproc(), etc. And finally do a performance test between them.

* Assignment-3 : This is about memory management. How memory allocation is done, what are system calls involved, etc. Here we also implement Lazy memory allocation stategy by modifying memory allocater and pagefault_handler. And we will also Implement a swap-in/out mechanism at a kernal level which frees RAM by exploiting free disk space, it also takes requests from processes to bring back the pages/page-directories required by the processes.

* Assignment-4 : This is a study on Linux process management and devising how to include some of the features into XV6. The features weren't implemented in XV6 code, the code flow required and the design are explained(System calls and logic). 

This is done under Dr.John Jose, in Operating Systems course at IIT Guwahati.
