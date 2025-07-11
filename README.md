# 📊 Financial Performance Dashboard

**Tool Used:** Tableau Public  
**Level:** Intermediate  
**Domain:** Business Analytics / Financial Analysis  

---

## 📁 Project Overview

This Tableau project analyzes financial performance across multiple countries and products over time. The dashboard highlights sales, profit, COGS, discounts, and their relationships with discount bands and product categories.

---

## 🧾 Dataset Summary

- **File:** `financial_data.csv`
- **Time Range:** 2011 to 2014
- **Dimensions:** Segment, Country, Product, Discount Band
- **Measures:** Units Sold, Manufacturing Price, Sale Price, Gross Sales, Discounts, Sales, COGS, Profit
- **Date Fields:** Date, Month Number, Month Name, Year

---

## 🔧 Data Cleaning in Tableau

All cleaning was performed inside Tableau using calculated fields:
- Handled corrupted entries like `$-`, missing values, and text-formatted numbers
- Created cleaned numeric fields (e.g., `Cleaned Sales`, `Cleaned Profit`)
- Created `Fixed Date` using `MAKEDATE([Year], [Month Number], 1)`

---

## 🧮 Calculated Fields

| Field Name         | Description                                 |
|--------------------|---------------------------------------------|
| `Profit Margin`    | Profit ÷ Sales                              |
| `Total Revenue`    | Gross Sales                                 |
| `Total Discounts`  | Total Discounts                             |
| `COGS to Sales`    | COGS ÷ Sales                                 |

---

## 📊 Visualizations

1. **Sales & Profit by Country** — bar chart with profit color
2. **Trend Over Time** — dual-axis line graph for Sales and Profit
3. **Gross Sales vs Discounts** — scatter plot with color by product
4. **Sales by Product and Discount Band** — heat map

All visualizations are combined into a single interactive dashboard.

---

## 🖥️ Dashboard Features

- Interactive filters: Date range, Segment, Product, Country
- Dynamic interlinked views
- Clean layout with clearly separated insights

---

## 📦 Included Files

| File                                  | Description                                |
|---------------------------------------|--------------------------------------------|
| `financial_data.csv`                  | Original dataset                           |
| `financial_dashboard.twbx`            | Tableau project file                       |
| `Financial Performance Dashboard.pdf` | Assignment PDF                             |
| `README.md`                           | This project report                        |

---

## 🔗 Credits

Project executed based on a guided step-by-step instruction and original assignment brief.
