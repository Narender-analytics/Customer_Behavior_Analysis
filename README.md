# 🛍️ Customer Shopping Behavior Analysis

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across various product categories. It uncovers insights into spending patterns, customer segments, product preferences, and subscription behavior to guide strategic business decisions.

## 📊 Project Workflow

### 1. Data Cleaning & Preparation (Python)
- Loaded dataset using `pandas`
- Handled missing values (e.g., imputed `review_rating` by category median)
- Standardized column names to snake_case
- Engineered features:
  - `age_group` from age
  - `purchase_frequency_days` from frequency
- Dropped redundant columns (`promo_code_used`)
- Connected to MYSQL for SQL analysis

### 2. Business Analysis (SQL)
- Revenue comparison by gender
- High-spending discount users
- Top-rated products
- Shipping type vs. purchase amount
- Subscriber vs. non-subscriber revenue
- Discount-dependent products
- Customer segmentation (New, Returning, Loyal)
- Top 3 products per category
- Repeat buyers vs. subscription status
- Revenue by age group

### 3. Dashboarding (Power BI)
- Built interactive dashboard showing:
  - Subscription breakdown
  - Revenue by category and age group
  - Shipping type filters
  - Review ratings and purchase trends

## 📌 Key Insights
- Male customers generated 2x revenue vs. female
- Express shipping users spent more on average
- Top-rated products: Gloves, Sandals, Boots
- Loyal customers form 80%+ of base
- Young Adults contributed highest revenue

## 💡 Business Recommendations
- Promote subscription benefits
- Launch loyalty rewards
- Optimize discount strategy
- Highlight top-rated products in campaigns
- Target high-revenue age groups

## 🛠️ Tools & Technologies
- Python (Pandas, NumPy)
- MYSQL (SQL queries)
- Power BI (Dashboarding)
