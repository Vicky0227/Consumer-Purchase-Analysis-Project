# Consumer-Purchase-Analysis-Project
Data Analytics Project Showcasing consume purchasing pattern using Pyhton, SQL and power Bi
📌 Overview

This project analyzes consumer shopping behavior using a dataset of retail purchase transactions. The goal is to uncover patterns in spending habits, product preferences, customer segments, and subscription behavior to support data-driven business decisions.

The workflow includes:

Data loading and cleaning in Python

Exploratory Data Analysis (EDA)

SQL-based business queries using PostgreSQL

Power BI dashboard development

A final analytical report summarizing insights

📊 Dataset

Source: Provided consumer purchase dataset 

Consumer purchase Analysis Repo…


Records: ~3,900 rows
Features: 18 columns covering

Customer demographics (age, gender, location, subscription status)

Purchase information (item, category, price, size, color, season)

Behavioral data (discount use, shipping type, previous purchases, review rating, frequency)

Data Notes:

37 missing values in review_rating

Required cleaning and feature engineering before analysis

🛠 Tools & Technologies

Python: pandas, numpy, matplotlib, seaborn, psycopg2

SQL: PostgreSQL for analytical queries

Power BI: Dashboard creation and visualization

Jupyter Notebook: EDA workflow and data cleaning

Git/GitHub: Version control

🔍 Project Steps
1. Data Loading (Python)

Imported raw dataset using pandas

Checked structure and summary statistics (info(), describe())

2. Data Cleaning & Preparation

Handled missing values (imputed median rating per category)

Standardized column names to snake_case

Created new features:

age_group based on age bins

purchase_frequency_days derived from timestamp calculations

Removed redundant fields (e.g., dropped promo code field when correlated with discount usage)

3. Exploratory Data Analysis (EDA)

Distribution checks for demographics and purchase behavior

Correlation analysis for rating, revenue, discounts, etc.

Visualizations for spending trends, category popularity, and subscription influence

4. SQL Analysis on PostgreSQL

Executed queries to answer business questions, including:

Revenue comparisons across demographics

Top-rated and top-selling products

Effect of discounts on spending behavior

Shipping type impact on purchase amount

Subscription vs. non-subscription spending analysis

Customer segmentation (new, returning, loyal)

Age-group revenue contribution

Category-wise top 3 most purchased products

5. Power BI Dashboard

An interactive dashboard was created to visualize:

Revenue trends

Customer segments

Discount usage impact

Product category performance

Ratings and shipping preferences

Subscription behavior analysis

📈 Results & Insights

Key findings from the analysis 

Consumer purchase Analysis Repo…

:

Subscribers spend more on average than non-subscribers

Female and male customers show differing revenue contributions by product category

Discount usage does not always indicate low spend—some high-value buyers use discounts

Express shipping users tend to generate higher revenue

Top-rated products align with categories that produce the most revenue

High-frequency buyers contribute significantly to long-term revenue
