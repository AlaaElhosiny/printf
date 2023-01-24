## Printf Re-Building:

This project is about re-building the printf function to mimic the behavior of the standard printf function found in the C library. The goal is to create a custom implementation of printf that can be used as a replacement for the standard function in various scenarios such as embedded systems or educational purposes.

## Usage:
The re-built printf function can be used in the same way as the standard printf function. It takes in a format string and a variable number of arguments, and returns the number of characters written to the output.

```c
int res = printf("Hello, %s!\n", "world");
printf("%d characters written to output\n",res);

This will output the string "Hello, world!" followed by "13 characters written to output"

```
## Conversion Specifiers:

the re-built printf function supports the same conversion specifiers as the standard printf function:

%d or %i: Prints an integer
%c: Prints a character
%s: Prints a string
%f: Prints a floating-point number
%x: Prints an integer in hexadecimal form

## Limitations:
This re-built implementation of printf does not support all the features that the standard printf function does, such as:

Precision specifier (e.g. %.2f)
Width specifier (e.g. %5d)
Flags (e.g. %-d)

## Building:
To use the re-built printf function in your program, you will need to include the "printf_rebuild.h" header file and link against the "printf_rebuild.c" file.

## Conclusion
