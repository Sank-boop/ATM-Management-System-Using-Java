# ATM-Management-System-Using-Java

##  Project Overview
The **ATM Management System** is a simple console-based application developed in **Core Java** that simulates the functionality of an **Automated Teller Machine (ATM)**. This project allows the user to **withdraw money, deposit money, check balance**, and **exit the system**. It also handles error scenarios like **insufficient balance, invalid input, or negative amounts**.

## Features of the Project

| Feature                | Description                                                                 |
|----------------------|-------------------------------------------------------------------------------|
|  **Withdraw Money**   | Allows users to withdraw money from their account, validating the balance.   |
|  **Deposit Money**    | Allows users to deposit money into their account and update the balance.     |
|  **Check Balance**     | Allows users to check the current account balance.                          |
|  **Exit System**      | Allows users to exit the ATM application safely.                             |
|  **Input Validation** | Ensures that negative or zero inputs are not allowed for deposits/withdrawals. |

---

## Technologies Used
- **Java SE (Core Java)**
- **Java Util Package (Scanner Class)**
- **File Handling (Optional)**
- **Console-based Application**

---

## How to Run the Project

### **1. Clone the Repository**
```bash
https://github.com/your-username/ATM-Management-System.git
```

### **2. Open the Project in any IDE (Optional)**
- Open the project in **Eclipse**, **IntelliJ IDEA**, or any text editor.
- Run the file `atm.java`.

### **3. Compile the Code**
```bash
javac atm.java
```

### **4. Run the Code**
```bash
java atm
```

### **5. Output Example**
```plaintext
Automated Teller Machine
1. Withdraw
2. Deposit
3. Check Balance
4. Exit
Choose the operation you want to perform: 1

Enter money to be withdrawn: 5000
Please collect your money

Balance: 95000
```

---

##  Folder Structure
```plaintext
ATM-Management-System
│
├── atm.java      <-- Main Java file
├── README.md     <-- Project Documentation
└── .gitignore    <-- Git Ignore File
```

