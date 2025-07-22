# 🛍️ Retail Sales Analysis Using PySpark in Databricks

This project demonstrates the end-to-end data processing and analysis of retail sales data using **PySpark** in a **Databricks** environment. It simulates a real-world use case where sales and product metadata are ingested from two separate files, cleaned, transformed, and analyzed to derive actionable business insights.

---

## 📁 Files Used

- `menu.txt`: Contains metadata about products — item names, categories, and prices.  
- `sales.txt`: Contains transaction data — items sold, quantity, and timestamps.

---

## 🎯 Objective

- Merge and analyze product and sales data  
- Clean and transform raw data using PySpark DataFrames  
- Generate key performance metrics (e.g., total sales, most popular items)  
- Export final data for visualization or reporting

---

## 🛠️ Tools & Technologies

- PySpark (Spark DataFrame API)  
- Databricks (Cloud-based collaborative platform)  
- CSV/Text Files  
- Python

---

## 🔄 Steps Performed

1. **Data Ingestion**
   - Loaded `menu.txt` and `sales.txt` into Spark DataFrames

2. **Data Cleaning**
   - Handled missing values, trimmed whitespaces, and corrected inconsistent formats

3. **Data Transformation**
   - Mapped item names to prices and categories from `menu.txt`
   - Joined sales data with menu data to compute total sales per item

4. **Aggregation & Analysis**
   - Calculated:
     - Total quantity sold per item
     - Revenue generated per product
     - Most and least popular products

5. **Output**
   - Final clean DataFrame exported to CSV (for further BI use)
   - Optional: Load into Power BI for dashboarding

---

## 📊 Sample KPIs (Calculated)

- 🏆 **Top-Selling Products**  
- 💰 **Total Revenue by Item/Category**  
- 🕒 **Sales Trends Over Time**  
- 🔍 **Popular vs. Low-Demand Items**

---

## 💡 Key Learnings

- Practical experience in using PySpark for real-time data cleaning and transformation  
- Applied join operations, filtering, aggregation functions on large-scale data  
- Simulated enterprise-grade workflows in Databricks  
- Built a reusable and scalable ETL pipeline

---

## 📎 Project Structure

