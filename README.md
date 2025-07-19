# 🪑 Inventory Management System (Furniture Company)

A bilingual (Arabic & English) desktop application developed using **Python**, **Tkinter**, and **MySQL** to help a local furniture business efficiently manage their inventory operations.

---

## 📖 Overview

This application enables users to:

- Add, view, update, and delete furniture inventory items  
- Generate barcodes for products  
- Manage inventory through a user-friendly graphical interface powered by Tkinter and **extensively customized with CustomTkinter widgets** for a modern look and feel  
- Supports both **Arabic and English** languages, allowing flexible usage  
- Store and retrieve data securely from a MySQL database  


## 🛠 Features

- Add, view, and update furniture inventory records  
- Barcode generation for products  
- Bilingual support: Arabic and English UI  
- MySQL database integration  
- Modern and customizable GUI built heavily using **CustomTkinter**  
- Modular, easy-to-extend codebase  
- Work in progress: some features/buttons are under development  

---

## ⚙️ How to Run

### 1. Prerequisites

- **Python 3.x** installed ([Download Python](https://www.python.org/downloads/))  
- **MySQL Server** installed and running  
- Clone the repo:
git clone https://github.com/ABDCODES12/inventory-management-system.git
cd inventory-management-system

### 2. Install Python dependencies
pip install pillow customtkinter mysql-connector-python python-barcode python-dotenv

### 3. Configure your database connection
Create a .env file in the project root directory with the following contents:
DB_HOST=localhost
DB_USER=your_mysql_username
DB_PASSWORD=your_mysql_password
DB_NAME=furniture_db

### 4. Run the application
If using Jupyter Notebook:
jupyter notebook Main.ipynb
Or run a Python script directly (if applicable):
python main.py

## ⚠️ Troubleshooting
Environment Variables Not Loading?
If you encounter issues with load_dotenv(), try specifying the full path to your .env file:
from dotenv import load_dotenv
load_dotenv(dotenv_path="full/path/to/.env")
Replace "full/path/to/.env" with the absolute path on your machine.

## 📦 Dependencies
Pillow — for image handling

customtkinter — for enhanced, modern Tkinter widgets (used extensively)

mysql-connector-python — to connect to MySQL

python-barcode — for barcode generation

python-dotenv — for loading environment variables

👤 Author
Abdullah Mahmoud
📧 abdullahhammam006@gmail.com
🔗 GitHub Profile

<img width="1919" height="1016" alt="image" src="https://github.com/user-attachments/assets/653d6e0c-498b-49bb-a277-b66ef9ac5f46" />
<img width="1919" height="1020" alt="image" src="https://github.com/user-attachments/assets/0defa265-424a-40a4-8a1f-e097bbac7aab" />
<img width="1918" height="1009" alt="image" src="https://github.com/user-attachments/assets/907f6792-4550-4cce-8d34-9f6081126b10" />
<img width="1919" height="1019" alt="image" src="https://github.com/user-attachments/assets/e1aa6ee9-3dfd-431b-9b2c-34dcda1cb2db" />


