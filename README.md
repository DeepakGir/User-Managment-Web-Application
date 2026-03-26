# User Management System (JSP + Servlet + JDBC)

This project is a **Java-based Web Application** developed using **JSP, Servlets, JDBC, and MySQL**.
The application allows users to manage records through **CRUD operations (Create, Read, Update, Delete)**.

## 🚀 Features

* Add new user
* View all users
* Update user information
* Delete user
* MySQL database connectivity
* Simple and user-friendly interface

## 🛠 Technologies Used

* Java
* JSP (Java Server Pages)
* Servlets
* JDBC (Java Database Connectivity)
* MySQL
* Apache Tomcat

## 📂 Project Structure

* **JSP Files** – Frontend user interface
* **Servlet Classes** – Handle request and business logic
* **DAO / JDBC** – Database connectivity
* **MySQL Database** – Store user data

## 🗄 Database Setup

Run the following SQL commands:

```sql
CREATE DATABASE userdb;

USE userdb;

CREATE TABLE users (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100),
    email VARCHAR(100),
    country VARCHAR(100)
);
```

## ▶ How to Run the Project

1. Install **Apache Tomcat Server**.
2. Import the project into **IntelliJ IDEA or Eclipse**.
3. Add **MySQL Connector (JDBC Driver)**.
4. Configure database connection in the project.
5. Deploy the project on **Tomcat Server**.
6. Open the application in your browser.

## 📋 Application Functions

* Create new user records
* Read and display users
* Update existing user information
* Delete user records

## 👨‍💻 Author

Deepak Gir
Computer Science Student
