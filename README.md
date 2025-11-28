A complete SQL-based database design project for modeling the workflow of a logistics company.
It covers schema creation, data preprocessing, validation, SSOT development, and business analytics — presented in a clean and professional format ideal for recruiters.

## 🚀 Project Summary

This project builds a fully relational logistics database using MySQL, covering employees, customers, shipments, memberships, payments, and delivery statuses.
It also includes data cleaning, date validation, error detection, and SQL-based EDA, demonstrating practical backend and analytical skills.

## ⭐ Highlights

✨ Designed a normalized relational schema with 7 interconnected tables
✨ Cleaned inconsistent and invalid date formats
✨ Detected erroneous values like invalid months & February 30/31
✨ Built a Single Source of Truth using multiple joins
✨ Created SQL views & calculated new fields (e.g., Total Payable Charges)
✨ Performed advanced analytics to derive operational insights
✨ Updated branch information and applied discount logic
✨ Delivered insights like highest revenue content, customer types, membership duration & more

## 🛠️ Tech Stack & Tools
Tool	Purpose
MySQL Workbench	Database creation, data loading & query execution
SQL	Joins, Constraints, Views, Aggregations, EDA
ER Modeling	Designing relationships
Data Cleaning	Date conversions, validations, preprocessing
🧱 Database Features
🗂️ 1. Relational Schema Design

## Created these core tables:

👨‍💼 Employee_Details

🧾 Membership

🧍‍♂️ Customer

📦 Shipment_Details

💳 Payment_Details

🚚 Status

🔗 Employee_Manages_Shipment

Includes primary keys, foreign keys, composite keys, constraints & datatypes.

🧹 2. Data Preprocessing

✔ Fixed date format inconsistencies
✔ Converted text dates → SQL DATE
✔ Identified invalid dates using substring + CAST
✔ Validated February constraints & month logic

🧩 3. SSOT (Single Source of Truth)

Created a unified table logistics_Emp using multi-table INNER JOINs combining:

Employees

Membership

Shipment

Customer

Payment

Delivery Status

Employee–Shipment relationships

This central dataset powers all analysis.

## 📊 Key Insights & Business Analytics

🔍 1. Employee & Customer Name Overlap

Identified common names across employees and customers.

💰 2. Payment Mode Distribution

Calculated % frequency of each payment mode (COD, Card, etc.).

📦 3. Shipment Cost Metrics

Added Total_Payable_Charges and computed the max payable amount.

🎖️ 4. Membership Duration

Extracted customers with membership > 10 years.

🚀 5. Fast Deliveries

Found shipments delivered next day using DATEDIFF.

🛒 6. Top Revenue Content

Ranked shipment contents by total amount (Top 5).

📊 7. Most Frequently Shipped Categories

Counted highest occurring shipment types.

🛠️ 8. Branch-Level Insights

Texas → 5% discount applied

New York employees → moved to New Jersey (branch shutdown)

## 🏁 Conclusion

This SQL project demonstrates strong data engineering & analysis capabilities:
✔ Database design
✔ Data cleaning
✔ Relationship modeling
✔ Analytical SQL

It mirrors real-world logistics operations and showcases end-to-end mastery of SQL for backend and analytics roles.

## Author 
Bansi Shah
