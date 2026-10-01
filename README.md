# 🏨 Booking System

A desktop-based booking and reservation management application built using **Java Swing** and **Object-Oriented Programming (OOP)** principles. This system features role-based access control, secure multi-tier user dashboards, and custom form layouts.

## ✨ Features
* **Role-Based Authentication:** Secure login supporting multiple user tiers:
  * **Admin:** Full access to system management and administrative controls (`admin` / `111`).
  * **Regular Customer:** Standard booking interface (`customer` / `222`).
  * **VIP User:** Premium booking portal (`vip` / `333`).
* **Graphical User Interface (GUI):** Built using Java Swing (`JFrame`, `JPanel`, and custom event handling).
* **Standalone Execution:** Runs smoothly out-of-the-box locally without requiring external database servers (like XAMPP/MySQL).

## 🔑 Default Login Credentials
* **Admin:** `admin` / `111`
* **Customer:** `customer` / `222`
* **VIP:** `vip` / `333`

## 🚀 Getting Started & Running Locally

### Prerequisites
* Ensure you have **Java Development Kit (JDK 17 or higher)** installed on your machine.
* Recommended IDE: **Visual Studio Code** (with the *Extension Pack for Java* extension installed).

### Steps to Run:
1. Open the project folder in **Visual Studio Code** on your local computer.
2. Navigate to the main source file: 
   `com/mycompany/bookingsystem/Main.java`
3. Click the **Run** button above the `main` method or use your terminal to compile and run:
   ```bash
   javac com/mycompany/bookingsystem/Main.java
   java com.mycompany.bookingsystem.Main