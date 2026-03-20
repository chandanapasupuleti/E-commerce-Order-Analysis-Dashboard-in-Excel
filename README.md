# E-commerce Order Analysis Dashboard in Excel

## Overview
This project is an end-to-end Excel-based data analysis of a real-world e-commerce dataset. The objective was to transform raw, multi-sheet operational data into a structured, analysis-ready dataset and build an interactive dashboard to generate business insights.

The project demonstrates core data analyst skills including data cleaning, data integration, exploratory analysis, and dashboard development using Microsoft Excel.

---

## Objectives
- Clean and standardize raw e-commerce datasets
- Handle missing and inconsistent data
- Integrate multiple datasets into a unified structure
- Analyze revenue, customer distribution, pricing, and delivery performance
- Build an interactive dashboard for business insights

---

## Dataset
The analysis is based on multiple related datasets:
- Orders
- Order Items
- Products
- Customers
- Product Category Translation

These datasets were originally independent and required consolidation for analysis.

---

## Tools & Techniques
- Microsoft Excel
- XLOOKUP for data integration
- IF / IFERROR for data cleaning and error handling
- TRIM and text standardization techniques
- Date transformation and feature engineering
- Pivot Tables and Pivot Charts
- KPI creation
- Slicers for interactivity
- Dashboard design and layout

---

## Data Preparation
- Cleaned each dataset individually to address missing values and inconsistencies
- Standardized categorical fields such as product categories and customer locations
- Handled missing values using a contextual approach:
  - Categorical fields → labeled as "Unknown"
  - Numerical fields → retained as blanks where appropriate
- Created derived metrics such as delivery time and delivery performance
- Integrated all datasets into a single master table using XLOOKUP

---

## Analysis & Dashboard
The final dashboard includes:

### Key Performance Indicators (KPIs)
- Total Revenue
- Average Price
- Average Delivery Days
- Total Order Items

### Analytical Views
- Revenue by Product Category
- Revenue by State
- Orders by State
- Delivery Performance Distribution
- Average Price by Category

### Interactivity
- Slicers for:
  - Order Year
  - Customer State
  - Delivery Performance

---

## Key Insights
- Top revenue-generating categories include **beleza_saude**, **relogios_presentes**, and **cama_mesa_banho**
- States **SP**, **RJ**, and **MG** contribute the highest revenue and order volume
- The majority of order items are delivered **on time or early**
- Significant variation exists in pricing across product categories, with **pcs** showing the highest average price

---

## Project Outcome
This project demonstrates the ability to:
- Work with messy, real-world data
- Perform data cleaning and validation
- Combine multiple datasets using lookup functions
- Build structured analytical models in Excel
- Develop interactive dashboards for decision-making

---

## Repository Contents
- `Ecommerce_Order_Analysis_Dashboard.xlsx` — Main project file
- `dashboard.docx` — Dashboard preview
- `raw_data`- Raw excel file
