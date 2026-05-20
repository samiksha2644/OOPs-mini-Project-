# 🛒 Smart Billing System

A simple yet structured **console-based Supermart Billing System** built using **Java** to demonstrate core **Object-Oriented Programming (OOP)** concepts in a practical way.

This project focuses on:

* clean OOP architecture
* inventory management
* invoice generation
* role-based access
* billing calculations

The system intentionally avoids advanced frameworks and databases to strengthen understanding of **core Java fundamentals**.

---

## ✨ Features

### 👨‍💼 Admin Panel

* Secure admin login
* Add new products
* Add taxable products
* View available stock
* Manage inventory

---

### 🧾 Cashier Panel

* Secure cashier login
* Generate customer invoices
* Add products to cart
* Automatic subtotal & tax calculation
* Display formatted final bill

---

## 🧠 OOP Concepts Demonstrated

This project was specifically designed to implement the **4 pillars of Object-Oriented Programming**.

---

### 🔒 Encapsulation

Class data is protected using `private` and `protected` access modifiers.

Example:

* Product price cannot be directly modified
* Data is accessed safely using getters/setters

---

### 🧬 Inheritance

Classes reuse existing functionality through inheritance.

Examples:

* `Admin` and `Cashier` inherit from the `User` class
* `TaxableProduct` inherits from `Product`

This avoids code duplication and improves maintainability.

---

### 🎭 Polymorphism

Different behaviors are achieved using method overriding and dynamic object references.

Examples:

* `getFinalPrice()` is overridden in `TaxableProduct`
* `User currentUser` can reference both `Admin` and `Cashier`

---

### 🏗️ Abstraction

Complex implementation details are hidden from the user.

Examples:

* `User` is an abstract class
* Main execution logic is encapsulated inside `BillingSystem`

---

# 📂 Project Structure

```bash
Smart-Billing-System/
│
├── BillingSystem.java
└── README.md
```

---

# ⚙️ Technologies Used

* ☕ Java
* OOP Principles
* Arrays & Loops
* Console-based UI

---

# 🚀 How to Run

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/Smart-Billing-System.git
```

---

## 2️⃣ Navigate to the Project Folder

```bash
cd Smart-Billing-System
```

---

## 3️⃣ Compile the Program

```bash
javac BillingSystem.java
```

---

## 4️⃣ Run the Program

```bash
java BillingSystem
```

---

# 🔑 Default Login Credentials

## 👨‍💼 Admin Access

| Username | Password |
| -------- | -------- |
| admin    | admin123 |

---

## 🧾 Cashier Access

| Username | Password   |
| -------- | ---------- |
| cashier  | cashier123 |

---

# 📸 Functionalities Included

✅ Inventory Management
✅ Product Addition
✅ Taxable Product Handling
✅ Invoice Generation
✅ Billing Calculations
✅ Role-Based Login
✅ Console Menu Navigation

---

# 🎯 Learning Outcomes

Through this project, you can understand:

* Java class design
* OOP architecture
* Method overriding
* Abstract classes
* Inventory management logic
* Console application flow

---

# 🔮 Possible Future Improvements

* Database integration (MySQL)
* GUI using Java Swing/JavaFX
* File handling for data persistence
* PDF invoice generation
* Search & filter products
* GST reporting system

---

# 👩‍💻 Author

Made with Java for learning and practicing Object-Oriented Programming concepts.
