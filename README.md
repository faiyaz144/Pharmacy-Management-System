# 💊 Pharmacy Management System

A complete modern Pharmacy Management System built using:

- PHP
- MySQL
- HTML5
- CSS3
- JavaScript
- XAMPP

This project helps manage pharmacy operations including billing, inventory, customer management, and sales history through a professional dashboard interface.

---

# 🚀 Features

## 🔐 Admin Authentication
- Secure Login System
- Session Management
- Logout System

## 📦 Inventory Management
- Add Medicines
- Update Stock
- Delete Medicines
- Search Medicines
- Low Stock Alerts
- Expiry Date Tracking
- Live Inventory Updates

## 🧾 Billing System
- Generate Invoices
- Auto Price Calculation
- Inventory Connected Billing
- Stock Validation
- Invoice Preview
- Print Invoice
- Automatic Stock Reduction

## 👤 Customer Management
- Auto Add Customers During Billing
- Customer Search
- Customer Database

## 📜 Purchase History
- View All Sales Records
- Invoice Tracking
- Billing Date & Time
- Print Reports

## 📊 Dashboard
- Modern Admin Dashboard
- Total Sales Statistics
- Low Stock Monitoring
- Recent Sales Tracking
- Responsive Design

---

# 🛠 Technologies Used

| Technology | Usage |
|---|---|
| PHP | Backend |
| MySQL | Database |
| HTML/CSS | Frontend |
| JavaScript | Dynamic Features |
| XAMPP | Local Server |

---

# 📂 Project Structure

```plaintext
pharmacy-management-system/
│
├── css/
│   └── style.css
│
├── js/
│   └── app.js
│
├── php/
│   ├── db.php
│   ├── login.php
│   ├── save_bill.php
│   ├── add_inventory.php
│   ├── update_stock.php
│   └── delete_product.php
│
├── dashboard.php
├── inventory.php
├── billing.php
├── customers.php
├── history.php
├── logout.php
├── index.php
│
└── database/
    └── pharmacy.sql
⚙ Installation Guide
1️⃣ Install XAMPP

Download and install XAMPP:

https://www.apachefriends.org/

2️⃣ Move Project Folder

Move the project folder into:

htdocs/

Example:

C:/xampp/htdocs/pharmacy-management-system
3️⃣ Start Apache & MySQL

Open XAMPP Control Panel and start:

Apache
MySQL
4️⃣ Create Database

Open:

http://localhost/phpmyadmin

Create a database named:

pharmacy
5️⃣ Import Database

Import:

database/pharmacy.sql
6️⃣ Configure Database Connection

Open:

php/db.php

Update credentials if needed:

<?php

$conn = mysqli_connect(
    "localhost",
    "root",
    "",
    "pharmacy"
);

?>
▶ Run The Project

Open browser:

http://localhost/pharmacy-management-system
🔑 Default Admin Login
Username: admin
Password: admin123
📸 Screenshots
Login Interface

Modern glassmorphism login UI.

Dashboard

Professional pharmacy admin dashboard.

Inventory System

Modern medicine stock management interface.

Billing System

Live invoice generation system with stock sync.

🌟 Future Improvements
Barcode Scanner Integration
Email Invoice System
Supplier Management
Multi-Admin System
Sales Analytics Charts
Dark Mode
Medicine Image Upload
Expiry Notifications
👨‍💻 Author

FAIYAZ

📜 License

This project is for educational purposes.

⭐ Support

If you like this project:

Star the repository
Fork the project
Share with others

💊 Happy Coding!
