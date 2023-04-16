# Python Variables

Python variables are the reserved memory locations used to store values with in a Python Program. This means that when you create a variable you reserve some space in the memory.

Based on the data type of a variable, Python interpreter allocates memory and decides what can be stored in the reserved memory. Therefore, by assigning different data types to Python variables, you can store integers, decimals or characters in these variables

## Creating Python Variables

Python variables do not need explicit declaration to reserve memory space or you can say to create a variable. A Python variable is created automatically when you assign a value to it. The equal sign (=) is used to assign values to variables.

The operand to the left of the = operator is the name of the variable and the operand to the right of the = operator is the value stored in the variable.
For example −
```
name = "Pavankumar"
number = 10
python_variables = "python"
```

## Printing Python Variables

Once we create a Python variable and assign a value to it, we can print it using print() function. Following is the extension of previous example and shows how to print different variables in Python:

```
# Creating variable and assigning the values
name = "Pavankumar"
number = 10
python_variables = "python"

# printing the variable value
print(name)
print(number)
print(python_variables)
```

## Multiple Assignment (assigning the multiple values)
Python allows you to assign a single value to several variables simultaneously which means you can create multiple variables at a time. For Example 1 −

```
a = b = c = 100

print (a)
print (b)
print (c)

# Output  
100
100
100
```
Example 2 −

```
a,b,c = 1,2,"Pavankumar"

print (a)
print (b)
print (c)

# output 
1
2
Pavankumar
```

Here, two integer objects with values 1 and 2 are assigned to variables a and b respectively, and one string object with the value "Pavankumar" is assigned to the variable c.

## Python Variable Names

Every Python variable should have a unique name like a, b, c. A variable name can be meaningful like color, age, name etc. There are certain rules which should be taken care while naming a Python variable:


- A variable name must start with a letter or the underscore character
- A variable name cannot start with a number or any special character like $, (, * % etc.
- A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
- Python variable names are case-sensitive which means Name and NAME are two different variables in Python.
- Python reserved keywords cannot be used naming the variable.


Example 1:-
```
# Following are valid Python variable names:

counter = 100
_count  = 100
name1 = "Pavankumar"
name2 = "Jack"
Age  = 20
pavan_salary = 100000

print (counter)
print (_count)
print (name1)
print (name2)
print (Age)
print (pavan_salary)

# This will produce the following result:

100
100
Pavankumar
Jack
20
100000

```

Example 2: 

```
# Following are invalid Python variable names:

1counter = 100
$_count  = 100
pavan-salary = 100000

print (1counter)
print ($count)
print (pavan-salary)


# This will produce the following result:

File "main.py", line 3
    1counter = 100
           ^
SyntaxError: invalid syntax
```

## Python Local Variable 

Python Local Variables are defined inside a function. We can not access variable outside the function.

Following is an example to show the usage of local variables:

```
def sum(x,y):
   sum = x + y
   return sum
print(sum(5, 10))

# output 15
```

## Python Global Variable

Any variable created outside a function can be accessed within any function and so they have global scope.

Python global is a keyword that allows a user to modify a variable outside of the current scope. It is used to create global variables from a non-global scope i.e inside a function. Global keyword is used inside a function only when we want to do assignments or when we want to change a variable. Global is not needed for printing and accessing.

Following is an example of global variables:

```
x = 5
y = 10
def sum():
   sum = x + y
   return sum
print(sum())

# output 15
```

### Rules of global keyword

- If a variable is assigned a value anywhere within the function’s body, it’s assumed to be local unless explicitly declared as global.
- Variables that are only referenced inside a function are implicitly global.
- We use a global in Python to use a global variable inside a function.
- There is no need to use a global keyword in Python outside a function.


<br>

You may use this tutorial freely at your own risk. See [LICENSE](https://github.com/hegdepavankumar/python-zero-to-hero/blob/main/LICENSE). <br>

| [Next](https://github.com/hegdepavankumar/python-zero-to-hero/blob/master/Day_02_Variables_%26_Data_Types/02_python_data_types.md) | [List of contents](https://github.com/hegdepavankumar/python-zero-to-hero/blob/master/list_of_contents.md) |







































