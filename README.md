# Consumer-Purchase-Analysis-Project
Data Analytics Project Showcasing consume purchasing pattern using Pyhton, SQL and power Bi

## 📌 Overview
This project analyzes consumer shopping behavior using a dataset of retail purchase transactions.  
It includes:  
- Data loading and cleaning in Python  
- Exploratory Data Analysis (EDA)  
- SQL queries using PostgreSQL  
- Power BI dashboard development  
- A final analytical report

---

## 📊 Dataset
**Records:** 3,900  
**Features:** 18 columns, including:  
- Customer demographics (age, gender, location, subscription status)  
- Purchase details (item, category, amount, season, size, color)  
- Behavioral metrics (discounts, promo codes, review rating, shipping type)  

**Data Notes:**  
- 37 missing values in `review_rating`  
- Some redundant fields removed during cleaning

---

## 🛠 Tools & Technologies
- Python (pandas, psycopg2)
- PostgreSQL (SQL analysis)
- Power BI (dashboard)
- Jupyter Notebook
- Git/GitHub

---

## 🔍 Project Steps

### 1. Data Loading (Python)
- Imported raw dataset using pandas  
- Inspected structure using `info()` and `describe()`

### 2. Data Cleaning & Preparation
- Imputed missing values  
- Standardized column names  
- Added new features such as `age_group`  
- Dropped redundant fields  
- Loaded cleaned data into PostgreSQL

### 3. Exploratory Data Analysis (EDA)
- Distribution analysis for spending and customer groups  
- Correlation checks  
- Visual exploration of trends

### 4. SQL Analysis (PostgreSQL)
- Revenue by demographic groups  
- High-spending discount users  
- Top-rated products  
- Standard vs express shipping comparison  
- Subscriber vs non-subscriber spending  
- Customer segmentation  
- Age-group revenue contribution  
- Category-wise best sellers  

### 5. Power BI Dashboard
- Created interactive dashboard visualizing:  
  - Revenue trends  
  - Customer segments  
  - Discount effects  
  - Category performance  
  - Ratings and shipping preferences  

---

## 📈 Key Insights
- Subscribers spend more on average  
- Express shipping users contribute higher revenue  
- Some discount users still fall into high-value segments  
- Top-rated products align with high-revenue categories  
- Frequent buyers strongly influence sales growth  



---

