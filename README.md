# Sales-Data-Capstone-Project

## Project Overview
This project analyzes a retail store's sales performance. The goal is to explore sales data to uncover key insights such as top-selling products, regional performance, and monthly sales trends. The project also aims to produce an interactive Power BI dashboard highlighting these findings.

## Data Collected
1. The dataset includes the following key columns:
2. OrderID: The unique identifier that specifies each order
3. Customer Id: The number that identifies each customer
4. Product: The products being sold
5. Region: The geographical area where the store operates.
6. Quantity: The number of products being purchased
7. UnitPrice: The price of each of the product
8. Sales: The total monetary value generated from the sale.

## Project Objectives
This project was designed to address the following analysis goals:
- Total Revenue: To analyze the total revenue generation during the sales
- Average Revenue per Region: Calculate each region's average revenue per sale to assess performance.
- Revenue by Region: Determine the total revenue generated by each region and identify the highest-performing regions
- Revenue by Product: To analyze the revenue generated by each product to identify the top-selling products
- Monthly Sales Trends: To determine the sales made each month during the fiscal period and identify the trends
- Total Revenue per Year: Calculate the total revenue generated during the fiscal period (2023-2024)

## Tools Used
The following tools were used in the analysis.
1.  Microsoft Excel
- For Data Cleaning
- For Data Transformation
- For Data Visualization
2. GitHub for Portfolio Building
3. SQL Server to write Query
4. PowerBI
- For Data analysis 
- For Data Visualization

  ## Exploratory Data Analysis

  1. **Top-selling Product**

 The top-selling product is shoes, while socks is the lowest-selling product as shown in the bar chart below

 ```SQL QUERY

 SELECT SUM(Total_Sales) as TotalSalesPerProduct, Product FROM SalesData$
GROUP BY Product
ORDER BY SUM(Total_Sales) desc


![Query](https://github.com/user-attachments/assets/72f83be3-e8df-4127-8a54-b3edd4329b24)

     
![Top-sellingP](https://github.com/user-attachments/assets/b184b171-635d-40bc-8b6d-c4d161edec70)

2. **Regional Performance**
   
 The south region is the best-performing region with a revenue generation of 44.16% of the total revenue as shown in the pie chart below
   

![SalesByRegion](https://github.com/user-attachments/assets/967d29e4-9cf1-4d5f-ab4b-4b13e0177c20)

3. **Total Revenue per Year**

   The analysis revealed a decline in the total revenue from 2023 to 2024. The year 2023 recorded more sales than the year 2024 as shown below
   

   ![RevenuePerYear](https://github.com/user-attachments/assets/662d1cf7-dde5-4aa9-9326-1e3daf2c93da)
   
5. **Product yearly performance between years 2023 and 2024** 
   

![Pivot5_SalesData](https://github.com/user-attachments/assets/cd6e16c1-d9d2-4e9e-8926-8659b389bd16)

As shown in the table;
- Gloves maintained the same sales.
- Hat, Jacket and Shoes recorded an increase in sales
- Shirt and Socks recorded a decline in sales


6. **Monthly Sales Trend**

   
![Pivot6_SalesData](https://github.com/user-attachments/assets/f207d103-e2b5-462a-a360-7f58eba9e1bb)


![Pivot10 SalesData](https://github.com/user-attachments/assets/50a63343-a73c-4169-a7a7-0c90319553f1)


![Pivot7_SalesData](https://github.com/user-attachments/assets/98d620e5-33ae-4b71-bd7a-586dd423ac79)

7. **Yearly Regional Sales Trend** 


![Pivot9_SalesData](https://github.com/user-attachments/assets/6770bb80-0d5d-4806-ae64-e9c0c19bb4a3)


## Observations
Revenue declined in the East and South regions while increasing in the North and West regions. The West market is experiencing low revenue generation. The company may need to investigate the causes of this decline, such as changes in consumer behaviour, economic factors, or competitive pressures.

Focused marketing efforts and customer engagement strategies may be necessary to revitalize sales in declining regions.


![PowerBI_SalesData](https://github.com/user-attachments/assets/fedd1c06-1350-46de-a9de-e48a6c027a6c)


## Conclusion

The revenue data from 2023 to 2024 shows a declining trend. This highlights the company's need to analyze market conditions and implement strategies to boost performance and regain lost revenue.




