# JavaJDBCEmployeeApp
# Java JDBC – Employee Database App

## 🎯 Objective
A simple Java application to perform CRUD operations on an Employee database using JDBC and MySQL.

## 🛠️ Tools
- Java
- MySQL
- JDBC Driver (mysql-connector-j-9.3.0.jar)
- VS Code

## 💡 Features
- Add Employee
- View All Employees
- Update Employee
- Delete Employee

## 🔗 Database Setup
```sql
CREATE DATABASE company_db;

USE company_db;

CREATE TABLE employee (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100),
    department VARCHAR(50),
    salary DOUBLE
);
#Output
=== Employee Management ===
1. Add Employee
2. View All Employees
3. Update Employee
4. Delete Employee
5. Exit
