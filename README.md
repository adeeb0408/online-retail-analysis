# Analyzing Customer Data for Business Insights

## Objective
The objective of this project is to analyze real-world customer transaction data to extract meaningful business insights. The analysis focuses on customer behavior, sales trends, and customer segmentation to support data-driven decision-making.

## Dataset
- Dataset: Online Retail Dataset
- Source: UCI Machine Learning Repository
- Records: ~500,000 transactions
- Features include invoice details, product information, quantity, price, customer ID, country, and purchase date.

## Steps Performed

### 1. Data Cleaning
- Removed missing CustomerID values
- Handled missing product descriptions
- Removed invalid transactions (negative quantity and price)
- Converted InvoiceDate to datetime format
- Cleaned dataset reduced to ~397,000 records

### 2. Data Transformation
- Created a new feature: `TotalPrice = Quantity × UnitPrice`
- Extracted time-based features such as month and year
- Aggregated sales data for trend analysis

### 3. Exploratory Data Analysis (EDA)
- Analyzed sales distribution and customer spending
- Identified top-selling products
- Visualized monthly sales trends
- Examined customer purchase behavior

### 4. Customer Segmentation (RFM Analysis)
- Created RFM (Recency, Frequency, Monetary) metrics
- Assigned RFM scores to customers
- Segmented customers into groups such as:
  - Champions
  - Loyal Customers
  - At Risk Customers
  - Lost Customers

### 5. Customer Lifetime Value (CLV)
- Estimated customer value using Monetary component of RFM
- Identified high-value and low-value customer segments

## Key Insights
- A small group of customers contributes a large portion of total revenue
- Loyal and Champion customers show high purchase frequency and value
- Sales peak during certain months, indicating seasonal trends
- Customer segmentation helps identify retention and marketing opportunities

## Tools & Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook
- Git & GitHub

## Conclusion
This project demonstrates end-to-end data analysis on a real-world dataset, including data cleaning, EDA, customer segmentation, and business insight generation. The insights can help businesses improve customer retention and optimize sales strategies.
