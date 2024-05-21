# Python Variables

Python has no command for declaring a variable.

A variable is created the moment you  assign a value to it.

```
n1 = 2
n2 = 3
sum = 2+3
print (sum)

```

Next example
the value assign after will remove the first one and will take it place 

```
number = 4
number = 'four'
print(number)

```

# Variable Names

Starts with a letter (A-Z) or underscore (_), not a number (0-9).

Contains only alphanumeric characters (A-Z, 0-9) and underscores (_).

Case-sensitive (e.g., "age", "Age", and "AGE" are treated as different variables).

### Reserved Python Keywords

You cannot use reserved keywords as variable names. Reserved keywords are words that have special meanings in Python.
Here is a list of reserved keywords:
for , in , as , and  , or 


example of legal name 

```
firstname     = "bilal"
first_name   = "bilal"
_first_name = "bilal"
firstName     = "bilal"
FIRSTNAME = "bilal"
firstname2    = "bilal"

```

example of illegal name

```
2firstname   = "bilal"
first-name    = "bilal"
first name    = "bilal"
#firstname   = "bilal"

```


### Many Values to Multiple Variables
Python allows you to assign values to multiple variables in one line:

```
x, y, z = "one", "two", "three"
print(x)
print(y)
print(z)

```

Note: Make sure the number of variables matches the number of values, or else you will get an error.

### One Value to Multiple Variables
And you can assign the same value to multiple variables in one line:

Example

```
x = y = z = "three"
print(x)
print(y)
print(z)

```

# output

print() function is often used to output 
output multiple variables should be  separated by a comma

```
x = "programmer"
y = "chachu"
print(x, y)

```

you can also use + but of same Data types only

```
x = "programmer"
y = "chachu"
print(x+y)

```