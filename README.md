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

```text
                    Gig Owner
                       |
          ---------------------------
          |            |            |
       Seller 1     Seller 2     Seller 3
          |
      Employee
