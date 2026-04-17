## Mexico-Toys-Sales-And-Inventory-Analysis-Using-Power-BI

### 📊 Project Overview

This project analyzes sales and inventory data for Maven Toys across multiple store locations in Mexico. The goal is to provide actionable insights for improving revenue, profitability, and inventory management using Power BI.

---

### 🎯 Business Objective

- Monitor sales performance across stores and product categories
- Identify high-performing products and locations
- Detect stock shortages and overstock situations
- Improve inventory planning and profitability

---

### 📂 Dataset

- **Source:** Maven Analytics
- **Time Period:** 2022–2023
- **Domain:** Sales Analytics

---

### 🧱 Data Model

- **Fact Tables:** Sales, Inventory
- **Dimension Tables:** Products, Stores, Calendar
- **Schema:** Star Schema

### Key Relationships:

- **Products** → Sales & Inventory
- **Stores** → Sales & Inventory
- **Calendar** → Sales

---

### ⚙️ Tools & Technologies

- Power BI – Dashboard & Visualization
- Power Query – Data Cleaning & Transformation
- Excel – Data Source

---

### 🧹 Data Preparation

- Removed duplicates and null values
- Created calculated columns:
  
- Revenue
- Profit
- Profit Margin
- Inventory Status (Low, Normal, Overstock)
- Standardized product and store data

  ---
  
### 📈 Key KPIs

1. Total Revenue
2. Total Profit
3. Profit Margin
4. Units Sold
5. Stock Levels
5. Low / Out-of-Stock Products

### 📊 Dashboard Preview

<img src="Dashboard/dashboard-executive .png" alt="Executive Overview" width="1000"/>

### 🔍 Key Insights

#### 🛍️ Sales Insights

- Toys category generates the highest revenue (~5M).
- Strong seasonal trend: peak in Q2, drop in October.
- Few products drive majority of revenue.

#### 💰 Profit Insights

- Toys is the most profitable category
- Electronics has higher profit margins
- Some high-revenue products have low margins

#### 🏬 Store Insights

- Top stores are in major cities (Mexico City, Guadalajara).
- Sales and profit strongly depend on volume.
- Downtown locations generate highest profit.

#### 📦 Inventory Insights

- Some products are overstocked while others face shortages.
- October shows major stock drop (possible supply issue).
- High-demand items need better stock planning.

---

### 💡 Business Recommendations

- Increase stock for high-demand products.
- Reduce slow-moving inventory.
- Focus on high-margin categories.
- Transfer stock between stores.
- Improve demand forecasting for seasonal trends.

---

### 📌 Conclusion

This dashboard helps businesses make data-driven decisions by improving visibility into sales trends, product performance, and inventory health. It supports better planning, reduces stock issues, and enhances profitability.

