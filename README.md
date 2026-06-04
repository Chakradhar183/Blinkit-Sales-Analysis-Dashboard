# Blinkit Sales Analysis Dashboard

## Overview

This project is a Power BI dashboard created using the Blinkit Grocery dataset. The goal of the dashboard is to analyze sales performance across different outlet types, locations, and product categories while providing an easy-to-understand view of key business metrics.

The dashboard helps identify sales trends, customer preferences, and outlet performance through interactive visualizations and KPI tracking.

---

## Dashboard Preview

![Blinkit Dashboard](Screenshot%202026-06-04%20150326.png)

---

## Dataset

The dataset contains information related to:

* Product details
* Item categories
* Fat content
* Outlet size and type
* Outlet location
* Establishment year
* Sales
* Customer ratings
* Item visibility

Source file included in the repository:

`BlinkIT Grocery Data.xlsx`

---

## Tools Used

* Power BI Desktop
* Power Query
* DAX
* Microsoft Excel

---

## Key Metrics

| Metric         | Value   |
| -------------- | ------- |
| Total Sales    | $1.20M  |
| Average Sales  | $140.99 |
| Total Items    | 8,523   |
| Average Rating | 3.92    |

---

## Dashboard Analysis

### Sales by Outlet Establishment Year

Shows how sales vary based on the year an outlet was established and helps understand overall growth trends.

### Sales by Fat Content

Compares revenue generated from Low Fat and Regular products.

### Sales by Item Type

Highlights the contribution of different product categories such as Fruits & Vegetables, Snack Foods, Dairy, Frozen Foods, and Household items.

### Sales by Outlet Size

Analyzes how Small, Medium, and High-sized outlets contribute to overall sales.

### Sales by Outlet Location

Compares outlet performance across Tier 1, Tier 2, and Tier 3 locations.

### Outlet Type Analysis

Provides a detailed comparison of outlet formats based on:

* Total Sales
* Number of Items
* Average Sales
* Average Rating
* Item Visibility

---

## Data Preparation

Before building the dashboard, the dataset was cleaned and transformed using Power Query.

Steps performed:

* Checked for missing values
* Standardized fat content categories
* Verified data types
* Removed inconsistencies
* Created DAX measures for KPI calculations

---

## DAX Measures

### Total Sales

```DAX
Total Sales = SUM('BlinkIT Grocery Data'[Sales])
```

### Average Sales

```DAX
Average Sales = AVERAGE('BlinkIT Grocery Data'[Sales])
```

### Number of Items

```DAX
No Of Items = COUNT('BlinkIT Grocery Data'[Item Identifier])
```

### Average Rating

```DAX
Avg Rating = AVERAGE('BlinkIT Grocery Data'[Rating])
```

---

## Key Findings

* Tier 3 locations recorded the highest sales.
* Regular fat products generated more revenue than low-fat products.
* Medium-sized outlets contributed a significant share of overall sales.
* Fruits & Vegetables and Snack Foods were among the top-performing categories.
* Supermarket Type 1 achieved the highest sales among all outlet types.

---

## Files Included

```text
Blinkit-PowerBI-Report/
│
├── BlinkIT Grocery Data.xlsx
├── blinkit.pbix
├── Screenshot 2026-06-04 150326.png
└── README.md
```

---

## About Me

Chakradhar Sadhana

Aspiring Data Analyst with an interest in Power BI, SQL, Python, and Data Visualization.

Feel free to explore the dashboard and share any feedback.
