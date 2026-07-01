# Personal Expense Tracker (Python)

A simple command-line **Personal Expense Tracker** built with Python that allows users to record daily expenses, organize them by category, view spending history, generate statistics, and save a report to a text file.

## Features

* Add unlimited expense records.
* Input validation for numeric amounts.
* Automatic timestamp for every expense.
* Custom expense categories (default: General).
* View complete expense history in a formatted table.
* Category-wise expense summary.
* Expense statistics including:

  * Total expenses
  * Average spending
  * Highest expense
  * Lowest expense
* Export the complete expense report to a `.txt` file.

## Technologies Used

* Python 3
* `datetime` module
* File Handling

## How to Run

1. Clone this repository.
2. Open the project folder.
3. Run the Python file:

   ```bash
   python expense_tracker.py
   ```
4. Enter your expenses one by one.
5. Type `done` when finished.
6. Choose whether to save the generated report.

## Project Structure

* Expense recording
* Expense history
* Category summary
* Statistics generation
* Report export

## Output

The program displays:

* Expense history
* Category-wise breakdown
* Total spending statistics
* Optional text report (`expenses_report.txt`)

---

### Developer

**Alina Mehmood**

This project was developed as a Python practice project to demonstrate concepts such as functions, loops, dictionaries, input validation, file handling, and modular programming.
