# 📊 Sales & Profit Analysis Dashboard — Power BI

## 📌 Project Overview

This project is an interactive **Sales & Profit Analysis Dashboard** developed using **Microsoft Power BI**.

The dashboard analyzes retail/store sales data to understand:

- Sales performance
- Profit performance
- Product performance
- Order volume
- Quantity sold
- Promotional performance
- Customer and city-level sales
- Sales trends over time
- Top and bottom performing products

The project demonstrates the use of **Data Cleaning, Data Modeling, DAX, Data Visualization, and Business Intelligence** to convert raw sales data into meaningful insights.

---

## 🎯 Project Objectives

The main objectives of this project are:

1. Analyze overall sales and profit performance.
2. Identify top-performing and low-performing products.
3. Analyze product quantity and order volume.
4. Understand the impact of promotional categories.
5. Analyze sales performance across different cities.
6. Identify relationships between profit and net sales.
7. Analyze sales trends over time.
8. Provide interactive filters for exploring the data.
9. Create an easy-to-understand business intelligence dashboard.

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Microsoft Excel**
- **Power Query**
- **DAX**
- **Data Modeling**
- **Data Visualization**

---

## 📂 Dataset

The project uses an Excel dataset containing customer, product, promotion, and transaction information.

### Dataset Structure

| Table | Records | Description |
|---|---:|---|
| Dim Customers | 50 | Customer details including name, city, state, email and phone |
| Dim Product | 30 | Product details, product category and price |
| Dim Promotion | 5 | Promotion and discount information |
| Sales Transactions | 3,510 | Transaction-level sales data |

### Main Transaction Fields

The transaction dataset contains fields such as:

- Date
- Customer ID
- Promotion ID
- Product ID
- Units Sold
- Price Per Unit
- Total Sales
- Discount Percentage
- Discount Value
- Net Sales

---

# 📊 Dashboard Pages

The Power BI report contains multiple interactive pages.

## 1. Overview Dashboard

The Overview page provides a high-level view of business performance.

### Key Visualizations

- Net Sales by Cities
- Number of Orders
- Profit vs Net Sales
- Average Discount Value by Promotion Category
- Sales Trends by Period

This page provides a quick understanding of overall sales activity, geographic distribution, promotions, and time-based sales trends.

---

## 2. Top/Bottom 5 Analysis

This page compares the highest and lowest performing products.

### Analysis Included

- Top 5 Products by Sales
- Bottom 5 Products by Sales
- Top 5 Products by Quantity
- Bottom 5 Products by Quantity
- Top 5 Products by Profit
- Bottom 5 Products by Profit

This helps identify products that contribute significantly to sales and profit as well as products with comparatively lower performance.

---

## 3. Sales / Profit / Quantity Comparison

This page provides a comparison of:

- Total Sales
- Total Profit
- Total Quantity Sold

The dashboard also includes date filters to analyze the metrics for selected time periods.

---

## 4. Datewise Sales / Profit / Quantity

This page provides a date-based view of important business metrics.

### Metrics

- Total Sales
- Total Profit
- Total Quantity

Date filters allow users to explore the metrics for different periods.

---

## 5. Edit Interactions / Detailed Data

The detailed analysis page provides interactive filters and a transaction-level data table.

### Filters

- Date
- Customer Name
- Product Name
- Promotion Name

### Detailed Fields

- Customer ID
- Order ID
- Product ID
- Promotion ID
- Date
- Discount Percentage
- Discount Value
- Net Sales
- Price Per Unit
- Profit
- Total Sales
- Units Sold

This page allows users to drill down from summary-level insights into individual transactions.

---

# 📈 Key Dashboard Metrics

The dashboard provides several important business metrics, including:

- **Total Sales**
- **Total Profit**
- **Net Sales**
- **Number of Orders**
- **Units Sold**
- **Average Discount Value**
- **Sales by City**
- **Profit vs Net Sales**
- **Product-wise Sales**
- **Product-wise Profit**
- **Product-wise Quantity**

---

# 🔍 Key Analysis Areas

### 🌍 Geographic Analysis

The dashboard uses a map visualization to analyze **Net Sales by City**, helping identify geographic areas contributing to sales.

### 🛍️ Product Analysis

Products are analyzed based on:

- Sales
- Profit
- Quantity Sold

The Top/Bottom 5 analysis makes it easier to identify differences in product performance.

### 🎯 Promotion Analysis

Promotional categories are analyzed using discount values to understand how different promotions are associated with discount activity.

### 📅 Time-Series Analysis

Sales trends are analyzed across the available transaction period to observe changes in sales performance over time.

### 💰 Profitability Analysis

The **Profit vs Net Sales** visualization helps examine the relationship between net sales and profit.

---

# 🧮 Power BI / DAX Concepts Used

The project demonstrates concepts such as:

- Calculated Measures
- Aggregations
- SUM
- COUNT
- AVERAGE
- Filtering
- Top N Analysis
- Date-based analysis
- Interactive slicers
- Cross-filtering
- Data relationships
- Data modeling
- Conditional analysis
- Drill-down and dashboard interactions

---

# 🎨 Dashboard Features

- Interactive Power BI visuals
- Date range filtering
- Product filtering
- Customer filtering
- Promotion filtering
- Cross-visual interactions
- Geographic visualization
- Top/Bottom product analysis
- Detailed transaction table
- KPI-style summary metrics
- Time-series analysis

---

# 📷 Dashboard Preview

## Overview

![Overview Dashboard](Screenshots/overview.png)

## Top & Bottom 5 Analysis

![Top Bottom Analysis](Screenshots/top-bottom-analysis.png)

## Sales / Profit / Quantity Comparison

![Comparison Dashboard](Screenshots/comparison.png)

## Datewise Analysis

![Datewise Analysis](Screenshots/datewise-analysis.png)

## Detailed Data

![Detailed Data](Screenshots/detailed-data.png)

---

# 📁 Project Structure

```text
Sales-Profit-PowerBI-Dashboard/
│
├── README.md
│
├── PowerBI/
│   └── Sales_Profit_Analysis.pbix
│
├── Dataset/
│   └── Store_Data.xlsx
│
├── Screenshots/
│   ├── overview.png
│   ├── top-bottom-analysis.png
│   ├── comparison.png
│   ├── datewise-analysis.png
│   └── detailed-data.png
│
└── Documentation/
    └── Project_Documentation.pdf
