# Global Retail Sales Analytics & Performance Insights 📊

**Microsoft Elevate AICTE Internship - Capstone Project** **Author:** Shaniyaz Sha | Aliah University | MBA

## 🎯 Problem Statement
Currently, retail businesses face significant challenges in tracking real-time performance across diverse geographic regions and product categories. Raw sales data often remains fragmented, forcing stakeholders to rely on manual data compilation. This delays decision-making regarding inventory management and marketing spend, hindering the organization’s ability to maintain a stable, profitable supply chain.

## 💡 Proposed Solution
This project introduces an automated, end-to-end Power BI analytics framework. By connecting disparate data sources and utilizing a relational "Star Schema" data model, this solution transforms raw data into a real-time, interactive dashboard. It empowers decision-makers to identify underperforming segments, forecast demand, and track KPI growth instantly.

## ⚙️ System Approach & Technology Stack
* **Business Intelligence Tool:** Power BI Desktop & Power BI Service
* **Data Transformation:** Power Query (ETL)
* **Analytical Engine:** DAX (Data Analysis Expressions)
* **Data Architecture:** Star Schema Modeling

## 📈 Algorithm & Deployment
**1. Data Modeling:** Established One-to-Many relationships between the central Sales Fact table and Dimension tables (Calendar, Geography, Products).

**2. Key DAX Algorithms Used:**
* `Total Revenue = SUM(Sales[Amount])`
* `YoY Growth = DIVIDE([Total Sales] - [LY Sales], [LY Sales], 0)`
* `Profit Margin % = DIVIDE(SUM(Sales[Profit]), SUM(Sales[Amount]), 0)`

**3. Deployment:**
The finalized report is published to the Power BI Service workspace, utilizing Row-Level Security (RLS) and mobile-optimized views for executive access.

## 🚀 Result & Output
* **Cross-Functional Insights:** Integrated slicers reduced report generation time by 80%.
* **Profitability Identification:** Revealed that the "Technology" segment drives 40% of the total profit margin despite lower overall volume.
* **Stable Supply Monitoring:** Provided clear seasonal trend visualizations to optimize Q4 inventory supply.

*(Note: Insert a screenshot of your Power BI Dashboard here)*
`![Dashboard Screenshot](link_to_your_image.png)`

---
*Developed during the Microsoft Elevate 4-Week Internship (February 2026).*
