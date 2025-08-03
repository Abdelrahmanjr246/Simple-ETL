# 🔄 Simple ETL Project

This project demonstrates a basic ETL (Extract, Transform, Load) pipeline using **Microsoft SQL Server** and **SSIS (SQL Server Integration Services)**. It is designed for learning purposes and showcases how raw data from multiple resources (Flat file(CSV), Excel Sheet) can be cleaned, transformed, and loaded into a structured SQL Server database.

---

## 🧰 Tools & Technologies

- **SQL Server**
- **SSIS (SQL Server Integration Services)**
- **Visual Studio Data Tools**
- **Flat Files (.csv)**
- **Excel**
---

## 📁 ETL Process Overview

### 1. Extract
- Source: Flat file, Excel Sheets containing raw data (e.g., sales, products, dates)
- Data is imported using SSIS Data Flow Tasks

### 2. Transform
- Applied transformations include:
  - Derived Columns
  - String manipulation (e.g., formatting date fields)
  - Data type conversion
  - Handling nulls and cleaning data

### 3. Load
- Transformed data is loaded into SQL Server tables
- Tables are structured for easier querying and reporting

---

## 🧪 Sample Use Case

Imagine an e-commerce business receiving daily sales data. This ETL project reads the files, formats dates and numeric values, and loads them into a SQL Server database for reporting.

---



---

## 🚀 How to Run

1. Open the solution in **Visual Studio with SSIS tools installed**
2. Update file paths in **Flat File Source** components to match your local environment
3. Create database and tables using `create_tables.sql`
4. Execute the package

---

## 📌 Project Purpose

This mini-project was developed to:
- Understand ETL fundamentals
- Gain practical experience with SSIS
- Integrate basic BI concepts into a database project

---

## 🧑‍💻 Author

**Abdelrahman Mostafa Saad**  
Information Systems Graduate | Front-End Developer | Aspiring Data Engineer

---

## 📜 License

This project is for educational purposes. No license is applied.
```
