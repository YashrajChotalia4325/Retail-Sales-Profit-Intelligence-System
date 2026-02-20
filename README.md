Retail Sales & Profit Intelligence System

A complete Retail Analytics solution built in Power BI to provide business-ready insights into sales performance, profitability, customer behavior, product performance, and geography analytics using a clean star schema, advanced DAX, and professional visuals.

## Project Overview

This dashboard transforms raw Superstore sales data into a fully functional analytics system covering:

 Executive overview  
 Time & trend intelligence  
 Product profitability analysis  
 Customer behavior insights  
 Geographic performance evaluation  

It’s designed to help decision-makers understand patterns, identify opportunities, and monitor business KPIs.

##  Contents

- `Retail-Sales-Profit-Intelligence-System.pbix` – Power BI Desktop report
- `Storytelling.md` – Project narrative & business explanation
- `pdf/` – Key visuals from report

## Key Features & Pages

### 1. Executive Overview
- Total Orders, Sales, Profit & Margin
- YoY growth
- Category & Region breakdown
- Top products snapshot

### 2️. Sales Intelligence
- Year-to-year monthly trend
- Seasonality analysis
- Regional comparison

### 3️. Product Analytics
- Sales & profit by category
- Profitability scatter matrix
- Top products by sales

### 4️. Customer Insights
- Top customers by revenue
- Segment contribution
- Customer profitability analysis

### 5️. Geography Analysis
- State & city performance
- Region contribution

## Data Model

This project uses a **Star Schema** with:
- **Fact_Sales** (Fact table)
- **Dim_Product**
- **Dim_Customer**
- **Dim_Geography**
- **Dim_Date** (marked as date table)

Relationships are single-direction Many-to-One, optimized for filtering and performance.

## DAX Measures Used

Examples include:
- `Total Sales`
- `Total Profit`
- `Profit Margin %`
- `YoY Growth %`
- `Average Sales`
- `Seasonality` by Month
- `Customer Contribution %`
- `Top N` ranking measures

---

## How to Use

1. Open the Power BI Desktop file (.pbix)  
2. Explore each page using navigation buttons  
3. Use slicers to filter by year / region / segment  
4. Hover over visuals for deeper detail
   
## About Me

Yashraj Chotalia – Aspiring Data Analyst  
 Pune, Maharashtra  
 Power BI | SQL | Analytics | Data Storytelling  
 chotaliayashraj12@gmail.com  
 LinkedIn: https://www.linkedin.com/in/yashraj-chotalia-755028278
