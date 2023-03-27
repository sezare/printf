###Compilation

1. Your code will be compiled this way:
$ gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c
2. As a consequence, be careful not to push any c file containing a main function in the root directory of your project (you could have a test folder containing all your tests files including main functions)
3. Our main files will include your main header file (main.h): #include main.h
4. You might want to look at the gcc flag -Wno-format when testing with your _printf and the standard printf. Example of test file that you could use:
5. We strongly encourage you to work all together on a set of tests
6. If the task does not specify what to do with an edge case, do the same as printf
