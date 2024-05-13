# Lesson: Introduction to Python Loops

**Objective:**  
- Understand the concept of loops in Python.
- Learn how to use `for` and `while` loops.
- Explore basic math operations.

**Table of Contents:**
1. [Introduction to Loops](#1-introduction-to-loops)
2. [Basic Math Operations](#2-basic-math-operations)
3. [Examples using `for` Loops](#3-examples-using-for-loops)
4. [Examples using `while` Loops](#4-examples-using-while-loops)
5. [Exercises](#5-exercises)

---

### 1. Introduction to Loops

In programming, loops are used to execute a block of code repeatedly. This lesson will introduce two types of loops in Python: `for` loops and `while` loops.

#### For Loops:
A `for` loop is used when you know the number of times you want to execute a block of code.

#### While Loops:
A `while` loop is used when you want to execute a block of code repeatedly as long as a condition is true.

### 2. Basic Math Operations

Before we delve into loops, let's review some basic math operations in Python:

- Addition: `+`
- Subtraction: `-`
- Multiplication: `*`
- Division: `/`
- Exponentiation: `**`
- Modulus (remainder): `%`

### 3. Examples using `for` Loops

#### Example 1: Printing Numbers from 1 to 10

```python
for i in range(1, 11):
    print(i)
```
This code will print numbers from 1 to 10.

### Example 2: Calculating Factorial of a Number

```python
num = 5
factorial = 1
for i in range(1, num + 1):
    factorial *= i
print("Factorial of", num, "is", factorial)
```

This code calculates the factorial of 5.

### Example 3: Finding Prime Numbers between 1 and 100

```python
for num in range(1, 101):
    if num > 1:
        for i in range(2, num):
            if (num % i) == 0:
                break
        else:
            print(num)
```

This code will print all prime numbers between 1 and 100.

### Examples using while Loops

#### Example 4: Countdown

```python
count = 10
while count > 0:
    print(count)
    count -= 1
```

This code will count down from 10 to 1 using a while loop.

#### Example 5: Password Validation

```python
password = ""
while password != "secret":
    password = input("Enter the password: ")
print("Access granted!")
```

This code prompts the user to enter a password until they enter "secret".

### Exercises

1. Write a Python program to find the sum of all even numbers between 1 and 50 using a for loop.
2. Create a program to generate the Fibonacci sequence up to the nth term using a for loop.
3. Implement a Python function to check if a given number is a palindrome using a while loop.

**Resources:**

Here are the Python utilities used in the examples:

- Printing Numbers from 1 to 10 using a for loop
- Calculating Factorial of a Number using a for loop
- Finding Prime Numbers between 1 and 100 using a for loop

Feel free to use this Markdown content for your teaching repository. Let me know if you need further assistance!
