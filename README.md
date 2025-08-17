# Assignment-3
# Module 4: Functions & Modules in Python 
# Task 1: Calculate Factorial Using a Function 
 def factorial(n):
    if n<2:
      return 1
    else:
         return n*(factorial(n-1))
         result=factorial(5)
         print(result)

# output 
120
# Task 2: Using the Math Module for Calculations
 
# Problem Statement: Write a Python program that:
1.   Asks the user for a number as input.
2.   Uses the math module to calculate the:
o   Square root of the number
o   Natural logarithm (log base e) of the number
o   Sine of the number (in radians)
3.   Displays the calculated results.

import math

num = int(input("Enter a number: "))

print("Square root:", math.sqrt(num))
print("Logarithm:", math.log(num))
print("Sine:", math.sin(num))

# output 
Enter a number = 25
Square root =  5.0
Logarithm = 3.2188758248682006
Sine = -0.1323517009777303
