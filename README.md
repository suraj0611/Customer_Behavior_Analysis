# Customer_Behavior_Analysis
Data Analytics Project Showcasing Customer Behavior Analysis Using (Python , SQL Server , Power BI).

**1️ - Overview**

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories.

The objective is to:

Understand customer demographics and spending patterns

Identify high-value customers and segments

Analyze the impact of discounts and subscriptions

Build interactive business dashboards

Provide actionable business recommendations

The project covers end-to-end data analytics, including Python EDA, SQL Server analysis, Power BI dashboarding, reporting, and presentation.

**2️ - Dataset**

Source: Transactional retail dataset
Total Records: 3,900
Total Columns: 18

Key Features:

Customer demographics (Age, Gender, Location)

Subscription status

Product details (Category, Item, Season, Size, Color)

Purchase amount

Review rating

Discount usage

Shipping type

Purchase frequency

Data Issues Identified:

37 missing values in the review_rating column

Redundant columns (discount_applied & promo_code_used)

Inconsistent column naming format

**3️ -  Tools & Technologies**

Python (Pandas, NumPy, Matplotlib, Seaborn)

SQL Server

Power BI

Gamma (for PPT creation)

Jupyter Notebook

**4️ -  Project Workflow / Steps**

**Step 1: Data Loading & Cleaning (Python)**

Loaded dataset using Pandas

Performed .info() and .describe() for structure understanding

Handled missing values (imputed median rating by category)

Standardized column names (snake_case)

Created new features:

age_group

purchase_frequency_days

Removed redundant columns

Notebook file:
shopping_behaviour.ipynb

**Step 2: SQL Analysis (SQL Server)**

Cleaned data was loaded into SQL Server for structured business queries.

SQL file:
customer_behavior_project.sql

Key Business Queries:

Revenue by gender

High-spending discount users

Top 5 products by average rating

Shipping type comparison

Subscribers vs non-subscribers revenue

Discount-dependent products

Customer segmentation (New / Returning / Loyal)

Revenue by age group

Repeat buyers vs subscriptions

Top products per category

This step demonstrates strong SQL skills including:

GROUP BY

JOINs

CASE statements

Aggregations

Subqueries

Ranking functions

**Step 3: Power BI Dashboard**

Power BI file:
Customer Behavior Report.pbix 

Customer Shopping Behavior Anal…

Built an interactive dashboard with:

KPI cards (Total Customers, Avg Purchase, Avg Rating)

Revenue by category

Revenue by age group

Subscription distribution

Sales comparison by shipping type

Category-level performance analysis

Dynamic slicers (Gender, Category, Shipping Type, Subscription)

The dashboard provides decision-ready business insights.

**Step 4: Final Report & Presentation**

Business report created in PDF format
Customer Shopping Behavior Analysis.pdf

Presentation slides created using Gamma

Summarized insights and recommendations for stakeholders

**5️ - Dashboard Highlights**

Total Customers: 3.9K

Average Purchase Amount: ~$59

Average Review Rating: 3.75

Loyal Customers: Majority segment

Express shipping users spend slightly more

Certain products are highly discount-dependent

The dashboard enables filtering and dynamic business exploration.

**6️ - Key Results & Insights**

-> Male customers generated higher total revenue
-> Loyal customers form the largest segment
-> Discount-heavy products can impact margins
-> Subscribers do not significantly outspend non-subscribers
-> Young adults contribute the highest revenue
-> Express shipping customers show slightly higher average purchase

**7️ - Business Recommendations**

Improve subscription benefits to increase conversion

Introduce loyalty rewards for repeat customers

Optimize discount strategy to protect margins

Promote top-rated products in campaigns

Focus marketing on high-revenue age groups

Target express-shipping customers with premium offers
