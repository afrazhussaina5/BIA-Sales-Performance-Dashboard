# 📊 BIA Sales Performance Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Analytics-yellow?logo=powerbi)
![Business Intelligence](https://img.shields.io/badge/Business-Intelligence-blue)
![Data Analytics](https://img.shields.io/badge/Data-Analytics-orange)
![Data Visualization](https://img.shields.io/badge/Data-Visualization-purple)
![DAX](https://img.shields.io/badge/DAX-Measures-blueviolet)
![Project Status](https://img.shields.io/badge/Status-Completed-success)

---

## 📌 Project Overview

The **BIA Sales Performance Dashboard** is an interactive Business Intelligence and Data Analytics project developed using **Microsoft Power BI**.

The project transforms sales transaction data into meaningful and interactive visual insights related to sales, profit, quantity, products, orders, payment modes, sale types, and time-based performance.

The dashboard provides a centralized platform for monitoring business performance through **Key Performance Indicators (KPIs), interactive filters, DAX measures, data modeling, and data visualizations**.

The main objective of this project is to convert raw sales data into actionable business insights that can support better analysis and decision-making.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Analyze overall sales performance.
- Monitor total sales and total profit.
- Track total quantity sold.
- Analyze total orders.
- Identify high-performing products.
- Analyze monthly sales trends.
- Analyze daily sales performance.
- Compare sales and profit performance.
- Analyze different payment modes.
- Analyze different sale types.
- Analyze buying and selling values.
- Provide interactive filtering capabilities.
- Transform raw business data into meaningful visual insights.
- Support data-driven business decision-making.

---

## 🛠️ Tools & Technologies

| Technology | Purpose |
|------------|---------|
| **Microsoft Power BI** | Dashboard development and visualization |
| **Power Query** | Data cleaning and transformation |
| **DAX** | Calculated measures and business metrics |
| **Data Modeling** | Connecting and organizing data tables |
| **GitHub** | Project hosting and version control |

---

## 📂 Dataset Overview

The project uses structured sales data containing transaction-level and product-level information.

The data is organized into two primary tables:

### 🔹 InputData

The `InputData` table contains transaction and analytical information.

Important fields include:

- Date
- Day
- Month
- Month Name
- Year
- Product ID
- Quantity
- Sale Type
- Payment Mode
- Discount %
- Total Sales
- Total Profit
- Total Buying Value
- Total Orders
- Profit %
- Average Discount

### 🔹 MasterData

The `MasterData` table contains product-related information.

Important fields include:

- Product ID
- Product
- Category
- Buying Price
- Selling Price
- UOM

---

## 🔗 Data Model

The dashboard uses a relationship between the transaction data and product master data.

The primary connecting field is:

```text
PRODUCT ID
