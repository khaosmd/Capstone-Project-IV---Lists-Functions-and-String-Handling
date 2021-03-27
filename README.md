# Capstone-Project-IV---Lists-Functions-and-String-Handling

Compulsory Task 1 (SickleCellDisease.py):

This is a program that simulates the effects of the Single Nucleotide Polymorphism that results in Sickle Cell Disease.

A 'translate' function is created that returns the amino acid sequence of the DNA using the amino acid SLC code when the function is given a DNA sequence of any length.
It makes use of a dictionary to store the slc codes as keys with matching amino acid values for the first five amino acids. If a key has multiple matching amino acid values, these are stored as a list. A for loop is used to populate an amino variable, this amino is looked up in the dictionary and the output is stored in the translate variable. This variable is printed as a string.

Compulsory Task 2 (SickleCellDisease.py):

Another function is added to the program called 'mutate'. This function reads the contents of the 'DNA.txt" file and identifies the first instance of the lower case letter 'a' in the file.

Two new text files are then written, normalDNA.txt and mutatedDNA.txt. 'normalDNA' has the same DNA sequence as in the DNA file except the 'a' is changed from lower case to upper case. 'mutatedDNA' has the same DNA sequence as in the DNA file except the 'a' is changed to a 'T'.

Lastly, a function called 'txtTranslate' is created that calls the translate function to take text file input. It is called for both normalDNA and mutatedDNA and prints the output to the screen.
