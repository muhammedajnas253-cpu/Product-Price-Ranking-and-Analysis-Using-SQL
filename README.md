# Product-Price-Ranking-and-Analysis-Using-SQL
This MySQL project uses CTEs and the DENSE_RANK() window function to rank products by price within each category and identify the second-highest-priced product. It demonstrates database creation, table design, data insertion, and category-based SQL analysis.
# 🗄️ SQL Product Ranking Project

## 📌 Overview

This project demonstrates SQL database creation, table design, data insertion, Common Table Expressions (CTEs), and window functions using MySQL.

The project creates a product database containing products from different categories such as Food, Drinks, Shoes, Cars, and Watches. It then uses the `DENSE_RANK()` window function to rank products according to their price within each category.

The main objective is to identify the **second-highest-priced product in every category**.

---

## 🎯 Project Objective

The key objective of this project is to practice:

* Creating a MySQL database
* Creating relational tables
* Defining primary keys
* Using `AUTO_INCREMENT`
* Inserting product records
* Using Common Table Expressions (CTEs)
* Applying window functions
* Using `DENSE_RANK()`
* Ranking products within categories
* Finding the second-highest price in each category

---

## 🗃️ Database Structure

### Database

```sql
PP8
```

### Table

```text
PRODUCT3
```

### Columns

| Column   | Data Type     | Description                     |
| -------- | ------------- | ------------------------------- |
| P_ID     | INT           | Primary key with auto increment |
| P_NAME   | VARCHAR(100)  | Product name                    |
| CATEGORY | VARCHAR(100)  | Product category                |
| PRICE    | DECIMAL(10,2) | Product price                   |

The table structure and primary-
