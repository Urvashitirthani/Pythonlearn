Python Programs: Factorial Function and Math Module Calculations

This repository contains two Python scripts that demonstrate:

- Using a recursive function to calculate the factorial of a number.
- Performing mathematical operations using Python's built-in `math` module.

---

## Task 1: Factorial Calculation

This script prompts the user to enter a non-negative integer and calculates its factorial using a recursive function.

### Example

Enter a number: 5
Factorial of 5 is 120

### Code

```python
def factorial(n):
    if n < 2:
        return 1
    else:
        return n * factorial(n - 1)

n = int(input("Enter a number: "))
print("Factorial of", n, "is", factorial(n))


---

Task 2: Math Module Calculations

This script prompts the user to enter a number and calculates:

Square root (math.sqrt)

Natural logarithm (math.log)

Sine of the number in radians (math.sin)


Example

Enter a number: 9  
Square root : 3.0  
Logarithms : 2.1972245773362196  
Sine : 0.4121184852417566

Code

import math

num = float(input("Enter a number: "))

sqrt_value = math.sqrt(num)
log_value = math.log(num)
sine_value = math.sin(num)

print(f"Square root : {sqrt_value}")
print(f"Logarithms : {log_value}")
print(f"Sine : {sine_value}")
