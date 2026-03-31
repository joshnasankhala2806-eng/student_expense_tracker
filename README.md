# Smartspend 

A simple Python console application designed to help users track daily expenses and manage their monthly budget effectively.

---

## Overview

Smartspend is a beginner-friendly Python program that allows users to record expenses along with notes. Each entry is automatically timestamped and saved in a text file (`expenses.txt`) so the data remains available for future use. The program also provides a summary of total spending and remaining budget to help users build better financial habits.

---

## Features

- Add expenses with amount and short notes  
- Automatically records date and time of each entry  
- Stores data permanently in `expenses.txt`  
- Displays total spending and remaining budget  
- Provides basic spending suggestions  
- Simple and menu-driven interface (easy for beginners)

---

## Technologies Used

- Python 3  
- `datetime` module  
- File Handling (read/write operations)

---

## Installation & Setup

1. Make sure Python 3 is installed on your system.
2. Clone this repository:

git clone https://github.com/your-username/smart-expense-tracker.git

Make sure the script file (expense_tracker.py) is located in the folder where you want expenses.txt to be generated.

The program will automatically create expenses.txt if it does not exist.

---

## How to Run

-Use the terminal or command prompt to execute the program:
-python expense_tracker.py
-Testing Instructions
-To test the project, you may follow these steps:
-Start the program and enter a sample monthly budget such as 90000.
-Choose the option to add expenses and input sample values (for example, 100, 2000, 3000).
-Add a short note for each expense.
-Select the summary option to view:
-Total expenses
-Remaining budget
-Suggestions based on your spending

## flowchart

Start Program
      |
Ask for Monthly Budget
      |
Display Menu
  1. Add Expense
  2. View Summary
  3. Exit
      |
-----------------------------
|           |              |
Add Expense  View Summary   Exit
|           |              |
Save data   Read file       End
in file     Calculate total
|           |
Return to Menu

-author 
-JOSHNA SANKHALA
