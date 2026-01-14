# 🔐 Secure Data Access & File Encryption System (Python)

## 📌 Project Overview

This project is a **Python-based secure file encryption and access control system** that allows **only authorized users** to encrypt or decrypt files.
User credentials are **encrypted and stored securely in a text file**, and sensitive file operations are restricted using **login-based authorization**.

The project demonstrates **strong Python fundamentals**, **Object-Oriented Programming**, **file handling**, and **data structure usage**, making it suitable for **Data Analyst, Backend, and Entry-Level Software roles**.

---

## 🎯 Key Features

* 🔑 **User Registration & Login System** with encrypted password storage
* 🔐 **File Encryption & Decryption** using character-level encryption
* 🚫 **Access Control (Authorization)** – only logged-in users can access files
* 🗑 **User Account Deletion** using username
* 📂 **Persistent Data Storage** using text files
* 🧱 **Clean OOP Design** with separation of responsibilities

---

## 🧠 Concepts & Skills Demonstrated

* Object-Oriented Programming (OOP)
* File Handling (Read / Write / Update)
* Authentication vs Authorization
* Data Structures: **Stack (LIFO)** & **Queue (FIFO)**
* String Manipulation & ASCII operations
* Exception Handling
* Command-Line Interface (CLI)

---

## 🏗 Project Architecture

```
file_encryption_tool/
│
├── secure_file_encryptor.py
├── users.txt
├── input.txt
├── encrypted.txt
└── decrypted.txt
```

---

## 🔐 How Password Security Works

* User passwords are **encrypted before being stored**
* Passwords are **never saved in plain text**
* During login, the entered password is encrypted again and compared with stored encrypted values
* This ensures **secure credential validation**

**users.txt format:**

```
username:encrypted_password
```

Example:

```
admin:rcuu345
user1:vguv678
```

---

## ⚙ How File Encryption Works

* Each character in the file is encrypted using **ASCII character shifting**
* A **Stack (LIFO)** is used during encryption to reverse the data
* A **Queue (FIFO)** is used during decryption to restore the original order
* This combination adds an extra layer of data transformation

---

## ▶ How to Run the Project

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/secure-file-encryption.git
cd secure-file-encryption
```

### 2️⃣ Run the application

```bash
python secure_file_encryptor.py
```

### 3️⃣ Follow the menu options

* Register
* Login
* Encrypt File
* Decrypt File
* Delete User
* Exit

---

## 📊 Sample Input & Output

### input.txt

```
Hello Secure World
```

### encrypted.txt

```
fntqY#gwtgeU#qnngJ
```

### decrypted.txt

```
Hello Secure World
```


---

## 🚀 Possible Enhancements

* Replace encryption with **SHA-256 hashing**
* Add **login attempt limits**
* Mask password input
* Add **role-based access control**
* Log user activities

---

## 🛠 Technologies Used

* **Python**
* **Object-Oriented Programming (OOP)**
* **File Handling**
* **Data Structures (Stack, Queue)**
* **Authentication & Authorization**
* **String Manipulation**
* **Exception Handling**
* **Command-Line Interface (CLI)**


## 👤 Author

**HrishiKesh Waghmare**
Aspiring **Data Analyst | Python Developer**
