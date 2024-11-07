Day 2: Loop Control Statements and Nested Loops
Objective: Understand how to control loops using break, continue, and else statements, and learn how to use nested loops.

2.1 Break Statement
The break statement is used to exit the loop prematurely when a certain condition is met.

Example:
for i in range(10):
    if i == 5:
        break
    print(i)

This will print numbers from 0 to 4 and stop when i is 5.

Exercise:

1. Write a program that breaks out of a loop when a user inputs the number 3.


2.2 Continue Statement
The continue statement is used to skip the current iteration of the loop and move to the next iteration.

Example: 
for i in range(5):
    if i == 2:
        continue
    print(i)

This will print numbers from 0 to 4, except 2.

Exercise:

2. Write a program that prints even numbers from 1 to 10, skipping odd numbers using continue.

2.3 Else Statement with Loops
The else statement can be used with loops. It is executed when the loop completes normally (i.e., it wasn't terminated by a break statement).
Example:

for i in range(3):
    print(i)
else:
    print("Loop finished without a break.")


This will print 0, 1, 2 and then "Loop finished without a break."

Exercise:

3. Write a program using a for loop and an else statement that prints all numbers from 1 to 5, and if the loop completes without a break, print "Done".

2.4 Nested Loops
A nested loop is a loop inside another loop.

for i in range(3):
    for j in range(2):
        print(f"i = {i}, j = {j}")

Exercise:
4. Write a program using nested loops that prints a 5x5 multiplication table.
