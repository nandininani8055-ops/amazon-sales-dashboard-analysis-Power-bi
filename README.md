# Amazon Sales Dashboard Analysis 📊

An interactive **Power BI dashboard** developed to analyze Amazon-style sales data and provide insights into sales performance, products, categories, regions, customers, and payment methods.

## 📌 Project Overview

This project transforms a raw **6,000-row sales dataset** into a clean and interactive **3-page Power BI dashboard**.

The project covers the complete data analysis workflow:

**Raw Data → Data Cleaning → Power Query → DAX → Visualization → Business Insights**

## 🎯 Objectives

* Analyze overall sales performance
* Identify top-performing categories and products
* Analyze monthly sales trends
* Compare regional sales and orders
* Analyze payment-method usage
* Track key business KPIs
* Generate meaningful business insights

## 📂 Dataset

* **Rows:** 6,000
* **Columns:** 10
* **Period:** January 2023 – December 2024
* **Data:** Orders, products, quantity, price, sales, region, customers, and payment methods

## 🧹 Data Cleaning

Data preparation was performed using **Power Query**:

* Removed duplicate records
* Handled missing values
* Trimmed unnecessary spaces
* Standardized text values
* Removed invalid quantity records
* Recalculated sales using Quantity × Price
* Applied appropriate data types

After cleaning, the dataset contained **5,820 valid unique orders**.

## 🧮 DAX Analysis

Key measures created using DAX include:

* Total Sales
* Total Orders
* Total Quantity
* Average Order Value
* Total Customers
* Sales MoM % Change
* Top Category Sales
* % of Total Sales

## 📊 Dashboard Pages

### 1. Sales Overview

* Total Sales
* Total Orders
* Average Order Value
* Units Sold
* Monthly Sales Trend
* Sales by Payment Method
* Sales by Region

### 2. Product & Category Analysis

* Number of Categories
* Products Tracked
* Top Category
* Top Product
* Sales by Category
* Top 5 Products by Sales
* Units Sold by Category

### 3. Regional & Customer Analysis

* Unique Customers
* Number of Regions
* Top Region
* Sales per Customer
* Orders by Region
* Regional Sales Share
* Orders by Payment Method

## 🔍 Key Insights

* **Furniture** is the highest-revenue category.
* **South** records the highest regional sales.
* **Credit Card and Debit Card** contribute the highest payment-method sales.
* Sales performance varies across months and categories.
* Data cleaning was essential for producing reliable dashboard results.

## 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **Power Query**
* **DAX**
* **Excel / CSV**
* **GitHub**

## 📁 Project Files

```text
amazon-sales-dashboard-analysis/
│
├── Amazon_Sales_Dashboard.pbix
├── amazon_sales_dashboard_data.csv
├── PDD.md
├── SDD.md
└── README.md
```

## 👩‍💻 Author

**Nandini Ganesh**

Aspiring Data Analyst | Power BI | SQL | Excel | Data Visualization
