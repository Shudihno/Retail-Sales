
# Retail-Sales Data Agent

## OBJECTIVE
The objective was to:
*	Upload and prepare a retail sales dataset in Databricks
*	Create a Data Agent connected to the data
*	Write custom instructions for the agent
*	Test the agent with 10 business questions
*	Validate 3 answers against the source data
*	Provide business insights and recommendations

## TOOLS USED
*	The dataset is named: retail_sales_data
*	Environment: This project was completed using Databricks Community Edition with Apache Spark SQL.
*	Submission: This project was submitted on Github

## DATASET OVERVIEW
*	The dataset is named: retail_sales_data
*	Total rows: 1,000 transactions
*	Date range: January 2023 to January 2024


## STEPS FOLLOWED
* Uploaded CSV
* Table prep and checking my dataset rows and columns
* Setup and created my data agent called Retail Sale Data Analysis Agent
* Provided my data agent with instructions
* Review df.printSchema() and df.describe() output

## DATA AGENT INSTRUCTIONS
*	Group customers by Age Group
*	For each group, look at total money spent and total items bought.
*	Split by Gender (Male / Female)
*   Which age + gender group spends the most money? (best performing)
*   Which spends the least? (worst performing)
*   For each product category (Beauty, Clothing, Electronics), which age group buys the most?
*   For each product category (Beauty, Clothing, Electronics)
*   Which product category makes the most total money? 
*   Compare years using the Date column (2023 vs 2024)
*   Trends Over Time 
*   Compare Categories 
*   Marketing Ideas by Gender 
*   Performance & Trend Rules

## DATA QUESTIONS TESTED
1.	Which product category sells the most items for each age group? (Age groups: 18–25, 26–35, 36–50, 51–64)
2.	Which age group has the best sales (most money) and which has the worst sales (least money)?
3.	For each product category (Beauty, Clothing, Electronics), which age group buys the most?
4.	What is the average price per item? Also, what is the total money made and total items sold?
5.	Which year had more sales from 2023 or 2024? (Use the Date column. Only compare years that exist in the data.)
6.	In which month did each product category sell the most?
7.	Show me sales trends by month, by quarter, and by year. (How did sales go up or down over time?)
8.	Compare the three product categories (Beauty, Clothing, Electronics). Which is best and which is worst?
9.	Do men or women buy more? Show me total money and total items for each gender, broken down by product category.
10.	Which age group buys the most expensive items? (Expensive = price per unit over 300)

## KEY INSIGHTS
1. Best performing age group: 36-50 ($139,660 revenue)
2. Worst performing age group: 18-25 ($84,550 revenue)
3. Best product category: (e.g, product category has the highest      revenue?)
4. Worst product category: (e.g, Which product category has the lowest revenue?]
5. Total sales: $456,000 across 2,514 items
6. Average price per item: $179.89
7. Sales are heavily concentrated in 2023 (99.7% of revenue)

## BUSINESS RECOMMENDATIONS
1. Target the 36-50 age group – They spend the most money ($139,660). Create marketing campaigns focused on this group.
2. Investigate the 18-25 age group – They have the lowest total revenue but the highest average transaction value ($500). Consider more expensive products targeted at younger buyers.
3. Beauty products should be sold more as they make up the most product sold
4. Focus analysis on 2023 data – 2024 data is incomplete. Collect more 2024 data for proper year-over-year comparison.

## CONSCLUSION
What worked well:
*	The agent correctly answered all 10 questions
*	All 3 validated answers matched the source data
*	The agent provided useful insights beyond just numbers
*	The instructions successfully guided the agent to use correct age groups
