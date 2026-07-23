# 📊 Sales Analytics Dashboard
### Adventure Works | Power BI Business Intelligence Case Study

An end-to-end Business Intelligence solution built in Microsoft Power BI to transform transactional sales data into actionable business insights. The project demonstrates data preparation, dimensional modeling, DAX development, interactive dashboard design, and business analysis to support data-driven decision-making.

---

# Business Problem

*Adventure Works* generated large volumes of transactional data, and needed a centralized solution for monitoring performance across products, customers, and regions.

This project consolidates sales, profitability, customer, regional, and product data into an interactive reporting solution that uncovers performance trends, identifies growth opportunities, and delivers actionable business insights.

---

# Business Objectives

- Monitor key business KPIs
- Track monthly sales performance
- Identify high-performing products
- Analyze customer segments
- Evaluate regional performance
- Generate actionable business recommendations

---

# Dashboard Preview

*(Dashboard screenshots will be added here.)*

---

# Data Model

The report is built using a dimensional data model consisting of:

- Sales Fact Table
- Returns Fact Table
- Calendar Dimension
- Product Dimension
- Customer Dimension
- Territory Dimension

The model follows a star schema approach with a normalized Product hierarchy for efficient filtering and analytical performance.

*(Data model image will be inserted here.)*

---

# Dataset

Dataset: Adventure Works (Microsoft Sample Dataset)

The dataset contains transactional sales and returns data, customer demographics, product information, territories, and calendar data used to simulate real-world business reporting scenarios.

## Data Limitations

### 1. Static Product Pricing

Product prices remained constant throughout the analysis period. As a result, pricing-focused analyses such as **price elasticity**, **price optimization**, and **revenue responsiveness to price changes** were outside the scope of this project.

### 2. Historical Data Coverage

The dataset contains transactions only through **2022**, while the Calendar dimension uses a **dynamic rolling date table**. To prevent future dates from affecting time intelligence calculations, DAX measures were designed to validate only dates containing transaction data, ensuring accurate **Month-to-Date (MTD)**, **Quarter-to-Date (QTD)**, **Year-to-Date (YTD)**, and **Month-over-Month (MoM)** reporting.

---

# Technical Implementation

## Data Preparation

- Transformation of data in Power Query
- Data cleansing
- Data type optimization
- Normalization of Product Dimension
- Used DAX to derive Calendar Dimension Table

## Data Modeling

- Star schema design with Normalised Product Dimension
- Fine Tuned the Table Connections
- Active and Inactive Relations

## DAX Measures

Examples include:

- Sales Revenue
- Net Profit
- Profit Margin
- Return Rate
- Month-over-Month Growth
- Running Totals
- Running Averages
- Dynamic Rankings
- KPI Measures

---

# Key Business Insights

- Revenue is concentrated among top-performing products.
- Accessories deliver the highest profitability.
- Bikes lead sales but lag in profit margins.
- Regional performance reveals optimization opportunities.

---

# Business Recommendations

| Recommendation | Expected Business Impact |
|---------------|--------------------------|
| Expand investment in high-margin products | Increase profitability |
| Optimize Bike pricing and costs | Improve profit margins |
| Prioritize top-performing products | Maximize revenue growth |
| Improve regional performance | Reduce returns and increase profitability |

---

# Tools & Technologies

- Microsoft Power BI
- DAX
- Power Query
- Data Modeling
- Microsoft Excel

---

# Skills Demonstrated

- Business Intelligence
- Data Visualization
- Dashboard Development
- Data Modeling
- DAX
- Power Query
- KPI Design
- Business Analysis
- Executive Reporting
- Strategic Recommendations
- Data Storytelling

---

# Project Files

- Power BI Report (.pbix)
- Portfolio PDF
- Dashboard PDF
- Dashboard Images

---

# Author

**Debjyoti Roy**

Economics Graduate | Aspiring Data Analyst

