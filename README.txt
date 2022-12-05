0. The project was built in Python 3.10.6

1. Libraries required to run the project including the full version of each library

numpy==1.23.3
opencv_python==4.6.0
os

2. How to run each task and where to look for the output file.

For all tasks first run cells adnotated with "1. Imports", and "2. Main utility functions"
For all task the output is stored in './results/'

Task 1: 
	Run cell "4. Task 1"
	Output: Only the positions are computed. The letter is 'A' for all input files.
		The score is '10' for all input files.
	Example: 
		1_01.txt => 8H A
		            8I A
		            8J A
		            8K A
		            8L A
		            10

Task 1 & Task 2: 
	Run cell "5. Task 2"
	Output: The positions and the letter for all positions are computed. 
		The score is '10' for all input files.
		
	Example: 
		1_01.txt => 8H P
		            8I U
		            8J N
		            8K C
		            8L T
		            10
		
Task 1, Task 2 & Task 3 (The complete application):
	Run cell "6. Task 1, Task 2 & Task 3"
	Output: The positions, the letter for all positions and the score are computed.
	
	Example: 
		1_01.txt => 8H P
		            8I U
		            8J N
		            8K C
		            8L T
		            14

I choose this output to get help from script 'evalueaza_solutie.py'.
If the ouput for task 1 was only the positions like this

		1_01.txt => 8H 
		            8I 
		            8J 
		            8K 
		            8L 

the the script does not work, so I can't get feedback for every individual task.		            	
