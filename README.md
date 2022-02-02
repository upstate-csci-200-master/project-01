# project-01
play with random numbers and strings

Write a Java program named RandomStrings.java that does the following:

for a grade of C:  
  - read in a string
  - set your random number generator using a seed of 100 (example: https://www.geeksforgeeks.org/random-setseed-method-in-java-with-examples/)
  - pick a random number between 1 and the length of the string-1 (example: https://www.codegrepper.com/code-examples/java/java+random+number+between+1+and+10)
  - output a new string that removes the letter at the random number position of the string; remember character positions in Java Strings start with 0
  - for example if the string is HELLO JOHN and the random number is 3, output HELO JOHN
  - another example if string is GOODBYE SALLY and the random number is 0, output OODBYE SALLY
  - if string is GOODBYE SALLY and the random number is 12, output GOODBYE SALL
  - if string is 123456789 and random number is 6, output 12345789
  
  
for a grade of B:
  - in addition to the C version
  - pick another random number between 1 and the length of the string-1
  - output a new string that exchanges the letters at the random number position and the one to the left of it
  - for example if the string is HELLO JOHN and the random number is 7, output HELLO OJHN
  - another example if string is GOODBYE SALLY and the random number is 1, output EHLLO JOHN


for a grade of A: 
  - in addition to the B version
  - output the reverse of the original string (DO NOT use any loops); (example: https://www.javatpoint.com/java-stringbuilder-reverse-method)
  - for example if the string is 123456789, output 98765432
  - pick another random number between 1 and length of the string-1
  - output a new string that reverse all the characters starting at the random position to the end of the string
  - for example if the string is 123456789 and random number is 5, output 123459876

FOR ALL VERSIONS add the following comments as appropriate
```
// create random object

// C version code

// B version code

// A version code
```

Submit your java source code file to CodePost. Include the following comments at the top of your file:
```
 // NAME: your name
 // CLASS: CPSC 200
 // DATE: current date
 // VERSION: grade version you completed
 // TIME: how much time did you spend on this program
 // STATUS: write down any problems you had and whether or not the program works, be specific
 ```
