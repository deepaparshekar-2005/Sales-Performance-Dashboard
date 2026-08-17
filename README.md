# 📊 Sales Performance Dashboard

## 🌐 Live Dashboard
leafy-banoffee-26ffa3.netlify.app

## 📌 Project Overview

The Sales Performance Dashboard is a data analytics project that analyzes online retail sales data to understand revenue, product performance, regional sales, and customer purchasing behavior.

The project uses Python for data cleaning and analysis and Power BI for interactive dashboard visualization.

## 🎯 Objectives

- Analyze overall sales performance
- Identify top-performing products
- Analyze monthly revenue trends
- Compare sales performance across countries
- Understand customer purchasing behavior
- Create an interactive sales dashboard
- Generate useful business insights

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Power BI
- DAX


## 🗂️ Dataset

The project uses the Online Retail dataset containing transaction-level sales information.

The dataset contains the following fields:

- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

## 🧹 Data Cleaning & Preprocessing

The raw dataset was cleaned and prepared for sales analysis.

The following preprocessing steps were performed:

- Removed duplicate records
- Removed records with missing product descriptions
- Removed invalid Quantity values
- Removed invalid UnitPrice values
- Created a Revenue column

### Revenue Calculation

Revenue was calculated using:

`Revenue = Quantity × UnitPrice`

## 📊 Key Performance Indicators

The dashboard includes the following key performance indicators:

- Total Revenue
- Total Orders
- Total Quantity Sold
- Average Order Value
- Unique Products
- Unique Customers
- Unique Countries

## 📈 Dashboard Features

The Power BI dashboard provides an interactive view of sales performance.

### Monthly Revenue Trend

Shows the change in revenue over time.

### Top 10 Products by Revenue

Identifies the products generating the highest revenue.

### Top 10 Countries by Revenue

Compares revenue performance across different countries.

### Interactive Filters

The dashboard includes filters for:

- Country
- Year
- Product Description

## 📁 Project Structure

```text
Sales-Performance-Dashboard/
│
├── dataset/
│   └── cleaned_sales_data.csv
│
├── notebooks/
│   └── Sales_Performance_Analysis.ipynb
│
├── powerbi/
│   └── Sales_Performance_Dashboard.pbix
│
├── report/
│   └── Business_Insights.pdf
│
├── README.md
└── requirements.txt

## 🚀 How to Run

### Python Analysis

Install the required Python libraries:

```bash
pip install pandas numpy matplotlib openpyxl jupyter

Open the Jupyter Notebook:

jupyter notebook

Then open:

notebooks/Sales_Performance_Analysis.ipynb

Power BI Dashboard

Open the Power BI file:

powerbi/Sales_Performance_Dashboard.pbix

The dashboard provides interactive sales analysis using KPIs, charts, and filters.
## 💡 Business Insights

The analysis provides insights into:

- Monthly revenue performance and trends
- Top-performing products by revenue
- Top-performing products by quantity sold
- Revenue contribution by country
- High-value customers based on revenue
- Customer purchasing behavior
- Overall sales performance

These insights can help identify high-performing products, important markets, and valuable customer segments.

## 👩‍💻 Author

Deepa Anand Parshekar
BE – Information Science and Engineering

## 📌 Project Deliverables

- Python data analysis notebook
- Cleaned sales dataset
- Interactive Power BI dashboard
- Business Insights report
- Project documentation