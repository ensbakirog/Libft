Tabii, işte projeyi tanıttığınız bir metin örneği:

---

# Libft Project - Implementation Summary

## Project Overview

In this project, I developed a custom C library named `libft`, which includes implementations of various standard library functions and additional utilities. The objective was to build a foundational library to enhance my C programming skills and understanding of library creation.

## Key Components

### Mandatory Functions

1. **Standard Library Reimplementations**: I reimplemented several commonly used functions from the C standard library. These functions include:
   - `ft_strlen`: Calculates the length of a string.
   - `ft_memset`: Fills a block of memory with a specific value.
   - `ft_strchr`: Finds the first occurrence of a character in a string.
   - `ft_strcpy`: Copies a string from source to destination.
   - `ft_strcmp`: Compares two strings.
   - `ft_atoi`: Converts a string to an integer.
   - And more...

2. **Additional Utility Functions**: I also created extra functions that provide useful utilities beyond the standard library:
   - `ft_substr`: Extracts a substring from a string.
   - `ft_strjoin`: Concatenates two strings.
   - `ft_itoa`: Converts an integer to a string.
   - `ft_strtrim`: Removes leading and trailing characters from a string.
   - `ft_split`: Splits a string into an array of substrings based on a delimiter.
   - And others...

### Bonus Section

In the bonus section, I expanded the library to include functions for manipulating linked lists:
   - `ft_lstnew`: Creates a new list element.
   - `ft_lstadd_front`: Adds a new element to the front of the list.
   - `ft_lstadd_back`: Adds a new element to the end of the list.
   - `ft_lstmap`: Applies a function to each element in the list.
   - And more...

## Implementation Details

- **No Global Variables**: Ensured that no global variables are used, adhering to good programming practices.
- **Static Helper Functions**: Used `static` keyword for helper functions to limit their scope to the file in which they are defined.
- **Makefile**: Created a Makefile with rules for building the library (`make`), cleaning up object files (`make clean`), and fully cleaning (`make fclean`). Added a bonus rule (`make bonus`) for the additional linked list functions.

## Testing and Usage

To use the library:
1. **Clone the Repository**:
   ```bash
   git clone <repository_url>
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd libft
   ```

3. **Build the Library**:
   ```bash
   make
   ```

4. **Include in Your Projects**: Include the `libft.h` header file and link `libft.a` in your C projects.

5. **Test Your Functions**: Write test programs to ensure that all functions work as expected.

## Conclusion

The `libft` project was an excellent exercise in understanding and implementing fundamental C functions. It provided a solid foundation in library creation, memory management, and function implementation.
