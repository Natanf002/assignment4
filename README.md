Group members: 
==============

	Akiva Yeshurun - 6283697 - ayesh001@fiu.edu

	Natan Farhy - 6346028 - nfarh002@fiu.edu

	Noah Pilkington - 6391207 - npilk001@fiu.edu

Section: U02

Continuous Memory Allocation
==================
//Fix this
This program simulates the banker's algorithm to avoid a deadlock for systems with multiple instances of each resource type.

Compilation Instructions:
------------------------

To compile the program, use the following command: make

If that doesn't work, use this command: gcc continuous_memory_allocator.c -static -o memory_allocator -lm

Running the Program:
------------------
1. Make sure you have the input.txt file in the same directory as the executable
2. Run the program using:
    ./memory_allocator
3. Test with //fix this
4. To quit, press 'q'

Input File Format:
----------------
The input.txt file should follow this format:
1000
1 100
2 200
3 150
4 50
5 125
6 75