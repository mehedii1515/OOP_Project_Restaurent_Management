"""
# 🍽️ Mamar Restaurement – Terminal-Based OOP Restaurant Management System

**Mamar Restaurement** is a Python-based restaurant management system developed using Object-Oriented Programming (OOP) concepts. It simulates a small restaurant where Admins can manage menus and employees, while Customers can place and pay for orders—all via a command-line interface.

---

## 🚀 Features

### 👥 Role-Based Access
#### 👨‍🍳 Admin:
- Add/remove food items from the menu
- Add/view employees
- View current menu

#### 👤 Customer:
- View menu
- Add items to cart
- View cart
- Pay bill

### 🧠 OOP Concepts Applied
- Inheritance
- Encapsulation
- Polymorphism (via Abstract Base Class `User`)
- Composition (e.g., restaurant contains employees and menu)

---

## 🧾 Project Structure

📁 MamarRestaurement/
├── main.py               # Entry point: handles role-based menus and operations  
├── food_item.py          # FoodItem class: represents menu items  
├── menu.py               # Menu class: adds, removes, and shows menu items  
├── orders.py             # Order class: manages cart and billing  
├── restaurent.py         # Restaurent class: central manager for menu and employees  
└── users.py              # User classes: Admin, Customer, Employee (inherits from abstract User)  

---

## ▶️ How to Run

### Prerequisites
- Python 3.6 or higher

### Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/mamar-restaurent.git
   cd mamar-restaurent
"""
2. Run the program:
   ```bash
   python main.py
   ```
"""
3. Follow the on-screen options to operate as an Admin or Customer.

---

## 📦 Sample Flow

### 👤 Customer Flow:
1. Enter personal information (Name, Email, Phone, Address)
2. View the available food menu
3. Add items to your cart
4. View your cart and total price
5. Pay the bill and clear the cart

### 🛠️ Admin Flow:
1. Enter admin credentials (Name, Email, Phone, Address)
2. Add new food items to the restaurant menu
3. Add new employees with their details
4. View all employees
5. View all menu items
6. Delete items from the menu

---

## 💡 Technologies Used

- Python 3
- Object-Oriented Programming (OOP)
- Terminal-based interface

---

## 📚 Learning Outcomes

Through this project, students will learn:
- Class inheritance and abstraction in Python
- How to structure a Python project using modules
- Real-world simulation using class-based design
- Practical use of encapsulation and data management

---

## 👨‍💻 Author

Developed by **Md. Mehedi Hasan**  
As part of an Object-Oriented Programming (OOP) course project.

---


