Superstore Sales Analysis & Power BI Dashboard

Overview:
 This project presents an end-to-end analysis of the Superstore dataset (from Kaggle), focusing on data cleaning, preprocessing, and interactive visual storytelling using Power BI. The final dashboard provides key business insights into sales, profit, customer behavior, and regional performance.

Files in the Repository:
 File	Description
 superstore.csv	Raw dataset from Kaggle
 cleaned_dataset.csv	Cleaned version after preprocessing
 superstore_dashboard.pbix	Power BI dashboard file
 dashboard_screenshots/	Folder with visual report screenshots
 summary.pdf	PDF report of dashboard insights
 README.md	Project overview and documentation 


Data Cleaning & Preprocessing
 Performed using Python (Pandas):
 Removed duplicates
 Handled missing values:
 Filled Country, Customer Name, Category, etc.
 Standardized text formats (e.g., lowercase, trimmed whitespace)
 Converted date columns to datetime
 Renamed columns for consistency (e.g., Order Date → order_date)
 Cast numeric columns to appropriate types
 Dashboard Highlights (Power BI)

 
Key Visuals:
 Sales by Region and Category
 Profit by Sub-Category (Treemap)
 Top 10 Customers by Sales
 Sales and Profit by Ship Mode
 Geographic Sales Map (by State)
 KPIs: Total Sales, Profit, Orders, Customers


Key Business Insights:
 Technology leads in sales, but Office Supplies has the highest volume of orders.
 Corporate Segment yields highest profit per order.
 California and New York are top revenue-generating states.
 Standard Class is the most used shipping method.
 Tables and Bookcases are consistently unprofitable.


Tools Used:
 Power BI (for visualization and dashboard creation)
 Python (Pandas) (for data cleaning)
 Excel (optional pre-inspection)


How to Use:
 Clone or download this repository.
 Open new_dataset.csv in Power BI or Excel to explore.
 Open superstore_dashboard.pbix in Power BI Desktop to view or edit the dashboard.
 Refer to summary.pdf or dashboard_screenshots/ for the final report.

 
Acknowledgements:
 Dataset: Kaggle - Superstore Sales



