# Financial Analysis Dashboard

📌 Project Overview
The Financial Analysis Dashboard is an interactive Business Intelligence project developed using Microsoft Power BI. It transforms sample financial data into an organized reporting solution that helps users monitor performance, compare results across time periods, and explore business performance across multiple dimensions.

The project demonstrates an end-to-end BI workflow, including data preparation, data modeling, DAX calculations, time-intelligence analysis, and dashboard design. The report allows users to analyse financial results by country, segment, product, discount band, and date.

The overall goal is to make financial information easier to understand and help stakeholders investigate trends, identify strong and weak performance areas, and support data-informed decisions.

🎯 Project Objectives
- Import and prepare financial data using Power Query Editor.
- Validate data quality, consistency, and column data types.
- Build a structured data model supported by a dedicated Date table.
- Develop reusable DAX measures for key financial metrics.
- Perform year-over-year (YoY) comparisons using time-intelligence functions.
- Design an interactive, executive-friendly dashboard that communicates key performance indicators and trends.

🧰 Tools and Technologies
Tool / Technology	Purpose
Power BI Desktop	Data modeling, report development, interactive visualizations, and dashboard design
Power Query Editor	Data inspection, cleaning, transformation, and data-type validation
DAX (Data Analysis Expressions)	KPI calculations, filter-context analysis, and time intelligence
Power BI Financials Sample Dataset	Sample data source used to build and analyse the report

📂 Dataset
This project uses the Financials sample dataset available in Power BI. The dataset contains financial information that can be analysed across dimensions such as:
- Time: Date, month, and year
- Geography: Country
- Business: Segment and product
- Discounting: Discount band
- Financial metrics: Sales, profit, discounts, and units sold
Note: This is a portfolio and learning project based on sample data. The dataset does not represent the actual financial performance of a real organization. No external dataset file is required when using the built-in Power BI Financials sample.

🔄 Project Workflow
The dashboard was developed through three main stages: data preparation, data modeling, and DAX measure development.
1. Data Preparation
Data preparation was performed in Power Query Editor to ensure that the dataset was consistent and ready for analysis.
- Loaded the built-in Financials sample dataset into Power BI.
- Inspected columns and reviewed the available fields.
- Validated categorical attributes such as segment, country, product, and discount band.
- Checked and corrected data types for date and numerical columns.
- Set Units Sold to a whole-number data type.
- Renamed tables and columns where appropriate to improve clarity and maintainability.
Outcome: A clean and analysis-ready dataset for reporting and further modeling.
2. Data Modeling
A dedicated Date table was created to support date-based filtering and time-intelligence calculations.
- Generated a continuous date range using DAX CALENDAR or CALENDARAUTO.
- Added calendar attributes such as Year, Month Number, and Month Name.
- Established a relationship between the Date table and the financial fact table through the date field.
- Used the Date table as the foundation for previous-year calculations and date-based report filtering.
Modeling best practices applied:
- Marked the Date table as the model's date table in Power BI.
- Sorted Month Name by Month Number to maintain chronological month order.
- Used the Date table consistently for time-based analysis.
3. DAX Measures and KPIs
Reusable DAX measures were developed to calculate financial KPIs and support consistent reporting across different filters and visualizations.
Core Financial Measures
Measure	Description
Total Sales	Calculates total sales for the selected filters and reporting period.
Total Units Sold	Calculates the total quantity of units sold.
Total Profit	Calculates the total profit generated.
Profit Margin (%)	Calculates profit as a percentage of sales.
Total Discounts	Calculates the total discount value offered.


Profit Margin is calculated as Total Profit divided by Total Sales. The DAX DIVIDE function can be used to handle cases where the denominator is zero.
Previous-Year Measures
The report also includes previous-year measures to compare performance against the corresponding period in the prior year:
- Sales Last Year
- Units Sold Last Year
- Profit Last Year
- Profit Margin Last Year
- Discounts Last Year
Measure naming note: The Financials sample dataset contains a Units Sold field rather than a dedicated order-count field. Therefore, the previous-year quantity measure is referred to as Units Sold Last Year, not Orders Last Year.

DAX Functions Used
DAX Function	Purpose
SUM	Aggregates values in numeric columns.
DIVIDE	Performs division safely, including when the denominator is zero.
CALCULATE	Evaluates an expression under a modified filter context.
DATEADD	Shifts a date range to support time-intelligence calculations.


📊 Dashboard Features and Visualizations
The report combines KPI cards, charts, and a matrix to provide an interactive view of financial performance.
Visualization	Purpose
KPI Cards	Display key financial metrics and current-versus-previous-year comparisons.
Country-wise Bar Chart	Compares financial performance across countries.
Segment-wise Bar Chart	Compares performance across business segments.
Year-and-Month Line Chart	Displays sales trends over time.
Discount-band Donut Chart	Shows the distribution of discounts across discount bands.
Top 3 Products	Highlights the top-performing products using DAX logic and conditional formatting.
Segment and Product Matrix	Compares profit margins across segments and products using icon indicators.


Report filters and visual interactions allow users to explore the data by relevant dimensions and investigate patterns in greater detail.
🎨 Dashboard Design
The dashboard uses a clean, executive-oriented layout, with an emphasis on readability and a consistent visual hierarchy.
- Applied a custom theme with coordinated colours, fonts, and transparency.
- Organized the report using shapes, text boxes, and clearly defined sections.
- Grouped related KPIs and charts to make the information easier to scan.
- Used consistent number formats, labels, and chart styling.
- Applied conditional formatting and icon indicators to emphasize important values.
🔍 Key Insights and Analysis
The dashboard enables users to investigate questions such as:
- How does current-year financial performance compare with the previous year?
- How have sales and profit changed over time?
- Which countries, segments, and products show comparatively strong or weak performance?
- How does profit margin vary across segment and product combinations?
- Which discount bands account for the largest share of discounts?
- Which products rank among the top performers?
These analyses help surface trends and areas that may require attention. Findings should be interpreted alongside business context before making operational or financial decisions.

