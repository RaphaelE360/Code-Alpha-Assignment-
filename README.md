# Python Beginner Projects Collection

A collection of three entry-level Python scripts designed to demonstrate core programming concepts including loops, conditional logic, data structures, and file handling.

## 🚀 Projects Overview

1.  **Basic Stock Tracker**: A tool to calculate investment totals and save portfolios to a text file.
2.  **Rule-Based Chatbot**: A simple interactive bot that responds to specific user keywords.
3.  **Hangman Game**: A classic word-guessing game featuring random word selection and attempt tracking.

---

## 📈 1. Basic Stock Tracker

This script allows users to simulate building a stock portfolio by selecting from a predefined list of stocks and quantities.

### Key Features
* **Dictionary usage**: Stores hardcoded stock prices.
* **Input Validation**: Checks if the entered stock exists in the database.
* **File Handling**: Offers an option to export the final summary to `portfolio.txt`.
* **Arithmetic**: Calculates individual and total investment values.

### How to Use
1. Run the script.
2. Enter the stock ticker (e.g., AAPL, TSLA).
3. Enter the quantity.
4. Type `DONE` to finish and see the total.
5. Choose `yes` to save the results to a file.

---

## 🤖 2. Rule-Based Chatbot

A simple terminal-based chatbot that uses conditional logic to "converse" with the user.

### Key Features
* **Infinite Loop**: Keeps the conversation going until the exit command is given.
* **Case Insensitivity**: Uses `.lower()` to handle user input regardless of capitalization.
* **Conditional Logic**: Uses `if-elif-else` blocks to match user inputs to bot responses.

### How to Use
1. Run the script.
2. Type "hello", "how are you", or other phrases.
3. Type "bye" to exit the program.

---

## 🎮 3. Hangman Game

A classic game where the player must guess a hidden word one letter at a time within a limited number of attempts.

### Key Features
* **Randomization**: Uses the `random` module to select a word from a list.
* **List Manipulation**: Manages a list of underscores that get replaced by correctly guessed letters.
* **Input Filtering**: Ensures the user only enters single alphabetic characters.
* **Game State Tracking**: Monitors both correct guesses and the number of remaining attempts.

### How to Use
1. Run the script.
2. Guess one letter at a time.
3. Win by revealing the full word before running out of 6 wrong guesses.

---

## 🛠️ Concepts Covered
* **Data Types**: Strings, Integers, Floats, Lists, and Dictionaries.
* **Control Flow**: `while` loops, `for` loops, and `if-elif-else` statements.
* **Functions**: Defining and calling reusable blocks of code.
* **Standard Libraries**: `import random` for game logic.
* **I/O Operations**: `input()`, `print()`, and `open()` for file writing.

## 📝 Requirements
* Python 3.x
