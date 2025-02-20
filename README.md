# Stock Management System

## About the Project

The Stock Management System is a web-based application developed using the following technologies:

- **XAMPP v3.3.0** as the local webserver, running **PHP**
- **PHP** Language
- **MySQL** Database
- **HTML**, **CSS**, **JavaScript**, **jQuery**, **Ajax**
- **Bootstrap**, **AdminLTE**
- Additional plugins and libraries

### User Access
The system supports two types of users:
- **System Admins**: Can access and manage all the pages, forms, and features.
- **Staff Users**: Have limited access, restricted to certain pages and functionalities.

### Features
- **Secure Login and Logout**
- **Manage Supplier List** (CRUD operations)
- **Manage Item List** (CRUD operations)
- **Manage Purchase Order Records**:
  - Create New
  - Edit Record
  - View Record
  - Print Record
  - Delete Records
- **Manage Receiving Records**:
  - Receive Items from Purchase Orders
  - Automatically Create New Back Order for Unavailable Items
  - Edit Record
  - Print Record
  - Update Item Stock Availability
  - Delete Record
- **Manage Back Order Records**:
  - View Record
  - Receive Back Orders
  - Print Record
- **Manage Return Records**:
  - Create New Records
  - Edit Record
  - View Record
  - Print Record
  - Automatically Update Stock Availability Upon Saving
  - Delete Record
- **Manage Sales Records**:
  - Create New Records
  - View Record
  - Edit Record
  - Print Record
  - Automatically Update Stock Availability Upon Saving
  - Delete Record
- **Manage Users List** (CRUD operations)
- **Manage Account Details/Credentials**
- **Manage System Information**

## How to Run the Project

### Requirements
- Download and install a local web server like **XAMPP** or **WAMP**.
- Download the provided source code zip file (link provided below).

### Installation/Setup
1. Open your **XAMPP/WAMP Control Panel** and start **Apache** and **MySQL**.
2. Extract the downloaded source code zip file.
3. If using **XAMPP**, copy the extracted folder to the `htdocs` directory.
   If using **WAMP**, copy it to the `www` directory.
4. Open **PHPMyAdmin** in a browser (e.g., `http://localhost/phpmyadmin`).
5. Create a new database named `sms_db`.
6. Import the provided SQL file: `sms_db.sql`, located in the `database` folder.
7. Browse to the Stock Management System in a browser (e.g., `http://localhost/sms/`).

### Default Admin Access Information
- **Username**: admin
- **Password**: admin123

## Contributing
Feel free to fork the repository and contribute to improvements or fixes.

---

If you encounter any issues, please feel free to open an issue, and I will respond as soon as possible.



