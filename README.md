# Personal Finance Tracker

A command-line personal finance tracker in Python. Add income/expense
transactions, store them in a CSV file, review them over a date range with a
summary (total income, total expense, net savings), and optionally plot income
vs. expenses over time.

Built as a learning project following [Tech With Tim](https://www.youtube.com/@TechWithTim)'s
tutorial, to practice pandas and matplotlib.

## Stack

- Python 3
- pandas (data handling)
- matplotlib (plotting)
- CSV file storage (`finance_data.csv`)

## Features

- Add a transaction: date, amount, category (Income / Expense), optional description
- View transactions within a date range, with an income / expense / savings summary
- Optional matplotlib chart of income vs. expenses over time

## Getting started

```bash
pip install -r requirements.txt
python main.py
```

Follow the menu prompts (dates use `dd-mm-yyyy`).

## Example session

```
1. Add a new transaction
2. View transactions and summary within a date range
3. Exit
Enter your choice (1-3): 1
Enter the date of the transaction (dd-mm-yyyy) or enter for today's date: 21-06-2026
Enter the amount: 1500
Enter the category ('I' for Income or 'E' for Expense): I
Enter a description (optional): Salary
Entry added successfully
```