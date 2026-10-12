# Retail Orders EDA Using Python

## 📌 Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on a retail orders dataset using Python. The objective is to analyze sales performance, customer behavior, product profitability, order statuses, payment methods, and monthly sales and profit trends.

The project demonstrates the complete EDA workflow, including data inspection, data cleaning, missing value handling, duplicate removal, outlier detection, data visualization, and business insights.

## 🎯 Project Objectives

- Clean and prepare raw retail order data for analysis.
- Identify and handle duplicate records and missing values.
- Analyze numerical and categorical variables.
- Explore relationships between sales, profit, regions, product categories, and customer segments.
- Analyze monthly net sales and profit trends.
- Answer business questions and extract meaningful insights.

## 🛠️ Tools and Technologies

- **Python** – Data analysis and programming
- **Pandas** – Data manipulation and cleaning
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Jupyter Notebook** – Interactive analysis

## 📂 Project Files

| File | Description |
|---|---|
| `Retail_Orders.ipynb` | Jupyter Notebook containing the complete EDA process |
| `retail_orders_eda_practice.csv` | Raw retail orders dataset |

## 📊 Dataset Description

The dataset contains **1,212 records and 20 columns** before cleaning. It includes retail order details such as order date, customer information, region, product category, sales channel, payment method, shipping days, sales, costs, and profit.

### Important Columns

- `Order_ID` – Unique order identifier
- `Order_Date` – Date of the order
- `Customer_ID` – Customer identifier
- `Region` and `City` – Geographic information
- `Customer_Segment` – Customer category
- `Sales_Channel` – Channel through which the order was placed
- `Product_Category` and `Product_Name` – Product details
- `Unit_Price` and `Quantity` – Price and quantity information
- `Discount` and `Discount_Amount` – Discount information
- `Gross_Sales` and `Net_Sales` – Sales values before and after discounts
- `Estimated_Cost` and `Profit` – Estimated cost and profit
- `Order_Status` – Current order status
- `Payment_Method` – Method used for payment
- `Shipping_Days` – Number of days required for shipping

## 🔍 Analysis Performed

### 1. Data Inspection
- Checked dataset shape, column names, data types, and sample records.
- Reviewed missing values and duplicate records.

### 2. Data Cleaning
- Standardized column names and categorical values.
- Removed duplicate records.
- Converted the order date column to datetime format.
- Handled missing values using appropriate imputation methods, including mode and median.
- Checked numerical columns for invalid values and potential outliers.

### 3. Univariate Analysis
- Created histograms to understand numerical data distributions.
- Used count plots to examine categorical variables.
- Used box plots to identify potential outliers.

### 4. Bivariate Analysis
- Compared regions with total net sales.
- Compared product categories with total profit.
- Analyzed net sales across customer segments.
- Examined order status distributions across sales channels.

### 5. Time-Series Analysis
- Analyzed monthly net sales.
- Analyzed monthly profit.
- Visualized monthly trends using line charts.

### 6. Business Questions
- Which sales channel has the most delivered orders?
- Which order status occurs most frequently?
- Which payment method is used most frequently?
- Which month has the highest net sales?
- Which month has the highest profit?

## 💡 Key Business Insights

- **Regional Performance:** The North region generated the highest total net sales, approximately 4.87 million.
- **Product Profitability:** Furniture generated the highest total profit among product categories, approximately 2.01 million.
- **Customer Segment:** The Consumer segment contributed the highest net sales, approximately 9.78 million.
- **Sales Channel:** Online recorded the highest number of delivered orders, with 326 orders.
- **Order Status:** Delivered was the most frequent order status, with 789 orders.
- **Payment Method:** UPI was the most frequently used payment method, with 439 orders.
- **Monthly Net Sales:** April recorded the highest total net sales, approximately 1.71 million.
- **Monthly Profit:** April recorded the highest total profit, approximately 578,811.

*Note: Sales and profit figures are expressed in the dataset's numerical units; no currency unit was specified.*

## ✅ Conclusion

This project provided hands-on experience in data cleaning, exploratory analysis, statistical visualization, and business-oriented problem-solving using Python.

The analysis identified important patterns in regional sales, product profitability, customer segments, order fulfillment, payment preferences, and monthly performance.

Overall, the project demonstrates how Python can transform raw retail data into meaningful business insights that support data-driven decision-making.

## 👨‍💻 Author

**Kousik Chakraborty**

