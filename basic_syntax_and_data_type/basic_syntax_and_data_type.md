This tutorial covers the basics of Python syntax to help you get started with writing Python code.


1. Hello, World!
The traditional first step in learning a programming language is printing "Hello, World!". In Python, you use the print() function:

# code
print("Hello, World!")
# output
Hello, World!


2. Variables and Data Types
Variables store values. In Python, you don’t need to declare a variable type explicitly.

name = "Bolaji"     # String
age = 25           # Integer
height = 5.6       # Float
is_student = True  # Boolean


Python automatically detects the variable type based on the value assigned.

# Common Data Types
String: Text enclosed in quotes (e.g., "Hello")
Integer: Whole numbers (e.g., 10)
Float: Decimal numbers (e.g., 3.14)
Boolean: True or False

3. Comments
Comments are used to explain code and are ignored by Python. Single-line comments start with #.

# This is a single-line comment

For multi-line comments, you can use triple quotes (''' or """):

"""
This is a multi-line comment.
It can span multiple lines.
"""


4. Basic Operations
Python supports various operators:

# Addition
x = 10 + 5       # 15

# Subtraction
y = 10 - 5       # 5

# Multiplication
z = 10 * 5       # 50

# Division
a = 10 / 2       # 5.0

# Modulus (remainder)
b = 10 % 3       # 1


5. Conditional Statements
Use if, elif, and else to perform conditional checks.

age = 18
if age >= 18:
    print("Adult")
elif age >= 13:
    print("Teenager")
else:
    print("Child")


Indentation is critical in Python; all statements inside the block must be indented.


6. Loops

# for Loop
Use for to iterate over a sequence.

for i in range(5):
    print(i)


# Output
0
1
2
3
4


# while Loop
Use while to repeat a block of code as long as a condition is true.

count = 0
while count < 5:
    print(count)
    count += 1


7. Functions
Functions help organize code into reusable blocks. Define a function using def.

def greet(name):
    return f"Hello, {name}!"

print(greet("Bolaji"))


# output
Hello, Bolaji!


8. Lists
Lists are ordered, mutable collections.

fruits = ["apple", "banana", "cherry"]
print(fruits[0])     # "apple"
fruits.append("date")
print(fruits)        # ["apple", "banana", "cherry", "date"]



9. Dictionaries
Dictionaries store key-value pairs.

person = {"name": "Bolaji", "age": 25}
print(person["name"])    # "Bolaji"
person["city"] = "Paris"
print(person)            # {'name': 'Bolaji', 'age': 25, 'city': 'Paris'}

