# E-Commerce-Cohort-Retention-CLTV-Analysis
## Executive Problem Statement
Acquiring new customers is up to five times more expensive than retaining existing ones.
High-growth startups often boast about rapid user acquisition but fail to track if those users
actually stick around. If a business loses customers faster than it acquires them, it will inevitably
collapse.
The objective of this project is to perform a deep-dive Cohort Analysis to understand user
retention and calculate Customer Lifetime Value (CLTV). By grouping users based on their
acquisition month, the intern will identify exactly when users churn and provide data-backed
recommendations to improve retention.
## Business Objectives and Key Performance Indicators
The strategic goal is to identify churn patterns. Does a specific product feature cause users to
stay? Do users acquired during Black Friday churn faster than others? Success is quantified by
producing a clean Cohort Retention Heatmap and an accurate predictive model for the
12-month CLTV of different user segments.

## Four-Week Engineering Roadmap
### Week 1: Transactional Data Cleaning and Wrangling
The intern will ingest a raw transactional dataset (e.g., an online retail or SaaS subscription log).
Using Python, the intern must filter out refunded/failed transactions, handle missing user IDs,
and calculate the "Cohort Month" (the month of the first transaction) for every unique user.
### Week 2: Building the Cohort Retention Matrix
Week two is heavily focused on data manipulation. The intern will use Pandas groupby and
pivot_table functions (or SQL pivot techniques) to build a retention matrix. The matrix must
calculate the absolute number of retained users and the percentage retention rate for Month 0,
Month 1, Month 2, etc.
### Week 3: Customer Lifetime Value (CLTV) Calculation
The third week introduces financial metrics. The intern will segment the cohorts (e.g., by
acquisition channel or geographic region) and calculate the Average Order Value (AOV) and
Purchase Frequency. Using these metrics, the intern will calculate the historical CLTV for each
segment.
### Week 4: Visualization and Strategic Insights
The final week focuses on storytelling. The intern will use Seaborn/Matplotlib or a BI tool to plot
the Retention Heatmap and line charts showing retention decay curves. The final GitHub
submission must include a detailed README explaining the business implications (e.g.,
"Retention drops by 40% in Month 2; recommend implementing an automated re-engagement
email sequence").
