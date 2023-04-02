# Ft_printf

It is a library function that mimics the functionality of the standard printf function in C.

## Installation

To use ft_printf in your project, follow these steps:

1. Clone the repository: `git clone https://github.com/raanki/ft_printf.git`
2. Change into the project directory: `cd ft_printf`
3. Compile the library: `make`

## Usage

To use ft_printf in your project, include the following header file in your code:


Then, you can use the ft_printf function to output formatted text to the standard output stream. For example:

```

#include "ft_printf.h"

int main(void) {
    ft_printf("Hello, world!\n");
    return 0;
}
```

This will output "Hello, world!" to the standard output stream.
Format Specifiers

ft_printf supports the following format specifiers:

    %c: Character
    %s: String
    %p: Pointer
    %d and %i: Signed decimal integer
    %u: Unsigned decimal integer
    %x and %X: Unsigned hexadecimal integer (lowercase and uppercase, respectively)
    %o: Unsigned octal integer
    %%: Literal percent sign


## Troubleshooting

If you encounter any issues while using ft_printf, try the following solutions:

    Make sure you are including the correct header file in your code.
    Make sure you are using the correct format specifiers and flags for your output.
    If you encounter any bugs or issues, please report them on the project's GitHub page.
