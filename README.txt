# Day 7 – Simple Calculator in Python

## 📌 About the Project

This is Day 7 of my 20-day Python programming practice challenge. In this project, I created a simple calculator using Python that performs basic arithmetic operations based on user input.

## 🎯 Objective

The objective of this program is to understand how to use conditional statements, user input, arithmetic operators, and basic error handling in Python.

## 🛠️ Technologies Used

- Python 3
- Visual Studio Code
- Git and GitHub

## ⚙️ Features

- Addition (+)
- Subtraction (-)
- Multiplication (*)
- Division (/)
- Accepts decimal numbers
- Handles division by zero
- Displays an error for invalid operators

## 💻 Program Code

```python
a = float(input("Enter first number: "))
op = input("Enter operator (+ - * /): ")
b = float(input("Enter second number: "))

if op == "+":
    print("Result =", a + b)
elif op == "-":
    print("Result =", a - b)
elif op == "*":
    print("Result =", a * b)
elif op == "/":
    if b != 0:
        print("Result =", a / b)
    else:
        print("Error: Cannot divide by zero")
else:
    print("Invalid operator")
```

## ▶️ Sample Output

```text
Enter first number: 10
Enter operator (+ - * /): *
Enter second number: 5
Result = 50.0
```

## 📚 Concepts Learned

- Variables and data types
- User input using `input()`
- Type conversion using `float()`
- Conditional statements: `if`, `elif`, and `else`
- Arithmetic operators
- Basic error handling

## 🚀 How to Run

1. Install Python 3.
2. Open the project in Visual Studio Code.
3. Create a file named `day7_simple_calculator.py`.
4. Copy the program into the file.
5. Open the terminal and run:

```bash
python day7_simple_calculator.py
```

## 🎓 Learning Journey

This project is part of my 20-day Python programming challenge, where I practice Python concepts step by step and upload my programs to GitHub.

**Day 7 completed: Simple Calculator using Python!** 🐍

## 👨‍💻 Author

Sashank Gotte