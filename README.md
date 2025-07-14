Blinkit City Insights – SQL-Based Inventory and Sales Estimation

This project demonstrates advanced SQL skills by generating a derived table called blinkit_city_insights from raw Blinkit product listing data. The goal is to estimate product-level sales performance by city, based on inventory changes over time.

📌 Key Features:
Written entirely in PostgreSQL using CTEs and window functions
Estimated est_qty_sold based on inventory deltas across timestamps
Aggregated sales metrics (est_sales_sp, est_sales_mrp) at SKU & city level
Calculated on-shelf availability metrics (wt_osa, wt_osa_ls)
Final results exported to CSV and fully ATS-optimized SQL script

📂 Tech Stack:
PostgreSQL
SQL Shell / psql
CSV data handling

📈 Skills Demonstrated:
Data wrangling with SQL
Inventory-based sales estimation
Complex joins and aggregation logic
Window functions (LAG)
Performance-focused data modeling
