# Python Comments
- In this tutorial, we will learn about Python statements, why we use them, and how to use comments in the right way.
- Comments should always be complete and concise sentences.
- It’s better to have no comment at all than one that’s difficult to understand or inaccurate.
- Comments should be updated regularly to reflect changes in your code.
- Too many comments can be distracting and reduce code quality. Comments aren’t needed where the code’s purpose is obvious.

- In computer programming, comments are hints that we use to make our code more understandable.
- Comments are completely ignored by the interpreter. They are meant for fellow programmers. For example,
```
firstname = "Pavankumar"  #This is first name
lastname = "Hegde"

print(firstname + " " + lastname) # printing firstname and lastname
# Output  Pavankumar Hegde
```

## Types of Comments in Python

There are three types of comments in Python:

- Single line Comments
- Multiline Comments
- Docstring Comments

1. Single-Line Comments in Python (#)

Python single-line comment starts with the hashtag symbol (#) with no white spaces and lasts till the end of the line. If the comment exceeds one line then put a hashtag on the next line and continue the comment. Python’s single-line comments are proved useful for supplying short explanations for variables, function declarations, and expressions. See the following code snippet demonstrating single line comment:

Example: 
```
# This is Single-Line Comments in Python
print("Hi Coders")
```

2. Multi-Line Comments in Python

Python does not provide the option for multiline comments. However, there are different ways through which we can write multiline comments.

Multiline comments using multiple hashtags (#)

We can multiple hashtags (#) to write multiline comments in Python. Each and every line will be considered as a single-line comment.

Example 1:
```
''' This is also a
perfect example of
multi-line comments '''
```
Example 2:
```
#This is a comment
#written in
#more than just one line
print("Hello, World!")
```

3. Docstring in Python

Python docstring is the string literals with triple quotes that are appeared right after the function. It is used to associate documentation that has been written with Python modules, functions, classes, and methods. It is added right below the functions, modules, or classes to describe what they do. In Python, the docstring is then made available via the __doc__ attribute.

Example:
```
def multiply(a, b):
	"""Multiplies the value of a and b"""
	return a*b


# Print the docstring of multiply function
print(multiply.__doc__)

# Output  Multiplies the value of a and b
```
<br>

You may use this tutorial freely at your own risk. See [LICENSE](https://github.com/hegdepavankumar/python-zero-to-hero/blob/main/LICENSE). <br>

| [Next](https://github.com/hegdepavankumar/python-zero-to-hero/blob/master/Day_01_Python_Introduction/04_Exercise) | [List of contents](https://github.com/hegdepavankumar/python-zero-to-hero/blob/master/list_of_contents.md) |













