# Functions-Modules-in-Python
Task 1: Calculate Factorial Using a Function 

📘 Functionality Description of the Program:

This Python program is designed to calculate the factorial of a number using a function and recursion.

🔍 Step-by-Step Explanation:

User Input:

a = int(input("Enter a number: "))

The program first asks the user to input a number.

The input is converted from string to integer using int().

Defining the Function factorial(n):

def factorial(n):

  if n == 0 or n == 1:
        return 1
    else:
        return n * factorial(n - 1)

This function uses recursion to calculate the factorial.

If n is 0 or 1, it returns 1 (since 0! = 1 and 1! = 1).

Otherwise, it returns n * factorial(n - 1) — recursively multiplying n with the factorial of the previous number.

Calling the Function:

number = a

print(f"Factorial of {number} is: {factorial(number)}")

The input number is stored in number.

The program prints the factorial result using an f-string for formatting.

✅ Example Output:

If the user enters 5, the output will be:

Factorial of 5 is: 120

📌 Summary:

This program:

Takes an integer input from the user,

Uses a recursive function to compute the factorial,

Prints the result in a clean, formatted way.

Task 2: Using the Math Module for Calculations

📘 Functionality Description of the Program:

This Python program performs three mathematical operations on a number entered by the user using the math module.

🔍 Step-by-Step Explanation:

Importing the math Module:

import math

The program imports the built-in math module to access advanced mathematical functions like logarithm and sine.

User Input:

a = int(input("Enter a number: "))

Prompts the user to enter a number.

Converts the input string to an integer and stores it in variable a.

Assigning to number:

number = a

Stores the user input into another variable called number for clarity and reuse.

Calculating the Square Root:

square_root = (a**(1/2))

Calculates the square root of the number using exponentiation (**).

Equivalent to math.sqrt(a).

Calculating the Natural Logarithm:

natural_log = math.log(number)

Calculates the natural logarithm (log base e) of the number using math.log().

Calculating the Sine (in Radians):

sine_value = math.sin(number)

Calculates the sine of the number (treated as an angle in radians) using math.sin().

Displaying the Results:

print(f"Square root: {square_root}")

print(f"Logarithm: {natural_log}")

print(f"Sine: {sine_value}")

Displays all the calculated values using f-strings for clean formatting.

✅ Example Output:

If the user enters 9, the output will be:

Square root: 3.0

Logarithm: 2.1972245773362196

Sine: 0.4121184852417566

📌 Summary:

This program:

Takes an integer input from the user.

Calculates and prints:

The square root of the number.

The natural logarithm (log base e).

The sine value (in radians).

Demonstrates use of both basic arithmetic and the math module in Python.
