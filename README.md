# Online ATM System (Java Console Application)

## Overview

This project is a console-based Online ATM System developed in Java. It simulates core banking functionalities such as account creation, deposits, withdrawals, transfers, PIN management, card blocking/unblocking, loan application, and transaction history tracking.

The system is designed using Object-Oriented Programming (OOP) principles, focusing on abstraction, inheritance, and encapsulation.



## Features

- Create new bank accounts
- Deposit money into account
- Withdraw money from account
- Transfer money between accounts
- Check account balance
- Change PIN securely
- Block and unblock card functionality
- View transaction history
- Apply for a loan with repayment options
- Prevent duplicate PIN usage during account creation



## Technologies Used

- Java (Core Java)
- Object-Oriented Programming (OOP)
- Array and ArrayList data structures
- Console-based input/output using Scanner


## OOP Concepts Implemented

### Abstraction
- `BankAccount` is an abstract class that defines the structure of a bank account.

### Inheritance
- `OnlineATMSystem` extends `BankAccount` and implements banking operations.

### Encapsulation
- Account data such as balance, PIN, and personal details are protected within the class.


## Class Structure

### BankAccount (Abstract Class)

Contains core account properties and methods:

- accountNumber
- firstName, lastName, city
- balance
- pin
- transactionHistory
- personalizedAlerts

Abstract Methods:
- deposit(double amount)
- withdraw(double amount)


### OnlineATMSystem (Main Class)

Implements all banking operations:

- deposit()
- withdraw()
- transfer()
- changePin()
- blockCard()
- unblockCard()
- applyForLoan()
- main() method for menu-driven system

