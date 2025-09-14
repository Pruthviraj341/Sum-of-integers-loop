#Python basic programs
- **Task 1:** Check if a number is even or odd  
- **Task 2:** Calculate the sum of integers from 1 to 50  

---

## 🔹 Task 1: Check if a Number is Even or Odd

### Problem Statement
Write a Python program that:  
1. Takes an integer input from the user.  
2. Checks whether the number is even or odd using an `if-else` statement.  
3. Displays the result accordingly.  

### Description
The program asks the user to enter a number. It then checks if the number is divisible by 2 using the modulo operator `%`. If the remainder is 0, the number is **Even**, otherwise it is **Odd**.

### Code
```python
# Task 1: Check if a number is even or odd

num = int(input("Enter an integer: "))

if num % 2 == 0:
    print(f"{num} is Even")
else:
    print(f"{num} is Odd")
Enter an integer: 10
10 is Even
Enter an integer: 7
7 is Odd
# Task 2: Calculate the sum of integers from 1 to 50

total_sum = 0

for num in range(1, 51):
    total_sum += num

print("The sum of integers from 1 to 50 is:", total_sum)
The sum of integers from 1 to 50 is: 1275

