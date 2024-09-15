# Bank Account Simulation

This project is a simulation of bank accounts, specifically savings accounts, with randomly generated balances and transaction histories. The simulation generates 100 accounts, performs random transactions (deposits and withdrawals) over several months, and then stores the account data in an Excel file. The accounts are also printed and sorted by balance, from lowest to highest.

## Features
- **Random Account Generation**: Creates 100 bank accounts with a random initial balance.
- **Transaction Simulation**: Simulates random deposits and withdrawals over a specified number of months.
- **Data Storage**: Saves the generated account data (final balances and transaction history) to an Excel file.
- **Data Display**: Prints the details of all accounts, including the account number, final balance, and all transactions.

## Project Structure
- `BankAccount`: A class that represents a savings bank account. It supports deposit and withdrawal operations.
- `create_random_account`: Function to create a bank account with a random initial balance.
- `simulate_transactions`: Function to simulate deposits and withdrawals over a period of time.
- `generate_random_accounts`: Generates multiple accounts with transactions.
- `save_accounts_to_excel`: Saves account data to an Excel file.
- `print_accounts_data`: Prints account data in a readable format.
- `main`: Orchestrates the generation, simulation, and saving of account data.

## Requirements

The following Python libraries are required to run the project:

- `pandas`: For saving account data to an Excel file.
- `random`: For generating random numbers (used for balance and transaction amounts).


