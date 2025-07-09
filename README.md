# Sales Data Analysis Project

This project involves a detailed analysis of a sample sales dataset to uncover trends, patterns, and insights that can support data-driven decision-making in a business context.

# Project Summary

- Dataset: `sales_data_sample.csv`
- Tools Used : Python, Pandas, Matplotlib, Seaborn, Plotly
- Focus Areas:
  - Cleaning and preprocessing raw sales data
  - Time-based trend analysis
  - Product and regional sales comparisons
  - Customer-level revenue contribution
  - Correlation analysis between sales-driving variables



# Key Features

- Cleaned messy data by removing redundant and missing-value-heavy columns
- Extracted and engineered features like year, month, day from order dates
- Conducted visual Exploratory Data Analysis (EDA) on:
  - Yearly sales trends
  - Sales by product line
  - Top 10 countries and customers
  - Monthly trends
  - Correlation matrix
- Shared insights and implications after each chart for business context



# Example Insights

- 2004 was the best-performing year in terms of total revenue.
- "Classic Cars" was the highest-selling product line.
- USA contributed over 40% of total sales.
- Strong correlation between `PRICEEACH` and `SALES`.



# Folder Structure
Sales-Analysis-Project/
│
├── data/
│ ├── sales_data_sample.csv
│ └── sales_data_sample_cleaned.csv
│
├── notebooks/
│ └── Sales_Data_Analysis.ipynb
│
├── images/ # Visualizations exported from notebook
│
├── dashboard/ # Power BI files
│ └── sales_dashboard.pbix
│
├── README.md
│
└── requirements.txt



# Dashboard Overview (Power BI)

The dashboard will visualize key performance metrics including:

- Sales Trends by Year and Month
- Sales by Product Line
- Sales by Country
- Top Customers
- Relationship between Quantity, Price, and Sales

It will provide interactive filters and drill-down capabilities for business decision-makers.


# How to Run the Notebook

1. Clone this repository or download the ZIP.
2. Open `Sales_Data_Analysis.ipynb` in Jupyter Notebook or VS Code.
3. Run the notebook to explore visualizations and insights.
4. Cleaned data is saved to `data/sales_data_sample_cleaned.csv`.

