##  Sales Data Analysis Project


Introduction

This project analyzes a sales dataset covering transactions from January to April 2024.
The goal is to uncover product performance, regional contributions, customer insights, and sales trends using Python, Pandas, Matplotlib, and Seaborn.

Dataset Overview

- Columns: Date, Product, Quantity, Price, Customer_ID, Region, Total_Sales
- Rows: 100+ transactions
- Products: Phone, Laptop, Tablet, Monitor, Headphones
- Regions: North, South, East, West
Cleaning Steps
- Converted Date column to datetime format.
- Removed duplicates.
- Checked for missing values (none significant).
- Added derived fields (e.g., Month, Average Order Value (AOV)).

 Analysis & Metrics
 
Key Metrics

- Total Revenue by Product: Laptops and Tablets dominate sales.
- Total Revenue by Region: North and South regions lead.
- Average Order Value (AOV): ~₹28,000 per order.
- Top Customers: A few customers contribute disproportionately to revenue.
  
Patterns

- Product Leader: Laptops consistently generate the highest revenue.
- Regional Leader: North region is the strongest contributor.
- Trend: Sales steadily grow from January to March, continuing strong in April.
- Price vs Quantity: Weak correlation — customers buy across price ranges.

Visualizations

- Bar Chart: Total sales by product
- Pie Chart: Regional sales share
- Line Chart: Monthly sales trend
- Scatter Plot: Price vs Quantity relationship

 Insights
 
- Laptops and Tablets are the core revenue drivers.
- North and South regions should be priority markets.
- A small group of customers drives large revenue — opportunity for loyalty programs.
- Sales are stable and growing, suggesting strong demand.
- Price does not strongly deter purchases — premium products still sell well.
  
 Conclusion
 
This project demonstrates how data analysis + visualization can uncover actionable business insights.
By focusing on high-performing products and regions, and nurturing top customers, the business can maximize growth.
 Tools Used
- Python (Pandas, NumPy)
- Matplotlib & Seaborn (visualizations)
- Jupyter Notebook (analysis workflow)


 Folder Structure
sales-analysis/
├── data/          # raw & cleaned CSVs
├── notebooks/     # Jupyter notebooks
├── scripts/       # reusable Python scripts
├── visuals/       # charts & plots
├── report/        # final report (PDF/Markdown)
└── README.md      # project overview



