Day 1: Basics of Functions
Objective: Understand the fundamentals of functions, including defining functions, parameters, arguments, and return values.

What is a Function?
A function is a block of reusable code that performs a specific task. It helps make code more organized, modular, and reusable.

Defining a Function:
Functions in Python are defined using the def keyword.


1.1 Basic Function Structure
Syntax:
def function_name():
    # code to execute


Example:
def greet():
    print("Hello, world!")

This defines a function named greet that prints "Hello, world!" when called.


Calling a Function:
To execute a function, you simply "call" it by using its name followed by parentheses.

greet()  # Output: Hello, world!


Exercise:
Define a function welcome that prints "Welcome to Python functions!" and then call it.


1.2 Function Parameters and Arguments
Parameters are variables in a function definition that receive values from arguments.
Arguments are the values you pass to the function when calling it.

Example:
def greet(name):
    print(f"Hello, {name}!")


greet("Alice")  # Output: Hello, Alice!

Here, name is a parameter, and "Alice" is an argument.


Exercise:
1. Define a function square that takes a number as a parameter and prints its square.


1.3 Return Statement
Functions can return a value using the return keyword.

Example:
def add(a, b):
    return a + b

result = add(3, 5)
print(result)  # Output: 8


Here, the add function takes two parameters and returns their sum.


Exercise:
2. Define a function multiply that takes two numbers as parameters and returns their product.



1.4 Function with Default Parameters
You can set default values for parameters, which are used if no argument is passed.

def greet(name="Guest"):
    print(f"Hello, {name}!")

greet()         # Output: Hello, Guest!
greet("Alice")  # Output: Hello, Alice!



Exercise:
2. Define a function power that takes two parameters, base and exponent, with exponent having a default value of 2. Return the result of base raised to the exponent.

