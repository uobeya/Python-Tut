Day 1: Basics of Conditionals - If, Else, and Elif Statements
Objective: Learn the foundational conditional structures in Python: if, else, and elif

What are Conditionals?

Conditionals allow code to run only when specific conditions are met, enabling decision-making within a program.


Basic Structure of Conditionals:

if: Used to run code only if a condition is true.
else: Runs code if the if condition is false.
elif: Checks multiple conditions, running different blocks of code depending on the conditions.

If Statement
Syntax:
if condition:
    # code to execute if condition is true


Example:
age = 18
if age >= 18:
    print("You are eligible to vote!")

This checks if age is 18 or older. If true, it prints "You are eligible to vote!"

Exercise:

1. Write a program that checks if a number is positive and prints "Positive number".


1.2 If-Else Statement
Use else to specify what happens when the if condition is false.

Syntax:
if condition:
    # code if condition is true
else:
    # code if condition is false

Example:

age = 16
if age >= 18:
    print("You are eligible to vote!")
else:
    print("You are not eligible to vote.")


Exercise:

2. Write a program that checks if a number is positive or negative.

1.3 Elif Statement
Use elif to check multiple conditions.

Syntax:

if condition1:
    # code for condition1
elif condition2:
    # code for condition2
else:
    # code if all conditions are false

Example:

temperature = 25
if temperature > 30:
    print("It's hot!")
elif temperature < 15:
    print("It's cold!")
else:
    print("The weather is nice.")

Exercise:

3. Write a program that checks if a number is positive, negative, or zero.
