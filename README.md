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

This project is a professional **Retail & E-Commerce Sales Analysis Dashboard** developed using **Power BI** and **SQL**.

The dashboard transforms raw business data into meaningful insights that help stakeholders monitor:

- Revenue Performance
- Profitability
- Customer Purchasing Behavior
- Product Performance
- Regional Sales Trends
- Business Growth

The project follows a complete analytics workflow including:

```text
SQL → Data Cleaning → Data Modeling → Power BI → Dashboard → Business Insights
```

---

# 🎯 Business Problem

Retail and e-commerce businesses generate large volumes of transactional data daily.

Without proper analysis, companies face challenges such as:

- Identifying profitable products
- Tracking monthly sales trends
- Understanding customer behavior
- Monitoring regional performance
- Making data-driven decisions

This dashboard solves these problems through interactive business intelligence reporting.

---

# 🧰 Tools & Technologies Used

| Tool / Technology | Purpose |
|------------------|----------|
| Power BI | Dashboard Development & Visualization |
| SQL | Data Extraction & Business Queries |
| DAX | KPI Calculations & Measures |
| Power Query | Data Cleaning & Transformation |
| Excel / CSV | Dataset Source |
| Data Modeling | Relationship Building |

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

# 🗃 SQL Integration

This project uses SQL concepts for:

- Data Extraction
- Data Cleaning
- Table Joins
- Business Analysis
- Aggregation Queries
- Data Preparation for Power BI

---

# 🧾 Example SQL Queries

## 🔹 Total Revenue

```sql
SELECT SUM(Sales) AS Total_Revenue
FROM Orders;
```

---

## 🔹 Top 10 Products by Revenue

```sql
SELECT Product_Name,
       SUM(Sales) AS Revenue
FROM Orders
GROUP BY Product_Name
ORDER BY Revenue DESC
LIMIT 10;
```

---

## 🔹 Monthly Revenue Trend

```sql
SELECT MONTH(Order_Date) AS Month,
       SUM(Sales) AS Revenue
FROM Orders
GROUP BY MONTH(Order_Date)
ORDER BY Month;
```

---

# ⚙️ Power BI Techniques Used

## 🔹 Data Preparation
- Data Cleaning using Power Query
- Handling Missing Values
- Removing Duplicates
- Data Formatting

## 🔹 Data Modeling
- Table Relationships
- Star Schema Modeling
- Fact & Dimension Tables

## 🔹 DAX Measures
- Revenue Calculations
- Profit Measures
- Average Order Value
- Dynamic KPIs
- Time Intelligence Functions

## 🔹 Visualization Techniques
- Interactive Dashboard Design
- Dynamic Filtering
- Drill-through Analysis
- Conditional Formatting
- KPI Reporting

---

# 📈 Key Insights

- Identified top-performing product categories.
- Analyzed monthly business growth trends.
- Compared state-wise sales performance.
- Evaluated customer purchasing patterns.
- Improved business understanding through interactive analytics.

---

# 📂 Dataset Information

The dataset includes:

- Orders Data
- Product Categories
- Customer Information
- Sales & Profit Metrics
- Quantity & Revenue Data
- Regional/State Information

---

# 🚀 Project Workflow

```text
Data Collection
       ↓
SQL Data Extraction
       ↓
Data Cleaning
       ↓
Data Transformation
       ↓
Data Modeling
       ↓
Dashboard Development
       ↓
Business Insights
```

---

# 📸 Dashboard Preview

Add your dashboard screenshots here.

```md
![Dashboard Screenshot](IMAGE_LINK_HERE)
```

Example:

```md
![Dashboard](https://github.com/your-username/project-name/assets/image.png)
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

- Data Analytics
- Business Intelligence
- Power BI Dashboard Development
- SQL Query Writing
- DAX Calculations
- Data Visualization
- Data Cleaning
- Business Reporting
- KPI Analysis

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
3. Refresh the dataset if required
4. Explore the interactive dashboard

---

# 📜 License

This project is for educational and portfolio purposes.
