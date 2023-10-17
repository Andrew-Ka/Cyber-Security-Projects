# Cyber-Security-Projects
This Repository holds various projects for CyberSecurity CPSC 4363 given by Lamar University

Here are the project descriptions:

Project 1 - File Recovery:
Restore the deleted file by finding its associated clusters.
Input (by the evaluator):
1st line: the first cluster of each existing file in the root table
2nd line: the first row of the FAT table
3rd line: the second row of the FAT table
Output:
1st line: clusters for the data of the deleted file (in the correct sequence)
Example: 
Input:
2 7
2 3 4 5 6 7 8
3 4 0 6 8 0 0
Output:
5 6 8
