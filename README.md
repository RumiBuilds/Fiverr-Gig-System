# Fiverr Gig Management System

A console-based Fiverr Gig Management System developed in C++ using an N-ary Tree data structure.

The system simulates a freelance marketplace where gig owners can manage sellers and employees, while buyers can view sellers and place orders.

## Features

- Seller registration
- Seller and employee management
- Hierarchical team structure
- N-ary tree implementation
- Seller ratings
- Employee management
- Order placement
- Order completion tracking
- Seller information display
- Seller deletion
- Admin authentication
- Buyer and seller menus
- Console-based user interface

## Technologies Used

- C++
- Data Structures
- N-ary Tree
- Dynamic Memory Allocation
- File Handling
- Object-Oriented Programming
- Console Application

## Data Structure

The core of this project is an **N-ary Tree**.
Each gig owner acts as the root node, while sellers/employees can be connected as children or siblings, creating a hierarchical freelancing team structure.
This structure allows the system to represent relationships between gig owners and their team members.

## System Modules
### Seller Management

Sellers can be added to the system with information including:

- Name
- Country
- Rating
- Number of employees
- Orders completed

### Team Management

A seller can work under the main gig owner or another eligible team member.
The system maintains these relationships using an N-ary tree.

### Order Management

Buyers can select a seller and place an order. The system updates the selected seller's completed order count
and displays a confirmation message.

### Seller Display

The system displays:

- Gig owner
- Employees
- Team hierarchy
- Country
- Rating
- Employee count
- Completed orders

### Seller Deletion

Authorized users can remove sellers from the system.

### Authentication

The project includes a basic username/password authentication mechanism for protected operations.

### Main Menu
`Seller, Buyer, Quit`

### Seller Menu
`Insertion, Deletion, Display, Main Menu, Exit`

### Buyer Menu
`Placing Order, Displaying Sellers, Main Menu, Exit`

## Concepts Demonstrated

This project demonstrates practical use of:

- N-ary Trees
- Tree Traversal
- Nodes and Pointers
- Dynamic Memory Allocation
- Structures
- Classes and Objects
- Functions
- Conditional Statements
- Loops
- File Handling
- User Authentication
- Menu-driven Programming
- Search Operations
- Data Management

### Setup & Installations
- Using Visual Studio
- Clone the repository.
`git clone https://github.com/RumiBuilds/Fiverr-Gig-Management-System.git`
- Open the project in Visual Studio.
- Open:
`src/FiverrGigSystem.cpp`
- Build the project.
- Run the application.

### Project Purpose

This project was developed to demonstrate practical implementation of data structures and object-oriented programming concepts through a real-world-inspired freelance marketplace management system.

## Developer

### Rimsha Tariq

Computer Science Graduate

⭐ If you like this project, feel free to give it a star!
