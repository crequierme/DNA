# DNA
The purpose of this code was to create a linked-list abstract data type which represents a DNA strand. The left and right helices are represented by linked lists and nucleotides are represented by elements in the linked list. Two nucleotides which are "across" from each other (one in left helix, other in same position on right helix) form a base pair containing two characters (e.g. "CG").

Execution

	Run the main method of class DNA from a Java editing environment. This code was originally written in BlueJ, and I’ve found this is a very easy environment to use and test in. Running main({}) with no arguments will open a terminal. The user will be prompted to “Enter method information”. The user will submit a number representing the number of methods they will call. Each subsequent input will be a number representing which method the user would like to call (1-10) or inputs for said methods. Each necessary input will be prompted.

Methods

Insert a base pair into the DNA strand at the index. Prompts for an index then a 2 character base pair (ex. “CG”)
Remove a base pair at given index. Prompts for integer between 0 and the number of elements - 1
Print base pairs from start index to end index - 1. Prompts for start index and end index (not exceeding number of elements)
Clear the DNA structure
Return and print whether or not the DNA strand is empty (“true” if empty, “false” if there are elements)
Return and print the number of base pairs in the strand
Find base pair in the strand. Prompts for a 2 character base pair to search for. If the pair is in the strand, it will return and print the index at which it is located. If the base pair is not in the strand, it will return and print -1.
Print the entire left helix of the strand
Print the entire right helix of the strand
 Prints base pair at an indicated index from a particular helix. (Ex: If the nucleotide on the right helix is “C” and the nucleotide on the left helix is “T” and it is read from the left, it is returned as “TC”). Prompts for index and helix (enter 0 for left, 1 for right)

Sample
Here is an example of how the program may be used.

How many methods will you call? 
8
Method number: 1
Index to insert: 0
Enter base pair: AA
Method number: 1
Index to insert: 1
Enter base pair: BB
Method number: 1
Index to insert: 2
Enter base pair: CC
Method number: 3
Start index to print: 0
End index to print: 2
A
A
B
B
Method number: 8
ABC
Method number: 5
False
Method number: 4
Method number: 5
true

