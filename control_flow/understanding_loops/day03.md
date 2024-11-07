3.1 Optimizing Loops
Avoid using inefficient loops when possible. For example, when iterating over a sequence, try to avoid unnecessary operations inside the loop.

Example of inefficient loop:
for i in range(100):
    for j in range(100):
        if i == j:
            print(i)

This can be optimized by directly iterating over the values without a nested loop if possible.

Exercise:

1. Optimize the previous example to reduce the complexity of the code.


3.2 Looping through Multiple Sequences
Use the zip() function to loop through multiple sequences in parallel.

Example:
names = ['Bolaji', 'Anefu', 'Steve']
ages = [24, 27, 22]
for name, age in zip(names, ages):
    print(f"{name} is {age} years old.")


Exercise:

2. Write a program that combines two lists of numbers and prints their sums.


3.3 List Comprehensions
List comprehensions are a concise way to create lists based on existing sequences.

Example:

squares = [x ** 2 for x in range(10)]
print(squares)

This creates a list of squares from 0 to 9.


Exercise:

3. Write a list comprehension that generates a list of all even numbers between 1 and 20.


3.4 Nested Loops with List Comprehensions
You can also use list comprehensions with nested loops.

Example:

matrix = [[1, 2, 3], [4, 5, 6], [7, 8, 9]]
flattened = [element for row in matrix for element in row]
print(flattened)

Exercise:

4. Write a program using list comprehension to flatten a 3x3 matrix.
