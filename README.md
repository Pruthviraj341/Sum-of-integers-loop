# Check if a Number is Even or Odd

## 📌 Problem Statement
This program takes an integer input from the user and checks whether it is **even** or **odd** using an `if-else` statement.

## 📝 Description
- The user is prompted to enter an integer.
- The program checks if the number is divisible by 2 using the modulo operator `%`.
- If the remainder is 0, the number is **Even**.
- Otherwise, the number is **Odd**.
- The result is displayed accordingly.

## 💻 Code Example
```python
# Program to check if a number is even or odd

# Step 1: Take integer input from the user
num = int(input("Enter an integer: "))

# Step 2: Check even or odd using if-else
if num % 2 == 0:
    print(f"{num} is Even")
else:
    print(f"{num} is Odd").

