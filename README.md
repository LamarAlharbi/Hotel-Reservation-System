# 🏨 Hotel Reservation System (CS313 Project)

An end-to-end desktop software solution built in **Java** and **MySQL**, designed to streamline hotel operations including room management, guest bookings, billing, and system administration.

---

## 📌 Features

### 👤 Customer Features
* **Account Management:** User registration, profile updates, and login/logout functions.
* **Room Search & Filter:** Search available rooms by date, room type, and capacity.
* **Reservation System:** Book rooms, view booking history, update reservation dates, and process cancellations.
* **Billing & Payments:** Generate detailed invoices with itemized charges and process payments via mock Credit Card or Cash integration.

### 🛡️ Admin Features
* **User & Staff Management:** View, add, update, and remove user and staff accounts.
* **Room Management:** Dynamic CRUD operations for room inventory, including adjusting prices and maintaining maintenance/occupancy statuses.
* **System Analytics & Reports:** View occupancy rate statistics, total revenue summaries, and popular room types.

---

## 🛠️ Tech Stack & Architecture

* **Programming Language:** Java (JDK 17+)
* **GUI Framework:** Java Swing / JavaFX
* **Database:** MySQL
* **Database Driver:** JDBC (Java Database Connectivity)
* **Architecture Pattern:** Model-View-Controller (MVC) Design Pattern

---

## ⚙️ Database Design (ERD Key Entities)

* **User / Customer:** Stores personal information, login credentials, and contact details.
* **Room:** Maintains room number, type, price per night, and availability status.
* **Reservation:** Links customers and rooms with check-in/check-out dates and booking status.
* **Payment / Invoice:** Tracks transaction IDs, total cost, payment dates, and payment methods.

---

## 🚀 Getting Started

### Prerequisites
1. **Java Development Kit (JDK 17 or higher)** installed.
2. **MySQL Server** and **MySQL Workbench** (or XAMPP) running.
3. An IDE like **IntelliJ IDEA**, **Eclipse**, or **NetBeans**.
