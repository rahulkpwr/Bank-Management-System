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

**📸 Screenshots**

<img width="800" height="1000" alt="Screenshot (58)" src="https://github.com/user-attachments/assets/3d94c0ac-70f6-42f0-8c7a-3fcfa226587a" />

<img width="800" height="1000" alt="Screenshot (59)" src="https://github.com/user-attachments/assets/40b142d7-8e4b-4ac9-bda4-2367848f97c5" />

<img width="800" height="1000" alt="Screenshot (60)" src="https://github.com/user-attachments/assets/f8304ac3-532a-4f77-b6cb-dad044ac93d2" />

<img width="800" height="1000" alt="Screenshot (62)" src="https://github.com/user-attachments/assets/7de3b8dc-50c0-417e-aa52-3a7314d41430" />

<img width="800" height="1000" alt="Screenshot (64)" src="https://github.com/user-attachments/assets/5bb81f06-99c1-44ca-9ae6-02a541589487" />

<img width="800" height="1000" alt="Screenshot (65)" src="https://github.com/user-attachments/assets/af69f8ac-22b9-47dc-bbe2-d13f796a2d6f" />

<img width="800" height="1000" alt="Screenshot (67)" src="https://github.com/user-attachments/assets/b4537aad-72da-4a39-9f7d-b3bea788df06" />


📈 Future Enhancements

Online banking with web integration.

OTP-based authentication for transactions.

Role-based access (Admin/Customer).

Enhanced security with password hashing.













