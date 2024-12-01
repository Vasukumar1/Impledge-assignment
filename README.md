Search the longest compounded word assignment.
**NOTE**:-> This program is created by me by learning ArrayList concept in Java. It took me 2 days to implement it .I have tested it in VS Code Editor.
How the Program Works
Input File Reading:
The program reads each word from the file and stores it in a list. The input files should contain one lowercase word per line with no extra characters.
Compound Word Identification:
For each word, the program attempts to split it into a prefix and a suffix.
It checks if the prefix is a valid word and if the suffix is either a valid word or can itself be broken into smaller words recursively.
Longest Word Tracking:
As each compound word is identified, the program compares its length with the currently tracked longest and second-longest compound words, updating them as necessary.
Output:
The program outputs the longest and second-longest compound words for each input file in the console.



