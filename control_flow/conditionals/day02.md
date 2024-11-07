Day 2: Nested Conditionals and Logical Operators
Objective: Understand nested conditionals for more complex logic and learn to combine multiple conditions using logical operators.

2.1 Nested Conditionals
Conditionals can be embedded inside other conditionals.

Example:

age = 20
is_registered = True
if age >= 18:
    if is_registered:
        print("You can vote!")
    else:
        print("You need to register to vote.")
else:
    print("You are not eligible to vote.")



Exercise:

Write a program that checks if a person is eligible to apply for a driving license. If they’re 18, also check if they have parental consent.



2.2 Comparison Operators
Comparison operators allow us to compare values within conditions.


Operator	Description
==	Equal to
!=	Not equal to
>	Greater than
<	Less than
>=	Greater than or equal to
<=	Less than or equal to


Example:

a = 10
b = 5
print(a > b)   # True
print(a == b)  # False


Exercise:

Write a program that checks if two numbers are equal or not.


2.3 Logical Operators
Logical operators let you combine conditions in a single statement.

Operator	Description
and	True if both conditions are true
or	True if at least one condition is true
not	True if condition is false

Example:

age = 22
is_student = True
if age > 18 and is_student:
    print("You are an adult student.")


Exercise:

Write a program that checks if a number is between 10 and 20, inclusive.


