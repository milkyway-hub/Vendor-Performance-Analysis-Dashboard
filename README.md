# Vendor Performance Analysis Dashboard

## 📊 Project Overview
This project analyzes vendor performance using sales, purchase, and inventory datasets. The goal is to identify top-performing vendors, evaluate profitability, and analyze inventory efficiency using business analytics.

The project integrates **Python for data processing, SQLite for database storage, and Power BI for interactive data visualization**.

---

## 🎯 Project Objectives
- Analyze vendor sales and purchase performance
- Identify the most profitable vendors
- Measure vendor profitability using profit margin
- Evaluate inventory efficiency using stock turnover
- Build an interactive Power BI dashboard for business insights

---

## 🛠 Tools & Technologies
- Python (Pandas, NumPy)
- SQLite Database
- Jupyter Notebook
- Power BI
- GitHub

---
## 📁 Project Structure

Vendor-Performance-Analysis/
│
├── Data/
│   ├── sales_data.csv
│   ├── purchase_data.csv
│   ├── vendor_invoice_data.csv
│   ├── purchase_prices_data.csv
│   ├── begin_inventory.csv
│   ├── end_inventory.csv
│   └── inventory_database.db  (Not included due to size & confidentiality)
│
├── notebooks/
│   ├── Exploratory_Data_Analysis.ipynb
│   └── Vendor_Performance_Analysis.ipynb
│
├── scripts/
│   ├── ingestion_db.py
│   └── get_vendor_summary.py
│
├── dashboards/
│   └── vendor_performance_dashboard.pbix
│
├── logs/
│   └── ingestion_db.log
│
├── README.md


## 📂 Dataset

This project uses multiple datasets related to vendor sales, purchases, and inventory.

Some processed or smaller datasets used in the analysis are included in this repository. However, the main dataset belongs to the vendor and contains large-scale business data (10M+ records) stored in the **inventory database file**.

Due to confidentiality and size limitations, the full dataset is not included in this repository.

For demonstration purposes, selected dataset files are provided, and additional sample data can be accessed using the following Google Drive folder:

Dataset Link:  
https://drive.google.com/drive/folders/1QGAjNkewixiQpPNk8GRPcbt3peynrxEK?usp=sharing

Files included in the dataset:
- Sales Data
- Purchase Data
- Vendor Invoice Data
- Purchase Prices Data
- begin inventory
- end inventory

---

## 🔄 Project Workflow

This project follows a structured **data analytics pipeline** to analyze vendor performance and generate business insights.

### 1️⃣ Data Collection
Business datasets including **Sales Data, Purchase Data, Vendor Invoice Data, Purchase Prices Data, Begin Inventory, and End Inventory** were collected from vendor business records.

### 2️⃣ Data Ingestion
Large CSV datasets were ingested into a **SQLite database** using Python scripts.  
Chunk-based data processing was implemented to efficiently handle large datasets.

### 3️⃣ Data Storage
All datasets were stored in a centralized database file:

`inventory_database.db`

This database allows efficient querying and integration of multiple datasets.

### 4️⃣ Exploratory Data Analysis (EDA)
EDA was performed using **Jupyter Notebooks** to:
- Understand data distribution
- Detect missing values
- Identify trends and patterns
- Clean and prepare the data for analysis

### 5️⃣ Vendor Performance Analysis
Vendor performance was evaluated using key business metrics such as:
- Total Sales by Vendor
- Purchase Costs
- Profit Margins
- Inventory Levels
- Vendor Contribution to Revenue

### 6️⃣ Data Visualization
An interactive **Power BI Dashboard** was created to visualize:

- Vendor Sales Performance
- Profit Margin Analysis
- Inventory Trends
- Purchase Patterns
- Vendor Revenue Contribution

### 7️⃣ Business Insights
The dashboard helps businesses:
- Identify **top-performing vendors**
- Optimize **purchasing decisions**
- Improve **inventory management**
- Monitor **profitability and sales trends**
  
---

## 📊 Key Metrics

The following business metrics are calculated:

- Total Sales
- Total Purchase Cost
- Gross Profit
- Profit Margin
- Stock Turnover
- Sales-to-Purchase Ratio

---

## 📈 Power BI Dashboard

The Power BI dashboard includes the following visualizations:

- Top Vendors by Sales
- Profit by Vendor
- Profit Margin Analysis
- Stock Turnover Analysis
- Sales vs Purchase Scatter Plot
- Vendor Sales Contribution

---

## 🔍 Key Insights

- A small number of vendors contribute a large percentage of total sales.
- Some vendors generate high revenue but lower profit margins.
- Vendors with higher stock turnover demonstrate better inventory efficiency.

---

## 🚀 Future Improvements
- Time-based sales trend analysis
- Vendor ranking model
- Machine learning for vendor performance prediction
