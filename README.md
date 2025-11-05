🛒 Customer Shopping Behavior Analysis
📄 Overview

This project explores customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The goal is to uncover insights into spending patterns, customer segments, and product preferences to help businesses make data-driven marketing and operational decisions.

📊 Dataset

Rows: 3,900

Columns: 18

Key Features:

Demographics: age, gender, location, subscription_status

Purchase Details: item_purchased, category, purchase_amount, season, size, color

Behavior: discount_applied, previous_purchases, review_rating, shipping_type

Missing Data: 37 missing values in the review_rating column (handled with median imputation).

🧰 Tools & Technologies

Python (Pandas, NumPy, Matplotlib, Seaborn) — Data loading, cleaning, and EDA

PostgreSQL / MySQL / SQL Server — Structured data queries and analysis

Power BI — Interactive dashboard creation

Gamma App — Automated presentation creation

MS Word / Google Docs — Report writing

⚙️ Steps Followed
1. Data Loading & Cleaning (Python)

Imported the dataset using pandas.

Explored data using .info() and .describe().

Handled missing values and standardized column names.

Engineered new features:

age_group (binned age ranges)

purchase_frequency_days (derived from timestamps)

Verified data consistency and removed redundant columns.

2. SQL Analysis

Performed structured business analysis using SQL queries such as:

Revenue by Gender

High-Spending Discount Users

Top 5 Products by Rating

Shipping Type Comparison (Standard vs. Express)

Subscribers vs. Non-Subscribers

Discount-Dependent Products

Customer Segmentation (New, Returning, Loyal)

Revenue by Age Group

3. Power BI Dashboard

Created an interactive Power BI dashboard showcasing:

Total Revenue and Orders

Top Products & Categories

Gender and Age Group Analysis

Shipping Type Insights

Subscription vs. Non-Subscription Trends

4. Reporting & Presentation

Comprehensive report summarizing methodology, insights, and visualizations.

Gamma Presentation (PPT) automatically generated from the report for a professional project showcase.

📈 Results & Insights

Female customers generated higher average revenue than males.

Loyal customers and subscribers contributed the majority of total revenue.

Express shipping users spent more on average.

Discount-heavy products boosted sales but reduced profit margins.

Recommended loyalty programs, subscription promotions, and targeted marketing for high-value segments.

🧭 How to Run the Project
Prerequisites

Python 3.x

Power BI Desktop

PostgreSQL / MySQL / SQL Server installed locally or on cloud

Required Python libraries:

pip install pandas numpy matplotlib seaborn psycopg2

Steps

Clone the repository

git clone https://github.com/your-username/customer-shopping-analysis.git
cd customer-shopping-analysis


Run the Python script to clean and upload data to your SQL database.

Execute SQL queries using any SQL client (pgAdmin, MySQL Workbench, SSMS).

Open the Power BI file (.pbix) to view the dashboard.

Read the final report (PDF) and open the Gamma presentation link for project summary.
