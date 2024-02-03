## Python concepts

Date 03/02/2024 - [Python - Scientific Computation course](https://www.freecodecamp.org/learn/scientific-computing-with-python/#learn-string-manipulation-by-building-a-cipher) from freecodecamp.org
- map() function ??
- filter() function ??
- List expressions:
  ```python
  ### function that converts pascal or camel cased string to snake cased
  def convert_to_snake_case(pascal_or_camel_cased_string):
    ### below is an example of list expression
    snake_cased_char_list = [
        '_' + char.lower() if char.isupper()
        else char
        for char in pascal_or_camel_cased_string
    ]

    return ''.join(snake_cased_char_list).strip('_')
  ```

### Regex in python
```python
import re

re.compile(expression) # compiles the expression into searchable
```

### Generator expressions
Memory can be saved by using a generator expression. Generator expressions follow the syntax of list comprehensions but they use parentheses instead of square brackets.

## Python password generator
Interesting [password generator app](https://github.com/Rupanzil/python-practice/blob/main/password_generator.py) which can generate password of any length and based on any condition such as number of alphanumeric characters, special characters, lowercase, uppercase etc.

