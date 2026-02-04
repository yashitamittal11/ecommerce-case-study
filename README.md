# E-commerce Marketing Analysis Case Study

## Project Overview
This case study analyzes e-commerce transaction and marketing data from **1st January 2019 to 31st December 2019**.  
The goal is to understand **sales performance, customer behavior, discount effectiveness, and marketing impact** using structured data analysis.

The analysis combines transaction-level sales data with customer demographics, discount campaigns, marketing spend, and tax information.

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
