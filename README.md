# alx low level programming printf Project

## Description
ALX's first-year curriculum includes a team project, which involves creating a printf() function that mimics the functionality of the C standard library printf().

The following are some of the key takeaways from this project that we learnt:

* Collaboration and teamwork: As this project is a team effort, you will have the opportunity to improve your collaboration and teamwork skills.

* Programming fundamentals: You will need to have a solid understanding of programming fundamentals, such as data types, functions, loops, and conditional statements, to create a functional printf() function.

* Debugging and testing: You will learn how to debug and test your code to ensure that it is working as intended.

* Familiarity with the C programming language: This project involves replicating the printf() function in the C standard library, so you will need to be familiar with the C programming language.

* Attention to detail: The printf() function is a critical component of many C programs, and it is essential to ensure that your implementation is accurate and reliable.

* Time management: This project will require a significant time commitment, and you will need to manage your time effectively to meet the project deadlines.


---

## Prototype
```int _printf(const char *format, ...);```


## How to use
* This function prints a string to the standard output based on a specified format.

* All files included in this project were created and compiled on Ubuntu 14.04.4 LTS, using GCC 4.8.4 with the command gcc -Wall -Werror -Wextra -pedantic *.c.

* If successful, the function returns the number of characters in the output string; otherwise, it returns -1.

* To use this function, call it with the following syntax: _printf("format string", arguments...). The format string argument may contain conversion specifiers, flags, and regular characters.

## Examples

* ```_printf("Cynthia, main\n")``` *will print "Cynthia, Main" followed by a new line.*
* ```_printf("%s", "Moses")```  *will print "Moses".*
* ```_printf("This is a number: %d", 16)``` *will print "This is a number: 16".*

## Tasks

The printf alx project comprises of the following *two* mandatory task and *fourten* advance task

### Task 0: Function that produces output according to the following format.

* Prototype: int _printf(const char *format, ...);
* Returns: the number of characters printed (excluding the null byte used to end output to strings)
* write output to stdout 
* You need to handle the following conversion specifiers: *c s %*

### Task 1: write a function that Handle the following conversion specifiers:

* d
* i

### Task 2: write a function that handle the following custom conversion specifiers:

* *b*: the unsigned int argument is converted to binary

### Task 3: write a function that handle the following conversion specifiers:

* u
* o
* x
* X