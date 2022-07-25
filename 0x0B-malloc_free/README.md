				===================C - malloc, free====================
			
									
						THINGS TO  NOTE ABOU
				--------------------------------------------------------
			1.malloc function is used to allocate a certain amount of memory during the execution of a program. It will request a block of memory from the heap.

	
			2.When the amount of memory is not needed anymore, you must return it to the operating system by calling the function free.
			

			3.The malloc function allocates a specific number of bytes in memory and returns a pointer to the allocated memory.
		

			4.Contrary to local variables and function parameters, the memory that is allocated with malloc is not automatically released when the function returns.

			5.Just like with automatic allocation, the memory allocated by malloc is not initialized.


			6.When you are using malloc, you have to handle the memory yourself. 

			7.VALGRIND: When writing big and complex programs, it is not always easy to keep track of all allocated and deallocated memory.
			 We can use the program Valgrind in order to ensure we are freeing all allocated memory. It is a programming tool for memory debugging,
			 memory leak detection, and profiling.


			8.String literals are not always read-only
	
			9.String literals are not always stored as strings in the executable
