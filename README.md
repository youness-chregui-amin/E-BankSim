#
#  E-BankSim Cpp

This project is a simple **E-BankSim** implemented in C++  
that simulates a database for storing client information and performing transactions.

---

## Database Concept

The project uses a **text file (`Clients.txt`)** as a database to store client records.  
Each record contains:

- Account Number
- Pin Code
- Name
- Phone
- Account Balance

Records are stored with a custom separator: `#//#`.

---

## Features

- **CRUD Operations** (Create, Read, Update, Delete)
  - Add new clients
  - Update client info
  - Delete clients
  - Find clients by Account Number
- **Transactions**
  - Deposit money
  - Withdraw money
  - Show total balances of all clients
- Display all clients in a table-like format
- Simple command-line interface (CLI)

---

## How It Works

1. Data is read from `Clients.txt` into memory (vector of clients).
2. Operations are performed on the in-memory data.
3. Data is saved back to `Clients.txt` after changes.
4. Menus guide the user through actions:
   - Main Menu
   - Transactions Menu

---

## Main Menu Options

1. Show Client List  
2. Add New Client  
3. Delete Client  
4. Update Client Info  
5. Find Client  
6. Transactions  
7. Exit  

## Transactions Menu Options

1. Deposit  
2. Withdraw  
3. Total Balances  
4. Main Menu  

---

## Learning Goals

- Simulate a database using text files
- Learn **file handling** with `fstream` in C++
- Practice **CRUD operations** in a CLI project
- Understand **data persistence** without a real database

---

## Project Structure

- `E-BankSim.cpp`   → Source code  
- `Clients.txt` → Database file storing client records  
- `README.md`  → Project description  



