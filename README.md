# Printf
``` c
This project was done by Gabriel Tibi & Friday Blessed 
```

## Contributors
- [Gabriel Tibi ](https://github.com/Gabeytech)
- [Friday Blessed ](https://github.com/Blessedfriday007)
# Printf.
```` c
int printf ( const char * format, ... );
````
This is the first group project that we have at ALX africa which consists of replicating the **[printf (3)](http://man7.org/linux/man-pages/man3/printf.3.html)** function of language c, calling it this way **_printf.**

This function is part of the standard library **<cstdio>** and to use it we must specify the header file **<stdio.h>**.

Writes the C string pointed by format to the standard output **(stdout)**. If format includes format specifiers (subsequences beginning with **%**), the additional arguments following format are formatted and inserted in the resulting string replacing their respective specifiers.

## The tasks.
-[x] **I'm not going anywhere. You can print that wherever you want to. I'm here and I'm a Spur for life.** 
Write a function that produces output according to a format.

- Prototype:``int _printf(const char *format, ...);``
- Returns: the number of characters printed (excluding the null byte used to end output to strings)
- write output to stdout, the standard output stream
- format is a character string. The format string is composed of zero or more directives. See man 3 printf for more detail. You need to handle the following conversion specifiers:
-- ``c``
-- ``s``
--  ``%``

 -[x] **Education is when you read the fine print. Experience is what you get if you don't**
Handle the following conversion specifiers:
-- ``d``
--``i``

## Functions we use.

````c
int _putchar(char c); /*writes the character c to stdout */
int _printf(const char *format, ...);/* function that produces output according to a format.*/
int print_char(va_list c);/*writes the character c to stdout */
int print_string(va_list s);/*writes the character c to stdout */
int print_int(va_list i);/*function that prints an integer */
int print_dec(va_list d);/* function that prints an decimal*/

### Complilation
All of the ``.c`` files along with a main.c file are to be compiled with ``gcc 4.8.4`` on Ubuntu 14.04 LTS with the flags ``-Wall Werror`` ``-Westra`` and ``-pedantic.``

The files will be compiled this way:
- ``gcc -Wall -Werror -Wextra -pedantic *.c``
