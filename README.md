# Supermarket_Sales_Dashboard

## Business Understanding
### • Background
Analysis of supermarket data, focusing on total sales, product categories, highest-spending customers, states with the highest and lowest sales, top-selling regions, and the most profitable city. This analysis provides valuable insights into supermarket performance and customer behavior.

### • Main Question
1. What are the sales trends from month to month?
2. Which state has the highest sales each month?
3. Which segment has the highest number of customers?
4. Which product category has the highest sales?
5. How do profit trends change from month to month? 

## Data Understanding
1. The Data used of Supermarket obtained from https://www.kaggle.com/datasets/berkmamikoglu/supermarketsalesermarket obtained from
2. The Data used is Supermarket from Mei 2014 until December 2017
3. The Data used consist of 20 column and 994 rows

### • Data Dictionary
1. Row ID: Sequential number used to identify the row in the table.
2. Order ID: A unique code assigned to each order.
3. Order Date: The date when the order was placed.
4. Ship Date: The date when the order was shipped.
5. Ship Mode: The shipping method used (e.g., "Second Class", "Standard Class").
6. Customer ID: A unique code assigned to each customer.
7. Customer Name: Name of the customer who placed the order.
8. Segment: A market segment of the customer (e.g., "Consumer", "Corporate").
9. Country: The country where the customer is located.
10. City: The city where the customer is located.
11. State: State or province where the customer is located. 
12. Postal Code: The postal code where the customer is located. 
13. Region: Geographical region where the customer is located (e.g., "West", "South"). 
14. Product ID: Unique code assigned to each product. 
15. Category: Category of the product ordered (e.g., "Furniture", "Office Supplies"). 
16. Sub-Category: A more specific sub-category of the product (e.g., "Bookcases", "Chairs"). 
17. Product Name: Name of the product ordered. 
18. Sales: Total sales for the item. 
19. Quantity: Number of units of the product ordered. 
20. Discount: Discount given on the product. 
21. Profit: Profit generated from the sale of the product.

## Data Preparation
1. Python Version: 3.12.3
2. Packages: Pandas, NumPy, Matplotlib, and Seaborn

## Data Cleansing
1. Changing the data type of the 'Order Date' and 'Ship Date' columns from object to datetime.
2. Counting the number and percentage of missing values in the columns of the 'Supermarket' dataset, then displaying them back in a new DataFrame containing such information, such as column names, the count of missing values, and the percentage of missing values in each column.

## Exploratory Data Analysis
1. What are the sales trends from month to month?
   
3. Which state has the highest sales each month?
4. Which segment has the highest number of customers?
5. Which product category has the highest sales?
6. How do profit trends change from month to month? 
