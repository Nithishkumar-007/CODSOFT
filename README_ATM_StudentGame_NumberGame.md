
# Project Overview

This repository contains three Python-based projects: **ATM Interface**, **Student Grade Calculator**, and **Number Game**. 
Each project is designed to demonstrate practical programming concepts, user interaction, and input validation.

## 1. ATM Interface

This program simulates the functionality of an ATM machine.

### Features:
- **Withdraw:** Deducts an amount from the user's account balance.
- **Deposit:** Adds an amount to the user's account balance.
- **Check Balance:** Displays the current balance.
- **Input Validation:** Ensures sufficient funds for withdrawals and valid amounts for transactions.
- **Account Management:** The ATM is connected to a Bank Account class to handle balance modifications.

### How to Use:
1. Run the script and select an option from the menu.
2. Follow the prompts to perform transactions.

---

## 2. Student Grade Calculator

This program calculates the total marks, average percentage, and grade based on the marks obtained in each subject.

### Features:
- Input marks for multiple subjects.
- Calculate total marks and average percentage.
- Assign grades based on the average percentage:
  - A: 90-100%
  - B: 80-89%
  - C: 70-79%
  - D: 60-69%
  - F: Below 60%
- Displays the results in a user-friendly format.

### How to Use:
1. Enter the marks obtained in each subject when prompted.
2. View the total marks, average percentage, and grade.

---

## 3. Number Game

A fun and interactive guessing game where the user attempts to guess a randomly generated number.

### Features:
- Random number generation within a specified range (default: 1-100).
- Feedback provided for each guess (too high, too low, or correct).
- Limit the number of attempts for added challenge.
- Option for multiple rounds.
- Tracks and displays the user's score based on performance.

### How to Use:
1. Run the script and start the game.
2. Enter your guesses based on the feedback provided.
3. Continue guessing until the correct number is found or attempts run out.
4. Play multiple rounds and view your score.

---

## Prerequisites

- Python 3.x installed on your system.
- Basic understanding of running Python scripts.

---

## Installation

1. Clone the repository or download the source code.
2. Navigate to the directory containing the scripts.

```bash
git clone <repository_url>
cd <repository_directory>
```

3. Run the desired script:

```bash
python atm_interface.py
python student_grade_calculator.py
python number_game.py
```

---

## Future Enhancements

- **ATM Interface:** Add PIN-based authentication.
- **Student Grade Calculator:** Include subject-wise grade calculation.
- **Number Game:** Implement a leaderboard system.

---

## Acknowledgments

This project is part of an internship program to demonstrate core programming concepts and real-world applications.
