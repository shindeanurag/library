# Library Management System (JDBC + MySQL)

This is a simple console-based Library Management System developed in Java using JDBC for database connectivity. It allows users to manage books stored in a MySQL database.

## 📌 Features

- Add a new book
- Remove a book by ID
- Update book details (name, author, price)
- Search for a book by name
- Menu-driven user interface in the console

## 🛠️ Technologies Used

- Java (JDK 8 or above)
- JDBC API
- MySQL
- SQL (basic DDL and DML)

## 🗄️ Database Schema

Create the following table in your `library` database:

```sql
CREATE DATABASE library;

USE library;

CREATE TABLE Bookrack (
    id INT PRIMARY KEY,
    Book_name VARCHAR(100),
    auther VARCHAR(100),
    price INT
);
