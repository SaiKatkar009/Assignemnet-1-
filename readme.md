# 🐍 Python Mini Project: Calculator & Greeting Program

This is a simple beginner-friendly Python program that performs basic arithmetic operations and prints a personalized greeting message.

---

## 📌 Project Overview

This project contains **two tasks**:

### 🔹 Task 1: Basic Calculator
The program:
- Takes two integers as input from the user
- Performs the following operations:
  - Addition
  - Subtraction
  - Multiplication
  - Division
- Handles division safely to avoid division-by-zero errors

### 🔹 Task 2: Greeting Program
The program:
- Takes the user's first name and last name as input
- Adds an exclamation mark (`!`) to the last name
- Displays a friendly greeting message

---

## 🧾 Program Code

```python
# TASK 1 - Calculator
a = int(input("Enter the first number: "))
b = int(input("Enter the second number: "))

print("Addition:", a + b)
print("Subtraction:", a - b)
print("Multiplication:", a * b)

if b != 0:
    print("Division:", a / b)
else:
    print("Division: Not possible (cannot divide by zero)")


# TASK 2 - Greeting Program
first_name = input("Enter your first name: ")
last_name = input("Enter your last name: ")

print("Hello", first_name, last_name + "!", "Welcome to Python program.")
```

---

## ▶ How to Run the Program

1. Make sure Python is installed on your system
2. Save the file as `main.py`
3. Open a terminal or command prompt
4. Run the program using:

```bash
python main.py
```

---

## 💡 Sample Input & Output

### Example 1 – Calculator
```
Enter the first number: 10
Enter the second number: 5
Addition: 15
Subtraction: 5
Multiplication: 50
Division: 2.0
```

### Example 2 – Greeting Program
```
Enter your first name: Sai
Enter your last name: Katkar
Hello Sai Katkar! Welcome to Python program.
```

---

## 🛠 Concepts Used

- `input()` for user input
- Type conversion using `int()`
- Arithmetic operators (`+`, `-`, `*`, `/`)
- Conditional statements (`if-else`)
- String concatenation
- Print formatting

---

## 📚 Suitable For

- Python beginners
- College practical assignments
- Basic programming practice

---

## 👨‍💻 Author

Sai Katkar  

---

✅ Feel free to modify or extend this program by adding:
- More operations (modulus, power)
- Error handling using `try-except`
- Loop for repeated calculations

