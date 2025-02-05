# 📒 Contact Book Application

A simple yet powerful **Contact Book** application built using **Python, Tkinter, and SQLite**. This application allows users to **add, edit, delete, and search** contacts with an interactive and colorful user interface.

---
## ✨ Features
- 🎨 **Modern and Colorful UI**
- 🔍 **Dynamic Contact Search**
- ➕ **Add New Contacts Easily**
- ✏️ **Edit Existing Contacts**
- 🗑️ **Delete Unwanted Contacts**
- 📄 **Persistent Storage with SQLite Database**
- 📋 **Easy-to-Use Interface**
- 🔄 **Real-Time Updates**

---
## 🛠️ Installation

### 📌 Prerequisites
Make sure you have Python installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

### 📦 Install Required Libraries
```sh
pip install tk
```

---
## 🚀 Usage

### 📥 Clone the Repository
```sh
git clone https://github.com/charan300804/Contact-book.git
```

### ▶️ Run the Application
```sh
python contact_book.py
```

---
## 📚 How to Use
- **➕ Add Contact**: Click the "Add Contact" button, enter details, and save.
- **✏️ Edit Contact**: Select a contact from the list, click "Edit Contact", modify details, and save.
- **🗑️ Delete Contact**: Select a contact from the list and click "Delete Contact".
- **🔍 Search Contact**: Use the search bar to dynamically filter contacts.

---
## 🏛️ Database Structure
The application stores contacts in an SQLite database (`contact_book.db`) with the following schema:
```sql
CREATE TABLE CONTACTS_TABLE (
    Name TEXT NOT NULL,
    Mobile_Number TEXT PRIMARY KEY,
    Phone1 TEXT,
    Phone2 TEXT,
    Email TEXT,
    Notes TEXT
);
```

---


Happy Coding! 🚀

