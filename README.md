# DASHBOARD
# 🛒 BlinkIT Grocery Sales Dashboard | Power BI

## 📌 Project Title

**BlinkIT Grocery Sales Dashboard – Power BI Business Intelligence Project**

---

# 📖 Project Description

The **BlinkIT Grocery Sales Dashboard** is an interactive Power BI solution designed to analyze sales performance, customer preferences, outlet performance, and product trends across BlinkIT grocery stores.

The dashboard transforms raw grocery sales data into meaningful business insights through KPIs, visualizations, filters, bookmarks, and drill-down analysis. It helps stakeholders understand sales distribution, outlet efficiency, product performance, and customer ratings for data-driven decision making.

---

# 🛠️ Tech Stack

### Data Visualization

* Power BI Desktop

### Data Preparation

* Power Query Editor

### Data Modeling

* Power BI Data Model

### Data Analysis

* DAX (Data Analysis Expressions)

### Dataset

* BlinkIT Grocery Sales Dataset

### Reporting Features

* Cards
* Bar Charts
* Column Charts
* Donut Charts
* Treemap
* Scatter Plot
* Slicers
* Bookmarks
* Tooltips
* Page Navigation Buttons

---

# ⭐ Features & Highlights

### Executive Dashboard

* Total Sales KPI
* Average Sales KPI
* Average Rating KPI
* Total Items KPI
* Average Visibility KPI

### Sales Analysis

* Sales by Item Type
* Sales by Outlet Size
* Sales by Fat Content
* Sales by Location Type

### Outlet Performance Analysis

* Sales Trend by Establishment Year
* Sales by Outlet Type
* Outlet Contribution Analysis

### Product Analysis

* Product Rating Analysis
* Product Weight vs Sales Analysis
* Fat Content Distribution
* Top Performing Products

### Interactive Features

* Dynamic Slicers
* Custom Tooltips
* Bookmarks
* Navigation Buttons
* Cross Filtering
* Interactive Dashboard Experience

---

# 🎯 Business Problem Statement

BlinkIT operates through multiple outlets and offers thousands of grocery products across different categories.

Management requires a centralized reporting solution to:

* Monitor overall sales performance
* Identify high-performing products
* Evaluate outlet performance
* Understand customer preferences
* Analyze product ratings
* Improve inventory and business decisions

Without a dashboard, extracting these insights from raw data becomes time-consuming and inefficient.

---

# ❓ Key Business Questions Answered

### Sales Performance

* What is the total sales generated?
* What is the average sales per product?

### Product Analysis

* Which item categories generate the highest sales?
* Which products receive the highest ratings?
* How does product weight impact sales?

### Outlet Analysis

* Which outlet type contributes the highest revenue?
* Which outlet size performs best?
* How do different location tiers impact sales?

### Customer Insights

* Which fat content category is preferred by customers?
* Which product categories have higher ratings?

### Growth Analysis

* How has sales performance changed based on outlet establishment year?

---

# 📊 Dashboard Pages

## Page 1 – Executive Summary

Contains:

* KPI Cards
* Sales by Fat Content
* Sales by Item Type
* Sales by Outlet Size
* Sales by Location Type
* Interactive Slicers

---

## Page 2 – Outlet Analysis

Contains:

* Sales Trend by Establishment Year
* Sales by Outlet Type
* Treemap Analysis
* Outlet Performance Table

---

## Page 3 – Product Analysis

Contains:

* Scatter Plot Analysis
* Rating by Item Type
* Fat Content Distribution
* Product Performance Table

---

# 📈 DAX Measures Used

```DAX
Total Sales =
SUM('BlinkIT Grocery Data'[Sales])
```

```DAX
Average Sales =
AVERAGE('BlinkIT Grocery Data'[Sales])
```

```DAX
Average Rating =
AVERAGE('BlinkIT Grocery Data'[Rating])
```

```DAX
Total Items =
COUNT('BlinkIT Grocery Data'[Item Identifier])
```

```DAX
Average Visibility =
AVERAGE('BlinkIT Grocery Data'[Item Visibility])
```

```DAX
Highest Sale =
MAX('BlinkIT Grocery Data'[Sales])
```

---

# 🧮 Calculated Column

```DAX
Outlet Age =
YEAR(TODAY()) -
'BlinkIT Grocery Data'[Outlet Establishment Year]
```

---

# 📌 Dashboard Features Implemented

✅ Data Cleaning using Power Query

✅ Data Type Corrections

✅ Calculated Column

✅ Multiple DAX Measures

✅ KPI Cards

✅ Slicers

✅ Tooltips

✅ Bookmarks

✅ Navigation Buttons

✅ Interactive Visualizations

✅ Professional Dashboard Layout

---



# 🔍 Key Insights

* Low Fat products contribute the largest share of sales.
* Tier 1 outlets generate the highest revenue.
* Supermarket Type 1 outlets outperform other outlet types.
* Fruits & Vegetables and Snack Foods are the highest-selling categories.
* Product ratings remain consistently high across major categories.
* Larger outlet networks contribute significantly to total revenue.

---

# ✅ Final Conclusion

The BlinkIT Grocery Sales Dashboard successfully converts raw sales data into actionable business intelligence. Through interactive visualizations and KPI monitoring, the dashboard enables stakeholders to evaluate outlet performance, identify top-selling product categories, monitor customer ratings, and optimize business strategies. This solution demonstrates how Power BI can be leveraged to support data-driven decision-making and improve operational efficiency in the retail and grocery sector.

