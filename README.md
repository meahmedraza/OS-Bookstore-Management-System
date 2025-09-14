# 📚 Book Store Management System (BSMS) – Shell Script with MongoDB

This repository contains the **report** of a small Operating Systems project:  
A **Book Store Management System** implemented in **Shell Script**, with **MongoDB** as the backend database.  

> ⚠️ Note: The source code has been lost, but the detailed project **report** is included for reference and documentation.

---

## 📖 Abstract

The **Book Store Management System (BSMS)** provides functions for managing a bookstore’s inventory and customer records.  
It is a **menu-driven shell script** that interacts with a **MongoDB database** using the `mongosh` command-line tool.

---

## ⚙️ Features

### 📚 Book Management
- Add a new book (Title, Author, Price, Stock, ISBN)
- Display all books
- Buy a book by ISBN
- Modify book details
- Delete a book
- Delete all book data

### 👥 Customer Management
- Add customer details (Name, Address, Phone, Email)
- Display all customers
- Delete all customer data

### 🧾 Other Functions
- Generate receipt for book purchases
- Exit the system

---

## 🛠️ Implementation Details

- **Language**: Shell Script  
- **Database**: MongoDB (`mongosh`)  
- **Collections**:
  - `Inventory` → Stores book details
  - `Customers` → Stores customer details
  - `Receipts` → Stores purchase receipts

Each function interacts with MongoDB to perform CRUD operations (`insertOne`, `find`, `update`, `deleteOne`).

---

## 📑 Learning Outcomes

Through this project, we learned:  
- How to integrate **Shell Scripts** with **MongoDB**  
- Performing CRUD operations in a real database  
- Designing a **menu-driven interface** in shell  
- Importance of proper **database design** and data integrity  

---

## 📂 Repository Content
- `Report.docx / Report.pdf` → Detailed project description, implementation, and conclusion  

---

## ✅ Conclusion

The BSMS project is a **basic database-driven application** demonstrating:  
- Practical use of shell scripting  
- Database integration  
- Real-world problem solving  

Although the **code is lost**, the **documentation/report** provides a full explanation of the system’s design and functionality.
