# Python Programs – Factorial Function and Math Module Operations

This repository contains two Python scripts that demonstrate basic mathematical operations using functions and the built-in `math` module in Python.

## Task 1 – Factorial Calculation

This script prompts the user to enter a non-negative integer and calculates the factorial of that number using a recursive function. The result is printed to the console.

### Code Overview:

```python
def factorial(n):
    if n < 2:
        return 1
    else:
        return n * factorial(n - 1)

n = int(input("Enter a number: "))
print("Factorial of", n, "is", factorial(n))

Example Output:

Enter a number: 5  
Factorial of 5 is 120


---

## Task 2 – Math Module Operations

This script asks the user to enter a number (integer or float), then uses Python’s math module to calculate:

The square root

The natural logarithm

The sine of the number (in radians)


The results are displayed with appropriate labels.

Code Overview:

import math

num = float(input("Enter a number: "))

sqrt_value = math.sqrt(num)
log_value = math.log(num)
sine_value = math.sin(num)

print(f"Square root : {sqrt_value}")
print(f"Logarithms : {log_value}")
print(f"Sine : {sine_value}")

Example Output:

Enter a number: 9  
Square root : 3.0  
Logarithms : 2.1972245773362196  
Sine : 0.4121184852417566

Note: If the user enters a negative number, the math.sqrt() and math.log() functions may raise errors. Error handling can be added as needed.


---

How to Run

Make sure you have Python installed. Then, run the scripts from a terminal or code editor:

python task1_factorial.py
python task2_math_module.py


