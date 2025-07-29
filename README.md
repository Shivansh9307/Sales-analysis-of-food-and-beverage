# Food-Beverage-Sales-Analysis
Developed an interactive Power BI dashboard to analyze a food &amp; beverage dataset, revealing insights on revenue, product category trends, top-performing salespeople, and monthly/quarterly sales performance. Achieved a clear breakdown of $2M+ in revenue across 4,100+ orders.

# 🍽️ Food & Beverage Sales Analysis - Power BI Dashboard

This Power BI project provides a comprehensive analysis of a Food & Beverage dataset, uncovering critical business insights such as revenue distribution, product performance, and salesperson effectiveness. The dashboard is designed to help stakeholders make informed decisions using real sales data.

---

## 📊 Dataset Overview

The analysis is based on two main tables:

### 1. `Product`
- `ID` (Primary Key)
- `ProductCategory`
- `ProductGroup`
- `ProductName`

### 2. `Sheet1` (Sales Transactions)
- `Channel` (Retail, Distributor, Online)
- `Manager`
- `OrderDate`
- `OrderNumber`
- `ProductKey` (Foreign Key referencing `Product.ID`)
- `Quantity`
- `Sales Amount`
- `Salesperson`
- `SalespersonKey`

A one-to-many relationship is established between `Product.ID` and `Sheet1.ProductKey`.

---

## 🔍 Key Insights

### 💰 Revenue
- **Total Revenue:** $2M+
- **Average Ticket Price:** $416.70
- **Total Orders:** 4,100+

### 🛍️ Revenue by Channel
- **Retail Channel** contributed **100%** of the total revenue.

### 🍱 Revenue by Product Category
- **Food:** 85.89%
- **Drink:** 14.11%

### 📦 Top Revenue-Contributing Product Groups
- Wheat Products
- Liquor
- Oil
- Candy
- Coffee

### 📆 Time-Based Performance
- **Quarter 1** showed the highest sales volume and revenue.
- Monthly trends visible for January, February, and March.

### 👩‍💼 Salesperson Performance

| Salesperson         | Orders | Avg Ticket Price | Revenue     |
|---------------------|--------|------------------|-------------|
| Carla Ferreira      | 1787   | $516.50          | $922,987    |
| Leonardo Cardoso    | 963    | $283.54          | $273,045    |
| Isabella Sousa      | 430    | $506.60          | $217,838    |
| Kaua Araujo         | 541    | $346.68          | $187,556    |
| Gustavo Barros      | 320    | $284.94          | $91,180     |
| Julieta Gomes       | 59     | $269.18          | $15,882     |

---

## 📈 Dashboard Features
- Interactive slicers: Filter by product group, channel, category, or salesperson.
- Time-series visualizations for monthly and quarterly analysis.
- Category and salesperson performance comparisons.
- Drill-through capabilities for detailed insights.

---

## 🛠️ Tools Used
- **Power BI Desktop**
- **DAX** for calculated measures
- **Data modeling** with relationships

---

## 📁 Data
![Data Schema Preview](https://github.com/Harshalpatil9767/Food-Beverage-Sales-Analysis/blob/3ecc19a2d33aec8083196606b7d304fa6d708b86/Data_Schema.png)


---

## 📌 Objective
This project aims to provide actionable insights into sales performance within the food and beverage industry, supporting better business decisions across marketing, inventory, and sales teams.

---

## 📸 Preview

![Dashboard Preview](https://github.com/Harshalpatil9767/Food-Beverage-Sales-Analysis/blob/cc1be6c12c0e3aca3e5de47169bfdef8f96a5465/Food_Beverages_POWERBI.png)


