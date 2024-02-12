# modren_python Learning : PIAIC171375

# Project Setup Guide

This guide explains how to set up the development environment using Anaconda, Visual Studio Code (VS Code), and Python.

## YouTube Tutorial Link 
[2 hours live session](https://www.youtube.com/watch?v=rwDHhx76MMg)

## Prerequisites

- [Anaconda](https://www.anaconda.com/products/individual#Downloads)
- [VS Code](https://code.visualstudio.com/Download)

---

## Table of Contents

1. [Running a "Hello World" Program](#running-a-hello-world-program)
2. [Setting Up a Virtual Environment](#setting-up-a-virtual-environment)
 

# Class 2: String Formatting and Definitions in Python with Static Typing

## Youtube link 
2 hours live session: https://youtube.com/live/rwDHhx76MMg
## Table of Contents

- [String Definitions](#string-definitions)
- [String Formatting](#string-formatting)
  - [Basic Techniques](#basic-techniques)
  - [Advanced Techniques](#advanced-techniques)
- [Naming Conventions](#naming-conventions)

# Class 3: Operators

# Python Basics

This guide briefly introduces some of the foundational concepts in the Python programming language, including:

- Python Operators
- Comments
- Zen of Python

## Youtube link 
2 hours live session: https://youtube.com/live/CLM7FxMH7vw

Python supports a variety of operators, which can be categorized as:

- **Arithmetic Operators**: 
  - `+` : Addition
  - `-` : Subtraction
  - `*` : Multiplication
  - `/` : Division
  - `%` : Modulus
  ![Alt text](Whiteboard%5B2%5D-01.png)
  - `**`: Exponentiation
  - `//`: Floor division
  
- **Comparison Operators**: `==`, `!=`, `>`, `<`, `>=`, `<=`
- **Logical Operators**: `and`, `or`, `not`, `:=`
- ... and many more.

For a comprehensive list, refer to the [official Python documentation](https://docs.python.org/3/reference/operators.html).

## Comments

In Python, comments are lines that are not executed by the interpreter. They're used to explain code and improve readability.

- **Single-line comment**: Starts with `#`
  ```python
  # This is a single-line comment
  print("Hello, World!")  # This is an inline comment
  ```

- **Multi-line comment**: Python doesn't have explicit multi-line comment syntax, but you can use triple-quoted strings.
  ```python
  '''
  This is a multi-line
  comment or docstring
  '''
  print("Hello, World!")
  ```

## Zen of Python

The Zen of Python is a collection of 19 aphorisms that capture the philosophy of the Python language. To view them, simply run the following command in your Python environment:

```python
import this
```

# Class 4 : Python Lists and Their Methods

In this guide, we'll explore Python lists, their features, and the available methods. Lists are one of the most versatile and commonly used data types in Python.

## Youtube link 
2 hours live session: https://youtube.com/live/NzFLZkVtwMw

## Table of Contents

1. [Introduction to Lists](#introduction-to-lists)
2. [Indexing](#indexing)
3. [Slicing](#slicing)
4. [Positive and Negative Indexing](#positive-and-negative-indexing)
5. [List Methods in Python](#list-methods-in-python)

## Introduction to Lists

A list in Python is an ordered collection of items. Lists can contain a mix of different data types, including numbers, strings, and other lists. Lists are created by placing the items inside square brackets `[]`, separated by commas.

Example:
```python
fruits = ["apple", "banana", "cherry"]
```

## Indexing

You can access individual items in a list using an index. Indices start at 0 for the first item, 1 for the second, and so on.

Example:
```python
print(fruits[0])  # Outputs: apple
```

## Slicing

Slicing allows you to obtain a subset of items from a list. The syntax for slicing is `list[start:stop:step]`.

Example:
```python
print(fruits[1:3])  # Outputs: ['banana', 'cherry']
```

## Positive and Negative Indexing

- **Positive Indexing**: Starts from the beginning of the list.
  
  Example:
  ```python
  print(fruits[1])  # Outputs: banana
  ```

- **Negative Indexing**: Starts from the end of the list.
  
  Example:
  ```python
  print(fruits[-1])  # Outputs: cherry
  ```

## List Methods in Python

Python lists come with a set of built-in methods:

- `append()`: Adds an element to the end of the list.
- `clear()`: Removes all elements from the list.
- `copy()`: Returns a copy of the list.
- `count()`: Returns the number of elements with the specified value.
- `extend()`: Adds elements from another list (or any iterable) to the current list.
- `index()`: Returns the index of the first element with the specified value.
- `insert()`: Adds an element at a specified position.
- `pop()`: Removes the element at a specified position.
- `remove()`: Removes the first item with the specified value.
- `reverse()`: Reverses the order of the list.
- `sort()`: Sorts the list.

For more details and examples on each method, refer to the [official Python documentation](https://docs.python.org/3/tutorial/datastructures.html#more-on-lists).