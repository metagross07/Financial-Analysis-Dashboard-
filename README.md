# Financial Analysis Dashboard

🚀 Project Overview

This project focuses on building a scalable, well-structured Power BI dashboard that delivers meaningful financial insights. It covers data preparation, modeling, DAX-based KPIs, time intelligence, and dashboard design, following industry best practices.

The dashboard enables stakeholders to:

- Monitor financial performance
- Compare year-over-year trends
- Identify high-performing and loss-making areas
- Make data-driven business decisions

🎯 Project Objectives

- 🔹 Import and prepare data using Power Query Editor
- 🔹 Ensure data quality, consistency, and correct data types
- 🔹 Build a robust data model with a dedicated Date table
- 🔹 Create financial KPIs using clean and reusable DAX measures
- 🔹 Apply year-over-year time intelligence analysis
- 🔹 Design a professional, insight-driven dashboard suitable for executives

🧰 Tools & Technologies

- 🟡 Power BI Desktop – Dashboard development & reporting
- 🔧 Power Query Editor – Data cleaning & transformation
- 📐 DAX (Data Analysis Expressions) – Measures & calculations
- 📊 Financials Sample Dataset – Built-in Power BI dataset

🔄 Data Preparation

Data preparation was performed using Power Query Editor to ensure accuracy before analysis:

- 📥 Loaded built-in sample data (no external files required)
- 🔍 Performed column-by-column inspection
- 🔤 Validated categorical fields (segment, country, product, discount band)
- 🔢 Corrected numeric data types (e.g., unit sales as whole numbers)
- ✏️ Renamed tables and columns for clarity and maintainability

✔️ Result: Clean, analysis-ready dataset

🧱 Data Modeling

A well-structured data model was created to support advanced analysis:

- 📅 Built a dedicated Date Table using DAX
- ⚙️ Used CALENDAR / CALENDARAUTO for dynamic date generation
- ➕ Added Year, Month Number, and Month Name attributes
- 🔗 Established relationships between fact table and date table

✔️ Enabled time intelligence and scalable reporting

📐 DAX Measures & KPIs

📊 Core Financial Measures

- 💰 Total Sales
- 📦 Total Units Sold
- 📈 Total Profit
- 📊 Profit Margin (%)
- 🏷️ Total Discount Offered

⏳ Time Intelligence Measures

- ⏪ Sales Last Year
- ⏪ Orders Last Year
- ⏪ Profit Last Year
- ⏪ Profit Margin Last Year
- ⏪ Discount Offered Last Year

🧠 Key DAX Functions Used

SUM, DIVIDE, CALCULATE, DATEADD

📊 Dashboard Visualizations

The dashboard includes multiple interactive visuals designed for clarity and insight:

- 🟩 KPI Cards – Current vs Previous Year comparison
- 📊 Bar Charts – Country-wise & Segment-wise analysis
- 📈 Line Chart – Sales trend by Year & Month
- 🍩 Donut Chart – Discount distribution by discount band
- 🥇 Top 3 Products – Highlighted using DAX + conditional formatting
- 🧮 Matrix Visual – Profit margin by Segment & Product with icon indicators

🎨 Dashboard Design & UX

- 🎨 Custom theme (colors, fonts, transparency)
- 🧱 Structured layout using shapes & text boxes
- 🧭 Clear headers and logical section separation
- 👁️ High readability with consistent formatting

📐 Executive-friendly and presentation-ready design

🔍 Key Insights Enabled

- 📈 Year-over-Year performance comparison
- ⚠️ Identification of loss-making segments and products
- 🏆 Highlighting top-performing products
- 💰 Analysis of discount concentration
- 🌍 Country-wise and segment-wise performance trends


---

*This README was updated on 2026-01-14 by metagross07 via GitHub Copilot.*
