# 📊 Online Retail — Exploratory Data Analysis
### CodeAlpha Internship | Task 2

---

## 📌 Overview
This project performs an Exploratory Data Analysis (EDA) on an Online Retail dataset. The goal is to uncover key business insights such as top-selling products, revenue trends, customer behavior, and data anomalies.

---

## 📁 Dataset
- **Source:** Online Retail Data Set (Excel)
- **Records:** 536,641 transactions
- **Period:** December 2010 – December 2011
- **Columns:** InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

---

## 🔍 Questions Explored
- What are the top selling products?
- Which country generates the most revenue?
- What is the monthly sales trend?
- Who are the top customers?
- Are there any unusual quantities or prices in the dataset?

---

## 🛠️ Libraries Used
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

---

## 📊 Key Findings
- **Top Product:** World War 2 Gliders ASSTD Designs (~52,000 units sold)
- **Top Country:** United Kingdom dominates revenue by a massive margin
- **Sales Trend:** Revenue peaks in November (pre-Christmas surge)
- **Top Customer:** Customer 14646 generated ~£270,000 in revenue
- **Anomalies:** Negative quantities and prices detected (returns/cancellations)

---

## 📂 Project Structure
```
CodeAlpha_Exploratory-Data-Analysis/
├── Original_data set.xlsx        # Raw dataset used for analysis
├── Final_data set.xlsx           # Cleaned dataset after preprocessing
├── codealpha task 2 code.py.pdf  # Python code used for EDA
├── EDA_Report_by_Uzair_khan.pdf  # Final EDA report with insights
├── README.md                     # Project documentation
└── LICENSE                       # MIT License for the project
```

---

## ▶️ How to Run
1. Clone the repository
2. Install dependencies: `pip install pandas numpy matplotlib seaborn openpyxl`
3. Open `CodeAlpha_EDA_Task2.ipynb` in Jupyter or Google Colab
4. Run all cells

---

## 👤 Author
**Uzair Khan**
CodeAlpha Data Analytics Internship — April 2026
