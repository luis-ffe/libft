## Insight

C programming can be very tedious when one doesn’t have access to the highly useful standard functions. This project is about understanding the way these functions work, implementing and learning to use them. Your will create your own library. It will be helpful since you will use it in your next C school assignments
## HOW TO USE

Clone or download the project.

To use, include the header

Run `make` inside the project folder.

```c
#include "libft.h"
```
In case your project and libft are in different folders provide the correct path in the header include.

#### MAKEFILE RULES

`make` - Compile libft **mandatory** files.

`make bonus` - Compile libft **bonus** files.

`make all` - Compiles all previous parts.

`make clean` - Delete all .o files.

`make fclean` - Delete all .o and .a files.

`make re` - Use rules `fclean` + `all`.

#### Check and manipulate characters:

- [x] `ft_isalpha`
- [x] `ft_isdigit`
- [x] `ft_isalnum`
- [x] `ft_isascii`
- [x] `ft_toupper`
- [x] `ft_tolower`

#### Manipulate strings:

- [x] `ft_strlen`
- [x] `ft_strlcpy`
- [x] `ft_strlcat`
- [x] `ft_strchr`
- [x] `ft_strrchr`
- [x] `ft_strncmp`
- [x] `ft_strnstr`
- [x] `ft_substr`
- [x] `ft_strjoin`
- [x] `ft_strtrim`
- [x] `ft_split`
- [x] `ft_strmapi`
- [x] `ft_striteri`

#### Manipulate memory:

- [x] `ft_calloc`
- [x] `ft_memset`
- [x] `ft_bzero`
- [x] `ft_memcpy`
- [x] `ft_memmove`
- [x] `ft_memchr`
- [x] `ft_memcmp`
- [x] `ft_strdup`

#### Manipulate numbers:

- [x] `ft_atoi`
- [x] `ft_itoa`

#### Write to file descriptor:

- [x] `ft_putchar_fd`
- [x] `ft_putstr_fd`
- [x] `ft_putendl_fd`
- [x] `ft_putnbr_fd`

## BONUS

- [x] `ft_lstnew`
- [x] `ft_lstadd_front`
- [x] `ft_lstsize`
- [x] `ft_lstlast`
- [x] `ft_lstadd_back`
- [x] `ft_lstdelone`
- [x] `ft_lstclear`
- [x] `ft_lstiter`
- [x] `ft_lstmap`

## To do:

- Add a description in the .h file explaining in a coment below each function prototype exactly what the function is suposed to do.
- Importance of programing good practices to keep our work easy to understand, use and manipulate in ways that can help others.
