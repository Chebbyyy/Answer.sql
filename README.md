📘 E-commerce Store Database

✨ 1. Overview

This project implements a Relational Database Management System (DBMS) for an E-commerce Store using MySQL.
The schema is designed to handle users, products, orders, payments, reviews, and other essential components of an online store.

The database ensures data integrity with proper constraints and supports common e-commerce operations such as browsing products, managing inventory, placing orders, and tracking deliveries.

⚙️ 2. Features of the Schema
🗂️ Well-structured tables

users, user_profiles, roles, orders, order_items, products, categories, suppliers, payments, reviews, wishlists, etc.

🔒 Constraints

PRIMARY KEY on all tables

FOREIGN KEY to maintain referential integrity

UNIQUE and NOT NULL on important fields (e.g., emails, product SKUs, category names)

🔗 Relationships

One-to-One → users ↔ user_profiles

One-to-Many → users → orders, products → reviews

Many-to-Many →

products ↔ categories

products ↔ suppliers

users ↔ wishlists

📑 3. Main Tables

users → stores customer login information

user_profiles → extended user details (1-to-1 with users)

roles / user_roles → user access control (admin, customer, support)

addresses → multiple addresses per user

categories → hierarchical product categories (self-referencing)

products → product catalog with SKU, price, details

product_categories / product_suppliers → many-to-many mapping tables

inventory → stock levels per product

orders / order_items → customer purchases with line items

payments → payment information per order

reviews → product reviews by customers

wishlists → products saved by users for later

🖥️ 4. Usage

Run the .sql file in MySQL (via phpMyAdmin, Workbench, or CLI).

The database ecommerce_store will be created.

Tables, constraints, and relationships will be set up automatically.

You can then insert sample data or run queries as needed.

✅ 5. Deliverables Checklist

✔ CREATE DATABASE statement

✔ CREATE TABLE statements

✔ PRIMARY KEY, FOREIGN KEY, NOT NULL, UNIQUE constraints

✔ Relationships (1-1, 1-M, M-M)

✍️ Author: DAISY JEBICHII CHEBURET
📅 Date: 21/09/2025
