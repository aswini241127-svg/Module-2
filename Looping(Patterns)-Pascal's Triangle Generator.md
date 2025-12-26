# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
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
## Sample Output

<img width="796" height="173" alt="exp1" src="https://github.com/user-attachments/assets/80d4a153-bffa-4a02-97a1-2a3db395f85e" />


## Result
The Python program successfully takes the number of rows as input from the user and generates Pascal’s Triangle.

