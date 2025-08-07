# 🏧 ATM Service - C++ Project

This project simulates a simple ATM Machine System using C++, as part of Course 08 - Algorithms & Problem Solving Level 4 from the roadmap by [Mohammed Abu Hadhoud](https://www.youtube.com/@MohammedAbuHadhoud).

---

## 💡 Overview

The project focuses on creating an ATM interface for a user (client) to:

- 🔐 Log in securely using Account Number and PIN
- 💵 Perform Quick Withdraw
- 🏦 Perform Normal Withdraw
- 💰 Make Deposits
- 💳 Check balance
- ↩️ Log out securely

All data is stored and retrieved from a local text file Clients.txt.

---

## 📦 Features

- 👤 Client login system
- 💸 Quick withdraw options (20, 50, ..., 1000)
- 🧾 Normal withdraw with validation for multiples of 5
- ➕ Deposit with validation
- 📊 Check account balance
- 📁 Persistent storage using file I/O
- 🧠 Modular code using struct, enum, functions, and file handling

---

## 📂 File Structure

`bash
📁 ATM-Service
├── main.cpp
├── Clients.txt
└── README.md


---

🔐 Sample Clients.txt Format

Each line in the file represents one client using this format:

AccountNumber#//#PinCode#//#FullName#//#PhoneNumber#//#AccountBalance

Example:

1234#//#0000#//#John Doe#//#0555123456#//#1500.5


---

🧑‍💻 Author

> Abed-El-Hassib Lakhdari
🎓 Computer Science Student
🚀 Passionate about mastering C++ and problem solving




---

📜 License

This project is for learning and educational purposes. You are free to use and modify it for personal development.


---

🌟 Give this repository a star if you found it useful!

---
