# Project 15: eccomerce data pipeline


## Description
this project involves, creating data pipeline, extract transform and load data into warehouse, and then use power bi for visualisation



This project involves 
## Tools and Technologies
- Amazon Redshift
- Amazon s3
- Power BI
- SQL
- python

## Setup Instructions
1. Clone the already transformed csv files.
2. Set up the Redshift database and load the prepared data.

## Usage Instructions
1. Connect to the Redshift database.
2. copy the prepared data into redshift
3. Run the SQL scripts in the `queries` folder to perform the analysis.
4. Open the Power BI file to view visualizations or see pictures below.

## Summary of Insights

### Sales Trends
- **Total Sales by Month**: Sales vary month-to-month with the highest in August 2002.
  ![total quantity sold by Month](https://github.com/Shagola/p15-/blob/main/p15/screens/Capture.PNG?raw=true)
- **Total Sales by Product**: The highest revenue was from Spring Roll Veg Mini.
  ![Total Sales by Product](screens/2.png) ![Second Image](screens/3.PNG)


### Customer Behavior
- **Total Orders and Spending**: Jeremy Smith spent the most overall, while Alison Alvarez made the most orders.
  ![Total Orders and Spending](screens/4.PNG)

### Product Performance
- **Top 10 Products by Quantity Sold**: Muffin Batt - Blueberry Passion and Muffin Batt - Carrot Spice were top sellers.
  ![Top 16 Products by Quantity Sold](screens/5.png)
- **Product Ratings**: Bagelers - Cinn/Brown Sugar had the highest rating.
  ![Product Ratings](screens/6.png)

## Limitations of Data
This analysis is based on randomly generated data, which may not accurately reflect real-world scenarios. The insights derived are purely for demonstration purposes and may not provide meaningful business insights.

## Conclusion
This project demonstrates the ability to analyze e-commerce data using SQL and visualize insights using Power BI.

