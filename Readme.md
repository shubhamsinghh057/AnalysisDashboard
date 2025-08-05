# 📊 MySQL Sample Sales Database Project

This repository contains a sample MySQL relational database schema along with example data, resources, and dashboards for exploring relational data modeling and business intelligence reporting.

## 📂 Folder Structure

.
├── Data/ — Raw data files (CSV or other formats)
│ └── *.csv — Individual table data files
├── icons/ — Icons and resource images
├── Schema/ — Database schema and import files
│ ├── Data.rar — Compressed archive of all data files
│ ├── Schema.png — ER diagram of the database
│ └── mysqlsampledatabase.sql — SQL script to create/populate the DB
├── dashboard.pbix — Power BI dashboard
├── dashboard.twd — Tableau workbook



## 🗂️ Database Schema Overview

The database schema models a classic sales and order management system, with tables for products, orders, customers, employees, offices, and payments.

The database models a classic order management system with the following tables:

| Table          | Description                            |
|----------------|----------------------------------------|
| `productlines` | Categories of products                 |
| `products`     | Product details                        |
| `orders`       | Customer orders                        |
| `orderdetails` | Line items for each order              |
| `customers`    | Customer info                          |
| `payments`     | Customer payments                      |
| `employees`    | Employee directory                     |
| `offices`      | Office locations                       |

![Database Schema](Schema/Schema.png)



---

### 📈 4. **Dashboard Previews**

a small preview of the dashboards 

![Power BI Dashboard](dashboard.pbix)
![Tableau Dashboard](dashboard.twd)

---


```markdown
![MySQL](https://img.shields.io/badge/Database-MySQL-blue)
![Power BI](https://img.shields.io/badge/BI-Power%20BI-yellow)
![Tableau](https://img.shields.io/badge/BI-Tableau-blueviolet)
![License: MIT](https://img.shields.io/badge/License-MIT-green)




## 🚀 Getting Started

### 1️⃣ Create the Database

Use the provided SQL script to create and populate the database:

```bash
mysql -u your_username -p your_database < Schema/mysqlsampledatabase.sql
```

### 2️⃣ Load the Data

If you prefer to use the compressed data archive (`Data.rar`), extract it and import the tables manually or via your preferred ETL tool.

### 3️⃣ Explore the Dashboards
Open the following files to explore sample visualizations:

- `dashboard.pbix`: Power BI dashboard file.
- `dashboard.twd`: Tableau workbook file.

### 💡 Use Cases
This project is useful for:

- Practicing SQL queries on realistic business data.
- Learning database design and relationships.
- Building reports and dashboards in BI tools.
- Demonstrating data pipelines and ETL workflows.

## 🛠️ Requirements

- MySQL Server
- Power BI Desktop (for `.pbix`)
- Tableau Desktop (for `.twd`)
- Any SQL client (MySQL Workbench, DBeaver, etc.)

## 📄 License
This project is provided for educational and demonstration purposes. You may modify and use it freely.

## 🙌 Acknowledgments
This sample schema is inspired by common e-commerce sales databases. Feel free to contribute improvements or additional datasets.
