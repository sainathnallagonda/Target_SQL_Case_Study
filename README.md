# Target SQL Case Study

## Project Overview
This case study analyzes e-commerce orders using SQL queries, focusing on customer insights, sales trends, and economic impact. The dataset contains transactional details, including order dates, locations, and payment methods.

## Objectives
- Perform **Exploratory Data Analysis (EDA)** on customer demographics and order distribution.
- Investigate **seasonality trends** and order patterns across different states and cities.
- Analyze **payment types, freight costs, and delivery timelines**.
- Evaluate **sales growth and percentage change in order values**.

## Dataset
The dataset includes:
- **Customers Table** (customer ID, location details)
- **Orders Table** (timestamps, purchase details)
- **Payments Table** (payment method, installments)
- **Order Items Table** (freight and item costs)

## Tools & Technologies Used
- **SQL** (`BigQuery`, `Google Cloud`)
- **Data Aggregation & Querying**
- **Exploratory Analysis** (`group by`, `count`, `sum`, `extract`)
- **Time-Series Analysis** (`month-over-month trends`)
- **Joins & Nested Queries** (`INNER JOIN`, `CASE` statements)

## Key Findings
- **Orders were placed from 4119 cities and 27 states** in the observed time range.
- **Strong growth in e-commerce sales**, with orders increasing sharply from 2016 to 2018.
- **Seasonal dip in orders** observed in **September and October** each year.
- **Most orders placed in the afternoon**, showing peak shopping hours.
- **SP state dominates** e-commerce orders, accounting for a **majority of sales**.
- **Freight value varies across states**, with **RR having the highest average freight cost**.
- **Delivery speed differs**, with some states consistently delivering ahead of estimated time.
- **Credit cards are the most common payment method**, followed by UPI.

## Recommendations
- Businesses should focus on **September-October dips**, optimizing marketing efforts.
- Target **underperforming states**, especially those with fewer customers and lower engagement.
- **Optimize freight costs and improve delivery accuracy** for states with high delays.
- Consider **installment-based payment options** to enhance accessibility for buyers.

## Repository Contents
- `target_sql_case_study.sql` – SQL queries for analysis.
- `target_data.csv` – Sample dataset.
- `README.md` – This file.

## Conclusion
This SQL-driven analysis provides insights into **customer behavior**, **economic impact**, and **e-commerce growth patterns**. Businesses can leverage these findings to **optimize logistics, improve sales strategy, and enhance customer engagement**.
