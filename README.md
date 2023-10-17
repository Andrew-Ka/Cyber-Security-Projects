# Cyber-Security-Projects
This Repository holds various projects for CyberSecurity CPSC 4363 given by Lamar University

Here are the project descriptions:

## Project 1 - File Recovery: <be>

**Restore the deleted file by finding its associated clusters.**<br>
Input (by the evaluator):<br>
1st line: the first cluster of each existing file in the root table<br>
2nd line: the first row of the FAT table<br>
3rd line: the second row of the FAT table<br>
Output:<br>
1st line: clusters for the data of the deleted file (in the correct sequence)<br>
Example: <br>
*Input:*<br>
2 7<br>
2 3 4 5 6 7 8<br>
3 4 0 6 8 0 0<br>
*Output:*<br>
5 6 8<br>
