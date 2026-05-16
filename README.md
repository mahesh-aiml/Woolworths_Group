# 🛒 Retail & E-Commerce Sales Analysis Dashboard

<div align="center">

<img src="https://img.shields.io/badge/Tool-Power%20BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black" />
<img src="https://img.shields.io/badge/Database-SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Language-DAX-blue?style=for-the-badge" />
<img src="https://img.shields.io/badge/Project-Data%20Analytics-success?style=for-the-badge" />
<img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge" />

</div>

---

# 📌 Project Overview

This project is a professional **Retail & E-Commerce Sales Analysis Dashboard** built using **SQL** and **Power BI**.

The main objective of this project is to analyze retail sales data and generate meaningful business insights through interactive dashboards and visual analytics.

The project follows a complete data analytics workflow:

```text
SQL Database → Data Extraction → Power BI → Data Cleaning → Dashboard → Business Insights
```

---

# 🎯 Business Problem

Retail businesses generate huge amounts of transactional data daily.

Without proper analysis, businesses face challenges such as:

- Difficulty identifying top-performing products
- Lack of visibility into sales trends
- Poor understanding of customer behavior
- Difficulty tracking profit and revenue
- Limited business decision-making insights

This project solves these problems by creating a professional Power BI dashboard for business intelligence and reporting.

---

# 🧰 Tools & Technologies Used

| Tool / Technology | Purpose |
|------------------|----------|
| SQL | Data Storage & Querying |
| Power BI | Dashboard Development |
| DAX | KPI Calculations |
| Power Query | Data Cleaning |
| Excel / CSV | Dataset Source |
| Data Modeling | Relationship Management |

---

# 🚀 Project Creation Process

---

# 🔹 Step 1: Dataset Source Using SQL

The raw retail sales dataset was first stored and managed in a SQL database.

SQL was used for:

- Data Extraction
- Data Cleaning
- Joining Multiple Tables
- Aggregation Queries
- Business Analysis

---

## 📂 Import SQL Data into Power BI

### Step 1:
Open **Power BI Desktop**

### Step 2:
Click:

```text
Home → Get Data → SQL Server
```

### Step 3:
Enter:

```text
Server Name
Database Name
```

### Step 4:
Choose:

```text
Import Mode
```

### Step 5:
Load tables into Power BI.

---

## 🧾 Example SQL Queries

### ✔ Total Revenue

```sql
SELECT SUM(Sales) AS Total_Revenue
FROM Orders;
```

---

### ✔ Top 10 Products by Revenue

```sql
SELECT Product_Name,
       SUM(Sales) AS Revenue
FROM Orders
GROUP BY Product_Name
ORDER BY Revenue DESC
LIMIT 10;
```

---

### ✔ Monthly Revenue Analysis

```sql
SELECT MONTH(Order_Date) AS Month,
       SUM(Sales) AS Revenue
FROM Orders
GROUP BY MONTH(Order_Date)
ORDER BY Month;
```

---

# 🔹 Step 2: Data Analysis in Power BI

After importing the SQL data into Power BI, the dataset was analyzed and transformed using Power Query and DAX.

---

## ✔ Data Cleaning

Performed using Power Query:

- Removed duplicate records
- Handled missing values
- Changed data types
- Formatted columns
- Cleaned inconsistent data

---

## ✔ Data Modeling

Created relationships between multiple tables:

- Orders Table
- Customers Table
- Products Table
- Sales Table

Implemented:

- Fact Tables
- Dimension Tables
- Star Schema Model

---

## ✔ DAX Measures Created

```DAX
Total Revenue = SUM(Orders[Sales])
```

```DAX
Total Profit = SUM(Orders[Profit])
```

```DAX
Average Order Value = DIVIDE([Total Revenue],[Total Orders])
```

---

# 📊 Dashboard Features

## ✔ Executive KPIs

- Total Revenue
- Total Profit
- Total Orders
- Quantity Sold
- Average Order Value
- Profit Margin

---

## ✔ Interactive Visualizations

- KPI Cards
- Bar Charts
- Line Charts
- Pie Charts
- Treemaps
- Maps
- Slicers & Filters
- Drill-through Analysis

---

## ✔ Business Insights

- Top Products by Revenue
- Top States by Sales
- Monthly Revenue Trends
- Profitability Analysis
- Category-wise Performance
- Customer Purchase Analysis

---

# 📈 Key Insights

- Identified top-performing products and categories.
- Analyzed regional sales performance.
- Compared monthly business growth trends.
- Evaluated customer purchasing patterns.
- Improved business understanding through visual analytics.

---

# ⚙️ Power BI Techniques Used

## 🔹 Data Preparation
- Power Query
- Data Cleaning
- Data Transformation

## 🔹 Data Modeling
- Relationships
- Star Schema
- Fact & Dimension Tables

## 🔹 DAX Functions
- SUM()
- DIVIDE()
- CALCULATE()
- FILTER()
- Time Intelligence Functions

## 🔹 Visualization
- Interactive Dashboard Design
- Conditional Formatting
- Dynamic Filtering
- KPI Reporting

---

# 🚀 Project Workflow

```text
Dataset Collection
        ↓
SQL Database Storage
        ↓
SQL Queries & Analysis
        ↓
Import Data into Power BI
        ↓
Data Cleaning using Power Query
        ↓
Data Modeling
        ↓
DAX Calculations
        ↓
Dashboard Development
        ↓
Business Insights Generation
```

---

# 📸 Dashboard Preview

Add your dashboard screenshots here.

```md
![Dashboard Screenshot](IMAGE_LINK_HERE)
```

---

# 📁 Project Structure

```text
📦 Retail-Sales-Analysis-PowerBI
 ┣ 📊 E_COMMARCE.pbix
 ┣ 📄 README.md
 ┣ 📁 Dataset
 ┣ 📷 Dashboard Screenshots
 ┗ 📄 SQL Queries
```

---

# 💡 Skills Demonstrated

- SQL Query Writing
- Data Cleaning
- Data Modeling
- Power BI Dashboard Development
- DAX Calculations
- Business Intelligence
- Data Visualization
- KPI Reporting
- Retail Analytics

---

# 👨‍💻 Author

## Mahesh Lohar

Aspiring Data Analyst skilled in:

- Power BI
- SQL
- Excel
- Python
- Data Analytics

---

# 🔗 Connect With Me

- LinkedIn: Add Your LinkedIn Profile
- GitHub: Add Your GitHub Profile

---

# ⭐ Support

If you like this project, give it a ⭐ on GitHub.

---

# 📌 How to Use

1. Download the `.pbix` file
2. Open in Power BI Desktop
3. Refresh the SQL dataset if required
4. Explore the interactive dashboard

---

# 📜 License

This project is for educational and portfolio purposes.
