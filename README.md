# 🌍 **Global E-Commerce Sales**

### **Overview**

This notebook documents the process used to analyze a global e-commerce sales dataset and build an interactive dashboard. The main goal of the project is to explore sales, profit, customer, product, payment, and regional trends, then present the key business insights through clear visualizations and KPI cards.  

The workflow followed in this notebook includes data loading, data inspection, data preparation, feature engineering, exploratory data analysis, visualization, and dashboard development using Dash and Plotly.

---
### **Objectives**

- How do sales and profit trends vary across regions and product categories?
- Which customer segment is the most profitable?
- Are there seasonal patterns in ordering behavior?
- Which payment methods are preferred in different regions?
- do customer segments display any preferences for any specific product categories?

---
### **Dataset**

This dataset has been downloaded from Kaggle platform (URL). It contains 2000 transactions and 15 features:

- `Order_ID`:	Unique order identifier (ORD-10001 to ORD-12000)
- `Order_Date`:	Transaction date (2023-01-01 to 2025-12-31)
- `Customer_Name`:	Customer full name
- `Customer_Segment`:	Consumer, Corporate, or Home Office
- `Country`:	Customer's country (20 countries)
- `Region`:	Geographic region (North America, Europe, Asia Pacific, Middle East & Africa, South America)
- `Product_Category`:	Technology, Furniture, Office Supplies, or Clothing & Accessories
- `Product_Name`:	Specific product name (40 unique products)
- `Quantity`:	Units ordered (1–15)
- `Unit_Price`:	Price per unit in USD
- `Discount_Percent`:	Discount applied (0%–30%)
- `Total_Sales`:	Revenue = Quantity × Unit_Price × (1 − Discount%)
- `Shipping_Cost`:	Shipping fee (varies by region and quantity)
- `Profit`:	Net profit after product cost and shipping
- `Payment_Method`:	Credit Card, PayPal, Bank Transfer, or Cash on Delivery

---
### **Technologies Used**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Dash](https://img.shields.io/badge/Dash-008DE4?style=for-the-badge&logo=plotly&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

---
### **Project Workflow**

- Data prepation: Checking and addressing missing values and duplicates, converting data types, features engineering
- Exploratory Data Analysis (EDA): Descriptive statistics, grouping data, correlation
- Data Visualization: Line chart, Bar chart, Pie chart, Bubble chart, Scatter plot, Heatmap
- Dashboard: Dropdown list, KPI, Line chart, Bar chart, Pie chart, Country map

---
### **Key Insights**


### **Contributors**


