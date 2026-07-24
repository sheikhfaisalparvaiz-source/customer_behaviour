# 🛒 Customer Shopping Behavior & Trend Analysis

An end-to-end data analytics project exploring retail customer demographics, purchasing habits, and subscription drivers using **Python**, **SQL**, and **Power BI**.

---

## 📌 Executive Summary

Understanding customer purchasing patterns is vital for optimizing promotional strategies, product placement, and subscription retention. 

This project analyzes transactional data across **3,900 customer records** to uncover key sales drivers, evaluate the impact of discounts, and segment customers based on loyalty and spending behavior.

### Key Insights Uncovered:
- **Revenue Distribution:** Male customers generated higher aggregate revenue ($157.8K) compared to Female customers ($75.2K) in this dataset.
- **Subscription Rate:** Only **27%** of customers are active subscribers, yet their average spend ($59.49) is nearly identical to non-subscribers ($59.87), indicating an opportunity to increase value proposition for subscribers.
- **Discount Dependency:** Products like **Hats (50%)** and **Sneakers (49.66%)** have the highest rate of discounted purchases.

---

## 🛠️ Tech Stack & Workflow

- **Python (Pandas, NumPy, SQLAlchemy):** Data cleaning, missing value imputation (median category imputation), feature engineering (`age_group`, `purchase_frequency_days`), and database connection.
- **SQL (PostgreSQL / MySQL):** Advanced analytical querying using CTEs, window functions (`ROW_NUMBER`), conditional aggregations, and customer segmentation logic.
- **Power BI:** Interactive executive dashboard visualizing sales by category, revenue by age group, and subscription distributions.
- **Reporting:** Formal PDF report and PowerPoint deck for stakeholder presentation.

---

## 📁 Repository Structure

```text
customer_behaviour/
│
├── Customer_Shopping_Behavior_Analysis.ipynb  # Python EDA, Cleaning, & DB Migration
├── customer_behavior_sql_queries.sql         # 10 Analytical SQL Queries
├── customer_behavior_dashboard.pbix          # Interactive Power BI Dashboard
├── customer_shopping_behavior.csv            # Raw Dataset (3,900 rows)
├── Customer Shopping Behavior Analysis.pdf   # Complete Business Report & Visuals
└── README.md                                 # Project Documentation
