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
