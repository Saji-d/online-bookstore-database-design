# 📚 Online Bookstore Management System – Database Design Project

![Oracle](https://img.shields.io/badge/Oracle-F80000?logo=oracle&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=database&logoColor=white)

This repository contains the **database design and documentation** for an **Online Bookstore Management System**, developed as part of an academic **Database Systems course**.

The project focuses on **conceptual and logical database design**, normalization, and SQL query formulation rather than application-level implementation.

---

## 📌 Project Overview

The Online Bookstore Management System is designed to handle core bookstore operations, including:
- Customer information management
- Book inventory and author details
- Order processing and order details
- Payment and transaction records

The system is modeled using a structured **Entity-Relationship (ER) design** to ensure data consistency, integrity, and scalability.

---

## 🧩 Core Design Components

### 🔹 Entity-Relationship Design
The database includes the following core entities:
- Customers
- Books
- Authors
- Genres
- Orders
- Payments

Key relationships:
- One-to-Many (Customer–Order, Customer–Payment)
- Many-to-Many (Order–Book, Book–Genre)

---

### 🔹 Normalization
The database schema is normalized step-by-step:
- UNF → 1NF → 2NF → 3NF
- Reduces data redundancy
- Improves data integrity
- Produces an optimized relational schema

---

### 🔹 SQL Design & Queries
The documentation includes:
- Table creation using `CREATE TABLE`
- Primary and foreign key constraints
- Data insertion using `INSERT`
- Data modification using `UPDATE`
- Query implementation:
  - Joins
  - Subqueries
  - Aggregate functions
- View creation for simplified data access

---

## 🛠 Technologies Used
- **Oracle Database**
- **SQL**
- **ER Modeling**
- **Database Normalization**
- **Relational Schema Design**

---

## 📄 Documentation

The complete project documentation is available as a single report:

📘 **BookStore_Management_System.pdf**

The document contains:
- System overview
- ER diagrams
- Normalization process
- SQL schema and queries
- Sample data and views

---

## 🎓 Academic Context

This project was developed to demonstrate practical understanding of:
- Database design principles
- Relational modeling
- SQL query formulation
- Data integrity and constraints

It is intended as a **design-focused academic project**, not a full software application.

---

## 👤 Author
**Sajidur Rahman Sajid**  
BSc in Computer Science & Engineering  
Final-year undergraduate student
