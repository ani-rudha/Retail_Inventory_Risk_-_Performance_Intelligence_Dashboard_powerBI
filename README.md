# 🛍️ Retail Sales, Inventory & Supply Chain Intelligence Dashboard (Power BI)

This project presents an end-to-end **Retail Business Intelligence Dashboard** built using Power BI to analyze sales performance, inventory health, supplier reliability, and store profitability.

The dashboard integrates **sales analytics, inventory risk monitoring, supplier supply analysis, and profitability insights** to simulate a real-world retail analytics environment focused on operational efficiency and supply chain intelligence.

---

## ✴️ Project Overview

The objective of this project was to:

- Design a clean **star-schema data model**
- Implement **advanced DAX measures**
- Build **executive-ready KPI dashboards**
- Monitor **inventory health and stockout risks**
- Analyze **supplier contribution and supply chain reliability**
- Deliver **actionable business insights for retail operations**

---

## 🎯 Business Objectives

- Measure overall retail sales and profitability performance.
- Identify high-performing stores and product categories.
- Monitor inventory levels and detect stockout risks.
- Analyze supplier contribution to inventory supply.
- Track supply vs demand balance across the business.
- Provide insights to improve retail operations and inventory planning.

---

## 📂 Dataset Description

The dataset consists of the following tables:

| Table | Description |
|--------|------------|
| `fact_sales` | Sales transactions including revenue, cost and quantity sold |
| `fact_inventory` | Current inventory stock levels |
| `fact_inventory_movements` | Inventory inflow and outflow movements |
| `dim_products` | Product catalog with categories and supplier information |
| `dim_stores` | Store location, region and store attributes |
| `dim_suppliers` | Supplier information and supply relationships |
| `dim_date` | Calendar table used for time intelligence |
| `MyMeasures` | Dedicated table to store all DAX measures |

The dataset simulates a **real-world retail data warehouse structure**.

---

## 🧱 Data Model Design

The model follows a **star schema structure**:

- `fact_sales` acts as the primary **sales performance fact table**
- `fact_inventory` tracks **inventory stock levels**
- `fact_inventory_movements` tracks **inventory inflow and outflow**
- `dim_products` connects products with categories and suppliers
- `dim_stores` enables **store-level performance analysis**
- `dim_suppliers` enables **supplier contribution analysis**
- `dim_date` supports **time intelligence calculations**

Relationships are built using **product_id, store_id, supplier_id and date keys** with one-to-many cardinality.

This structure ensures **proper filter propagation and accurate KPI calculations**.

---

## 🧮 Key DAX Measures

### Core Business KPIs

- Total Revenue
- Total Profit
- Profit Margin (%)
- Total Units Sold
- Sales Last Year
- Year-on-Year Growth (%)

### Inventory & Risk Analysis

- Inventory Health Score
- SKU Critical Risk Count
- Inventory vs Reorder Point
- Inventory Risk by Category
- Stockout Risk Indicator

### Supply Chain & Inventory Flow

- Stock In
- Stock Out
- Net Inventory Flow
- Supplier Inventory Contribution
- Supplier Stockout Risk Exposure

### Profitability & Store Performance

- Store Level Profit
- Category Profit Contribution
- High Margin Product Categories
- Profit Distribution by Region

All measures were implemented using **proper filter context handling** to ensure KPI accuracy across all dashboard filters.

---

## 📈 Dashboard Structure

### 1️⃣ Executive KPI & Strategic Insights

- Total Revenue
- Total Profit
- Profit Margin (%)
- Total Units Sold
- Top Performing Store
- Sales & Profit Trend
- Sales Distribution by Region

Purpose: Provide a **high-level executive overview of business performance**, including revenue growth, profitability trends, and regional sales distribution.

---

### 2️⃣ Sales Performance Overview

- Inventory Health KPI
- Year-on-Year Growth (%)
- Category Performance Analysis
- Sales Performance by State (Map View)
- Inventory Risk by Category

Purpose: Analyze **sales trends and category-level performance while monitoring inventory health**.

---

### 3️⃣ Inventory Risk Intelligence

- Inventory vs Reorder Point Analysis (Scatter Plot)
- Inventory Risk Trend
- Stockout Risk by Product Category
- Supplier Stockout Risk Contribution
- Top 15 Critical SKU Risk Table

Purpose: Detect **inventory shortages, high-risk SKUs, and supplier-related stockout risks** to support proactive inventory management.

---

### 4️⃣ Supply Chain & Inventory Flow Intelligence

- Top 10 Suppliers by Inventory Contribution
- Top Product Categories by Supplier Deliveries
- Inventory Flow Trend (Supply vs Demand)
- Net Inventory Flow KPI

Purpose: Evaluate **supply chain reliability and supply-demand balance across the business**.

---

### 5️⃣ Store & Profitability Intelligence

- High Margin Product Categories
- Top 10 Stores by Profit
- Profit Contribution by Category
- Profit Distribution by State

Purpose: Identify **profit drivers across stores and product categories** to support better merchandising and pricing strategies.

---

## 📝 Overall Dashboard Objective

To provide a **complete 360° view of retail operations** by combining:

- Sales Performance Analytics
- Inventory Risk Monitoring
- Supply Chain Contribution Analysis
- Store Profitability Insights

This enables businesses to **balance revenue growth with operational efficiency and supply chain stability**.

---

## 🎨 Advance UX Features

- Collapsible slicer panel for clean dashboard layout
- Interactive filtering across multiple pages
- Donut-based KPI progress visuals
- Map-based regional sales analysis
- Custom `MyMeasures` table for clean DAX management
- Consistent KPI color themes for performance indicators

The dashboard balances **analytical depth with professional presentation design**.

---

## 🔍 Key Business Insights

- Sales performance varies significantly across regions and stores.
- Certain product categories show **higher inventory risk compared to others**.
- Supplier contribution analysis highlights **inventory dependency patterns**.
- Profit margins vary across categories indicating potential pricing opportunities.
- Net Inventory Flow helps monitor whether **supply is exceeding demand or vice versa**.

---

## 💼 Business Recommendations

- Monitor high-risk SKUs and adjust reorder strategies.
- Improve supplier diversification to reduce stockout dependency.
- Focus on high-margin product categories to maximize profitability.
- Analyze underperforming stores for operational improvements.
- Align supplier deliveries with demand trends to prevent overstock or shortages.

---

## 🛠 Tools Used

- Power BI
- Data Modeling (Star Schema Logic)
- Advanced DAX Measures
- Power Query (Data Cleaning & Transformation)
- Retail & Supply Chain Analytics Techniques
- Business Intelligence Visualization Design

---

## 🚀 Portfolio Value

This project demonstrates:

- End-to-end BI dashboard development
- Strong data modeling fundamentals
- Advanced DAX implementation
- Retail and supply chain analytics
- Inventory risk monitoring techniques
- Business storytelling through dashboards

Suitable for roles in:

- Data Analyst
- Business Intelligence Analyst
- Retail Analytics
- Supply Chain Analytics

It reflects the ability to **transform operational retail data into actionable business insights**.

---

> Note: *For any questions or collaboration opportunities, feel free to reach out!*
