# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
a = 16
print(bin(a))
    


## Output

<img width="803" height="77" alt="exp1" src="https://github.com/user-attachments/assets/cb691412-1a7b-43fc-a58e-a7f19d20c6f8" />

## Result
The program successfully converts the number 16 into its binary representation and displays the result as 0b10000 on the screen.
# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
```
# Define the lambda function
add = lambda a, b: a + b

# Example usage
result = add(4, 5)
print("Sum is:", result)
```
## Output

<img width="346" height="80" alt="exp1" src="https://github.com/user-attachments/assets/3dee4aae-640d-412a-8149-40e79c24511d" />

## Result
The program successfully created lambda function to find the sum
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
## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```
def find_modulo(a, b):
    return a % b
result = find_modulo(17, 5)
print("17 % 5 =", result)
```
## Output

<img width="198" height="58" alt="exp1" src="https://github.com/user-attachments/assets/2606af91-005f-4283-85f1-856d208bb421" />

## Result
The program successfully defines a function and returns the modulo of the two inputs
