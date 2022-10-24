# libft
**Codam [42 Network] project**: libft is the first project of the Codam curriculum. The aim of this project is to write your own C library and (re)code a selection of functions that can be used for C projects throughout the curriculum. This project consists of three parts:

1) Recode a selection of libc functions as defined in their man page
2) Code a set of functions that are either not included in the libc, or included in a different form
3) Bonus part: a set of functions that allow you to easily use linked lists

The bonus part is included in this project.

**Project requirements**

- The libc funtions need to present the same prototype and behaviors as the originals
- Function names must be prefixed by ft_
- Read the full subject

**Skills**
* Rigor
* Imperative programming
* Algorithms & AI

## Instructions :clipboard:

### Clone repo

`git clone https://github.com/nvanwinden/libft.git`

### Make

Run `make` to create the `libft.a` library.<br>
Run `make bonus` to compile including the bonus functions.

# Include libft in your project

```
#include "libft.h"
#include "stdio.h"

int main () {

	char *str = ft_substr("This is how to use libft!", 19, 5);
	printf("%s\n", str);
	free(str);
	return (0);
}
```

### Compile
`gcc main.c -L. -lft -o example` 

### Run
`./example`

### Function overview

| libc functions | 42 functions | Linked list  |
| ------------- |-------------| -----|
| memset | ft_substr | ft_lstnew |
| bzero | ft_strjoin | ft_lstadd_front |
| memcpy | ft_strtrim | ft_lstsize |
| memccpy |ft_split | ft_lstlast |
| memmove | ft_itoa | ft_lstadd_back |
| memchr | ft_strmapi | ft_lstdelone |
| memcmp | ft_putchar_fd | ft_lstclear |
| strlen | ft_putstr_fd | ft_lstiter |
| strlcpy |ft_putendl_fd | ft_lstmap |
| strlcat | ft_putnbr_fd ||
| strchr |||
| strrchr |||
| strnstr |||
| strncmp |||
| atoi |||
| isalpha |||
| isdigit |||
| isalnum |||
| isascii |||
| isprint |||
| toupper |||
| tolower |||
| calloc |||
| strdup |||
