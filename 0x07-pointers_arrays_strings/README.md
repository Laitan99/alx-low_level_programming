0x07. C - Pointers, arrays and strings.

Resources

Pointers, arrays and Data Structures
C - Pointer to Pointer
C - Pointer to Pointer with Example
C - Multidimensional Arrays in C

Two dimensional (2D) arrays in C programming with example
C Books and PDF's to check out and use as reference.

Tasks

memset : A function that fills memory with a constant byte.
Prototype: char *_memset(char *s, char b, unsigned int n);
The _memset() function fills the first n bytes of the memory area pointed to by s with the constant byte b.
Returns a pointer to the memory area s.
Read more on memset here
FYI: The standard library provides a similar function: memset. Run man memset to learn more.
Compile the code this way: gcc -Wall -pedantic -Werror -Wextra -std=gnu89 0-main.c 0-memset.c -o 0-memset
memcpy : A function that copies the memory area.
Prototype: char *_memcpy(char *dest, char *src, unsigned int n);
The _memcpy() function copies n bytes from the memory area src to the memory area dest.
Returns a pointer to dest
FYI: The standard library provides a similar function: memcpy. Run man memcpy to learn more.
Compile the code this way: gcc -Wall -pedantic -Werror -Wextra -std=gnu89

 1-main.c 1-memcpy.c -o 1-memcpy
strchr : A function that locates a character in a string.
Prototype: char *_strchr(char *s, char c);
Returns a pointer to the first occurrence of the character c in the string s, or NULL if the character is not found.
FYI: The standard library provides a similar function: strchr. Run man strchr to learn more.
Read more here on strchr.
Compile the code this way: gcc -Wall -pedantic -Werror -Wextra -std=gnu89

 2-main.c 2-strchr.c -o 2-strchr
strspn : A function that gets the length of a prefix substring.
Prototype: unsigned int _strspn(char *s, char *accept);
Returns the number of bytes in the initial segment of s which consist only of bytes from accept.
FYI: The standard library provides a similar function: strspn. Run man strspn to learn more.
Compile the code this way: gcc -Wall -pedantic -Werror -Wextra -std=gnu89

 3-main.c 3-strspn.c -o 3-strspn
strpbrk : A function that searches a string for any of a set of bytes.
Prototype: char *_strpbrk(char *s, char *accept);
The _strpbrk() function locates the first occurrence in the string s of any of the bytes in the string accept.
Returns a pointer to the byte in s that matches one of the bytes in accept, or NULL if no such byte is found.
FYI: The standard library provides a similar function: strpbrk. Run man strpbrk to learn more.
Compile the code this way: gcc -Wall -pedantic -Werror -Wextra -std=gnu89

 4-main.c 4-strpbrk.c -o 4-strpbrk
strstr : A function that locates a substring.
Prototype: char *_strstr(char *haystack, char *needle);
The _strstr() function finds the first occurrence of the substring needle in the string haystack.
The terminating null bytes ('\0') are not compared.
Returns a pointer to the beginning of the located substring, or NULL if the substring is not found.
FYI: The standard library provides a similar function: strstr. Run man strstr to learn more.
Compile the code this way: gcc -Wall -pedantic -Werror -Wextra -std=gnu89

 5-main.c 5-strstr.c -o 5-strstr
Chess is mental torture : A function that prints the chessboard.
Prototype: void print_chessboard(char (*a)[8]);
Compile the code this way: gcc -Wall -pedantic -Werror -Wextra -std=gnu89
 _putchar.c
 7-main.c 7-print_chessboard.c -o 7-print_chessboard
The line of life is a ragged diagonal between duty and desire : A function that prints the sum of the two diagonals of a square matrix of integers.
Prototype: void print_diagsums(int *a, int size);
Format: see main code.
You are allowed to use the standard library.
Note: that in the following example we are casting an int[][] into an int*.

This is not something you should do. The goal here is to make sure you understand how an array of array is stored in memory.
Compile the code this way: gcc -Wall -pedantic -Werror -Wextra -std=gnu89

 8-main.c 8-print_diagsums.c -o 8-print_diagsums
