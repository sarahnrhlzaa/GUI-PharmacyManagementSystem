## 🧪 Pharmacy Management System — Java Desktop Application

A desktop-based pharmacy management system developed using **Java Swing** and **MySQL** to support essential pharmacy operations. We designed this application to manage medicine inventory, handle sales transactions, and organise supplier data through a structured and interactive graphical interface.

This project was developed collaboratively as an academic implementation of **Object-Oriented Programming (OOP)** concepts, focusing on system logic, data consistency, and user interaction.

---

## 🔎 Core Functionalities

### 🔐 User Access Control

* Login system to ensure secure and authorised access to the application.

### 💊 Medicine Inventory Module

* Register medicines with complete details such as name, price, stock, expiration date, and manufacturer.
* View and manage medicine data, including removing expired or unavailable items.

### 🧾 Sales Transaction System

* Process medicine sales with automatic total price calculation.
* Update stock quantities in real time after each transaction.
* Generate transaction IDs automatically for tracking purposes.

### 🏢 Supplier Management

* Store and manage supplier or pharmaceutical company information.

### 📈 Application Dashboard

* Centralised dashboard to navigate between modules efficiently.

---

## ⚙️ Tech Stack

* **Language:** Java
* **GUI:** Java Swing (JFrame)
* **IDE:** NetBeans IDE
* **Database:** MySQL
* **Libraries:**

  * JDBC (MySQL Connector)
  * AbsoluteLayout
  * iText (PDF generation)

---

## 🛠️ System Requirements

* Java Development Kit (JDK 8 or higher)
* NetBeans IDE
* MySQL Server (XAMPP or equivalent)

---

## ▶️ Application Setup & Execution

### Database Preparation

 Start Apache and MySQL services.
* Create a database named `db_pharmacy` via phpMyAdmin.
* Import the provided SQL schema or create tables according to the application design.

### Project Configuration

* Open the project folder in NetBeans.
* Configure required external libraries if not automatically detected.

### Running the Program

* Execute `Login.java` as the main entry point.
* Sign in to access the full system functionality.

---

## 📁 Source Structure

```
src/
├── dao/
│   └── ConnectionProvider.java
├── image/
├── AddCompany.java
├── AddMedicine.java
├── Login.java
├── PharmacistDashboard.java
├── SellMedicine.java
├── Session.java
├── ViewMedicine.java
└── PharmacyManagementSystem.java
```

---

## 👩🏻‍💻 Team Members

* **Sarah Nurhaliza**, *Developer*
* **Neyza Maylanie Santosa**, *Developer*
* **Naufalnadi**, *Developer*

This project was created as part of the **Object-Oriented Programming** course at **CEP CCIT FTUI 2025**, representing our implementation of structured programming and desktop application development.

