#BlinkIT Sales Analysis

#Project Overview

This project presents a comprehensive analysis of BlinkIT's retail sales data. It explores product performance, customer preferences, and outlet effectiveness using SQL for data processing, Excel and Power BI for visualization, and Python for data wrangling and automation.

📁 Dataset Description
Table Name: Blinkit_data

Columns:

Item_Identifier: Unique item code

Item_Weight: Weight in kg

Item_Fat_Content: Fat content type (Low Fat/Regular)

Item_Visibility: Shelf visibility percentage

Item_Type: Category (e.g., Dairy, Snacks)

Outlet_Identifier: Unique outlet code

Outlet_Establishment_Year: Year outlet was opened

Outlet_Size: Small/Medium/High

Outlet_Location_Type: Tier 1/2/3

Outlet_Type: Supermarket Type1/2/3 or Grocery

Sales: Sales value in INR

Rating: Customer rating (1 to 5 scale)

🔧 Tools & Technologies Used
SQL: Data cleansing, transformation, aggregations, and insights

Excel: Data validation, pivot tables, and exploratory calculations

Power BI: Dynamic dashboards with filters and drill-down capability

Python:

Pandas for EDA

Matplotlib/Seaborn for visualizations

SQLAlchemy for SQL integration (optional)

📊 Key Insights
Fat Content: Standardized inconsistent fat type entries (LF, low fat, reg)

Item Type Analysis: Dairy and Snacks top the sales chart

Outlet Trends: Tier 1 locations and Supermarket Type1 dominate in revenue

Establishment Year Impact: Older outlets show higher average ratings

Sales Contributions:

By outlet size and type

By item fat content across regions (via pivoting)

🚀 #Getting Started
Clone this repo.

Load Blinkit_data into a SQL database (PostgreSQL/MySQL/SQLite).

Run the SQL scripts in /SQL folder.

Open /PowerBI/blinkit_dashboard.pbix for visual exploration.

Use analysis.py to run programmatic analysis with Python.



📌 Conclusion
The project enables data-driven decision-making for inventory, marketing strategies, and outlet expansions using well-integrated analytical tools.
