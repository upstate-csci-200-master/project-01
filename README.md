# project-01
play with random numbers and strings

Write a Java program named RandomStrings.java that does the following:

for a grade of C: 
  - read in an integer and use this to seed your random number generator (see this example: https://www.geeksforgeeks.org/random-setseed-method-in-java-with-examples/)
  - read in a string
  - set your random number generator using a seed of 100
  - pick a random number between 0 and the length of the string-1
  - output a new string that removes the letter at the random number
  - for example if the string is HELLO JOHN and the random number is 3, output HELO JOHN
  - another example if string is GOODBYE SALLY and the random number is 0, output OODBYE SALLY
  - if string is GOODBYE SALLY and the random number is 12, output GOODBYE SALL
  
  
for a grade of B:
  - in addition to the C version
  - pick another random number between 1 and the length of the string-1
  - output a new string that exchanges the letters at the random number and the one to the left of it
  - for example if the string is HELLO JOHN and the random number is 7, output HELLO OJHN
  - another example if string is GOODBYE SALLY and the random number is 1, output EHLLO JOHN


for a grade of A: 
  - read a string
  - pick 2 random numbers between 0 and the length of the string-1, make sure 2nd random number is greater than the first
  - output a new string which exchanges the characters at the 2 random positions
  - for example if the string is HELLO JOHN and the random numbers are 2 and 5, output HE LOLJOHN
  - if string is HELLO JOHN and the number numbers are 1 and 6, output HJLLO EOHN

Submit your java source code file to CodePost. Include the following comments at the top of your file:
// NAME: your name
// CLASS: CPSC 200
// DATE: current date
// VERSION: grade version you completed
// TIME: how much time did you spend on this program
// STATUS: write down any problems you had and whether or not the program works, be specific
