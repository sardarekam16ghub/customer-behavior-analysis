Customer Shopping Behavior Analysis
📌 Project Overview
This project analyzes 3,900 customer transactions across multiple product categories to uncover insights into spending patterns, customer segments, and subscription behavior.
The goal is to generate actionable business recommendations using Python, SQL, and Power BI.

📊 Dataset at a Glance
Transactions: 3,900 rows

Features: 18 columns (demographics, purchase details, shopping behavior)

Average Purchase Value: $59.76

Age Range: 18–70 years

Missing Values: 37 (in Review Rating column)

🛠️ Methodology
🔹 Data Preparation & Cleaning (Python + Pandas)
Loaded dataset and explored structure using df.info() and .describe()

Imputed missing Review Ratings with median per product category

Standardized column names to snake_case

Engineered new features: age_group bins and purchase_frequency_days

Connected cleaned dataset to PostgreSQL for SQL-based analysis

🔹 Analysis & Visualization
Revenue by Gender & Shipping Type

Male customers: $157,890 (double female revenue: $75,191)

Compared Standard vs. Express shipping spend behavior

Subscribers vs. Non-Subscribers

Subscription status linked with higher spend

Repeat buyers (>5 purchases) show strong subscription conversion potential

Customer Segmentation

Classified into New, Returning, Loyal segments

Revenue contribution analyzed by age groups

Top Products & Ratings

Identified Top 5 products by average rating

Listed Top 3 products per category for marketing focus

Power BI Dashboard

Interactive dashboard showcasing revenue, segments, product performance, and subscription trends
