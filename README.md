# Customer Shopping Behavior Analysis
### End-to-End Data Analytics Project (Python + SQL + Power BI)
<img width="1255" height="686" alt="customer_behavior_analysis_dashbaord" src="https://github.com/user-attachments/assets/9d6768d0-7d4f-4d3d-9f2a-47e64b34527e" />


##  Project Overview

A leading retail company wants to better understand customer shopping behavior to improve sales, customer engagement, and long-term loyalty.

This project analyzes customer purchase patterns across demographics, product categories, subscriptions, discounts, reviews, and shipping preferences to answer:

> **"How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?"**

The project follows a complete analytics workflow:

**Business Problem → Python Data Preparation → SQL Analysis → Power BI Dashboard → Insights → Business Recommendations**



##  Tech Stack

- **Python (Pandas)** – Data Cleaning & Feature Engineering
- **MySQL** – Business Analysis & SQL Queries
- **Power BI** – Interactive Dashboard & Visualization


##  Dataset

The dataset contains customer-level shopping transactions with information such as:

- Customer Demographics
- Product Categories
- Purchase Amount
- Review Ratings
- Subscription Status
- Shipping Preferences
- Discounts & Promotions
- Payment Methods
- Purchase Frequency


##  Data Preparation (Python)

The raw dataset was cleaned and transformed before analysis.

### Key Data Cleaning Steps

- Filled missing review ratings using **category-wise median**

- Converted column names to **snake_case**

- Created **Age Groups** for customer segmentation

  - Young Adult
  - Adult
  - Middle-Age
  - Senior

- Converted purchase frequency text into numerical values (`purchase_frequency_days`)

- Removed redundant columns after validating duplicate information

- Loaded cleaned data into MySQL for analysis


## SQL Business Analysis

After loading the cleaned data into MySQL, multiple business-focused queries were performed.

### Analysis Performed

- Revenue comparison by gender
- Subscription vs non-subscription spending behavior
- Top-rated products based on customer reviews
- Impact of shipping methods on spending
- Discount-driven product analysis
- Customer loyalty segmentation
- Repeat buyer subscription behavior
- Revenue contribution by age group
- Top-selling products within each category

These analyses helped uncover purchase drivers and customer behavior patterns.


## Power BI Dashboard

The final dashboard was designed to provide stakeholders with an interactive view of customer behavior.
### Dashboard Preview

<img width="1255" height="686" alt="customer_behavior_analysis_dashbaord" src="https://github.com/user-attachments/assets/ce59457e-d032-4a64-8e3c-a45aca519fa6" />


### Dashboard KPIs

- Number of Customers
- Average Purchase Amount
- Average Review Rating

### Interactive Filters

- Subscription Status
- Gender
- Product Category
- Shipping Type

### Visualizations Included

- Customer Distribution by Subscription Status
- Revenue by Category
- Sales by Category
- Revenue by Age Group
- Sales by Age Group



##  Key Insights

### Customer Behavior

- Approximately **73% customers are non-subscribers**, indicating growth opportunities for subscription programs.
- Subscribers contribute significantly to overall revenue and engagement.

### Product Performance

- Clothing generates the highest revenue and sales volume.
- Highly rated products can be leveraged in promotional campaigns.

### Customer Segmentation

- Young Adult and Middle-Age customers contribute the highest revenue.
- Loyal customers represent a valuable segment for retention strategies.

### Shipping Preferences

- Express and premium shipping customers tend to have higher purchase values.
- Faster delivery options influence customer spending behavior.


##  Business Recommendations

### 1. Increase Subscription Adoption

Promote exclusive discounts, early access offers, and loyalty perks to convert non-subscribers.

### 2. Strengthen Loyalty Programs

Reward repeat customers with points, cashback, and personalized offers.

### 3. Optimize Discount Strategy

Reduce dependency on discounts for products that already perform well.

### 4. Prioritize High-Performing Categories

Allocate marketing budget toward top-performing categories such as Clothing and Accessories.

### 5. Target High-Value Customer Segments

Focus campaigns on age groups and customer segments contributing the highest revenue.




##  Project Workflow

```text
Business Problem
        ↓
Data Cleaning & Feature Engineering (Python)
        ↓
Database Loading (MySQL)
        ↓
Business Analysis (SQL)
        ↓
Interactive Dashboard (Power BI)
        ↓
Insights & Recommendations
```

##  Skills Demonstrated

- Data Cleaning & Transformation
- Feature Engineering
- Exploratory Data Analysis (EDA)
- SQL Query Writing
- Customer Segmentation
- Business Analytics
- Dashboard Development
- Data Storytelling
- Business Recommendation Generation

