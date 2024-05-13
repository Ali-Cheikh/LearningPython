# Lesson 2: Python Functions

**Objective:**
- Understand the concept of functions in Python.
- Learn how to define and call functions.
- Explore function parameters and return values.

**Table of Contents:**
1. [Introduction to Functions](#1-introduction-to-functions)
2. [Defining and Calling Functions](#2-defining-and-calling-functions)
3. [Function Parameters and Return Values](#3-function-parameters-and-return-values)
4. [Examples](#4-examples)
5. [Exercises](#5-exercises)

---

### 1. Introduction to Functions

In Python, a function is a block of reusable code designed to perform a specific task. Functions provide modularity and code reusability by allowing you to encapsulate a sequence of statements into a single unit. 

### 2. Defining and Calling Functions

#### Defining a Function

A function in Python is defined using the `def` keyword, followed by the function name and parentheses `( )`. You can optionally specify parameters within the parentheses.

```python
def greet():
    print("Hello, world!")

def greet_user(name):
    print("Hello, " + name + "!")
```
markdown

Copy code

`## Calling a Function

To call a function, simply write its name followed by parentheses `()`.

```python
greet()  # Output: Hello, world!
greet_user("John")  # Output: Hello, John! `
```
### Function Parameters and Return Values

#### Parameters

Parameters are placeholders for data that can be passed into a function. You can define functions with parameters to accept input data.

```python

def add(x, y):
    return x + y
```
#### Return Values

A function can return data using the `return` statement. This allows functions to produce output that can be used by other parts of the program.

```python
def add(x, y):
   return x + y
```
### Examples

#### Example 1: Addition Function

```python

def add(x, y):
   return x + y

result = add(3, 5)
print("Result of addition:", result)  # Output: 8
```
#### Example 2: Greeting Function

```python

def greet_user(name):
    return "Hello, " + name + "!"

message = greet_user("Alice")
print(message)  # Output: Hello, Alice!
```
### Exercises

1.  Write a Python function to calculate the factorial of a number.
2.  Create a function to check if a given number is prime.
3.  Implement a function to reverse a string.

* * * * *
