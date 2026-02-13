# Vendor-Performance-Data-Analytics
🚀 Vendor Performance Analysis: End-to-End Data Engineering & Analytics
📊 Project Overview
This project focuses on optimizing retail profitability and supply chain efficiency through a deep dive into vendor performance. By processing and integrating 12.8 million records of sales and procurement data, this analysis identifies high-value suppliers, evaluates inventory turnover, and uncovers underperforming brands.
🛠️ Tech Stack

    Language: Python 3.x
    Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scipy (Stats)
    Database: SQL, SQLite3
    Visualization: Power BI
    Documentation: Microsoft Word

📁 Dataset Architecture
Kaggle Datasets : https://www.kaggle.com/datasets/gayathrisparkleai/vendor-performance-analysis
The analysis is built upon six interconnected datasets (available on Kaggle):

    Sales: 12.8M+ transaction records.
    Purchases: Procurement history.
    Beginning/Ending Inventory: Stock level snapshots.
    Purchase Prices: Official vendor pricing lists.
    Vendor Invoices: Including freight and shipping costs.

⚙️ Project Workflow
1. Data Engineering & Ingestion

    Processed 1.3GB+ of raw CSV data using Pandas.
    Built a persistence layer in SQLite to manage relational integrity.
    Automated table migration with validation checks to prevent data duplication.

2. Analytical Data Warehousing (SQL)

    Used Advanced SQL Joins and CTEs to create a unified vendor_sales_summary table.
    Integrated inflow (Purchases), outflow (Sales), and overhead (Freight) into a single analytical layer.

3. KPI & Feature Engineering
Developed custom metrics to evaluate business health:

    Gross Profit & Margin: Revenue minus Cost of Goods Sold.
    Stock Turnover: Efficiency of selling through purchased inventory.
    Sales-to-Purchase Ratio: Measuring ROI on inventory investment.

4. Exploratory Data Analysis (EDA)

    Statistical Profiling: Distribution analysis of pricing and quantities.
    Correlation Analysis: Identifying relationships between bulk purchasing and unit costs.
    Vendor Ranking: Identifying the Top 10 vendors by frequency and sales volume.

📈 Key Insights & Results

    Successfully reconciled procurement vs. sales data to identify profit leakage.
    Identified specific vendors with high freight-to-total-dollar ratios.
    Provided a roadmap for inventory reduction to lower holding costs.

📄 Final Deliverables

    Jupyter Notebook: Full Python/SQL pipeline.
    Power BI Dashboard: Interactive visualization of vendor KPIs.
    Written Report: A formal business analysis document prepared in Word.
