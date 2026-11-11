# 🛒 TrendMart – Retail Sales Data Cleaning & Dashboard

> **Retail Sales Data Cleaning, Analysis and Interactive Dashboard using Microsoft Excel**

<img width="652" height="436" alt="DASHBOARD SCREENSHOT" src="https://github.com/user-attachments/assets/e0a04d66-f9ce-401f-a95e-eacbb99a59c6" />


## 🎯 Objective

To clean the raw **TrendMart retail data** (sales, customers, stores, products, employees and suppliers) and build an interactive Excel dashboard that gives clear insights into **Sales, Profit, Quantity, Returns, Regions, States, Categories, Membership, Payment Modes, Sales Channels, Discounts, Brands, Stores and Time of Day**.

## 📁 Project Files

| File | Description |
| ---- | ----------- |
| `TrendKart_Data_Cleaning.xlsx` | Main workbook with cleaned data, pivot tables and dashboard |
| `Dashboard/Dashboard.jpeg` | Dashboard screenshot |
| `README.md` | Project documentation |

## 🗂️ Workbook Structure

| Sheet | Rows | Description |
| ----- | ---: | ----------- |
| 📊 `DASHBOARD` | – | Final dashboard with 9 charts and slicers |
| 🔢 `pivot table` / `pivottable` | – | Pivot tables that feed the dashboard charts |
| 🧾 `Sales_Transactions` | 3,000 | Invoice-level sales data (39 columns) |
| 👥 `Customers` | 850 | Customer profile, city, state, membership |
| 🏪 `Stores` | 120 | Store type, region, monthly target, manager |
| 🛍️ `Products` | 250 | Category, brand, cost price, selling price, MRP |
| 🧑‍💼 `Employees` | 300 | Department, designation, salary, performance rating |
| 🚚 `Suppliers` | 90 | Supplier city, lead time, rating |
| ✅ `Data_Quality_Log` | 23 | Log of every data issue found, by sheet and rows affected |

## 🛠️ Tools Used

* Microsoft Excel
* Data Cleaning
* Pivot Tables
* Pivot Charts
* Slicers
* Data Visualization
* Dashboard Design

## 🧹 Data Cleaning

A `Data_Quality_Log` sheet documents **23 types of data issues** found across the sheets, such as:

* Duplicate invoice numbers and duplicate phone numbers / product names
* Blank `Customer_ID`, `Product_ID`, `Employee_ID`, `Brand` and manager names
* Mixed date formats and text stored as numbers (`Quantity`)
* Extra spaces and mixed casing in `Payment Mode`, names and membership values
* Typos in `Return Status`, store status and employment status
* Invalid email addresses and mixed gender values
* Incorrect category spellings and `Quantity = 0` records
* Negative profit records

The raw `Payment Modee` column was standardised into a clean `Payment Mode` column, and helper columns such as `Profit Margin %`, `Order Period`, `Day Type` and `Target Key` were added for analysis.

## 📌 Key KPIs

| Metric            |         Value |
| ----------------- | ------------: |
| 💰 Total Sales    | ₹92,27,179.96 |
| 📈 Total Profit   | ₹18,04,518.54 |
| 📊 Profit Margin  |        19.56% |
| 💸 Total Cost     | ₹65,96,441.12 |
| 🧾 Total Transactions | 3,000 |
| 📦 Total Quantity |         6,118 |
| 🔄 Returns Rate   |         4.87% |

## 📊 Dashboard Analysis

* 🛒 **Sales by Channel** (Online vs Offline)
* 💳 **Payment Mode Distribution**
* 🏆 **Top 10 Brands by Profit**
* 📊 **Sales by Category**
* 🌍 **Sales by Region**
* 🏷️ **Sales & Profit by Discount Bracket**
* 👥 **Sales by Membership Tier**
* ⏰ **Sales by Time of Day**
* 🏪 **Top 10 Stores by Sales**
* 🎯 **Interactive slicer filters**

## 💡 Key Insights

* Total sales reached approximately **₹92.27 Lakhs** with a profit of **₹18.05 Lakhs** (**19.56% margin**).
* **Offline sales** contribute **66%** of sales, while **online sales** contribute **34%**.
* **UPI** is the most used payment mode (**28%**), followed by **Credit Card** (22%) and **Debit Card** (20%).
* **Regular** members contribute the most sales (**32%**), followed by Silver (31%), Gold (28%) and Platinum (9%).
* **South Zone 1** is the strongest region with about **₹44.6 Lakhs** in sales, nearly half of the total.
* **Karnataka** leads in state-wise sales, followed by Telangana, Kerala, Tamil Nadu and Andhra Pradesh.
* **Women Sarees, Handbags and Watches** are the top three categories by sales.
* **GRT Jewellers, Max Fashion and Reebok** are the top brands by total profit.
* **Higher discounts reduce profitability:** the profit margin falls from **28.5% at 0% discount** to just **1.7% at 30% discount**.
* **Afternoon and evening** hours bring the most sales, while night hours bring the least.
* **October and November** are the peak sales months.
* The overall **return rate is 4.87%**.
* The sales data contains **175 loss-making transactions** (negative profit), mostly linked to heavy discounts.

## 🚀 Recommended Actions

* Limit discounts above **20%**, as they sharply reduce margin.
* Promote **online sales** to grow beyond the current 34% share.
* Focus stock and marketing on top categories and high-margin brands.
* Plan campaigns and inventory ahead of the **October–November** peak.
* Review the causes of returns to bring the return rate down.

## ✅ Project Status

**Completed | TrendMart Excel Data Cleaning & Analytics Project**

---

### 👨‍💻 Skills Demonstrated

**Excel • Data Cleaning • Data Analysis • Pivot Tables • Slicers • Data Visualization • Dashboard Development**
