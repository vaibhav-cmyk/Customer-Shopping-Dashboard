🛍️ Customer Shopping Behavior Analysis
📌 Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across various product categories. The objective is to uncover insights into spending patterns, customer segments, product preferences, and subscription trends to guide data-driven business decisions.

📂 Dataset Summary

Total Records: 3,900

Columns: 18

Key Features:

Customer Demographics: Age, Gender, Location, Subscription Status

Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color

Shopping Behavior: Discount Applied, Promo Code Used, Frequency, Rating, Shipping Type

Missing Data: 37 values in review_rating column (imputed using median per category)

🧮 Analysis Workflow
1. Exploratory Data Analysis (Python)

Loaded and cleaned dataset using pandas.

Handled missing values and standardized column names.

Engineered new features:

age_group (binned customer ages)

purchase_frequency_days (time gap between purchases)

Integrated cleaned data into PostgreSQL for SQL-based analytics.

2. SQL Analysis

Performed in PostgreSQL to answer key business questions, including:

Revenue by Gender

Top Products by Rating

Subscribers vs. Non-Subscribers Spending

High-Spending Discount Users

Shipping Type Comparison

Revenue by Age Group

Customer Segmentation (New, Returning, Loyal)

3. Power BI Dashboard

Built an interactive dashboard for visualizing:

Revenue trends

Product performance

Customer segmentation

Subscription and shipping insights

💡 Business Recommendations

Boost Subscriptions: Offer exclusive benefits for members.

Loyalty Programs: Reward repeat buyers.

Review Discount Policies: Maintain balance between sales and margins.

Product Positioning: Highlight top-rated and best-selling items.

Targeted Marketing: Focus on high-spending demographics and express-shipping users.

🛠️ Tools & Technologies

Python (pandas, numpy, matplotlib, seaborn)

PostgreSQL

Power BI



