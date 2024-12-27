Overview :
This is a user-friendly C++ program that simulates basic banking operations for a single user. The program allows users to view their account information, deposit money, and withdraw money with proper checks for minimum balance and withdrawal limits. It uses Object-Oriented Programming (OOP) concepts, including constructors, encapsulation, and member functions.

Features :
Account Information:

Displays the user's name, account number, and balance.

Deposit:

Prompts the user to deposit money into their account.
Automatically updates the balance.

Withdrawal:

Ensures that the user cannot withdraw below the minimum balance.
Displays the available withdrawal limit before processing.

Validation:

Provides user-friendly error messages for invalid inputs.
Allows recursive retries for invalid choices.
OOP Concepts Used:

Constructors (default and parameterized)
Encapsulation (with getter and setter methods)
Class methods for modular functionality
How It Works
Account Creation:

A parameterized constructor is used to initialize the user’s account details.
Menu Options:

The user is presented with options to view account details, deposit money, or withdraw money.
Deposits:

Users can choose to deposit an amount into their account. The balance is updated accordingly.
Withdrawals:

Users can withdraw money, but only within the allowed limit. The program checks to ensure the balance does not fall below a set minimum.
