# String-memory
String memory database
azrieli college


==Description==
This program stores input-given strings in an external file, the program does two operations for each string and they are:
1-Counts how many words are in the given string.
2-Counts how many characters are in the given string. 
these calculation are written as results in the console after every string entered by the user unless the string that entered was one of two and they are:
1-the keyword "history" shows all the strings that were stored into the file we used to save our sentences
2-the keyword "exit" ends the program

functions:
two main functions:
1-print(): a void function that is responsible for recording the input and showing the output and check for the special keywords and write the string into the file.txt
2-CountFunc(): this function returns an array that stores all of the information related to the string, that includes How many words,how many characters,whether if history keyword was detected or whether if exit keyword was detected

==Program Files==
main.c- contain the main with the functions.
Makefile-to compile the program.
==How to compile?==
compile: gcc main.c -o ex1
run: ./ex1

==Input:==
the user inputs strings

==Output:==
word and character count unless if the input was "history"(the output is all the strings previously entered) or if it was "exit"(the program ends)
