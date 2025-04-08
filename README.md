# Retail Data Analysis
## Overview
This project analyzes retail transaction data to derive insights about customer behavior, sales trends, and product performance. It includes data cleaning, feature engineering, and several visualizations.

## Steps Taken
### 1. Importing Libraries
Pandas, Numpy, Matplotlib, Seaborn, and Plotly were used for data manipulation and visualization.

### 2. Data Upload and Preprocessing
The retail data was uploaded using Google Colab's files.upload() function.
Data columns were renamed for easier understanding, such as InvoiceNo to Transaction_ID and Quantity to Units_Purchased.

### 3. Data Cleaning
Missing Values: All missing values were dropped.
Duplicate Transactions: Duplicates were identified and removed based on Transaction_ID.
Negative Units: Negative values in the Units_Purchased column were handled by converting them to positive.

### 4. Feature Engineering
A Date column was converted to a datetime format.
New columns were created from Date:
Year, Month, Weekday, and Hour.

### 5. Data Analysis
Total Revenue: Calculated by multiplying Units_Purchased by Amount_Spent.
Top Products: The most sold products were identified based on total units purchased.
Retention Rate: Percentage of customers who made repeat purchases was calculated.

### 6. Visualizations
Monthly Revenue Trends: A line chart showing the monthly revenue trends.
Sales by Payment Type: A pie chart showing the distribution of sales across payment types.
Transaction Amount Distribution: A histogram to visualize the distribution of transaction amounts.
Sales Across Regions: An area chart comparing sales performance across different regions.

### 7. Advanced Analysis
Correlation: Analyzed the correlation between Units_Purchased and Total_Revenue.
Heatmap: Created a heatmap to visualize total sales by weekday.

## Conclusion
This project provides key insights into retail sales, payment preferences, and customer retention. The analysis can help in decision-making processes related to marketing, product stocking, and customer engagement strategies.
