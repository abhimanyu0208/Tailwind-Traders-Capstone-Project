# Tailwind-Traders-Capstone-Project
End-to-end Power BI capstone project for Tailwind Traders. Includes preparing and transforming sales data, configuring data sources, designing a snowflake schema data model, creating DAX calculations, and building interactive reports and executive dashboards for global sales and profit insights.
"Tailwind Traders Capstone Project
📊 Project Overview

This capstone project demonstrates how to prepare, model, and analyze sales and profit data for Tailwind Traders using Power BI Desktop. The project walks through data preparation in Excel, source configuration, data modeling, DAX calculations, and the design of an executive-ready dashboard.

The end result is a Power BI Desktop report (.pbix) that provides actionable insights into Tailwind Traders’ global sales performance.

🛠️ Project Steps
1. Prepare Sales Excel Data

Created Gross Revenue, Total Tax, and Net Revenue columns in Excel.

Verified data correctness by comparing min, max, and average values for the first ten records.

Ensured clean, structured sales data for import into Power BI.

2. Configure Data Sources in Power BI

Imported Sales, Purchases, and Countries tables.

Applied correct data types for each column.

Used a Python script to transform and load Currency Exchange Rates data.

Verified data quality by checking column validity, statistics, and filtering refunded purchases.

3. Design & Develop the Data Model

Built a snowflake schema to connect Sales, Purchases, Countries, and Exchange data.

Established relationships:

Countries ↔ Exchange Data (1:1)

Sales ↔ Countries (Many:1)

Purchases ↔ Sales (1:1)

Calendar ↔ Purchases (Many:1)

Sales in USD ↔ Sales (Many:1)

Created a Calendar table using DAX for time-based reporting.

Built a Sales in USD calculated table with exchange rate conversions for Gross Revenue, Net Revenue, and Total Tax.

4. Develop Executive Report in Power BI

Designed an Executive Dashboard including:

Sales Overview with KPIs, regional breakdown, and sales trends.

Profit Overview with margin analysis and profitability by country.

Global Insights showing sales distribution across regions in USD.

Optimized report visuals and added interactive slicers for better usability.

✅ Skills Demonstrated

Data preparation in Excel

Power BI data source configuration

Data modeling & snowflake schema design

DAX calculations (Calendar table, Sales in USD conversions)

Report building & executive dashboard design

📂 Files in Repository

Tailwind Traders Sales.xlsx → Prepared sales data

Tailwind Traders Report.pbix → Final Power BI project file

🚀 Conclusion

This project showcases how Power BI Desktop can be used end-to-end — from data preparation and modeling to visualization — to generate actionable insights. Tailwind Traders now has a unified reporting solution to track global sales and profits in USD, enabling informed decision-making."
