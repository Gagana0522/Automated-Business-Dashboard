![Dashboard Preview](dashboard_screenshot.png)
[Download Dashboard (.pbix)](Business%20Intelligence%20Visualization.pbix)
[SQL View .sql](https://github.com/user-attachments/files/29092453/SQL.View.sql)
[executive_summary;.sql](https://github.com/user-attachments/files/29092447/executive_summary.sql)
[clean_executive_summary.csv](https://github.com/user-attachments/files/29092440/clean_executive_summary.csv)
 E-Commerce Business Analytics Pipeline & Dashboard

##  Project Overview
This project demonstrates an end-to-end data analytics pipeline. It takes raw transactional data from isolated tables, cleans and models it using advanced SQL    concepts, and visualizes key performance indicators (KPIs) in an interactive Power BI executive dashboard.

 ## The Business Insights & Visuals
* Gross Sales & Net Margins: Displays immediate top-line versus bottom-line performance ($1,590.00 Gross Sales vs. $635.00 Net Profit).
* Geographic Market Distribution:Identifies regional performance, highlighting India as a key high-value revenue driver.
* Operational Churn Analysis:  Monitors transaction lifecycles across Successful, Returned, and Cancelled flags to mitigate profit leakage.

 ## Tech Stack & Skills Used
* Database Management: MySQL Workbench (Star Schema architecture using Fact & Dimension models)
* Data Engineering & Analytics: Advanced SQL (INNER JOINs, Reusable Views, Aggregate Functions, and Window Functions like `DENSE_RANK()`)
* Business Intelligence: Power BI Desktop (Data imports, KPI cards, visual charts, and interactive filtering)

##  Database Architecture
Data was normalized into separate dimensions to ensure enterprise-grade data integrity before processing:
- `orders_fact`: Central transactional table.
- `users_dim`: Customer demographic details.
- `products_dim`: Product cost and retail listings.
