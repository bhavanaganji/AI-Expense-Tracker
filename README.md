# AI-Expense-Tracker
Expense Tracker
A simple command-line tool to record and summarize your daily expenses, categorized by type, and track your budget.

Features:
Record new expenses interactively
Categorize expenses (Food, Home, Work, Fun, Misc)
Store expenses in a CSV file
Summarize expenses by category
Track total spending and remaining budget
Calculate daily budget suggestions based on remaining days in the month

Project Structure:
expense_tracker/
├── expense_tracker.py     # Main expense tracker logic
├── expense.py             # Expense class definition (required)
├── expenses.csv           # File where expenses are stored (auto-created)

Requirements:
Python 3.x

Expenses are stored in a file named expenses.csv. Each entry includes:
Expense name, Amount, Category
Example:
Coffee,3.50,🍔 Food
Rent,800.00,🏠 Home

