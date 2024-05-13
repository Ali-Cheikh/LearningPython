# Lesson 4: Python File Handling

## Introduction to File Handling

In Python, file handling is an essential part of working with data. It allows us to read from and write to files on our system.

## Reading from Files

To read from a file in Python, we can use the `open()` function with the file mode set to `'r'`.

```python

with open('example.txt', 'r') as file:

    content = file.read()

    print(content)

```

## Writing to Files

To write to a file in Python, we can use the `open()` function with the file mode set to `'w'`.

```python

with open('example.txt', 'w') as file:

    file.write('Hello, world!')

```

## Appending to Files

To append to a file in Python, we can use the `open()` function with the file mode set to `'a'`.

```python

with open('example.txt', 'a') as file:

    file.write('\nAppending new content!')

```

## Exercises

1\. Write a Python program to count the number of lines in a text file.

2\. Create a program to read a CSV file and print its contents.

3\. Implement a Python function to copy the contents of one text file to another.

## Lesson 5: Python Modules and Packages

## Introduction to Modules and Packages

In Python, modules are files containing Python code, and packages are directories containing Python modules. They help in organizing and reusing code.

## Importing Modules

To import a module in Python, we can use the `import` statement.

```python

import math

print(math.pi)

```

## Creating Modules

We can create our own modules by saving Python code in a `.py` file.

```python

# mymodule.py

def greet(name):

    print(f'Hello, {name}!')

```

# Importing from Packages

To import from a package, we can use dot notation.

```python

from mypackage import mymodule

mymodule.greet('Alice')

```

## Exercises

1\. Write a Python module that contains a function to calculate the area of a circle.

2\. Create a package with multiple modules, each containing functions related to a specific topic (e.g., math, strings, files).

3\. Implement a Python program that imports functions from different modules within a package and uses them to perform a task.
