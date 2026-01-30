📊 Business Performance Analysis

SQL • Python • Power BI | End-to-End Business Analytics Project

🔍 Project Summary

This project delivers a complete business performance analysis pipeline, combining SQL-based data extraction, Python-based analysis, and Power BI visualization to generate actionable business insights.

The repository demonstrates how a data analyst works in real industry settings — from raw transactional data to executive-ready dashboards and reports.

⭐ Key Highlight:
SQL and Python code are both implemented inside a single Jupyter Notebook, ensuring a seamless, end-to-end analytical workflow.

🎯 Business Objectives

The analysis aims to help decision-makers answer key business questions such as:

Which vendors are most profitable?

Are some products being sold at a loss?

How do freight costs impact gross profit?

Which products have poor stock turnover?

Where can we optimize pricing and vendor selection?


🗂️ Dataset Description

The data is distributed across multiple relational tables:

Purchases Table
Contains vendor purchase transactions including quantity and dollar amounts.

Purchase Price Table
Stores product-wise actual and purchase prices (unique by vendor & brand).

Vendor Invoice Table
Aggregates purchase data and includes freight costs.

Sales Table
Records sales transactions with quantity sold, selling price, and revenue.

Because the data is fragmented, a vendor-wise summary table is created using SQL joins and aggregations.

🛠 Tools & Technologies
•	SQL – Data extraction and querying
•	Python (Pandas, NumPy, Matplotlib, Seaborn) – Data cleaning, EDA, and analysis
•	Jupyter Notebook – SQL and Python code written together in a single notebook
•	Power BI – Interactive dashboards and visual analytics

📂 Project Files
•	Business-Performance-Analysis.ipynb
Contains the complete workflow with SQL queries and Python code combined in one Jupyter Notebook, including data cleaning, exploratory data analysis, correlation analysis, and statistical testing.
•	Business-Performance-Analysis.pdf
A detailed insights report summarizing EDA results, correlations, research questions, hypothesis testing, and final business recommendations.
•	Business-Performance-Analysis.pbix
Power BI dashboard file showcasing interactive visualizations for sales, inventory, profit, and vendor performance.
•	Business-Performance-Analysis.png
Screenshot preview of the Power BI dashboard.

🧠 Approach & Methodology
1️⃣ SQL Data Engineering

Complex joins across multiple tables

Vendor-wise aggregation of:

Purchase quantity & cost

Sales quantity & revenue

Freight costs

Actual product prices

Optimized summary table created for faster analytics & dashboarding

2️⃣ Exploratory Data Analysis (Python)

Distribution analysis of financial metrics

Detection of:

Negative profits

Zero sales despite purchases

High-value outliers

Business interpretation of anomalies and risks

📈 Key Insights

🚨 Negative Gross Profit
Some vendors/products are selling at a loss due to high costs or poor pricing strategies.

📦 Unsold Inventory
Products with purchase quantity but zero sales indicate slow-moving or obsolete stock.

🚚 Freight Cost Inefficiencies
Freight costs vary drastically, highlighting potential logistics optimization opportunities.

🔄 Extreme Stock Turnover
Some products sell unusually fast, while others remain idle indefinitely.

🔍 Key Analysis & Insights
•	Identified loss-making transactions with negative gross profit and profit margins
•	Detected unsold inventory contributing to $2.71M in blocked capital
•	Found strong correlation between purchase quantity and sales quantity, indicating efficient stock conversion
•	Observed weak correlation between purchase price and profitability
•	Identified over-reliance on top vendors contributing ~66% of total purchases
•	Discovered higher profit margins among low-performing vendors with lower sales volume

📊 Statistical & Business Findings
•	Bulk purchasing results in ~72% lower unit costs
•	High stock turnover does not always lead to higher profitability
•	Hypothesis testing confirms a significant difference in profit margins between top and low-performing vendors

✅ Final Recommendations
•	Optimize pricing strategies for low-sales, high-margin brands
•	Reduce dependency on a limited number of vendors
•	Leverage bulk purchasing while maintaining margin control
•	Improve management of slow-moving inventory
•	Strengthen marketing and distribution for underperforming vendors

🎯 Outcome
This project demonstrates an end-to-end business analytics workflow using SQL, Python, and Power BI, highlighting practical data analysis, statistical reasoning, and visualization skills relevant to Data Analyst roles.

📌 Explore the notebook, report, and dashboard to understand the complete analysis and insights.

