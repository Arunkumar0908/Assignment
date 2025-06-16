# Assignment
# 👋 Welcome Program in Python

## 📋 Description
This is a basic Python program that prompts the user to enter their **first name** and **last name**, then combines them and displays a personalized greeting message.

## 🧾 How It Works
1. The program asks the user to input their **first name**.
2. Then, it asks for the **last name**.
3. It combines both names into a full name.
4. Finally, it prints a greeting message using the full name.

## 🧑‍💻 Code Example
```python
FN = input("Enter the First name : ")
LN = input("Enter the Second name: ")
FLN = FN + " " + LN
print("Hello " + FLN + "! Welcome to python program")

## Basic Mathematical Operations in Python

## 📋 Description
This simple Python program takes **two numbers** as input from the user and performs basic mathematical operations:
- Addition
- Subtraction
- Multiplication
- Division (with handling for division by zero)

## 🧑‍💻 Code Overview
```python
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

