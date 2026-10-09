## Project Overview
In a competitive e-commerce environment, businesses rely on data to understand what drives revenue, how customers behave, and which products contribute the most to overall performance. This project presents an Exploratory Data Analysis (EDA) of an e-commerce sales dataset using SQL, with the goal of uncovering actionable insights that can support strategic, operational, and marketing decisions.

## Business Problem
The e-commerce business operates across multiple product categories, including Bikes, Components, Clothing, and Accessories, serving customers across several countries. With a diverse product catalog and geographically distributed customer base, the business needs a clearer understanding of its sales performance, customer distribution, and product contribution. The goal of this exploratory data analysis is to use SQL to examine sales trends, identify top-performing products and markets, and uncover patterns in customer and product performance to support informed, data-driven business decisions.

## Dataset
The company’s data is structured using a star schema, consisting of:
- A Sales fact table capturing transactional details such as order dates, quantities, prices, and revenue
- Customer and Product dimension tables containing demographic and product classification information

## Tools
To complete this project, I used the following tools:
 
- SQL: Core tool for data exploration, joins, aggregations, and analysis
- PostgreSQL: Relational database used to store and query the data
- gAdmin / VS Code: For writing and executing SQL queries

## Analysis Performed
Performed exploratory data analysis using PostgreSQL to examine database structures, explore customer and product dimensions, and analyze sales performance. Used SQL queries, joins, aggregations, and ranking techniques to evaluate key business metrics, identify top-performing products, examine customer distribution across countries, and uncover patterns in sales and customer behavior. The analysis provides a foundation for understanding business performance and identifying opportunities for further investigation.

## Key Insights
This Exploratory Data Analysis revealed several clear and actionable patterns across sales, products, customers, and geography.

- Total sales amount to $29.36M, driven overwhelmingly by the Bikes category, which alone generated $28.3M+ in revenue.
- The product catalog is largest in Components (127 products), yet this category does not translate into proportional revenue.
- The customer base is evenly distributed by gender, indicating no gender-driven bias in purchasing behavior.
- The United States is the largest market across customers, sales volume, and items sold.

## Business Recommendations
The business should prioritize understanding customer purchasing patterns in key markets, particularly the United States, Australia, and the United Kingdom, to identify opportunities for customer retention and growth. Top-selling products, such as Mountain-200 Black-46, should be examined further to understand the factors driving their performance and identify potential cross-selling opportunities. Additionally, the business should evaluate sales and profitability across product categories and countries to identify growth opportunities, optimize product offerings, and support data-driven decisions on marketing and inventory planning.

## Full Analysis Report
[View the complete SQL EDA Report](report/ecommerce_eda_report.pdf)
