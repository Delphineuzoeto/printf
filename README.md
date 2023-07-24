ALX Software Engineering Printf Team Project

Printf Team Project

Table of Contents
1.	Introduction
2.	Project Description
3.	Installation
4.	Usage
5.	Supported Conversion specifiers
6.	Contributing
7.	Licence
8.	Author

Introduction 

Welcome to our amazing team project on creating a custom "printf" function for the C programming language. In this project we have developed a function called _printf that mimics the behavior of the standard function "Printf", allowing you to print formatted output to the standard output stream.

Project Description

Our custom _printf function has been optimized to handle various inputs and optional arguments, providing you with flexibility similar to the standard "printf" function. The primary purpose of _printf is to write formatted output to the standard output stream(stdout) without relying on any of the std library files. It returns the total number of characters printed (excluding the null byte at the end of strings) after a successful execution. In case of an output error, it returns a negative value of -1.

 Installation


 a. create a repo with the name printf

 b. on your sandbox, git clone git clone https://github.com/your-username/printf-team-project.git

 c. Include the _printf function in your project source file

 d. Compile your project, linking with the printf.c file containing the _printf implementation gcc -Wall -Werror -Wextra -pedantic main.c printf.c -o my_program

Usage

 The prototype of our _printf function is "int _printf(const char *format, ...);" It accepts a "format" string and an optional number of arguments based on the format specifiers provided in the "format" string. The string contains zero or more directive that control the output format

Supported Conversion Specifiers

 Our _printf function supports the following conversion specifiers:

 a. %c: Character 

b. %s: String 

c. %%: Percent sign

Contributing

 We welcome contributions from the community to improve our _printf function. If you find any bugs or have suggestions for enhancement, feel free to submit a pull request or open an issue in the repository. 

Licence  This project is licensed under the ALX Software Engineering program.

 AUTHORS 

DELPHINE UZOETO

 BAWO VICTOR EJUEYITCHIE


