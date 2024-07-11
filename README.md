# Libft, My Very First C Library and programming toolbox!

![ToolBox](https://raw.githubusercontent.com/isilva-t/42.Mile.1_tools/main/01_libft/assets/toolbox.jpg)

## About

Libft is my implementation of a personal C library containing common functions that will be used throughout my future projects. Rather than just using existing standard library functions, this project challenged me to recreate these functions from scratch, helping me develop a deeper understanding of how they work under the hood.

## Key Benefits of Building Your Own Library

- **Understanding Core Mechanics**: By reimplementing standard functions, I've gained insight into how they actually work
- **Memory Management Practice**: Working directly with memory allocation and ensuring no leaks
- **Strengthening Programming Logic**: Solving complex problems with simple, efficient solutions
- **Building a Toolbox**: Creating a collection of reliable functions for future projects
- **Foundation for C Programming**: Learning good practices with proper error handling and edge cases

## What's Inside

### Libc Functions
Reimplemented versions of various standard C library functions:

- **Character Functions**: `ft_isalpha`, `ft_isdigit`, `ft_isalnum`, `ft_isascii`, `ft_isprint`, `ft_toupper`, `ft_tolower`
- **String Functions**: `ft_strlen`, `ft_strchr`, `ft_strrchr`, `ft_strncmp`, `ft_strnstr`, `ft_strlcpy`, `ft_strlcat`, `ft_strdup`
- **Memory Functions**: `ft_memset`, `ft_bzero`, `ft_memcpy`, `ft_memmove`, `ft_memchr`, `ft_memcmp`, `ft_calloc`
- **Conversion Functions**: `ft_atoi`

### Additional Functions
Functions not in the C standard library but useful for common operations:

- **String Manipulation**: `ft_substr`, `ft_strjoin`, `ft_strtrim`, `ft_split`, `ft_strmapi`, `ft_striteri`
- **Number to String**: `ft_itoa`
- **File Output**: `ft_putchar_fd`, `ft_putstr_fd`, `ft_putendl_fd`, `ft_putnbr_fd`

### Bonus: Linked List Functions
Functions for creating and manipulating linked lists:

- `ft_lstnew`, `ft_lstadd_front`, `ft_lstsize`, `ft_lstlast`, `ft_lstadd_back`
- `ft_lstdelone`, `ft_lstclear`, `ft_lstiter`, `ft_lstmap`

## Why Build Instead of Import?

While it would be simpler to just use the standard library functions, reimplementing them:

1. **Develops deeper understanding** of common algorithms and data structures
2. **Improves debugging skills** by working with low-level operations
3. **Creates customizable functions** tailored to specific project needs
4. **Builds confidence** in handling complex programming challenges

This project serves as a foundation for my journey in C programming, giving me the tools and knowledge to approach more complex challenges with a solid understanding of the fundamentals.

