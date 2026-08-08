# Final-Power-BI-Project
This Repo contains my final power bi project with ROUTE

## Dataset for project
apple_product_pricing_2020_2026.csv

## Business Problem
Apple needs a dashboard to analyze product pricing, discounts, ratings, and customer engagement to support pricing decisions.

## In this model, we have:
•	One Fact Table
•	Seven-Dimension Tables 

## The grain
Product which is recorded or updated in specific date

## DAX Calculations
### 1.	Basic / KPI Measures
•	Average Current Price
•	Average Launch Price
•	Average Savings
•	Average Discount %
•	Average Rating
•	Total Reviews
•	Highest Current Price
•	Lowest Current Price
•	Product Count
•	Product on Sale
•	Stock Availability %

### 2.	Dynamic Currency Measures
Because we have two currencies: INR & USD so we made a dynamic measure changes according to your choice and apply it to these measures:
•	Current Price
•	Launch Price
•	Highest Price
•	Lowest Price

#### Note
Current Price: Calculates the average current price of products based on the selected filters and currency. It’s just a name for the average current price

### 3.	Time Intelligence Measures 
•	Current Price MTD
•	Current Price QTD
•	Current Price YTD
•	Avg Current Previous Year
•	YoY Growth %
•	Rolling 3 Months Avg

### 4.	Analysis / Business Measures
These Measures are related to the analysis that we’re doing. For Example:
#### Sale Event
•	Products on Sale 
•	Average Discount by Sale Event 
•	Average Savings by Sale Event 
•	Average Rating by Sale Event 
•	Total Reviews by Sale Event 
#### Category
•	Product Count by Category 
•	Average Current Price by Category 
•	Average Discount by Category 
•	Average Rating by Category 
#### Platform
•	Product Count by Platform 
•	Average Current Price by Platform 
•	Average Rating by Platform 
•	Average Discount by Platform 
The Pros here that we don’t have to create specific measures for these attributes.

### 5.	Supporting Measures
Intermediate measures used by other calculations 

#### Note:
•	All DAX measures created during the project, including the core, time intelligence, supporting, and analytical measures, are available in the dedicated Measures table within the Power BI project file.




