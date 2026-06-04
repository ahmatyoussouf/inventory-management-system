# 📦 Inventory Management System

A console-based Inventory Management System built in Java as part of the **ITGN230** course project.

## 👥 Team Members
- Baabde
- Defallah
- Youssouf
- Amini

## 📋 Description

This program simulates a basic inventory system for a store. It allows users to manage products through a simple text-based menu interface, including adding products, updating stock quantities, applying discounts, and receiving automated low-stock alerts.

## ✨ Features

- **Add Products** — Register new products with name, price, and initial quantity
- **Update Quantity** — Increase or decrease stock (with validation to prevent negative stock)
- **Display Inventory** — View all products with automated stock alerts:
  - 🔴 `OUT OF STOCK` alert when quantity reaches 0
  - 🟡 `LOW STOCK` warning when quantity drops below 5
- **Apply Discounts** — Apply a percentage discount to products above a quantity threshold
- **Exit** — Gracefully close the application

## 🛠️ Technologies Used

- Java
- `java.util.Scanner` for user input
- Arrays for data storage

## 🚀 How to Run

1. Make sure you have [Java JDK](https://www.oracle.com/java/technologies/downloads/) installed
2. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/inventory-management-system.git
   cd inventory-management-system
   ```
3. Compile the Java file:
   ```bash
   javac InventorySystem.java
   ```
4. Run the program:
   ```bash
   java InventorySystem
   ```

## 📸 Sample Output

```
--- INVENTORY MANAGEMENT SYSTEM ---
1. Add a New Product
2. Update Product Quantity
3. Display Inventory & Stock Alerts
4. Apply Discount
5. Exit
Please choose an option (1-5):
```

## 📚 Course Info

- **Course:** ITGN230
- **Institution:** CEIT Department
- **Academic Year:** 2025–2026
