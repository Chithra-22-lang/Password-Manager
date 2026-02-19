🔐 Password Manager using Python

A simple and secure Password Manager Application built using Python, Tkinter GUI, and Cryptography (Fernet Encryption).
This project allows users to securely store and retrieve passwords for multiple online accounts.

📌 Project Overview

This Password Manager application provides a graphical interface to:

Store account credentials securely

Encrypt passwords before storing

Retrieve and decrypt passwords when required

Manage multiple account entries easily

The project demonstrates the concepts of:

GUI development

Data encryption & decryption

Python dictionary data storage

Event-driven programming

🚀 Features

➕ Add new password entries (Service Name, Username, Password)

🔐 Password encryption using Fernet symmetric encryption

🔎 Retrieve stored passwords securely

🖥️ User-friendly GUI using Tkinter

⚠️ Input validation with message alerts

🛠️ Technologies Used

Python

Tkinter – GUI Framework

cryptography.fernet (Fernet) – Encryption & Decryption

Any Python IDE (VS Code / PyCharm / IDLE)

🔒 How Encryption Works

A unique encryption key is generated using Fernet.generate_key()

Passwords are encrypted before storing in memory

Encrypted passwords are decrypted only when retrieving

Each password is stored securely inside a dictionary

📂 Project Structure
Password-Manager/
│
├── password_manager.py
└── README.md

▶️ How to Run the Project
1️⃣ Install Required Library
pip install cryptography

2️⃣ Run the Python File
python password_manager.py

💡 How to Use
🔹 Add a Password

Enter Account/Service Name

Enter Username

Enter Password

Click "Add Password"

🔹 Retrieve a Password

Enter Account/Service Name

Click "Get Password"

Decrypted password will be displayed

🖼️ Application Interface

Clean and simple Tkinter GUI

Input fields for Account, Username, Password

Buttons for Add & Retrieve operations

Message boxes for confirmation and alerts

📚 Learning Outcomes

This project helped in understanding:

GUI development using Tkinter

Symmetric encryption using Fernet

Secure password handling concepts

Python functions and event handling

Basic cybersecurity principles

⚠️ Limitations

Passwords are stored in memory (dictionary) and not saved permanently.

Encryption key resets when the application restarts.

Not yet connected to a database or file system.

🔮 Future Improvements

Save passwords in encrypted file/database

Master password authentication

Password strength checker

Generate strong random passwords

Dark mode UI enhancement
