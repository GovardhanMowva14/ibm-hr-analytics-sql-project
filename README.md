# ibm-hr-analytics-sql-project

# IBM HR Analytics: SQL & MongoDB Project

This project explores employee attrition and performance patterns using IBM’s HR Analytics dataset. It was completed as part of the **BUAN 6320 (Database Foundations for Business Analytics)** course at The University of Texas at Dallas.

The goal of this project is to perform deep analysis on HR data using both **relational (MySQL)** and **NoSQL (MongoDB)** technologies, answering real-world business questions through SQL queries, data modeling, and visual insights.

---

## 📌 Objectives

- Model a relational database from raw Excel data following 3NF standards.
- Populate and query the database using advanced SQL (joins, ranking, window functions).
- Answer practical HR/business questions like attrition causes, performance trends, pay disparities, and employee satisfaction.
- Translate selected SQL insights into **MongoDB aggregate queries** to compare relational and NoSQL paradigms.

---

## 🧠 Business Questions Answered (SQL)

✔ Which department has the **shortest commute** on average?

✔ Can **female employees from medical backgrounds** succeed in the Sales department?

✔ Which department truly has **the highest job satisfaction or environment satisfaction**?

✔ Are **women paid less than men** across all departments?

✔ Is it true that **married men perform better** than single or divorced men?

Each of these questions was answered through optimized SQL queries, grouped and ranked results, and interpretation of HR performance and feedback data.

---

## 🧾 Dataset Description

The dataset includes detailed attributes of 1,470 employees across categories like:

- Personal information (age, gender, marital status)
- Job roles and departments
- Educational background and work experience
- Salary and compensation structure
- Attrition status and performance feedback

---

## 🛠️ Technologies Used

- **MySQL Workbench** (ER modeling and query execution)
- **MongoDB** (NoSQL conversion and aggregation pipelines)
- **Microsoft Excel** (data preprocessing and raw data management)
- **.mwb** and `.sql` files for schema and query logic

---

## 📁 Repository Structure

ibm-hr-analytics-sql-project/
├── README.md # Project overview and documentation
├── SQL/
│ └── Phase 2.sql # All SQL queries solving real-world HR problems
├── Data Models/
│ └── Project Phase 1 ER Model.mwb # MySQL ER diagram and schema
├── Excel/
│ ├── WIP.xlsx # Transformed Excel data
│ └── Master(Original).xlsx # Original raw dataset
├── Report/
│ └── Hr Analytics.docx # Full report with ER model, SQL output, and analysis


---

## 📊 MongoDB Perspective

MongoDB was used to replicate a denormalized, document-based version of the HR dataset. We then answered similar questions using **aggregation pipelines** to compare performance and ease of use versus traditional SQL joins.

---

## 📌 Key Skills Demonstrated

- Data modeling in 3NF
- Complex SQL: joins, subqueries, window functions
- Translating SQL logic to NoSQL (MongoDB)
- HR analytics interpretation: compensation fairness, performance, attrition
- Report writing and data storytelling
