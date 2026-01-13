Calculator Application (Python)

A menu-driven Python calculator application that performs basic arithmetic operations with a clean structure, reusable functions, and user-friendly interaction through the terminal.

Project Analysis & Improvements
 Features Implemented

Modular design using functions

Menu-driven interface using while loop

Supports continuous calculations until user exits

Handles division by zero safely

Uses dictionary + lambda functions for clean operation mapping

Maintains history of calculations

 Concepts Used

This project is built using core Python fundamentals, making it ideal for beginners:

Data Types

Numbers (int, float)

Strings

Lists

Dictionaries

Booleans

Control Flow

if / elif / else

while loop

Functions

Lambda Expressions

Dictionary-based function mapping

List for storing calculation history

Input / Output handling

Error handling (division by zero)

 Project Structure
python-calculator/
├── calculator.py        # Main calculator program
└── README.md            # Project documentation

 How to Run
Requirements

Python 3.x installed

Steps
python calculator.py

 Application Menu
1. Addition
2. Subtraction
3. Multiplication
4. Division
5. View History
6. Exit

 Sample Output
1. Addition
2. Subtraction
3. Multiplication
4. Division
5. View History
6. Exit

Enter your choice: 1
Enter first number: 10
Enter second number: 5
Result: 15

History Output
--- Calculation History ---
Addition: 10 and 5 = 15
Multiplication: 4 and 6 = 24
----------------------------------

 Core Logic (Overview)

Dictionary + Lambda approach is used to map operations:

operations = {
    '1': ("Addition", lambda a, b: a + b),
    '2': ("Subtraction", lambda a, b: a - b),
    '3': ("Multiplication", lambda a, b: a * b),
    '4': ("Division", lambda a, b: a / b if b != 0 else "Error")
}


History tracking is done using a list:

history = []

 Edge Cases Handled

Division by zero

Invalid menu choices

Continuous execution until exit

 Future Improvements

Add GUI using Tkinter or JavaFX-style UI

Add scientific calculator functions

Save calculation history to file

Support keyboard shortcuts

Add unit testing

 Author

Meet Tailor
Python & Programming Enthusiast
GitHub:https://github.com/MeetTailor-Data

 License

This project is created for learning and educational purposes.

 Status

 Fully working
 Last Updated: 2026
