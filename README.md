# Customer Shopping Behaviour Analysis

## Problem Statement

Retail businesses often struggle to understand what drives customer spending, which segments are most valuable, and where revenue is being lost. Without clear visibility into customer behaviour — such as the impact of discounts, subscription patterns, and seasonal trends — businesses cannot make informed decisions on marketing, inventory, or customer retention.

This project aims to analyse a retail customer dataset to uncover spending patterns, identify high-value segments, and provide actionable insights that can help improve revenue and reduce churn.

---

## Why This Project

Understanding customer behaviour is at the core of any data-driven retail strategy. This project was built to demonstrate how raw transactional data can be transformed into meaningful business insights using SQL, Python, and Power BI — covering the full analytics pipeline from data extraction to visual reporting.

---

## What Was Done

### Data Analysis with SQL
The dataset was loaded into PostgreSQL and queried to answer key business questions. The analysis covered revenue breakdowns by gender, age group, and product category, discount usage patterns, customer loyalty segmentation, subscription behaviour, and churn risk identification. Window functions were used to rank customers within segments, and CTEs were used to build multi-step logic for segmentation and benchmarking.

### Exploratory Data Analysis with Python
A Jupyter notebook was used to clean the data, explore distributions, and visualise relationships between variables such as age, purchase amount, rating, and frequency of purchases. This helped validate findings from SQL and surface additional patterns.

### Power BI Dashboard
An interactive dashboard was built to present the key findings visually. It includes KPI cards for average purchase amount ($59.76), average review rating (3.75), and total customers (3.9K), along with charts breaking down revenue and customer count by category, age group, and subscription status. Slicers allow filtering by gender, category, shipping type, and subscription status.

---

## Key Findings

- Clothing is the highest-grossing category, contributing the largest share of both revenue and customer volume, followed by Accessories, Footwear, and Outerwear.
- Young Adults and Middle-aged customers are the top spending segments, together accounting for the majority of total revenue.
- Only 27% of customers are subscribed. Subscribed customers show higher average spend and stronger loyalty, making subscription growth a clear revenue opportunity.
- A significant portion of customers who applied discounts still spent above the average purchase amount, suggesting discounts are not hurting revenue quality.
- Repeat buyers (more than 5 previous purchases) have a noticeably higher subscription rate, indicating that loyalty and subscription are strongly linked.
- Shipping type had minimal effect on average spend, meaning customers are not being driven by delivery perks alone.
- Churn risk analysis among subscribers revealed a subset of customers with low ratings and infrequent purchases who are at risk of dropping off.

---

## Tools Used

- PostgreSQL and pgAdmin4 for querying and analysis
- Python (Pandas, Matplotlib, Seaborn) for EDA
- Power BI for dashboard and reporting
- GitHub for version control and project documentation

---

## Author

**Rakshit Bhardwaj**
B.Tech Student — NSUT Delhi
rakshit.bhardwaj.ug23@nsut.ac.in
