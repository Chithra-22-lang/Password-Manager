🔐 Password Manager 
-

A secure desktop-based Password Manager built using Python and Tkinter, implementing Fernet symmetric encryption from the cryptography library to protect user credentials.

This project demonstrates practical implementation of GUI development, secure password encryption, and event-driven programming in Python.

📖 Overview

The Password Manager allows users to:

Securely store credentials for multiple online services

Encrypt passwords before storage

Retrieve and decrypt passwords when required

Interact through a clean graphical interface

The primary focus of this project is to combine usability with basic cybersecurity practices.

✨ Key Features

Secure password encryption using Fernet

Add and retrieve account credentials

User-friendly Tkinter-based GUI

Input validation with alert messages

In-memory encrypted storage structure

🛠️ Tech Stack
Technology	Purpose
Python	Core programming language
Tkinter	GUI development
cryptography (Fernet)	Encryption & Decryption
🔐 Security Implementation

A unique encryption key is generated using Fernet.generate_key().

Passwords are encrypted before being stored.

Decryption occurs only during retrieval.

Encrypted passwords are stored in a dictionary structure during runtime.

📂 Project Structure
password-manager/
│
├── password_manager.py
├── requirements.txt
└── README.md

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/password-manager.git
cd password-manager

2️⃣ Install Dependencies
pip install cryptography

3️⃣ Run the Application
python password_manager.py

🖥️ How It Works
Add Password

Enter Account Name

Enter Username

Enter Password

Click Add Password

Retrieve Password

Enter Account Name

Click Get Password

Decrypted credentials are displayed securely via message box

📚 Learning Outcomes

This project strengthened understanding of:

Secure credential management

Symmetric key encryption (Fernet)

GUI design principles

Event handling in Python

Input validation and user interaction

⚠️ Current Limitations

Data is stored only in memory (not persistent).

Encryption key is regenerated each time the application runs.

No database or file storage integration.

No master authentication system.

🚀 Future Enhancements

Persistent encrypted storage (JSON/File/Database)

Master password authentication

Password strength validation

Random password generator

UI enhancements and improved layout design
