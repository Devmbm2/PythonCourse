# Python Syntax

"In Python, semicolons are not necessary to terminate lines of code. Line breaks serve to end a line of code, and a new line automatically begins a new code line. 

in other languages such as:

php
```
echo('Hi, how are you?');
```
In Python, it would be written as:
```python
print('Hi, how are you?')
```


Python Indentation:
In Python, indentation refers to the spaces or tabs at the beginning of a code line. Unlike in many other languages where indentation is simply for readability, in Python, it plays a crucial role in defining the structure/scope of the code.

in php
```
if(3 > 2) 
{
 echo ('3 is greater');
}
```

in python 
```
if 3 > 2 :
  print('3 is greater')
```


 
common errors 


Python will give you an error if you skip the indentation

```
if 3 > 2:
print("Three is greater")

```



You have to use the same number of spaces in the same block of code, otherwise Python will give you an error
```

if 5 > 4:
 print("Five is greater")
        print("Five is greater")
        
 ```