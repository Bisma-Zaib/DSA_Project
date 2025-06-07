Project Overview: 
This Expense Tracker is a Java application that helps users manage their personal finances by tracking expenses, recurring payments, and income. The system uses an AVL tree data structure to efficiently store and retrieve transactions sorted by amount, providing fast search, insertion, and deletion operations.

Key Features: 
Transaction Management
Regular Expenses: Track one-time expenses with category, description, amount, and date

Recurring Expenses: Manage periodic payments with customizable frequency (monthly, weekly, annually)

Income Tracking: Record income sources with details and dates

Core Functionality
AVL Tree Implementation: All transactions are stored in a self-balancing binary search tree for efficient operations

Balance Tracking: Real-time calculation of remaining balance after each transaction

Transaction History: View all transactions in amount-sorted order

Undo Functionality: Revert the last transaction with a single command

Search Capability: Quickly find transactions by amount

Data Structures:

AVL Tree for transaction storage (O(log n) operations)

Stack for undo functionality

List for maintaining transaction history

Object-Oriented Design:

Inheritance hierarchy (Transaction → Expense → RecurringExpense/Income)

Polymorphism for different transaction types

Date Handling: Uses Java's LocalDate for transaction dates

How to Use
Set your initial balance when starting the application

Use the menu to:

Add regular/recurring expenses

Record income

Delete transactions

View balance and history

Undo mistakes

Search for specific transactions

