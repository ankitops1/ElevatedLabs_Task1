# 🛒 E-commerce Database Schema Design

## 📌 Objective
This task focuses on setting up a relational database schema for an e-commerce platform. It demonstrates how to:
- Create a new SQL database
- Define tables with appropriate fields and constraints
- Establish relationships between tables using foreign keys

---

## 🧱 Database Structure

The project includes the following tables:

1. *Customers*
   - Stores customer details like name, email, phone, and address.

2. *Products*
   - Contains information about the products such as name, description, price, and stock.

3. *Orders*
   - Represents a customer's purchase; linked to Customers.

4. *Order_Items*
   - Maps individual products to specific orders with quantity and purchase price.

5. *Payments*
   - Captures payment details associated with an order.

---

## 🗃 SQL

### ✅ Features
- Auto-incrementing primary keys
- Foreign key relationships
- Data types suitable for e-commerce context
- Unique constraints on customer email
