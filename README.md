# Library Management Database

## 📌 Overview
This project implements a **Library Management System** database in MySQL.  
It includes tables for members, books, authors, staff, and borrowings, with relationships and constraints.

## 📂 Files
- `library_management.sql` → SQL script with database creation and table definitions.

## 🔹 Database Features
- Members table (library users)
- Books table (library collection)
- Authors table (book authors)
- BookAuthors table (junction table for Many-to-Many relationship)
- Staff table (librarians)
- Borrowings table (borrowing transactions)

## 🔹 Relationships
- One-to-Many: Members → Borrowings
- One-to-Many: Staff → Borrowings
- One-to-Many: Books → Borrowings
- Many-to-Many: Books ↔ Authors (via BookAuthors)

## ▶️ How to Run
1. Clone this repo:
   ```bash
   git clone <your_repo_url>
   cd Databases
