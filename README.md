# Libft

This project is a C library of useful functions that we will use in the future projects.

## Table of Contents

- [About](#about)
- [Functions](#functions)
  - [Functions from `<ctype.h>`](#functions-from-ctypeh)
  - [Functions from `<string.h>`](#functions-from-stringh)
  - [Functions from `<stdlib.h>`](#functions-from-stdlibh)
  - [Non-standard functions](#non-standard-functions)
  - [Linked list functions](#linked-list-functions)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installing](#installing)
- [Usage](#usage)
- [Built Using](#built-using)
- [Authors](#authors)
- [Acknowledgements](#acknowledgements)
- [License](#license)

## About

Libft is a library of useful functions that we will use in the future projects. The library is written in C and is based on the standard C library. The project is a part of the School 21 curriculum.

## Functions

### Functions from `<ctype.h>`

- [`ft_isalpha`](ft_isalpha.c) - checks  for  an  alphabetic  character.
- [`ft_isdigit`](ft_isdigit.c) - checks for a digit (0 through 9).
- [`ft_isalnum`](ft_isalnum.c) - checks for an alphanumeric character.
- [`ft_isascii`](ft_isascii.c) - checks whether c fits into the ASCII character set.
- [`ft_isprint`](ft_isprint.c) - checks for any printable character.
- [`ft_toupper`](ft_toupper.c) - convert char to uppercase.
- [`ft_tolower`](ft_tolower.c) - convert char to lowercase.

### Functions from `<string.h>`

- [`ft_memset`](ft_memset.c) - fill memory with a constant byte.
- [`ft_strlen`](ft_strlen.c) - calculate the length of a string.
- [`ft_bzero`](ft_bzero.c) - zero a byte string.
- [`ft_memcpy`](ft_memcpy.c) - copy memory area.
- [`ft_memmove`](ft_memmove.c) - copy memory area.
- [`ft_strlcpy`](ft_strlcpy.c) - copy string to an specific size.
- [`ft_strlcat`](ft_strlcat.c) - concatenate string to an specific size.
- [`ft_strchr`](ft_strchr.c) - locate character in string.
- [`ft_strrchr`](ft_strrchr.c) - locate character in string.
- [`ft_strncmp`](ft_strncmp.c) - compare two strings.
- [`ft_memchr`](ft_memchr.c) - scan memory for a character.
- [`ft_memcmp`](ft_memcmp.c) - compare memory areas.
- [`ft_strnstr`](ft_strnstr.c) - locate a substring in a string.
- [`ft_strdup`](ft_strdup.c) - creates a dupplicate for the string passed as parameter.

### Functions from `<stdlib.h>`

- [`ft_atoi`](ft_atoi.c) - convert a string to an integer.
- [`ft_calloc`](ft_calloc.c) - allocates memory and sets its bytes' values to 0.

### Non-standard functions

- [`ft_substr`](ft_substr.c) - returns a substring from a string.
- [`ft_strjoin`](ft_strjoin.c) - concatenates two strings.
- [`ft_strtrim`](ft_strtrim.c) - trims the beginning and end of string with specific set of chars.
- [`ft_split`](ft_split.c) - splits a string using a char as parameter.
- [`ft_itoa`](ft_itoa.c) - converts a number into a string.
- [`ft_strmapi`](ft_strmapi.c) - applies a function to each character of a string.
- [`ft_striteri`](ft_striteri.c) - applies a function to each character of a string.
- [`ft_putchar_fd`](ft_putchar_fd.c) - output a char to a file descriptor.
- [`ft_putstr_fd`](ft_putstr_fd.c) - output a string to a file descriptor.
- [`ft_putendl_fd`](ft_putendl_fd.c) - output a string to a file descriptor, followed by a new line.
- [`ft_putnbr_fd`](ft_putnbr_fd.c) - output a number to a file descriptor.

### Linked list functions

- [`ft_lstnew`](ft_lstnew.c) - creates a new list element.
- [`ft_lstadd_front`](ft_lstadd_front.c) - adds an element at the beginning of a list.
- [`ft_lstsize`](ft_lstsize.c) - counts the number of elements in a list.
- [`ft_lstlast`](ft_lstlast.c) - returns the last element of the list.
- [`ft_lstadd_back`](ft_lstadd_back.c) - adds an element at the end of a list.
- [`ft_lstclear`](ft_lstclear.c) - deletes and free list.
- [`ft_lstiter`](ft_lstiter.c) - applies a function to each element of a list.
- [`ft_lstmap`](ft_lstmap.c) - applies a function to each element of a list.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them.

```text
gcc >= 7.5.0
make >= 4.1
```

```bash
sudo apt-get install make
sudo apt-get install gcc
```

### Installing

A step by step series of examples that tell you how to get a development env running.

Clone the repository.

```bash
git clone https://github.com/LudwigAndreas/libft

cd libft
```

Build the project.

```bash
make
```

It will compile the library and create a static library file `libft.a`.

## Usage

To use the library in your project, include the header file `libft.h` in your source files and compile the library with your source files.

```c
#include "libft.h"

int main(void)
{
    char *str = "Hello, World!";
    ft_putstr_fd(str, 1);
    return (0);
}
```

## Built Using

- [C](https://en.wikipedia.org/wiki/C_(programming_language)) - Programming language
- [Make](https://en.wikipedia.org/wiki/Make_(software)) - Build automation tool

## Authors

This project was developed by:

| <img src="https://avatars.githubusercontent.com/u/88089961?v=4" alt="drawing" width="50"/> |[LudwigAndreas](https://github.com/LudwigAndreas)|
| --- | --- |

## Acknowledgements

- [School 21](https://21-school.ru/) - Educational institution

## License

This project is licensed under the School 21 License - see the [LICENSE](LICENSE) file for details.
