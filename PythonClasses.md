
# Lesson 3: Python Classes and Objects

## Objective:

-   Understand the concept of classes and objects in Python.
-   Learn how to define classes and create objects.
-   Explore class attributes, methods, and inheritance.

### Table of Contents:

1.  [Introduction to Classes and Objects](https://chatgpt.com/c/77203d83-df8e-4698-8fec-79bbe33865a9#1-introduction-to-classes-and-objects)
2.  [Defining Classes](https://chatgpt.com/c/77203d83-df8e-4698-8fec-79bbe33865a9#2-defining-classes)
3.  [Creating Objects](https://chatgpt.com/c/77203d83-df8e-4698-8fec-79bbe33865a9#3-creating-objects)
4.  [Class Attributes and Methods](https://chatgpt.com/c/77203d83-df8e-4698-8fec-79bbe33865a9#4-class-attributes-and-methods)
5.  [Inheritance](https://chatgpt.com/c/77203d83-df8e-4698-8fec-79bbe33865a9#5-inheritance)
6.  [Examples](https://chatgpt.com/c/77203d83-df8e-4698-8fec-79bbe33865a9#6-examples)
7.  [Exercises](https://chatgpt.com/c/77203d83-df8e-4698-8fec-79bbe33865a9#7-exercises)

* * * * *

### 1\. Introduction to Classes and Objects

In Python, a class is a blueprint for creating objects. An object is an instance of a class. Classes allow you to logically group data and functions in a structured way.

### 2\. Defining Classes

#### Class Declaration

To define a class in Python, use the `class` keyword followed by the class name.

```python

class Car:
    pass
```
#### Constructor Method

The `__init__()` method is called automatically when an object is created. It initializes object attributes.

```python

class Car:
    def __init__(self, make, model, year):
        self.make = make
        self.model = model
        self.year = year
```
### 3\. Creating Objects

To create an object of a class, simply call the class name followed by parentheses `( )`.

```python

car1 = Car("Toyota", "Corolla", 2020)
car2 = Car("Honda", "Civic", 2019)
```
### 4\. Class Attributes and Methods

#### Attributes

Attributes are variables that belong to a class or object.

```python

class Car:
    def __init__(self, make, model, year):
        self.make = make
        self.model = model
        self.year = year
```
#### Methods

Methods are functions that belong to a class or object.

```python

class Car:
    def __init__(self, make, model, year):
        self.make = make
        self.model = model
        self.year = year

    def get_description(self):
        return f"{self.year} {self.make} {self.model}"
```
### 5\. Inheritance

Inheritance allows a class to inherit attributes and methods from another class.

### 6\. Examples

#### Example 1: Creating Objects

```python

class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age

person1 = Person("Alice", 30)
person2 = Person("Bob", 25)
```
#### Example 2: Class Inheritance

```python

class Animal:
    def sound(self):
        return "Animal sound"

class Dog(Animal):
    def sound(self):
        return "Bark"

class Cat(Animal):
    def sound(self):
        return "Meow"
```
### 7\. Exercises

1.  Create a `Rectangle` class with methods to calculate its area and perimeter.
2.  Implement a `BankAccount` class with methods to deposit, withdraw, and check balance.
3.  Define a `Student` class with attributes `name`, `age`, and `grade`. Add a method to display student details.
