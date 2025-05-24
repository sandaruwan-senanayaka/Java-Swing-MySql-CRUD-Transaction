# Java Swing + MySQL CRUD with Transaction Scope

This is a simple desktop application built using **Java SE Swing** and **MySQL**, showcasing how to:

- Connect to a MySQL database using JDBC
- Perform basic `INSERT` operations
- Manage multiple operations within a **transaction scope**
- Handle `commit` and `rollback` safely

## 🧪 Features
- Simple user interface with Java Swing
- Insert data into `user` and `invoice` tables
- Demonstrates real-world use of transactions in JDBC

## 📦 Technologies
- Java SE (Swing)
- JDBC
- MySQL

## 🚀 How to Run
1. Clone the repo
2. Setup your MySQL with appropriate tables:
    ```sql
    CREATE TABLE user (id INT AUTO_INCREMENT PRIMARY KEY, name VARCHAR(100));
    CREATE TABLE invoice (id INT AUTO_INCREMENT PRIMARY KEY, price DOUBLE);
    ```
3. Modify your DB connection details in `MySQL.java`
4. Run the application and test inserts

## 📂 Author
Sandaruwan – [LinkedIn]([https://www.linkedin.com/in/sandaruwan-senanayaka/])

---

Feel free to fork, improve, or ask questions!
