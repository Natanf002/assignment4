Group members: 
==============

	Akiva Yeshurun - 6283697 - ayesh001@fiu.edu

	Natan Farhy - 6346028 - nfarh002@fiu.edu

	Noah Pilkington - 6391207 - npilk001@fiu.edu

Section: U02

Continuous Memory Allocation
==================
This program focuses on the implementation and comparative analysis of three core continuous memory
allocation strategies — First-fit, Best-fit, and Worst-fit — along with Memory coalescing and Block reuse techniques. These mechanisms simulate fundamental memory management behavior in modern operating systems.

Compilation Instructions:
------------------------

To compile the program, use the following command: make

If that doesn't work, use this command: gcc continuous_memory_allocator.c -static -o memory_allocator -lm

Running the Program:
------------------
1. Make sure you have the input.txt file in the same directory as the executable
2. Run the program using:
    ./memory_allocator
3. To quit, press 'q'

Input File Format:
----------------
The input.txt file should follow this format:
<Process_ID> <Size_in_KB>