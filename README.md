# Optimizing E-commerce Intelligence with SQL Views
## Overview
This project delivers a set of **optimized SQL views** that streamline analysis of e-commerce performance by joining **orders, items, reviews, and shipments** into unified, query-ready structures. It enables fast insights into product quality, delivery efficiency, and customer satisfaction — cut **93%** query time (78 → 5 sec) and saved 800+ analyst hours/year by reducing complex multi-table queries into simple `SELECT` statements.

## Core Deliverables
1. Per-Item Performance Metrics - **product_avg_rating**

![alt text](https://github.com/laimichael004/Optimizing-E-commerce-Intelligence-with-SQL-Views/blob/0868590936132a35cfbb306093686c8fdf6d0f7e/product_avg_ratings.png)

Computes key indicators per item:
- avg_review_score – Average customer rating
- review_count – Total number of reviews

2. Delivery vs. Satisfaction Correlation View - **review_delivery**

![alt text](https://github.com/laimichael004/Optimizing-E-commerce-Intelligence-with-SQL-Views/blob/6af6d38081b0acf7220b03c36f5bd81b89d757a7/review_delivery.png)

- Maps actual delivery duration → review score
- Ideal for quick correlation checks and identifying service thresholds
- **Findings**: Positive correlation — faster delivery drives higher ratings

For Analysts & Data Teams
- No more 4-way JOINs — just select from a view
- Consistent metrics across reports
- Fast ad-hoc exploration with pre-aggregated insights




