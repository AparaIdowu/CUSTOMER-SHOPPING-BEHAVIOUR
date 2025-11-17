# CUSTOMER SHOPPING BEHAVIOUR
A complete end-to-end data analytics project involving data cleaning (Python), database modeling &amp; insights (SQL), and an interactive dashboard (Power BI) to help a retail company understand customer trends and improve business decisions.
This project explores customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The goal is to uncover insights into spending patterns, customer segments, product preferences, and subscription behavior that can guide strategic business decisions.

**Project Overview**
The analysis focuses on identifying key factors that influence customer decisions such as:
Discounts and reviews
Shopping frequency
Subscription status
Demographics (age & gender)
Product categories and preferences
Seasonal purchasing trends
Insights were generated using Python, SQL (PostgreSQL), and Power BI.

**Dataset Summary**
Rows: 3,900
Columns: 18
Data Types: Customer demographics, purchase details, shopping behavior
Missing Data: 37 values in the review_rating column (imputed with category median)

**Python Analysis (EDA)**

Key steps in Exploratory Data Analysis included:
Data loading and initial inspection (df.info(), df.describe())
Missing value treatment for review_rating
Column standardization to snake_case

Feature engineering:
age_group
purchase_frequency_days
Dropping redundant column promo_code_used
Exporting cleaned data to PostgreSQL for SQL analysis

**SQL Analysis (Business Insights)**
Structured analysis in PostgreSQL included:
Revenue by gender
High-spending discount users
Top-rated products
Shipping type comparison
Subscriber vs. non-subscriber spending
Discount-dependent products
Customer segmentation (New, Returning, Loyal)
Top products per category
Subscription likelihood of repeat buyers
Revenue contribution by age group

**Power BI Dashboard**
A Power BI dashboard visualizes:
Revenue trends
Customer segments
Product performance
Discount usage
Subscription impact
Seasonal and demographic insights

**💡 Business Recommendations**
Promote subscription benefits to increase revenue
Strengthen loyalty programs for repeat buyers
Optimize discount strategy to balance sales and margins

Highlight top-rated and best-selling products

Target high-revenue age groups and express-shipping users
