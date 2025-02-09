🛒 Optimizing Wine Store Data Management
📌 Project Overview
This project analyzes and optimizes the sales and stock management of a wine store. The goal is to ensure data consistency, identify outliers, and gain insights into sales performance.

📂 Dataset Description

ERP Table (erp.csv) – 825 rows, 5 columns

product_id → Unique product identifier
onsale_web → Indicates if the product is available for online sales
price → Product price
stock_quantity → Quantity in stock
stock_status → Availability status
Liaison Table (liaison.csv) – 825 rows, 2 columns

product_id → Unique product identifier
id_web → Web store identifier
Web Table (web.csv) – 1513 rows, 28 columns

Contains additional product information from the online store
🛠️ Data Processing & Analysis
✔️ Data Cleaning:

Removed duplicates and inconsistencies
Checked for missing values
Ensured consistency between stock data and sales
✔️ Exploratory Data Analysis (EDA):

Sales and stock distribution
Detection of outliers in price and stock quantity
Identification of sales trends
✔️ Merging & Validation:

Performed SQL-like joins to combine tables
Verified coherence between stock and revenue
📊 Key Insights & Findings

Certain high-priced items had very low sales → possible pricing issue
Some outliers in stock status indicated potential inventory mismatches
Data inconsistencies between ERP and Web data affected revenue accuracy
📎 Tools Used

Python (Pandas, Matplotlib, Seaborn) for data cleaning and analysis
SQL for data merging and consistency checks
Jupyter Notebook for visualization and reporting
