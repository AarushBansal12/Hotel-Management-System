# Hotel Management System

A comprehensive Java-based Hotel Management System developed using Java Swing for the GUI and MySQL for the backend. This system helps automate core hotel operations such as customer check-in/check-out, room allocation, staff management, and billing.

## Features

- **User Authentication**  
  Secure login system for hotel staff and managers.

- **Customer Management**
  - Add new customers
  - Track customer details
  - View all registered guests

- **Room Management**
  - View all available/occupied rooms
  - Update room status and pricing

- **Employee Management**
  - Display all hotel staff
  - Filter by department and role

- **Search Functionality**
  - Find rooms by bed type or availability
  - Filter customers and employees

- **Billing & Checkout**
  - Calculate customer bills based on duration and room type
  - Easy checkout with receipt generation

- **Department Overview**
  - View and manage various departments in the hotel (e.g., Housekeeping, Kitchen)

## Tech Stack

- **Language:** Java  
- **GUI:** Java Swing  
- **Database:** MySQL  
- **IDE Used:** IntelliJ IDEA / Eclipse  
- **Build Tool:** Not required (pure Java project)

## Project Structure

Hotel-Management-System/
│
├── src/
│ ├── hotel/ # Main package
│ │ ├── AddCustomer.java
│ │ ├── Reception.java
│ │ ├── Dashboard.java
│ │ ├── AddRoom.java
│ │ ├── AddDriver.java
│ │ ├── AddEmployee.java
│ │ ├── Conn.java
│ │ ├── Checkout.java
│ │ ├── CustomerInfo.java
│ │ ├── Dashboard.java
│ │ ├── EmployeeInfo.java
│ │ ├── Login.java
│ │ ├── ManagerInfo.java
│ │ ├── Pickup.java
│ │ ├── Reception.java
│ │ ├── Rooms.java
│ │ ├── searchroom.java
│ │ ├── UpdateCheck.java
│ │ ├── UpdateRoom.java
│ 
├── assets/
│ └── icons/ # All icon and image assets
│
├── database/
│ └── hotel.sql # MySQL database schema
