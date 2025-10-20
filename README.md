# OOPs-mini-Project-

Supermart Billing System (Java)
This is a simple, console-based Supermart Billing System written in Java. It was developed as a mini-project to apply and demonstrate fundamental Object-Oriented Programming (OOP) concepts.

The system uses basic arrays and loops and avoids complex libraries to focus on core Java skills.

Features
Two User Roles: The system supports both an Admin and a Cashier.

Admin:

Log in to manage the store's inventory.

Add new products (both regular and taxable items).

View the current stock levels.

Cashier:

Log in to the billing counter.

Create a new invoice for a customer.

Add items from the stock to the invoice.

Automatically calculate subtotal, taxes, and the grand total.

Print a simple, formatted bill to the console.

Object-Oriented Programming Concepts
This project is designed to demonstrate the four main pillars of OOP:

Encapsulation: All class variables (like price in Product) are protected or private. Data is safely hidden and can only be accessed through public methods (getters).

Inheritance:

The Admin and Cashier classes inherit common properties (like username and password) from the parent User class.

The TaxableProduct class inherits from the Product class, reusing its code and adding new functionality (tax calculation).

Polymorphism:

Method Overriding: The getFinalPrice() method is defined in Product and overridden in TaxableProduct. The correct version is called automatically when calculating the bill.

The User currentUser object can hold either an Admin or a Cashier object, and the correct showMenu() is executed.

Abstraction:

The User class is abstract, providing a template for what a user should be without being instantiable itself.

The main BillingSystem class hides all the complex logic. The main method is very simple and just creates and runs the system.

How to Compile and Run
Save the code as BillingSystem.java.

Open your terminal or command prompt.

Navigate to the directory where you saved the file.

Compile the code:

Bash

javac BillingSystem.java
Run the program:

Bash

java BillingSystem
Default Logins
The program starts with two pre-loaded user accounts:

Admin:

Username: admin

Password: admin123

Cashier:

Username: cashier

Password: cashier123
