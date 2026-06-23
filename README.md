# 🌍 **Global E-Commerce Sales**

## 📖 **Overview**

The Global E-Commerce Sales Dashboard is a data analytics project designed to help users understand e-commerce sales performance across different countries and regions around the world.

The project provides valuable insights that can support business decision-making by analyzing sales performance, customer behavior, product trends, profitability, and regional performance. Through data analysis and visualization, users can better understand key business metrics and identify important patterns within the data.

The dashboard was developed using Python, Dash, and Plotly. It includes interactive charts, maps, and filters that allow users to explore sales data in a simple and effective way. These interactive features make it easier to identify trends, compare performance, and gain meaningful business insights.

Overall, the Global E-Commerce Sales Dashboard serves as a powerful tool for understanding e-commerce sales and provides a comprehensive view of how e-commerce businesses are performing across different markets.

---
## 🎯 **Objectives**

- How do sales and profit trends vary across regions and product categories?
- Which customer segment is the most profitable?
- How do shipping costs affect profit margins across geographies?
- Which payment methods are preferred in different regions?
- Do customer segments display any preferences for any specific product categories?

---
## 📊 **Dataset**

The dataset used in this project has been downloaded from `Kaggle` platform [CLICK HERE](https://www.kaggle.com/datasets/muhammadaammartufail/global-e-commerce-sales-and-customer-data/data). It contains 2000 transactions and 15 features:

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
## 🛠️ **Technologies Used**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)  
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)  
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)  
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)  
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)  
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)  
![Dash](https://img.shields.io/badge/Dash-008DE4?style=for-the-badge&logo=plotly&logoColor=white)  
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)  

---
## ⚙️ **Project Workflow**

### 🔧 Data Cleaning and Transformation (Data Wrangling)

- The dataset was imported into Python using a Pandas DataFrame for analysis and processing.
- Missing values and duplicate records were identified and handled to improve data quality and ensure accurate results.
- Data type corrections were performed, particularly for date-related columns, to support time-based analysis.
- Additional date features such as Year, Month, and Quarter were extracted from the Order Date column to enable trend analysis over different time periods.

### 🔍 Exploratory Data Analysis

- Summary statistics were generated to better understand the distribution of key numerical variables.
- Customer segment analysis was performed to identify the contribution of different customer groups to sales and profit.
- Product category analysis was conducted to compare sales and profitability across categories.
- Regional and country-level analyses were carried out to evaluate geographic sales performance.
- Sales trends were examined using monthly and quarterly aggregations to identify patterns and seasonal changes.
- Payment method analysis was performed to understand customer payment preferences.
- Correlation analysis was used to explore relationships between sales, profit, quantity, shipping cost, and profit margin.
- Top-selling products were identified based on order frequency and total sales.

### 📈 Visualization

- Bar charts were used to compare sales, profit, and shipping costs across categories, regions, and countries.
- Line charts were created to visualize monthly sales trends and quarterly profit trends over time.
- Pie charts were used to show the distribution of customer segments and payment methods.
- Scatter plots were developed to analyze relationships between sales, profit, and shipping costs.
- A correlation heatmap was created to highlight relationships among key numerical variables.
- Interactive geographic visualizations were used to display sales performance across different countries and regions.
- Dashboard filters and interactive components were implemented to allow users to explore the data dynamically and gain deeper insights.


---
## 🏆 **Key Insights**

- Among product category, Furniture has the top performance in terms of total sales and profit compared to others.
- Half of the customer segment is represented by consumers followed by corporate.
- Countries like Mexico and Canada consistently outperformed others in terms of revenue and profitability.
- Sales and profit show a strong positive relationship, indicating that higher sales generally led to higher profits.
- Prefered method of payment across region is credit card followed by paypal.
- Shipping costs were highest in the Middle East and Africa and lowest in North America, highlighting regional differences that influenced overall profitability.

---
## ✅ Conclusion

The Global E-Commerce Sales Dashboard successfully transformed raw sales data into meaningful business insights through data analysis and interactive visualizations. The project provided a better understanding of customer behavior, product performance, sales trends, and regional profitability. By combining exploratory data analysis with an interactive dashboard, users can efficiently explore the data and make informed business decisions based on real-world sales performance.


