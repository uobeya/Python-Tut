Day 2: Advanced Function Concepts
Objective: Understand advanced function concepts, including keyword arguments, variable-length arguments, and lambda functions.


2.1 Keyword Arguments
Keyword arguments allow you to specify the name of the parameter in the function call.

Example:
def introduce(name, age):
    print(f"My name is {name} and I am {age} years old.")

introduce(age=25, name="Alice")  # Output: My name is Alice and I am 25 years old.


Exercise:
Define a function book_details that takes two parameters, title and author. Call it using keyword arguments in any order.


2.2 Variable-Length Arguments
Python allows functions to accept an arbitrary number of arguments using *args for positional arguments and **kwargs for keyword arguments.

Positional Variable-Length Arguments (*args):
Use *args to pass multiple positional arguments.


Example:
def total_sum(*numbers):
    return sum(numbers)

print(total_sum(1, 2, 3, 4))  # Output: 10


Here, *numbers allows the function to accept multiple numbers and sum them up.


Exercise:

1. Define a function average that takes any number of arguments and returns their average.


Keyword Variable-Length Arguments (**kwargs):
Use **kwargs to pass multiple keyword arguments.

def print_info(**info):
    for key, value in info.items():
        print(f"{key}: {value}")

print_info(name="Alice", age=25, city="New York")


Exercise:
Define a function personal_details that takes any number of keyword arguments and prints each key-value pair.


2.3 Lambda Functions
Lambda functions are small anonymous functions defined with the lambda keyword, useful for short operations

Syntax: 
lambda arguments: expression


Example: 
square = lambda x: x ** 2
print(square(5))  # Output: 25


Exercise:
2. Create a lambda function that takes two arguments and returns their product.


2.4 Scope and Lifetime of Variables
Variables defined inside a function are local to that function. They are created when the function is called and destroyed when the function ends.

Example:
def my_function():
    x = 10  # local variable
    print(x)

my_function()
print(x)  # This will raise an error because x is not accessible outside the function


Exercise:
3. Write a program with a function that has a local variable and demonstrates its scope by trying to access it outside the function.


2.5 Higher-Order Functions
A higher-order function is a function that accepts another function as a parameter or returns a function.

Example:
def apply_operation(func, x, y):
    return func(x, y)

result = apply_operation(lambda a, b: a + b, 5, 3)
print(result)  # Output: 8


Exercise:
4. Define a function operate that takes two numbers and a function operation as parameters. Use it to add and multiply numbers with lambda functions.


