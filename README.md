# printf()
> The printf project is a collaboration between Belove Olusola and Fasil Solomon, actual students of Software Engineering at ALX-Africa, where a function named "_printf" imitates the actual "printf" command located in the stdio.h library. It contains some of the basic features and functions found in the manual 3 of "printf".

## Description
> _printf() is a function that performs formatted output conversion and print data.
Prototype: `int _printf(const char *format, ...)`

## Return Value
> Upon successful return, _printf returns the number of characters printed (excluding the terminating null byte used to end output to strings). If an output error is encountered, the function returns -1.

| Conversion Specifier | Output |
|----------------------|--------|
| c |	Character |
| d or i |	Signed decimal integer |
| s |	String of characters |
| b |	Signed binary |
| o |	Signed octal |
| u |	Unsigned integer |
| x |	Unsigned hexadecimal |
| X |	Unsigned hexadecimal (uppercase) |
| p |	Pointer address |
| r |	Reverse string of characters |
| R |	ROT13 translation of string |
| S |	String with special chars replaced by their ASCII value |
| % |	Character |

| Flags |	Description	| Specifiers |
|-------|---------------|------------|
| + |	Prints a plus sign (+) when the argument is a positive number. In other case, prints a minus sign (-).	| i, d |
| (space) |	Prints a blank space if the argument is a positive number	| i, d |
| #	| Prints 0, 0x and 0X for o, x and X specifiers, respectively. It doesn't print anything if the argument is zero	| o, x, X |

| Length	| Description	| Specifiers |
|-----------|---------------|------------|
| l	| Prints a long int or unsigned long int	| i, d, o, u, x and X |
| h	| Prints a short int or unsigned short int	| i, d, o, u, x and X |

## About _printf Functions
**int _printf(const char *format, ...)**
> This function produces output according to a format.

**void write_format(va_list *args_list, fmt_info_t *fmt_info)**
> This function writes data formatted against some parameters.

**int _putstr(char *str)**
> This function writes the given string to the buffer.

**int _putchar(char c)**
> This function writes the character c to the buffer.

**int write_to_buffer(char c, char action)**
> This function writes a char to the buffer based on an action code.


# Authors
- Fasil Solomon
- Belove Olusola
