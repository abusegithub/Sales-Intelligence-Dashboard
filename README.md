# 📊 Sales Intelligence Dashboard

> An interactive Power BI dashboard for analyzing sales performance, profitability, customers, products, regional performance, and target achievement.

---

## 📌 Overview

The **Sales Intelligence Dashboard** transforms raw sales data into an interactive business intelligence solution using Microsoft Power BI.

The dashboard provides a centralized view of key business metrics and allows users to explore performance across different **time periods, categories, customers, products, cities, and states**.

It is designed to help business users quickly identify trends, top performers, performance gaps, and opportunities for improvement.

---

## 🎯 Business Objectives

- Monitor overall sales and profitability
- Track performance against sales targets
- Identify high-performing categories and sub-categories
- Analyze customer purchasing behavior
- Compare sales performance across states and cities
- Identify top customers by sales
- Understand monthly sales trends
- Evaluate target achievement and sales variance

---

## 📊 Dashboard Pages

### 01. Executive Overview

Provides a high-level view of overall business performance.

**Key metrics:**
- Total Sales
- Total Profit
- Profit Margin %
- Sales Variance
- Target Achievement %
- Sales Target

**Visual analysis:**
- Sales by Category
- Sales by State
- Monthly Sales vs Sales Target
- Interactive filters for Month, Category, and State

![Executive Dashboard](Dashboard%20SS/sales%20dashboard%20ss1.jpeg)

---

### 02. Product Analysis

Analyzes product and category-level performance.

**Key analysis:**
- Sales by Category
- Profit by Category
- Sales by Sub-Category
- Category comparison
- Sub-category performance

![Products Dashboard](Dashboard%20SS/sales%20dashboard%20ss2.jpeg)

---

### 03. Customer Analysis

Provides insights into customer and geographical performance.

**Key analysis:**
- Top 10 Customers by Sales
- Total Customer Count
- Sales by State
- Sales by City
- Customer-level performance
- Interactive state filtering

![Customers Dashboard](Dashboard%20SS/sales%20dashboard%20ss3.jpeg)

---

### 04. Target Performance

Focuses on sales targets and performance achievement.

**Key analysis:**
- Total Sales
- Sales Target
- Sales Variance
- Target Achievement %
- Monthly Sales vs Target
- Target Achievement Gauge

![Targets Dashboard](Dashboard%20SS/sales%20dashboard%20ss4.jpeg)

---

## 📈 Key KPIs

| KPI | Purpose |
|---|---|
| **Total Sales** | Measures overall revenue generated |
| **Total Profit** | Measures total business profit |
| **Profit Margin %** | Evaluates profitability relative to sales |
| **Sales Target** | Defines expected sales performance |
| **Sales Variance** | Measures the gap between actual sales and target |
| **Target Achievement %** | Shows progress toward the sales target |
| **Total Customers** | Measures the customer base |
| **Total Orders** | Tracks total orders |
| **Total Quantity** | Measures units sold |
| **Average Order Value** | Measures average revenue per order |

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Data Modeling**
- **Data Visualization**
- **Interactive Slicers**
- **Drill-through**
- **Page Navigation**

---

## 🧮 Data Model

The report uses a structured Power BI data model containing:

```text
Calendar
   │
   ├── Order Details
   │
   ├── List of Orders
   │
   ├── Category
   │
   └── Sales Target
