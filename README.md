# 🦞 Lobster Land Marketing Campaign Analysis

📌 Overview

This project analyzes customer engagement and spending behavior across different marketing campaigns at Lobster Land, a theme park. The goal is to evaluate the effectiveness of various campaigns in influencing visitor spending and to derive insights for optimizing marketing strategies.

📊 Data

Dataset: lobster_land_campaigns_new.csv
Columns:
customerID: Unique identifier for customers
campaign_seen: The marketing campaign a customer interacted with
total_spending: The amount spent by the customer

📈 Key Analyses

Campaign Popularity Analysis
Used Seaborn to visualize campaign distribution.
Identified the Family Fun Campaign as the most viewed campaign.
Spending Behavior Analysis
Compared mean total spending across campaigns.
Found that the Loyalty Reward Push campaign led to the highest average spending.
Statistical Testing (Two-Sample t-tests)
Conducted pairwise comparisons to determine significant differences in spending.
Applied Bonferroni correction to adjust for multiple tests.
Found statistically significant differences in spending across all campaigns.

🛠️ Tools & Libraries

Python (Pandas, Seaborn, Matplotlib, SciPy)
Statistical Tests (t-tests, Bonferroni correction)
🔍 Insights & Recommendations

Campaigns like Thrill Seeker Blitz and Relaxation and Leisure Drive attract higher-spending visitors.
Loyalty Reward Push effectively increases spending among returning customers.
Future marketing efforts should focus on campaigns that drive higher revenue.
