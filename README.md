# Personal Finance Tracker

A Python-based, command-line tool for tracking personal finances. Users can add and manage transactions, view transaction history, and analyze their finances over a specific date range, with a summary that includes total income, total expenses, and net savings. All data is saved in a CSV file for easy access and modification, and summary data is presented in a plot diagram for visual insights.

## Features

- **Add Transactions**: Easily log new transactions by entering the amount, category (either "Income" or "Expense"), and an optional description. Each entry is saved in a CSV file for permanent storage.
- **View Transactions and Summary**: Retrieve and view transaction history within a specified date range, including a summary of total income, total expenses, and net savings.
- **Plot Diagram**: Visualize financial summaries with a plot diagram to easily interpret income, expenses, and savings trends.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Mohammed-Abdelmoneim/personal-finance-tracker.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd personal-finance-tracker
   ```
3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Run the tracker**:

   ```bash
   python3 main.py
   ```

2. **Options**:

   - **Add a Transaction**:

     - Enter the transaction amount, category (either "Income" or "Expense"), and an optional description.
     - The transaction details are stored in a `finance_data.csv` file.

   - **View Transactions and Summary**:
     - Specify a date range by entering the start and end dates.
     - The app retrieves transactions from the `finance_data.csv` file within the date range and displays:
       - Total Income
       - Total Expenses
       - Net Savings
     - Additionally, a plot diagram is generated, visualizing income, expenses, and savings for the selected period.

## Example

```plaintext
Welcome to Personal Finance Tracker

Choose an option:
1. Add a New Transaction
2. View Transactions and Summary
3. Exit

Enter your choice (1-3): 1

Enter transaction date (dd-mm-yyyy) or enter for today's date: 03-08-2024
Enter the amount: 150.00
Enter the category ('I' for Income or 'E' for Expense): E
Enter a description (optional): Groceries
Transaction added successfully!
```

## Dependencies

- **Matplotlib**: For generating plot diagrams.
- **Pandas**: For data handling and filtering within date ranges.

---
