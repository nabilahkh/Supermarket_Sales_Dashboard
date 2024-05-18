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
   <div align="center"><img src="https://github.com/nabilahkh/Supermarket_Sales_Dashboard/assets/92252191/761a3833-fab3-481f-83e2-bf8745a4e280" /></div>
   The graph shows monthly sales fluctuations: starting at 94.9K in January, dropping to 59.8K  in February, then rebounding to 205K in March. Sales remained stable from April to July (137.8K to 155K). August saw a rise to 159K, peaking in September at 307.6K, likely due to effective marketing. After dipping to 200.3K in October, sales surged to 352.5K in November, and remained strong at 325.3K in December, indicating a strong upward trend towards year-end.
   
2. Which state has the highest sales each month?
   <div align="center"><img src="https://github.com/nabilahkh/Supermarket_Sales_Dashboard/assets/92252191/5b354621-3789-4b8a-af8f-8e6218e68571" /></div>
   The chart highlights the top 10 states with the largest sales by month. California leads with $457K in sales, indicating its dominant market presence. New York follows with $310K. Texas and Washington also show significant contributions, while Pennsylvania and Florida have moderate sales. Illinois, Michigan, Ohio, and Virginia contribute less, with Virginia at $70K. This distribution shows strong sales concentration in California and New York, with notable contributions from other key states.
   
3. Which segment has the highest number of customers?
   <div align="center"><img src="https://github.com/nabilahkh/Supermarket_Sales_Dashboard/assets/92252191/3059a75c-c14e-4f90-b795-109bf9ffee81" /></div>
   The chart shows customer segments by total percentage: Consumer, Corporate, and Home Office. Consumers make up the largest segment at 51.6%, indicating they form the majority of customers. Corporate customers follow with 29.8%, while Home Office accounts for 18.7%. This highlights the dominance of individual consumers in the market, with significant contributions from corporate and home office segments.
   
4. Which product category has the highest sales?
   <div align="center"><img src="https://github.com/nabilahkh/Supermarket_Sales_Dashboard/assets/92252191/a2d7d261-0e2e-46a2-bbe4-42675148ac33" /></div>
   The graph shows the total sales by category, with Office Supplies leading significantly at 60.48%. Furniture follows with 21.2%, while Technology accounts for 18.32%. This indicates a dominant demand for Office Supplies, making up more than half of the total sales, with Furniture and Technology contributing moderately.
   
5. How do profit trends change from month to month?
   <div align="center"><img src="https://github.com/nabilahkh/Supermarket_Sales_Dashboard/assets/92252191/0e1d39be-6874-4654-96ce-5368100922ae" /></div>
   The graph shows monthly profit starting at 9.1K in January, peaking at 28.6K in March, and dipping to 11.6K in April. After stabilizing around 21K from May to August, profit peaked again at 36.9K in September. Despite a small dip in October to 31.8K, profits rose to 35.5K in November, reaching the year's highest at 43.4K in December, indicating a strong upward trend towards year-end.

## Summary
1. Monthly Sales Fluctuations: Sales started at 94.9K in January, dipped to 59.8K in February, and rebounded to 205K in March. They peaked at 307.6K in September and ended strong at 325.3K in December.
2. Top 10 States by Sales: California led with $457K, followed by New York with $310K. Texas and Washington also contributed significantly, while Virginia had the lowest among the top 10 states at $70K.
3. Customer Segments: Consumers dominated with 51.6% of total customers, followed by Corporate at 29.8% and Home Office at 18.7%.
4. Sales by Category: Office Supplies led with 60.48% of total sales, followed by Furniture at 21.2% and Technology at 18.32%.
5. Monthly Profit Trends: Profit started at 9.1K in January, peaked at 28.6K in March, and saw another peak at 36.9K in September, ending the year at a high of 43.4K in December.
