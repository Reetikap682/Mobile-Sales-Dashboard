Mobile Sales Dashboard – Power BI

Project Overview

This Power BI project presents a detailed analysis of mobile phone sales data across various Indian cities. It visualizes monthly sales trends, brand and model performance, city-wise distribution, transaction modes, and customer ratings.
The interactive dashboard empowers data-driven decision-making by providing clear insights into sales performance and consumer behavior.



📁 Key Features

🚀 KPIs: Total Sales, Quantity Sold, and Transactions

📅 Sales Trends by Month

🏙️ Quantity Sold by City (Map Visual)

📱 Brand and Model-wise Sales Performance

💳 Transaction Count by Payment Method

🌟 Customer Ratings by Model

🧹 Data Wrangling (Power Query)



Data cleaning and transformation steps:
Removed null or unnecessary columns
Converted data types (e.g., text, date, number)
Filtered invalid rows
Merged and shaped tables for analysis
Created additional calculated columns for better segmentation


🧮 DAX Measures
Custom measures were created using DAX to calculate KPIs:

Total Sales = SUM('Sales'[SalesAmount])  
Total Quantity = SUM('Sales'[Quantity])  
Total Transactions = COUNTROWS('Sales')  
Formatted Sales = FORMAT([Total Sales], "₹#,##0,,M")  
Calculated Sales = SUMX('Sales', 'Sales'[UnitPrice] * 'Sales'[Quantity])  



📊 Visuals Included

📊 Bar Chart: Total Sales by Month

🧭 Map: Quantity by City

📈 Column Chart: Sales by Model and Brand

🧾 Table: Ratings by Mobile Model

🧮 Cards: Total Sales, Quantity, Transactions, Avg Rating

🥧 Pie Chart: Transactions by Payment Method

📷 Dashboard Preview


📌 Tools & Technologies
Microsoft Power BI (Desktop)

Power Query for ETL

DAX for custom calculations


📂 Project Files
.pbix – Power BI project file

README.md – Project documentation

Data source files (CSV/Excel)


