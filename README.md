# Sales & Customer Analysis Dashboard

## Project Overview

This project focuses on analyzing sales and customer data using **SQL and Power BI**.
The goal is to derive meaningful business insights from raw data and present them through an interactive dashboard.

---

## Tools & Technologies

* SQL (MySQL)
* Power BI
* DAX (Data Analysis Expressions)
* AdventureWorks Dataset

---

## Project Structure

```
Retail-Sales-Analysis/
│
├── data/
│   ├── CustomerMaster.csv
│   ├── SalesOrderHeader.csv
│   └── VendorMaster.csv
│
├── sql/
│   └── analysis_queries.sql
│
├── powerbi/
│   └── dashboard.pbix
│
├── images/
│   └── dashboard.png
│
└── README.md
```

---

## Dashboard Features

### Key KPIs

* Total Sales
* Total Orders
* Average Order Value
* Total Customers

### Time-based Analysis

* Monthly Sales Trend
* Year-over-Year (YoY %)
* Month-over-Month (MoM %)
* Quarter-to-Date (QTD) Sales

### Customer Insights

* Top 10 Customers
* Customer distribution

### Sales Insights

* Country-wise Sales
* Weekend vs Weekday Sales

### Advanced Analytics

* Running Total (Monthly & Quarterly)
* Previous Month & Quarter Comparison
* Tooltip with detailed insights

---

## Key Business Insights

* Sales peaked in **2013**, showing strong growth before a decline.
* **Weekday sales (~71%)** are significantly higher than weekend sales.
* **United States** contributes the highest share of revenue.
* A small group of customers contributes a large portion of total sales.

---

## SQL Analysis

SQL queries were used for:

* Data exploration
* Aggregations (SUM, COUNT, AVG)
* Joins across multiple tables
* Customer and sales analysis

All queries are available in the `sql/analysis_queries.sql` file.

---

## DAX Measures Used

* YoY %
* MoM %
* QTD Sales
* Running Total
* Weekend vs Weekday classification
* Average Delivery Time

---

## How to Use

1. Open the `.pbix` file in Power BI Desktop
2. Explore filters (Year, Country)
3. Hover over charts for tooltip insights
4. Interact with visuals for deeper analysis

---

## Conclusion

This project demonstrates:

* End-to-end data analysis workflow
* SQL + Power BI integration
* Business-focused dashboard design

---

## Author

**Nitisha Phore**

