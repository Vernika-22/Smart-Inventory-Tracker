# Smart-Inventory-Tracker
Smart Inventory Tracker is a Java-based console app to manage products and monitor stock levels. It supports adding, updating, searching, and deleting items. It features low stock alerts, smart reorder suggestions, and uses file handling for data storage, demonstrating OOP and inventory management concepts.
# 📦 Smart Inventory Tracker

A Java-based console application designed to manage and monitor product inventory efficiently. This project helps users track stock levels, receive low stock alerts, and get smart reorder suggestions.

---

## 🚀 Features

- ➕ Add new products
- 📋 View all products
- ✏️ Update product stock
- 🔍 Search products by name
- 🗑️ Delete products
- ⚠️ Low stock alerts
- 📦 Smart reorder suggestions
- 💾 Data persistence using file handling

---

## 🛠️ Tech Stack

- Java (Core Java)
- Object-Oriented Programming (OOP)
- File Handling

---

## 🧠 How It Works

- Each product has an ID, name, quantity, and threshold.
- When stock goes below the threshold, the system shows a **low stock alert**.
- The system also suggests a **reorder quantity** automatically.
- All data is saved in a file and loaded when the program starts.

---

## ▶️ How to Run

1. Copy the code into `Main.java`
2. Compile the program:
   ```bash
   javac Main.java
