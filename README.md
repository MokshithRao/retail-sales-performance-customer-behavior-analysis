#  Retail Sales Performance & Customer Behavior Analysis

This project is an **end-to-end retail analytics case study** that demonstrates the complete workflow of a **Data Analyst**, starting from raw, messy data and ending with **professional Power BI dashboards** and **business insights**.

The project focuses on:
- Data cleaning and preprocessing  
- Feature engineering  
- Exploratory Data Analysis (EDA)  
- Business insight generation  
- Interactive dashboard creation using Power BI  

---

##  Dataset Source

The dataset used in this project was obtained from Kaggle:

🔗 **Retail Store Sales – Dirty Dataset for Data Cleaning**  
https://www.kaggle.com/datasets/ahmedmohamed2003/retail-store-sales-dirty-for-data-cleaning

This dataset intentionally contains missing values, inconsistent formats, and data quality issues, making it suitable for real-world data cleaning and analytics practice.

---

##  Project Objectives

- Clean and preprocess raw retail transaction data  
- Handle missing and inconsistent values  
- Engineer useful features for analysis  
- Perform exploratory data analysis (EDA)  
- Derive actionable business insights  
- Build interactive and professional Power BI dashboards  

---

##  Tools & Technologies

| Tool | Purpose |
|-----|--------|
| **Python (Pandas, NumPy)** | Data cleaning & transformation |
| **Matplotlib, Seaborn** | Exploratory Data Analysis |
| **Jupyter Notebook** | Analysis workflow |
| **Power BI** | Dashboard creation & storytelling |
| **DAX** | KPI and metric calculations |
| **Git & GitHub** | Version control |

---

##  Project Structure

```
Retail-Sales-Performance-Analysis/
│
├── dashboard/
│   ├── retail_sales_dashboard.pbix
│   └── retail_sales_dashboard.pdf
│
├── Data/
│   ├── raw/
│   │   └── retail_store_sales.csv
│   └── Cleaned/
│       └── retail_sales_cleaned.csv
│
├── notebooks/
│   └── retail_sales_analysis.ipynb
│
└── README.md
```

---

## 🔹 Phase 1: Data Cleaning & Preprocessing

**Objective:** Prepare clean, reliable data from a messy raw dataset.

### Issues Identified
- Missing values in:
  - Item  
  - Price Per Unit  
  - Quantity  
  - Total Spent  
- Inconsistent date formats  
- Boolean discount column  
- Unstandardized categorical values  

### Cleaning Steps
- Reconstructed missing numeric values using business logic  
- Standardized category, payment method, and location fields  
- Converted transaction dates to proper datetime format  
- Removed invalid or unusable records  
- Created a clean dataset for analysis  

 Output: `retail_sales_cleaned.csv`

---

## 🔹 Phase 2: Feature Engineering

**Objective:** Create meaningful features to support analysis and dashboards.

New features added:
- Month  
- Month Name (properly sorted)  
- Year  
- Day of Week  
- Price Category (Low / Medium / High)  

These features were created to analyze seasonality, customer behavior, and pricing trends.

---

## 🔹 Phase 3: Exploratory Data Analysis (EDA)

**Objective:** Understand sales performance and customer behavior.

Key analyses performed:
- Monthly revenue trends  
- Revenue by product category  
- Revenue by location (Online vs In-Store)  
- Payment method distribution  
- Price vs quantity purchasing behavior  
- Discount impact on transactions  
- Sales patterns across weekdays  

EDA visualizations were created using Python to support insights.

---

## 🔹 Phase 4: Business Insights & Recommendations

### Key Insights
- January shows the highest revenue spike; other months are stable.
- Butchers and Electric Household Essentials are top-performing categories.
- Online and In-Store channels generate nearly equal revenue.
- Quantity purchased remains consistent across price levels → price-insensitive demand.
- Discounts slightly increase average transaction value, not quantity.
- Payment methods are evenly distributed across customers.

### Business Recommendations
- Focus inventory and promotions on high-performing categories.
- Improve data quality for product information (reduce unknown items).
- Use targeted discounts instead of blanket discounting.
- Maintain strong omnichannel presence.
- Continue offering multiple payment options.

---

## 🔹 Phase 5: Power BI Dashboards

Two interactive dashboards were created using Power BI.

###  Dashboard 1: Sales Overview
- KPIs:
  - Total Revenue
  - Total Transactions
  - Average Transaction Value
  - Total Quantity Sold
  - Discount Rate
- Revenue by Month
- Revenue by Category
- Revenue by Location
- Payment Method Distribution
- Discount Impact Analysis
- Interactive slicers (Year, Month, Category, Payment Method)

###  Dashboard 2: Customer & Product Behavior
- Transactions by Day of Week
- Quantity variation across price categories
- Average quantity by price category
- Top revenue-generating products
- Price vs Quantity purchase frequency analysis

---

##  How to Run the Project

1. Open `retail_sales_analysis.ipynb` to view data cleaning, feature engineering, and EDA.
2. Open `retail_sales_dashboard.pbix` in Power BI to explore the dashboards.
3. Use slicers in Power BI for interactive analysis.

---

##  Conclusion

This project demonstrates a **complete data analytics workflow**, including:

- Handling messy real-world data  
- Performing structured analysis  
- Translating data into business insights  
- Communicating insights through professional dashboards  

It reflects the responsibilities and skills expected of a **Data Analyst / BI Analyst** in real industry projects.

---

##  Acknowledgements

Dataset provided by the Kaggle community:  
https://www.kaggle.com/datasets/ahmedmohamed2003/retail-store-sales-dirty-for-data-cleaning

