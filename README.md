# 🚚📦 Supply Chain Intelligence Dashboard (Power BI)

An end-to-end **Supply Chain & Risk Intelligence Dashboard** built using Power BI to analyze revenue performance, inventory efficiency, working capital optimization, and supplier risk exposure.

This project simulates a real-world enterprise supply chain monitoring system integrating financial, operational, and supplier risk analytics.

---

## ✴️ Project Overview

The objective of this project was to:

- Design a clean star-schema data model
- Implement advanced DAX measures
- Build executive-ready KPI dashboards
- Identify revenue concentration and supplier risk exposure
- Deliver actionable business insights

The dashboard connects revenue analytics, inventory health, and supplier dependency into a structured decision-support system.

---

## 🎯 Business Objectives

- Measure Total Revenue & Financial Performance  
- Analyze Inventory Turnover & DSI  
- Perform ABC Revenue Classification (Pareto 80/20)  
- Identify Inventory Allocation by Category  
- Detect Overstock & Stockout Risks  
- Evaluate Supplier Risk Exposure  
- Measure Revenue & Inventory Exposure to High-Risk Suppliers  

---

## 📂 Dataset Description

The dataset consists of the following tables:

| Table | Description |
|--------|------------|
| `Fact_SupplyChain` | Transaction-level revenue, inventory, supplier & operational data |
| `Dim_Product` | Product attributes (ProductID, Category) |
| `Dim_Supplier` | Supplier information including Risk_Score |
| `Dim_Date` | Date dimension for time-based analysis |
| `Dim_Warehouse` | Warehouse-level storage data |
| `ABC_Table` | Disconnected table for ABC classification |
| `MyMeasures` | Dedicated table for all DAX measures |

---

## 🧱 Data Model Design

The model follows a **Star Schema architecture**:

- Centralized Fact table
- One-to-Many relationships
- Single-direction filtering
- No ambiguous joins
- Disconnected ABC classification table
- Separate Measures table for clean organization

This ensures proper filter propagation and KPI accuracy.

---

## 🧮 Key DAX Measures

### Core Financial KPIs
- Total Revenue
- COGS
- Average Inventory Value
- Inventory Turnover (Financial)
- Days Sales of Inventory (DSI)

### Inventory Intelligence
- Total Inventory Value
- Inventory % by Category
- Avg Product Days on Hand (DOH)
- Inventory Risk Flag
- Stockout Rate

### Revenue Concentration (ABC Analysis)
- Revenue by Product
- Product Rank
- Cumulative Revenue %
- ABC Classification
- Revenue by ABC Class
- Inventory by ABC Class

### Supplier Risk Analytics
- Average Risk Score
- High Risk Suppliers
- Revenue High Risk
- Revenue Exposure %
- Inventory High Risk
- Supplier Risk vs Revenue Scatter Matrix

---

## 📈 Dashboard Structure

### 1️⃣ Executive Summary
- Revenue KPIs
- Inventory Turnover
- DSI
- On-Time Delivery %
- Stockout Rate

### 2️⃣ Revenue & Demand Analysis
- Revenue by Category
- ABC Classification
- Revenue Concentration
- Category Contribution

### 3️⃣ Inventory & Working Capital Optimization
- Inventory Value by Category
- Inventory % by Category
- Inventory by ABC
- Product-Level Inventory Health Table

### 4️⃣ Supplier Risk & Lead Time Analysis
- Avg Risk Score
- Revenue Exposure %
- Inventory Exposure
- Supplier Risk vs Revenue Scatter Plot
- High-Risk Supplier Identification

---

## 🔍 Key Business Insights

- 42.76% of revenue exposed to high-risk suppliers
- $454M+ inventory tied to high-risk suppliers
- Supplier S04 identified as high-risk & high-revenue dependency
- Electronics category shows highest structural risk concentration
- Stable lead time indicates risk is structural, not logistical
- Revenue heavily concentrated among limited suppliers

---

## 💼 Business Recommendations

- Diversify supplier base to reduce concentration risk
- Reduce inventory capital tied to high-risk suppliers
- Implement supplier performance monitoring system
- Align procurement with ABC revenue strategy
- Develop alternate sourcing for high-risk categories

---

## 🧪 KPI Validation & Model Integrity

- Verified Revenue aggregation consistency
- Confirmed Inventory Turnover formula logic
- Validated DSI calculation
- Ensured correct relationship directions
- Tested ABC classification accuracy
- Removed circular dependencies
- Confirmed slicer & filter responsiveness

---

## 🛠 Tools Used

- Power BI Desktop
- DAX (Advanced Filter Context Handling)
- Star Schema Data Modeling
- Power Query (Data Cleaning & Transformation)
- Supply Chain Risk Modeling Concepts

---

## 🚀 Portfolio Value

This project demonstrates:

- End-to-end BI dashboard development
- Advanced DAX modeling
- Working capital & inventory analytics
- Supplier risk modeling
- Revenue concentration analysis
- Executive-level dashboard storytelling

It reflects the ability to move beyond descriptive reporting and deliver actionable supply chain intelligence.

---
>Note *For any questions or collaboration opportunities, feel free to reach out!*
