# Customer Segmentation and Sales Analysis

Overview
This repository contains an analysis of customer transaction data to identify the most profitable customer segments and bestselling products. The analysis leverages customer characteristics such as life stage and premium membership status to uncover valuable insights into customer behavior. These insights can be used to tailor marketing strategies and optimize product offerings for greater profitability.

Files Included
transaction_data.csv: Contains transaction details, including product information, sales data, and customer loyalty card numbers.
purchase_behaviour.csv: Contains customer characteristics, such as life stage (e.g., Young Adult, Senior) and premium membership status (Premium or Non-Premium).
analysis_code.py: Python code for data cleaning, analysis, and visualization. The script performs the following tasks:
Data exploration and cleaning.
Identification of top-selling products by total sales.
Analysis of loyal customers based on transaction frequency.
Segmentation of loyal customers by life stage and premium membership status.
Visualization of customer segments and their average sales.
Key Insights
Top-Selling Products: The most profitable products are identified based on total sales, and their distribution is visualized using pie charts.
Loyal Customers: Customers with more than 14 transactions were classified as loyal. The characteristics of these loyal customers were analyzed to determine which segments generate the most revenue.
Customer Segmentation: Customer segments were defined based on life stage (e.g., Senior, Young Adult) and premium membership status (Premium vs. Non-Premium). The analysis revealed that certain segments, particularly Premium customers in the Senior and Middle-Aged groups, are the most profitable.
Visualizations
Bar Plot: Displays the average total sales for each customer segment, with separate bars for premium and non-premium customers.
Pie Chart: Shows the sales distribution for the top-selling products.
How to Use
Clone this Repository:

Run the following command to clone the repository:

git clone https://github.com/your-username/customer-segmentation-sales-analysis.git
Install Required Libraries:

Ensure you have Python installed on your system.
Install the necessary libraries by running:

pip install pandas numpy matplotlib seaborn
Run the Analysis:

Navigate to the folder containing the repository and run the analysis code:

python analysis_code.py
Purpose
The primary objective of this analysis is to provide insights into:

Which customer segments (based on life stage and premium membership status) are the most profitable.
How the marketing team can target high-value customer groups.
What products are driving the most revenue, allowing for better inventory and marketing decisions.
Potential Applications
Targeted Marketing: Use insights from customer segments to craft targeted campaigns for the most profitable groups.
Product Optimization: Focus on top-selling products and understand customer preferences to align marketing and sales strategies.
Customer Retention: Develop strategies to increase loyalty among customers who have fewer transactions, potentially turning them into frequent buyers.
