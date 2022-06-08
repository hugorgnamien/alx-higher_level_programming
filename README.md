# 0x01. Python - if/else, loops, functions
## About
An introductory project on:
- How to use the `if`, `if ... else` statements
- How to use comments
- How to affect values to variables
- How to use the `while` and `for` loops
- How Python’s `for` different from C‘s
- How to use the `break` and `continues` statements
- How to use `else` clauses on loops
- What the `pass` statement does, and when to use it
- How to use `range`
- Functions and how to use them
- What functions without `return` statements return
- Variable scope
- Tracebacks
- Arithmetic operators and how to use them

## Requirements
- Python 3.4
- pep8 1.7
## File Descriptions
### Mandatory
**[0-positive_or_negative.py](./0-positive_or_negative.py)** - This program will assign a random signed number to the variable `number` each time it is executed. Complete the [source code](https://intranet.hbtn.io/rltoken/2S3G4vOnRrWymCjKYd6Wew) in order to print whether the number stored in the variable `number` is positive or negative.
  - The variable `number` will store a different value every time you run this program
  - The output of the program should be:
    - The number, followed by:
      - if the number is greater than 0: `is positive`
      - if the number is 0: `is zero`
      - if the number is less than 0: `is negative`
    - followed by a new line

**[1-last_digit.py](./1-last_digit.py)** - This program will assign a random signed number to the variable `number` each time it is executed. Complete the [source code](https://intranet.hbtn.io/rltoken/e9k9---MJXcMmIjlMdlBpw) in order to print the last digit of the number stored in the variable `number`.
  - The variable `number` will store a different value every time you run this program
  - The output of the program should be:
    - The string `Last digit of`, followed by
    - the number, followed by
    - the string `is`, followed by
      - if the number is greater than 5: the string `and is greater than 5`
      - if the number is 0: the string `and is 0`
      - if the number is less than 6 and not 0: the string `and is less than 6 and not 0`
    - followed by a new line

**[2-print_alphabet.py](./2-print_alphabet.py)** - Write a program that prints the alphabet, in lowercase, not followed by a new line.
  - You can only use one `print` function with string format
  - You can only use one loop in your code
  - You are not allowed to store characters in a variable
  - You are not allowed to import any module

**[3-print_alphabt.py](./3-print_alphabt.py)** - Write a program that prints the alphabet, in lowercase, not followed by a new line.
  - Print all the letters except `q` and `e`
  - You can only use one `print` function with string format
  - You can only use one loop in your code
  - You are not allowed to store characters in a variable
  - You are not allowed to import any module

**[4-print_hexa.py](./4-print_hexa.py)** - Write a program that prints all numbers from 0 to 98 in decimal and in hexadecimal (as in the following example)
  - You can only use one `print` function with string format
  - You can only use one loop in your code
  - You are not allowed to store numbers or strings in a variable
  - You are not allowed to import any module
  - Example:
  ```
  0 = 0x0
  ...
  10 = 0xa
  ...
  98 = 0x62
  ```

**[5-print_comb2.py](./5-print_comb2.py)** - Write a program that prints numbers from 0 to 99.
  - Numbers must be separated by `,` followed by a space
  - Numbers should be printed in ascending order, with two digits
  - The last number should be followed by a new line
  - You can only use no more than 2 `print` functions with string format
  - You can only use one loop in your code
  - You are not allowed to store numbers or strings in a variable
  - You are not allowed to import any module

**[6-print_comb3.py](./6-print_comb3.py)** - Write a program that prints all possible different combinations of two digits.
  - Numbers must be separated by `,` followed by a space
  - The two digits must be different
  - 01 and 10 are considered the same combination of the two digits 0 and 1
  - Print only the smallest combination of two digits
  - Numbers should be printed in ascending order, with two digits
  - The last number should be followed by a new line
  - You can only use no more than 3 `print` functions with string format
  - You can only use no more than 2 loops in your code
  - You are not allowed to store numbers or strings in a variable
  - You are not allowed to import any module

**[7-islower.py](./7-islower.py)** - Write a function that checks for lowercase character.
  - Prototype: `def islower(c):`
  - Returns `True` if `c` is lowercase
  - Returns `False` otherwise
  - You are not allowed to import any module
  - You are not allowed to use `str.upper()` and `str.isupper()`

**[8-uppercase.py](./8-uppercase.py)** - Write a function that print a string in uppercase followed by a new line.
  - Prototype: `def uppercase(str):`
  - You can only use no more than 2 `print` functions with string format
  - You can only use one loop in your code
  - You are not allowed to import any module
  - You are not allowed to use `str.upper()` and `str.isupper()`

**[9-print_last_digit.py](./9-print_last_digit.py)** - Write a function that prints the last digit of a number.
  - Prototype: `def print_last_digit(number):`
  - Returns the value of the last digit
  - You are not allowed to import any module

**[10-add.py](./10-add.py)** - Write a function that adds two integers and returns the result.
  - Prototype: `def add(a, b):`
  - Returns the value of `a + b`
  - You are not allowed to import any module

**[11-pow.py](./11-pow.py)** - Write a function that computes `a` to the power of `b` and return the value.
  - Prototype: `def pow(a, b):`
  - Returns the value of `a ^ b`
  - You are not allowed to import any module

**[12-fizzbuzz.py](./12-fizzbuzz.py)** - Write a function that prints the numbers from 1 to 100 separated by a space.
  - For multiples of three print `Fizz` instead of the number and for multiples of five print `Buzz`.
  - For numbers which are multiples of both three and five print `FizzBuzz`.
  - Prototype: `def fizzbuzz():`
  - Each element should be followed by a space
  - You are not allowed to import any module
### Advanced
**[100-print_tebahpla.py](./100-print_tebahpla.py)** - Write a program that prints the alphabet, in reverse order, alternating lowercase and uppercase (`z` in lowercase and `Y` in uppercase) , not followed by a new line.
  - You can only use one `print` function with string format
  - You can only use one loop in your code
  - You are not allowed to store characters in a variable
  - You are not allowed to import any module

**[101-remove_char_at.py](./101-remove_char_at.py)** - Write a function that creates a copy of the string, removing the character at the position `n` (not including negative indices).
  - Prototype: `def remove_char_at(str, n):`
  - You are not allowed to import any module

**[102-magic_calculation.py](./102-magic_calculation.py)** - Write the Python function `def magic_calculation(a, b, c):` that does exactly the same as the following Python bytecode:
```
  3           0 LOAD_FAST                0 (a)
              3 LOAD_FAST                1 (b)
              6 COMPARE_OP               0 (<)
              9 POP_JUMP_IF_FALSE       16

  4          12 LOAD_FAST                2 (c)
             15 RETURN_VALUE

  5     >>   16 LOAD_FAST                2 (c)
             19 LOAD_FAST                1 (b)
             22 COMPARE_OP               4 (>)
             25 POP_JUMP_IF_FALSE       36

  6          28 LOAD_FAST                0 (a)
             31 LOAD_FAST                1 (b)
             34 BINARY_ADD
             35 RETURN_VALUE

  7     >>   36 LOAD_FAST                0 (a)
             39 LOAD_FAST                1 (b)
             42 BINARY_MULTIPLY
             43 LOAD_FAST                2 (c)
             46 BINARY_SUBTRACT
             47 RETURN_VALUE
```alx-higher_level_programming