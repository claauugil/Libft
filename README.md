
## Libft

Libft is a project from the 42 Madrid curriculum. The goal is to create a custom C library that implements a series of standard functions, along with additional functions useful for future projects. 

The entire project was developed in compliance with all the Norminette rules, ensuring clean and consistent code formatting.
## Features

Libft includes reimplementations of standard C library functions to handle characters, strings, and memory, also with other utility functions:


### Character Classification and Conversion: ###

- isalpha: Checks if a character is alphabetic (A-Z, a-z).
- isdigit: Checks if a character is a numeric digit (0-9).
- isalnum: Checks if a character is alphanumeric (letter or digit).
- isascii: Checks if a character is an ASCII character (0-127).
- isprint: Checks if a character is printable, including spaces.
- toupper: Converts a lowercase letter to uppercase.
- tolower: Converts an uppercase letter to lowercase.

### Character Handling and Output: ###

- ft_putchar_fd: Writes a character to a specified file descriptor.
- ft_putstr_fd: Writes a string to a specified file descriptor.
- ft_putendl_fd: Writes a string followed by a newline to a specified file descriptor.
- ft_putnbr_fd: Writes an integer as a string to a specified file descriptor.
- ft_strmapi: Applies a function to each character of a string and returns a new string.
- ft_striteri: Applies a function to each character of a string, passing the character's index and address.


### String Searching and Comparison:

- strchr: Finds the first occurrence of a character in a string.
- strrchr: Finds the last occurrence of a character in a string.
- strncmp: Compares two strings up to a given number of characters.
-  strnstr: Finds the first occurrence of a substring within a string, up to a specified length.

### String Manipulation:

- ft_substr: Allocates and returns a substring from a given string.
- ft_strjoin: Allocates and returns a new string formed by concatenating two strings.
- ft_strtrim: Trims specified characters from the start and end of a string.
- ft_split: Splits a string into an array of substrings based on a delimiter.
- ft_itoa: Converts an integer to a string.

### Memory Handling:

- memset: Fills a block of memory with a specified value.
-  bzero: Sets a block of memory to zero.
- memcpy: Copies data from one memory area to another.
- memmove: Copies data between memory areas that may overlap.
- memchr: Searches for a byte in a memory block.
- memcmp: Compares two memory blocks.

### Memory Allocation and Utility:

- calloc: Allocates and zero-initializes memory for an array.
- strdup: Duplicates a string by allocating memory for a new copy.
- atoi: Converts a string to an integer.

These functions provide a comprehensive toolkit for efficient string and memory management in C programming.

## Compilation

Compile the library: Use make to compile and generate the static library libft.a:

```bash
  make
```

Clean temporary files: To remove object files and temporary files:

```bash
  make clean
```

Delete all generated files: To remove the compiled library and all generated files:

```bash
  make fclean
```

Recompile the library: To clean and recompile from scratch:
```bash
  make re
```

Use the library in your project: Include the library in your project by adding the libft.a file and necessary headers. You can do this with:

```bash
 gcc -o your_program your_program.c libft/libft.a
```
