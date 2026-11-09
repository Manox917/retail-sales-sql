# Duka Smart Electronics: Retail Sales SQL Analysis

## 1. Project Overview

Duka Smart Electronics is a fictional Kenyan electronics retailer operating across ten towns, including Nairobi, Mombasa, Meru and Machakos.

The business sells mobile phones, laptops, accessories, televisions and home appliances. Trading since January 2025, the company maintains transactional sales data that can be used to understand customer purchasing behaviour, product performance, revenue trends and profitability.

This project uses PostgreSQL to analyse the retailer's sales database and answer 46 business questions to support data-driven management decisions.

## 2. Project Objectives

- Analyse customer purchasing behaviour and identify high-value customers.
- Evaluate product and category revenue performance.
- Calculate product costs, profits and profit margins.
- Identify monthly sales trends and revenue growth.
- Investigate customer retention and purchasing patterns.
- Develop reusable SQL views and functions.
- Generate actionable business recommendations.

## 3. Tools and Technologies

- PostgreSQL
- DBeaver / pgAdmin
- SQL
- Git and GitHub

## 4. Repository Structure

```text
retail-sales-sql/
├── README.md
├── schema.sql
├── queries.sql
├── insights.md
└── screenshots/
```

## 5. Key Business Findings

The analysis identified Mobile Phones as the leading category in completed-order revenue and absolute profit. Accessories recorded the highest profit margin at approximately 42.39%.

VIP customers recorded the highest average customer spending at KSh 253,251.88, followed by Corporate customers at KSh 197,958.71 and Retail customers at KSh 163,575.21.

Further findings and management recommendations are documented in `insights.md`.

## 6. How to Run the Project

1. Install PostgreSQL.
2. Create the project database.
3. Execute `schema.sql` to create the database tables.
4. Load the supplied project dataset.
5. Execute `queries.sql` to reproduce the 46 business analyses.
6. Review the findings in `insights.md`.

## 7. Business Value

The project demonstrates how SQL can transform raw retail transaction data into meaningful business information, helping management make informed decisions about customer retention, inventory, pricing, product profitability and sales performance.

## 8. Author

**Samson Nyakang'o Manono**



