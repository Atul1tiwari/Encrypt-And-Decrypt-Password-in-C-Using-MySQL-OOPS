# Encrypt-Decrypt-Password
# Overview
This project demonstrates how to securely encrypt and decrypt user passwords in C++ while integrating with a MySQL database. It uses Object-Oriented Programming (OOP) principles to structure the code, ensuring maintainability and scalability. The system allows users to securely store their passwords in an encrypted form and retrieve them after decryption when needed.

# Features
Password Encryption: Encrypt user passwords before storing them in the MySQL database.
Password Decryption: Decrypt the password when the user logs in or requests it.
Database Integration: Use MySQL to store encrypted passwords and related user data.
Secure Hashing: Use hashing algorithms (e.g., SHA-256 or bcrypt) to encrypt passwords.
OOP Principles: Implement classes for better organization and separation of concerns.

# Prerequisites
C++ Compiler (e.g., GCC or Visual Studio)
MySQL Database: A running MySQL server and a MySQL database to store the data.
MySQL Connector for C++: MySQL C++ Connector must be installed to allow communication between the C++ program and MySQL database.
OpenSSL: OpenSSL is required for encryption and decryption operations.
