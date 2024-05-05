# Bank Management System

This project aims to design a database and develop an application to manage the administration of a bank. The system is built using Java programming language and MySQL database.

## Database Design

The database design began with an Entity-Relationship (E-R) diagram to understand the requirements. The E-R diagram visually represents entities and their relationships within the system. The tables in the database are designed following normalization rules and are in the Third Normal Form (3NF).

## Features

This project includes three roles within the bank system: customer, representative, and manager, each with their own interfaces and responsibilities.

### Customers
- Customers can withdraw and deposit money from their accounts.
- They can open new accounts or close existing ones.
- Customers can transfer money between accounts.
- They have the ability to update their information.
- Customers can request and manage transfers and credit.

### Representatives
- Each customer is assigned a representative.
- Representatives can add, delete, or edit customer information.
- They manage account opening, closing, and credit requests from customers.
- Representatives can view and approve account-related requests from customers.
- They can oversee transactions of their assigned customers.

### Managers
- Managers have access to the overall financial state of the bank (income, expenses, profits, and total balance).
- They can add new currencies (Dollar, Euro, Sterling, etc.) and update exchange rates.
- Managers can set employee salaries, credit, and interest rates.
- They have the ability to add new customers to the system.

This project provides a comprehensive system for managing a bank's operations efficiently through a well-structured database and an intuitive Java application.

## Technologies Used
- Java
- MySQL

For detailed information on the database schema, E-R diagram, and application functionalities, please refer to the project documentation and source code.

---

Feel free to customize this template with installation instructions, usage guidelines, and other relevant details based on your project's specific requirements.
