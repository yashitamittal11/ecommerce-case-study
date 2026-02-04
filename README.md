# E-commerce Marketing Analysis Case Study

## Project Overview
This case study analyzes e-commerce transaction and marketing data from **1st January 2019 to 31st December 2019**.  
The goal is to understand **sales performance, customer behavior, discount effectiveness, and marketing impact** using structured data analysis.

The analysis combines transaction-level sales data with customer demographics, discount campaigns, marketing spend, and tax information.

---

## Business Questions

1. **Acquisition Fluctuations**
   - Identify the months with the highest and lowest customer acquisition counts.
   - Suggest strategies to reduce fluctuations and drive consistent growth throughout the year.

2. **High-Retention Months**
   - Analyze customer behavior during high-retention months.
   - Suggest ways to replicate this success across other months.

3. **New vs Existing Revenue**
   - Compare revenue from new vs existing customers month-over-month.
   - Interpret what this trend suggests about acquisition vs retention focus.

4. **Top-Performing Products**
   - Identify top-performing products.
   - Analyze factors driving their success.
   - Use insights to improve inventory planning and promotional strategy.

5. **Customer Segmentation (RFM)**
   - Segment customers into **Premium, Gold, Silver, and Standard** using **RFM segmentation**.
   - Propose targeted strategies for each segment to improve retention and revenue.

6. **Revenue Contribution by Segment**
   - Analyze revenue contribution of each customer segment.
   - Recommend how to prioritize high-value segments while nurturing lower-value segments.

7. **Cohort Retention**
   - Group customers by their month of first purchase and analyze retention over time.
   - Identify cohorts with highest and lowest retention.
   - Suggest strategies to improve retention for weaker cohorts.

8. **LTV by Acquisition Month**
   - Analyze lifetime value (LTV) of customers acquired in different months.
   - Explain how this should influence acquisition and retention strategy.

9. **Seasonality by Category and Location**
   - Identify seasonal sales trends by **product category** and **location**.
   - Recommend how to prepare for peak vs off-peak periods to maximize revenue.

10. **Daily Trends (High vs Low Performing Days)**
   - Analyze daily sales trends to identify high-performing and low-performing days.
   - Suggest strategies to boost sales on slower days.

---

## Dataset Overview
The project uses the following datasets:

### Online_Sales.csv
Contains transaction-level order data.

- CustomerID: Customer unique ID  
- Transaction_ID: Transaction unique ID  
- Transaction_Date: Date of transaction  
- Product_SKU: Unique product identifier  
- Product_Description: Product description  
- Product_Category: Product category  
- Quantity: Number of items ordered  
- Avg_Price: Price per unit  
- Delivery_Charges: Delivery charges  
- Coupon_Status: Whether a discount coupon was applied  

---

### Customers_Data.csv
Contains customer demographic information.

- CustomerID: Customer unique ID  
- Gender: Gender of the customer  
- Location: Customer location  
- Tenure_Months: Customer tenure in months  

---

### Discount_Coupon.csv
Contains discount details by category and month.

- Month: Month in which the coupon was applied  
- Product_Category: Product category  
- Coupon_Code: Coupon code  
- Discount_pct: Discount percentage  

---

### Marketing_Spend.csv
Contains daily marketing spend data.

- Date: Date  
- Offline_Spend: Spend on offline channels (TV, radio, newspapers, hoardings, etc.)  
- Online_Spend: Spend on online channels (Google ads, Facebook, etc.)  

---

### Tax_Amount.csv
Contains GST details by product category.

- Product_Category: Product category  
- GST: GST percentage  

---

## Key Analysis Objectives
- Analyze overall sales performance and revenue trends
- Identify seasonality and monthly sales patterns
- Understand customer behavior based on tenure, gender, and location
- Evaluate the impact of discount coupons on sales
- Analyze marketing spend and its relationship with sales
- Estimate revenue after applying discounts, delivery charges, and tax

---

## Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

---

## Notebook
- [E-commerce Marketing Analysis Notebook](notebooks/ecommerce_marketing_analysis.ipynb)
- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/yashitamittal11/ecommerce-case-study/blob/main/notebooks/ecommerce_marketing_analysis.ipynb
)

---

## Key Steps in Analysis
- Data cleaning and preprocessing
- Handling missing values and duplicates
- Feature engineering (month, revenue, discount impact, tax calculation)
- Merging multiple datasets
- Exploratory Data Analysis (EDA)
- Visualization of trends and patterns
- Business insights and recommendations

---

## Folder Structure
```text
├── data/
│   ├── Online_Sales.csv
│   ├── Customers_Data.csv
│   ├── Discount_Coupon.csv
│   ├── Marketing_Spend.csv
│   └── Tax_Amount.csv
├── notebooks/
│   └── ecommerce_marketing_analysis.ipynb
├── README.md
