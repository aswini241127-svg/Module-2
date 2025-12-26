# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```
from math import factorial

# Input number of rows
rows = int(input("Enter the number of rows: "))

# Generate Pascal's Triangle
for i in range(rows):
    # Print spaces for alignment
    print(" " * (rows - i), end="")
    
    # Calculate and print each value
    for j in range(i + 1):
        print(factorial(i) // (factorial(j) * factorial(i - j)), end=" ")
    print()
```  
## Output

<img width="796" height="173" alt="exp1" src="https://github.com/user-attachments/assets/b6db587c-6c4f-4ece-8d7b-f0daa89b449c" />

## Result
The Python program successfully takes the number of rows as input from the user and generates Pascal’s Triangle.
