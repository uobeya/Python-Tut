Day 3: Advanced Conditionals - Combining Operators and Conditional Expressions
Objective: Learn to create complex conditional statements by combining operators, and explore conditional expressions (ternary operator) for concise conditions.


3.1 Combining Comparison and Logical Operators
Combine comparison and logical operators to create complex conditionals.

Example:

score = 85
if score > 90:
    print("Grade: A")
elif score > 80:
    print("Grade: B")
elif score > 70:
    print("Grade: C")
else:
    print("Grade: D")



Exercise:

Write a program that assigns letter grades based on scores:
Score >= 90: A
Score >= 80: B
Score >= 70: C
Below 70: F


3.2 Conditional Expressions (Ternary Operator)
Python provides a shorthand way for simple if-else statements, known as the ternary operator.

Syntax:
result = value_if_true if condition else value_if_false

Example:
age = 20
status = "Adult" if age >= 18 else "Minor"
print(status)  # Output: Adult


Exercise:

Write a program that checks if a number is even or odd using a conditional expression.


3.3 Practice Problem: Nested Conditionals and Complex Logic
Problem:

1. Write a program that evaluates a student’s score and determines their status:
	If the score is 90 or above, print "Excellent."
	If it’s 70-89, check if the student has attended over 75% of classes:
		If so, print "Good."
		Otherwise, print "Needs Improvement."
	If the score is below 70, print "Fail."

