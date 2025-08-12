# Bank Management System

## 📌 Overview
The **Bank Management System** is a Java-based desktop application designed to simplify banking operations.  
Using **Java Swing** for the frontend and **MySQL** for the backend, this project allows customers to perform basic banking transactions conveniently from their home or office.

---

## 🚀 Features
- **Account Creation** – Register new customers with necessary details.
- **Deposit Funds** – Add money to customer accounts.
- **Withdraw Funds** – Secure cash withdrawal functionality.
- **Account Reports** – View transaction history and account details.
- **User-Friendly Interface** – Built using Java Swing for a clean and intuitive design.
- **Secure Database Storage** – All data stored and managed using MySQL.

---

## 🛠️ Technologies Used
- **Programming Language:** Java
- **Frontend:** Java Swing
- **Backend:** MySQL
- **Database Connectivity:** JDBC

---

## 📂 Project Structure
BankManagementSystem/
│── src/ # Java source code files
│── lib/ # JDBC driver and dependencies
│── database/ # SQL scripts for creating tables
│── README.md # Project documentation
│── BankMS.jar # Executable JAR file


---

## ⚙️ Installation & Setup
1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/BankManagementSystem.git
   cd BankManagementSystem
   
2.**Setup Database
  Install MySQL.
  Create a database:**
  CREATE DATABASE bank_management;
  **Import the provided SQL file:**
  USE bank_management;
  SOURCE database/bank_management.sql;
  
3.**Configure JDBC Connection Open DBConnection.java and update:**
 String url = "jdbc:mysql://localhost:3306/bank_management";
 String username = "root";
 String password = "your_password";
 
4.**Run the Project
   Compile and run:**
   javac -cp lib/mysql-connector-java.jar src/*.java
   java -cp "lib/mysql-connector-java.jar;src" Main


