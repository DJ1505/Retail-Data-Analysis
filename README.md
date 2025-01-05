# Retail Data Analysis with SQL

## Overview
This project involves comprehensive analysis of retail data using SQL. The analysis includes data preparation, transformation, and insights generation across customer demographics, transactions, and product categories. The project focuses on identifying trends, customer behaviors, sales performance, and revenue insights to support business decision-making.

---

## Project Objectives
1. **Data Preparation and Cleaning**:
   - Validate and transform date formats across datasets.
   - Calculate the range of available transaction data.
   - Link subcategories to their respective product categories.

2. **Key Insights and Analytics**:
   - Identify the most frequently used transaction channels.
   - Analyze customer demographics by gender and city.
   - Determine subcategories, sales trends, and top-performing categories.
   - Compute revenues and returns by product category and store type.
   - Explore customer behavior based on age and transaction patterns.

3. **Advanced Business Insights**:
   - Determine top-performing product categories and subcategories.
   - Analyze percentage of sales and returns across categories.
   - Identify store types with maximum sales by value and quantity.

---

## Database Schema
The database includes the following tables:
1. **Customer**:
   - Contains customer demographic details such as age, gender, and city.
2. **Transactions**:
   - Records transaction details, including date, quantity, store type, and revenue.
3. **Product Category Info (prod_cat_info)**:
   - Maps product categories to their subcategories.

---

## Analysis Highlights
### Data Preparation
1. Converted date formats for `Customer` and `Transactions` tables.
2. Calculated the range of transaction data in days, months, and years.
3. Linked subcategories like "DIY" to their parent categories.

### Insights and Results
1. **Top Channel**: Identified the most frequently used transaction channel.
2. **Customer Analysis**: Counted male and female customers and identified the city with the highest customer count.
3. **Revenue Insights**:
   - Calculated combined revenue for specific categories in flagship stores.
   - Analyzed revenue contributions by male customers in the electronics category.
4. **Product Trends**:
   - Found the subcategories with the maximum sales and returns.
   - Identified top categories by revenue and quantity sold.
5. **Customer Behavior**:
   - Analyzed transactions by customers aged 25-35 in the last 30 days.
   - Identified customers with more than 10 transactions excluding returns.

---

## SQL Queries and Their Purpose
1. **Data Preparation Queries**:
   - Calculate row counts in tables.
   - Convert and format date fields.
   - Find subcategories and time range of transactions.

2. **Business Insights Queries**:
   - Identify top categories, store types, and transaction trends.
   - Calculate total and average revenues across demographics and product categories.
   - Determine percentage contributions of sales and returns.

3. **Advanced Analysis Queries**:
   - Find top-performing categories and subcategories.
   - Compute average revenue for top product categories.

---

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/retail-data-analysis-sql.git
