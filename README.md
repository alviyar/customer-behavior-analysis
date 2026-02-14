<img width="1387" height="758" alt="image" src="https://github.com/user-attachments/assets/7e1c8c7c-d9d8-4ca1-839f-b5b03a486cf2" />

🛍️ Customer Shopping Behavior Analysis

📌 Overview
This project analyzes 3,900 customer purchase records to uncover insights into spending behavior, product performance, customer segmentation, and subscription trends.
The workflow covers data cleaning, SQL-based business analysis, and dashboard visualization.

📊 Dataset
3,900 rows | 18 columns
Includes customer demographics, purchase details, discounts, shipping type, ratings, and subscription status
37 missing values in review_rating handled during preprocessing

🐍 Data Processing (Python)
Cleaned and standardized column names
Imputed missing review ratings using median by category
Created features like age_group and purchase_frequency_days
Removed redundant columns
Loaded cleaned data into PostgreSQL

🗄️ SQL Business Analysis
Answered key business questions such as:
Revenue by gender and age group
Subscribers vs non-subscribers spending
High-spending discount users
Top-rated and most purchased products
Customer segmentation (New, Returning, Loyal)
Shipping type comparison

📈 Power BI Dashboard
Built an interactive dashboard to visualize:
Revenue trends
Customer segments
Product performance
Subscription impact

🎯 Key Outcomes
Identified high-revenue customer groups
Analyzed discount impact on spending
Evaluated subscription value
Provided strategic recommendations for marketing and loyalty programs

🛠️ Tech Stack
Python | PostgreSQL | Power BI

