
Simple Calculator

A Python-based command-line calculator that performs basic arithmetic operations including addition, subtraction, multiplication, and division with division-by-zero protection.

Introduction

The Simple Calculator is a Python program designed to perform basic arithmetic operations such as addition, subtraction, multiplication, and division. The system accepts user input, performs the selected calculation, and displays the result.

I developed this project to strengthen my understanding of mathematical operations, user input handling, conditional statements, and program design. It demonstrates how Python can be used to create practical tools that solve everyday calculation problems.

Objective

The objective of this project is to create a simple calculator that performs basic arithmetic operations such as addition, subtraction, multiplication, and division. The program allows users to select an operation, enter two numbers, and receive the calculated result.

Features

· Addition of two numbers
· Subtraction of two numbers
· Multiplication of two numbers
· Division of two numbers
· Menu-driven interface
· Division-by-zero protection
· Simple and user-friendly design

Tech Stack

· Python 3.x
· Command-line interface

Installation

1. Make sure Python 3 is installed on your system.
2. Save the code file as calculator.py.
3. Run the script:
  
   python calculator.py
   
Usage

1. Launch the program.
2. Choose an operation from the menu (1-4):
   · 1 for Addition
   · 2 for Subtraction
   · 3 for Multiplication
   · 4 for Division
3. Enter two numbers when prompted.
4. View the calculated result.

Sample Output

Addition

===== SIMPLE CALCULATOR =====
1. Addition
2. Subtraction
3. Multiplication
4. Division
Choose an operation (1-4): 1
Enter first number: 15
Enter second number: 10
Result = 25.0
Division

===== SIMPLE CALCULATOR =====
1. Addition
2. Subtraction
3. Multiplication
4. Division
Choose an operation (1-4): 4
Enter first number: 20
Enter second number: 5
Result = 4.0
Division by Zero (Error Handling)

===== SIMPLE CALCULATOR =====
1. Addition
2. Subtraction
3. Multiplication
4. Division
Choose an operation (1-4): 4
Enter first number: 10
Enter second number: 0
Result = Division by zero is not allowed.
Invalid Choice

===== SIMPLE CALCULATOR =====
1. Addition
2. Subtraction
3. Multiplication
4. Division
Choose an operation (1-4): 5
Enter first number: 10
Enter second number: 5
Invalid choice.
Concepts Used

· Variables
· User input
· Functions
· Arithmetic operators
· Conditional statements (if, elif, else)
· Output statements
· Error handling (division by zero)

Program Logic

1. Display the calculator menu
2. Ask the user to choose an operation
3. Ask the user to enter two numbers
4. Call the appropriate function based on the user's choice
5. Display the result
6. End the program

Functions Used

Function Operation Return
add(a, b) Addition a + b
subtract(a, b) Subtraction a - b
multiply(a, b) Multiplication a * b
divide(a, b) Division a / b (with zero check)

What I Learned

Through this project, I learned how to:

· Create and use functions in Python
· Accept input from users
· Use conditional statements to make decisions
· Perform arithmetic calculations
· Organize a program into smaller and reusable functions
· Handle simple errors such as division by zero

Future Improvements

In the future, this calculator can be improved by:

· Adding more operations such as square roots and powers
· Allowing multiple calculations in one run
· Creating a graphical user interface (GUI)
· Adding advanced mathematical functions
· Improving input validation

Conclusion
This project helped me understand how functions, user input, and conditional statements work together to build a practical application. It strengthened my programming skills and improved my ability to solve problems using Python.
The Author

Nura Husein
Student / Beginner Python Developer

This project was developed as part of a learning exercise to strengthen programming fundamentals. Passionate about building small, useful tools and gradually moving into real-world applications.

· GitHub: nurahusein47
· Goal: Continue improving and building more interactive systems with databases and GUIs.

Acknowledgments

· Inspired by the need for quick and simple calculations.
· Thanks to Python practice projects that helped build this system.

Version

v1.0 – Basic calculator with addition, subtraction, multiplication, and division (command-line based)

License

This project is for educational purposes only.
