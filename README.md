# inventory-management-system.
Inventory Management System

A console-based inventory management system written in C. It lets an authorized admin log in, add products, update stock, remove items, and view the full inventory from the terminal.

Submitted as a BCA-IT (1st Semester) project at Aryan School of Engineering, Purbanchal University, Kathmandu (June 2026).

## Features
Secure admin login: up to 3 attempts, with masked password input
Add new products: each product gets a unique auto-generated ID, plus a name, price and quantity
Update stock: increase or decrease the quantity of an existing item
Remove items: delete a product from the inventory by ID
View inventory: shows all items in a clean, aligned table
Input validation: blocks invalid menu choices and negative stock values
## How It Works
The program starts and asks for admin credentials.
After a successful login, the dashboard menu is shown:
1. Add Item
2. Update Stock
3. Remove Item
4. View Inventory
5. Exit
After each operation the program returns to the menu, and it keeps running until you choose Exit.

Records are stored in an array of structs (inventory[MAX_ITEMS]), and the program is split into modules: Authentication, Dashboard, Registration, Update & Remove, and Display.

## Concepts Used
Structures (struct)
Arrays
Loops and conditional statements
Functions and modular programming
Input validation
Requirements

## Software

OS: Windows / Linux / macOS
Compiler: GCC / Turbo C / Code::Blocks / Dev C++

## Hardware

Intel Core i3 or better
2 GB RAM minimum (4 GB recommended)
500 MB free storage 
## Team
- Kabi Raj Bhat (312729)
- Sanjay B.K (312744)
- Sameer B.K (312742)

Aryan School of Engineering, Purbanchal University
