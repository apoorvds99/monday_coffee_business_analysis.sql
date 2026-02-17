# Monday Coffee SQL Analysis

## Project Overview
This project analyzes sales, customer behavior, product performance, and city-level business metrics for Monday Coffee using SQL.

The goal is to generate actionable insights that can help the company improve revenue, customer retention, and location strategy.

---

## Dataset
The dataset contains four tables:

1. city – city-level data including population and rent
2. customers – customer information
3. products – product catalog
4. sales – transaction-level data

---

## Business Questions Solved
1. Total revenue generated
2. Monthly revenue trends
3. Average order value
4. Top products by revenue
5. Most frequently sold products
6. Highest-rated products
7. Top customers by spending
8. Average purchases per customer
9. Repeat customer percentage
10. Revenue by city
11. Revenue per customer by city
12. Revenue per capita
13. Revenue-to-rent ratio
14. Top product per city
15. Month-over-month growth rate

---

## Key Business Insights

- The company generated over ₹60 lakh in total revenue during the analysis period.
- Revenue showed fluctuations month-to-month, indicating possible seasonality or campaign-driven sales.
- The Cold Brew Coffee Pack is the top-performing product across most cities.
- A small group of customers contributes a significant portion of total revenue.
- The repeat customer rate is extremely high, indicating strong customer loyalty.
- Pune and Jaipur show the highest revenue efficiency, both per capita and relative to rent.
- Metro cities like Bangalore and Delhi have high revenue but lower profitability due to higher rent.

---

## Business Recommendations

- Focus marketing and expansion efforts in high-efficiency cities like Pune and Jaipur.
- Promote the Cold Brew Coffee Pack as a flagship product.
- Introduce bundles and subscriptions to increase average order value.
- Investigate causes of revenue drops in certain months and replicate successful campaigns.

---

## Key SQL Concepts Used
- Joins
- Aggregations
- GROUP BY and HAVING
- Subqueries
- Common Table Expressions (CTEs)
- Window functions (ROW_NUMBER, LAG)

---

## Tools Used
- PostgreSQL
- SQL
