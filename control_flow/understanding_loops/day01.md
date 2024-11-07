Day 1: Introduction to Loops in Python
Objective: Understand the basic concept of loops, types of loops, and their basic syntax.



What is a Loop?

A loop in programming is a sequence of instructions that is repeated until a certain condition is met. Loops are used to automate repetitive tasks.
Types of Loops in Python:

For Loop: 
Used to iterate over a sequence (like a list, string, or range).

While Loop: 
Repeats a block of code as long as a given condition is true.


1.1 For Loop
Syntax:

for variable in sequence:
    # code to execute

Example:
for i in range(5):
    print(i)

This loop will print numbers from 0 to 4 because 
range(5) generates numbers from 0 to 4.


Exercise:

Write a program that prints each character in a string using a for loop.

word = "Python"
for letter in word:
    print(letter)


1.2 While Loop
Syntax:

while condition:
    # code to execute

Example:
i = 0
while i < 5:
    print(i)
    i += 1

This loop continues to run until the condition i < 5 is no longer true.


Exercise:

Write a program that prints numbers from 1 to 10 using a while loop.

num = 1
while num <= 10:
    print(num)
    num += 1

