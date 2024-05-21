# Python String

Strings in Python are sequences of characters enclosed within single quotes (' '), double quotes (" "), triple single quotes (''' '''), or triple double quotes (""" """). They are one of the most commonly used data types in Python.

```
single_quoted_str = 'Hello, World!'
double_quoted_str = "Hello, World!"
print(single_quoted_str)
print(double_quoted_str)

```
### multiple line String

Triple quotes are used for multi-line strings or strings that contain both single and double quotes:

```

multi_line = '''This is a string
that spans multiple lines.'''

multi_line_2 = """You can also use double quotes
for multi-line strings."""

print(multi_line)
print(multi_line_2)

```

You can access individual characters in a string using indexing (starting at 0 for the first character):

```

my_string = "Hello"
first_character = my_string[0]  # 'H'
last_character = my_string[-1]  # 'o'
print(first_character)
print(last_character)

```


### Slicing Strings

You can slice strings to get substrings:

```
my_string='Hello'
substring = my_string[1:4]  # 'ell'
print(substring)

```
### String Methods

Python provides many built-in methods for string manipulation:

len(): Returns the length of the string.
lower() and upper(): Convert the string to lowercase or uppercase.
strip(): Removes leading and trailing whitespace.

```
my_string='Hello'
length = len(my_string) 
print(length)

lower_string = my_string.lower()  # 'hello'
upper_string = my_string.upper()  # 'HELLO'
stripped_string = "   Hello   ".strip()  # 'Hello'

```

