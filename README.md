* **This project has been created as part of the 42 curriculum by yaabed**

# Libft

Libft is the first project of the 42 Core curriculum.

The goal of this project is to create a personal C library by reimplementing standard C library functions and adding useful functions for working with strings, memory, and linked lists.

## Features

### Part 1 — Libc Functions
> A custom C library implementing standard libc functions and additional utilities for strings, memory, and linked lists.
#### **Character checks**
* ft_isalpha
* ft_isdigit
* ft_isalnum
* ft_isascii
* ft_isprint
#### String manipulation
* ft_strlen
* ft_strlcpy
* ft_strlcat
* ft_strchr
* ft_strrchr
* ft_strncmp
* ft_strnstr
#### Memory manipulation
* ft_memset
* ft_bzero
* ft_memcpy
* ft_memmove
* ft_memchr
* ft_memcmp
#### Character conversion
* ft_toupper
* ft_tolower
#### Number conversion
* ft_atoi
#### Memory allocation and duplication
* ft_calloc
* ft_strdup

### Part 2 — Additional Functions
> Additional functions for manipulating strings, converting data, iterating over characters, and writing output to file descriptors.
#### String manipulation
* ft_substr
* ft_strjoin
* ft_strtrim
* ft_split
#### Conversion
* ft_itoa
#### String iteration
* ft_strmapi
* ft_striteri
#### File descriptor output
* ft_putchar_fd
* ft_putstr_fd
* ft_putendl_fd
* ft_putnbr_fd

### Part 3 — Linked Lists
> Functions for creating, manipulating, traversing, and managing singly linked lists using the t_list structure.
#### Node creation and insertion
* ft_lstnew
* ft_lstadd_front
* ft_lstadd_back
#### List information
* ft_lstsize
* ft_lstlast
#### Node deletion and list clearing
* ft_lstdelone
* ft_lstclear
#### List iteration and transformation
* ft_lstiter
* ft_lstmap

## Compilation

The project includes a `Makefile`.

### Build the library:

```bash
make
```

### Remove object file

```bash
make clean 
```

### Remove object file and library
```bash
make clean
```
### Clean everything and rebuild
```bash
make re
```

`cc`-C compiler used to compile the source code.
`-Wall`— Enables a broad set of compiler warnings.
`-Wextra`— Enables additional compiler warnings.
`-Werror`— Treats all compiler warnings as errors.

**These flags help maintain clean, consistent, and reliable C code.**

## Sources & Acknowledgments
* **Man Pages (man) — Used standard Unix/Linux documentation (man 3, man ar, man make) for detailed reference on C library functions, Makefile rules, and archiver flags.**

* **Official GNU Documentation — Referenced the official GNU Make Manual and GCC Online Documentation for compilation flags (-Wall -Wextra -Werror) and build automation best practices.**

* **AI Assistance — Utilized AI tools for clarifying low-level C concepts, reviewing edge cases, validating logic, and refining project documentation structure.**
```
