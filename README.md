# 🛒 Online Retail Customer Analysis

## 📌 Project Overview
This project analyzes transactional data from an online retail store to understand
customer purchasing behavior, sales trends, and customer segments using **RFM analysis**.
The objective is to generate **actionable business insights** for marketing and customer
retention.

---

## 📊 Dataset
- **Source:** UCI Machine Learning Repository – Online Retail Dataset
- **Records:** ~541,000 transactions
- **Time Period:** 2010 – 2011
- **Note:** The raw dataset is not included in this repository due to file size limitations.

---

## 🛠️ Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib
- Jupyter Notebook

---

## 🧹 Data Cleaning
The following steps were performed:
- Removed records without `CustomerID`
- Excluded cancelled invoices and returned items
- Filtered invalid quantities and prices
- Created a `TotalPrice` feature
- Converted invoice dates to datetime format

Final cleaned dataset contains **~397,000 valid transactions**.

---

## 📈 Exploratory Data Analysis (EDA)
Key analyses include:
- Daily revenue trend analysis
- Top countries by total revenue
- Top customers by total spending

---

## 👥 Customer Segmentation (RFM Analysis)
Customers were segmented using:
- **Recency:** Days since last purchase
- **Frequency:** Number of purchases
- **Monetary:** Total spending

### Segments Identified
- **Champions**
- **Loyal Customers**
- **New Customers**
- **At Risk**
- **Others**

---

## 💡 Key Business Insights
- A small group of **Champions** contributes a large portion of revenue.
- **Loyal customers** are strong candidates for loyalty and upsell campaigns.
- **At-risk customers** require re-engagement strategies to prevent churn.

---

## 📁 Project Structure
online-retail-analysis/
│
├── data/
│ ├── raw/ # Raw data (not included)
│ └── processed/ # Cleaned data and RFM outputs
│
├── notebooks/
│ ├── 01_data_cleaning.ipynb
│ └── 02_eda_rfm.ipynb
│
├── README.md
└── requirements.txt


---

## 🚀 How to Run the Project
1. Download the Online Retail dataset from the UCI repository
2. Place the dataset file inside `data/raw/`
3. Install dependencies:
```bash
pip install -r requirements.txt


📬 Author

Adeeb
Aspiring Data Analyst
Python • Data Analysis • Visualization
