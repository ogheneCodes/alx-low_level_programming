	============MALLOC AND FREE=============



				NOTE
			--------------------


 The malloc function is used to allocate a certain amount of memory during the execution of a program.
 It will request a block of memory from the heap. If the request is granted,
 the operating system will reserve the requested amount of memory and malloc will return a pointer to the reserved space.



#NOTE:

***Malloc is used for memory allocation during runtime execution. 


**The malloc function allocates a specific number of bytes in memory and returns a pointer to the allocated memory.


****memory that is allocated with malloc is not automatically released when the function returns.


**When you are using malloc, you have to handle the memory yourself. This means that:
	

	1.You need to keep track of all the addresses of the allocated memory (in a variable of type pointer).

	
	2. You have to deallocate every memory space you previously allocated yourself.
	   If you do not do this, then your program can run out of memory.
	   Your operating system could even kill your program while it is running



#THE FREE FUNCTION


**The free function frees the memory space which has been allocated by a previous call to malloc (or calloc, or realloc).

