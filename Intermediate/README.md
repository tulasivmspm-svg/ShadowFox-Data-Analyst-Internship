# Online Retail Data Analysis

## Overview

This project is an intermediate-level Data Analyst internship project focused on analyzing an Online Retail dataset to understand customer behaviour, revenue performance, product performance, and sales trends.

The analysis goes beyond basic summaries by examining customer retention, repeat purchase behaviour, customer segmentation, revenue contribution, active months, product performance, geographic performance, and monthly sales trends.

## Objective

The main objectives of this project are to:

- Analyze customer purchasing behaviour
- Compare repeat and one-time customers
- Identify high-value and frequent customer segments
- Analyze revenue performance over time
- Identify high-performing products
- Compare revenue across countries
- Study customer activity across different months
- Identify important business patterns and trends
- Provide actionable business recommendations

## Dataset

The project uses the Online Retail dataset containing transaction-level sales information.

The main columns include:

- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

The dataset contains 541,909 transaction records and 8 columns.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Performed

### 1. Data Cleaning and Preparation

- Inspected the dataset structure
- Checked missing values
- Prepared the data for analysis
- Created a Revenue metric using quantity and unit price
- Prepared customer-level and time-based datasets

### 2. Customer Analysis

- Calculated customer-level orders and revenue
- Classified customers as one-time or repeat customers
- Calculated average order value
- Identified high-value and lower-value customers
- Analyzed customer activity across months

### 3. Customer Segmentation

Customers were grouped into four segments based on value and purchase frequency:

- High Value - Frequent
- High Value - Less Frequent
- Lower Value - Frequent
- Lower Value - Less Frequent

The High Value - Frequent segment generated approximately 89.21% of identifiable customer revenue.

### 4. Revenue Analysis

Monthly revenue, orders, customers, and Average Order Value (AOV) were analyzed.

Key findings include:

- November 2011 was the highest-revenue month at approximately £1.50 million.
- February 2011 recorded the lowest monthly revenue at approximately £522.55K.
- September to November showed strong revenue growth.
- December showed a sharp decline in revenue, orders, and customers.

### 5. Product Performance

Product revenue and sales quantity were analyzed to identify important products.

Key findings include:

- PAPER CRAFT, LITTLE BIRDIE had the highest recorded quantity sold.
- MEDIUM CERAMIC TOP STORAGE JAR was among the highest-selling products by quantity.
- Products such as RABBIT NIGHT LIGHT and PAPER CHAIN KIT 50'S CHRISTMAS showed strong revenue performance during the September-November high-revenue period.

### 6. Geographic Performance

Revenue, orders, customers, revenue per order, and revenue per customer were compared across countries.

Key findings include:

- The United Kingdom generated approximately 84.59% of total revenue.
- The Netherlands, EIRE, Germany, and France were among the next highest-revenue countries.
- Some countries showed relatively high revenue per customer despite having smaller customer bases.

## Key Business Insights

- Repeat customers are a major contributor to revenue.
- High-value frequent customers are the most important customer segment.
- A relatively small group of customers contributes a large share of revenue.
- Sales performance increased strongly during September-November.
- The sharp decline in December requires further investigation.
- The United Kingdom is the dominant revenue-generating market.
- Several products performed particularly well during the high-revenue period.

## Business Recommendations

### 1. Focus on Repeat Customers

Develop loyalty programs, personalized offers, and targeted promotions to retain repeat customers and encourage one-time customers to purchase again.

### 2. Protect High-Value Customers

Provide high-value frequent customers with exclusive offers, early access to products, personalized recommendations, and loyalty benefits.

### 3. Convert One-Time Customers

Use follow-up campaigns, discounts, product recommendations, and reminders to encourage one-time customers to make a second purchase.

### 4. Prepare for Seasonal Demand

The strong performance from September to November suggests increased demand during this period. Inventory and marketing activities should be planned accordingly.

### 5. Investigate the December Decline

The sharp December decline should be investigated further to determine whether it is related to incomplete monthly data, seasonal purchasing patterns, operational factors, or other conditions.

### 6. Maintain Stock of High-Demand Products

Monitor products with consistently high sales quantities to reduce the risk of stockouts during high-demand periods.

### 7. Explore International Markets

The business can explore growth opportunities in markets such as the Netherlands, Germany, France, Australia, and Japan through targeted marketing.

## Project Files

- `Online_Retail_Analysis.ipynb` - Jupyter Notebook containing the complete analysis
- `Online_Retail_Analysis.html` - HTML version of the completed analysis

## Conclusion

This project demonstrates an end-to-end data analysis workflow, from data preparation and exploratory analysis to customer segmentation, trend analysis, visualization, business insights, and actionable recommendations.

The analysis shows that customer retention, high-value customer management, seasonal demand planning, product performance, and international market opportunities are important areas for business growth.
