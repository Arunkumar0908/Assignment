# 🐍 Python Beginner Programs

This repository contains two simple Python programs:

1. **Greeting Program** – Takes user's first and last name and greets them.
2. **Basic Mathematical Operations** – Accepts two numbers and performs basic arithmetic operations.

---

## 📘 Program 1: Greeting the User

### 🧾 Description
This script prompts the user to enter their **first name** and **last name**, then prints a personalized welcome message.

### 🧑‍💻 Code
```python
FN = input("Enter the First name : ")
LN = input("Enter the Second name: ")
FLN = FN + " " + LN
print("Hello " + FLN + "! Welcome to python program")

📘 Program 2: Basic Mathematical Operations
🧾 Description
This script prompts the user to input two numbers and performs:

Addition

Subtraction

Multiplication

Division (with zero-division handling)

🧑‍💻 Code
python
Copy
Edit
A = float(input("Enter the 1st number: "))
B = float(input("Enter the 2nd number: "))

def basicOps(a, b):
    add = a + b
    sub = a - b
    mul = a * b
    if b != 0:
        div = a / b
    else:
        div = "Undefined (cannot divide by zero)"
    
    print("\nThe basic math operations:")
    print("Addition:", add)
    print("Subtraction:", sub)
    print("Multiplication:", mul)
    print("Division:", div)

basicOps(A, B)
