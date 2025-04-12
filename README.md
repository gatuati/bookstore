
# BookStore Database Design & Programming with MySQL

## Overview

This project simulates the role of a Database Administrator tasked with designing and implementing a MySQL relational database system for managing operations of a bookstore. The system includes tables for books, authors, customers, orders, shipping, and more.

By completing this project, you'll gain practical experience with database design, SQL programming, and user management in MySQL.

---

##  Tools and Technologies

- **MySQL** – for building and managing the database.
- **VS Code** – as the development environment.
- **Draw.io** – for visualizing the ER diagram (optional).
- **SQLTools / MySQL Extension** – for connecting to MySQL from VS Code.

---

## Project Objectives

- Design and implement a normalized relational database.
- Create MySQL tables using appropriate data types and relationships.
- Enforce data integrity through primary and foreign keys.
- Manage user access with MySQL roles and privileges.
- Execute queries to retrieve and analyze bookstore data.

---

## 📋 Tables in the Database

| Table Name         | Description |
|--------------------|-------------|
| `book`             | List of all books in the store. |
| `author`           | List of all authors. |
| `book_author`      | Handles many-to-many relationship between books and authors. |
| `book_language`    | Languages in which books are available. |
| `publisher`        | Publishers of the books. |
| `customer`         | List of bookstore customers. |
| `customer_address` | Multiple addresses for each customer. |
| `address`          | All address records. |
| `address_status`   | Status of each address (e.g., current, old). |
| `country`          | Countries where customers live. |
| `cust_order`       | Orders placed by customers. |
| `order_line`       | Books included in each order. |
| `shipping_method`  | Different ways to ship orders. |
| `order_status`     | Possible statuses of orders. |
| `order_history`    | Status history of each order. |

---

## How to Run

### 1. Using phpMyAdmin (with XAMPP/WAMP)
- Open `http://localhost/phpmyadmin`
- Click **Import**
- Choose `bookstore_schema.sql`
- Click **Go**

### 2. Using VS Code
- Install **MySQL by Weijan Chen** or **SQLTools**
- Set up a new connection to MySQL (localhost:3306)
- Open `bookstore_schema.sql`
- Right-click → **Run Query**

---

##  Expected Outcomes

- A fully structured and normalized BookStore MySQL database.
- Logical table relationships and foreign key constraints.
- Ability to query the database efficiently for real-world scenarios.
- Secured access via MySQL roles and users.

---



