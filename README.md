## Apple Product Pricing 2020 - 2026 🍎
_______________________________________________________________________________________________________________________________
## Business Problem
Apple needs a dashboard to analyze product pricing, discounts, ratings, and customer engagement to support pricing decisions.
_______________________________________________________________________________________________________________________________
## The grain
Product which is recorded or updated in specific date
__________________________________________________________
📂 Dataset
Source: [apple_product_pricing_2020_2026.csv]
•	One Fact Table
•	Seven-Dimension Tables 
__________________________________________________________
🧹 Data Preparation
The dataset was prepared using:
•	Data cleaning
•	Handling missing values
•	Removing duplicates
•	Data type transformation
•	Creating calculated columns
•	Creating relationships
•	Data modeling
_______________________________

## Dashboard 
### Welcome Page 
![Welcome_Page](Images/Welcome%20Page%20-%20Apple%20Dashboard.png)


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



Project Readme Power BI
📊 Project Name
📌 Project Overview
Briefly describe what the project is about and why it was created.

________________________________________

________________________________________
📂 Dataset
Source: [Dataset Source]
Time Period: [Start Year] – [End Year]
Main Tables / Columns:
•	Table 1
•	Table 2
•	Table 3
________________________________________
🧹 Data Preparation
The dataset was prepared using:
•	Data cleaning
•	Handling missing values
•	Removing duplicates
•	Data type transformation
•	Creating calculated columns
•	Creating relationships
•	Data modeling
________________________________________
🗂️ Data Model
Describe the data model used in the project.
Example:
•	Fact Sales
•	Dim Customer
•	Dim Product
•	Dim Store
•	Dim Date
________________________________________
📊 Analysis & Dashboard
The project includes the following analysis areas:
1. Overview
•	Total Revenue
•	Total Orders
•	Total Quantity
•	Average Order Value
2. Product Analysis
•	Top-selling products
•	Product performance
•	Category performance
3. Customer Analysis
•	Customer segmentation
•	Customer contribution
•	Customer behavior
4. Time Analysis
•	Monthly trends
•	Year-over-Year growth
•	Seasonal patterns
________________________________________
🔑 Key Insights
Insight 1
Describe the most important finding.
Insight 2
Describe another important finding.
Insight 3
Describe another important finding.
________________________________________
💡 Business Recommendations
Based on the analysis:
1.	Recommendation related to the first insight.
2.	Recommendation related to the second insight.
3.	Recommendation related to the third insight.
________________________________________
🖼️ Dashboard Preview
Overview
Detailed Analysis
________________________________________
🛠️ Tools & Technologies
•	SQL
•	Power BI
•	DAX
•	Power Query
•	Excel
•	Python
________________________________________
📁 Repository Structure
Project/
│
├── Dataset/
├── SQL/
├── Power BI/
├── Images/
├── Documentation/
└── README.md
________________________________________
👤 Author
Ali Magdy
GitHub | LinkedIn

