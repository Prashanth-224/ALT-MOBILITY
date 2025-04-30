Summary of Findings: Alt Mobility Data Analysis

**Key Insights from SQL Queries**

1. Order Status and Sales Trends:

Delivered orders contributed the highest to total revenue.

A large portion of orders remains in 'Pending' or 'Cancelled' states, reflecting missed revenue opportunities.

Seasonal trends showed higher order volumes in Q2 and Q4, suggesting peak marketing or demand cycles.

2. Customer Behavior Analysis:

Around 65% of customers made only a single purchase, while 35% were repeat buyers.

Repeat customers spent 2.5x more than one-time buyers and showed higher engagement over time.

Customer lifecycle analysis revealed that most second orders occurred within 1-2 months of the first purchase.

3. Payment Success & Trends:

Overall payment success rate is approximately 92%, with failure rates concentrated around PayPal transactions.

Payment failures have declined over time, indicating platform or UX improvements.

Credit cards remain the most reliable method.

Monthly payment trends showed inconsistencies, which could be used to pinpoint weak processing periods.

4. Order-Payment Consolidation:

A comprehensive LEFT JOIN between orders and payments helps reveal unpaid but completed orders.

This cross-tabulated view is essential for finance, customer support, and operations.

Identifies potential fulfillment issues when orders show as delivered but payment is missing.

 **Observations from Customer Retention Analysis**  

Using the cohort-based model implemented in Python:

Retention drops significantly after Month 0 (initial purchase month).

Few customers return after the second month.

The most successful cohorts (e.g., Q2 2023) showed retention up to Month 4, which aligns with strong campaign or product performance during that period.

Heatmap visualization clearly tracks how each cohort performs over time and provides a pattern of post-purchase behavior.

 **Recommendations for Alt Mobility**

Short-Term Actions:

Improve Fulfillment Efficiency: Reduce the number of pending/cancelled orders via better inventory and logistics planning.

Retarget One-Time Buyers: Automate re-engagement flows within 30 days post-purchase with tailored offers.

Fix Payment Pain Points: Reduce failed payments by promoting credit card usage or improving fallback options.

Medium-Term Strategies:

Segment & Reward Repeat Customers: Use spending and order count segmentation to offer loyalty perks.

Monthly Performance Dashboards: Track order-to-payment conversion and cohort retention KPIs.

Long-Term Vision:

Automated Cohort Monitoring: Use cohort analysis to shape lifecycle campaigns and long-term LTV prediction.

Data-Driven Personalization: Target high-retention cohorts with exclusive features, benefits, or product previews.

Continuous Testing: A/B test onboarding flows, payment gateways, and loyalty campaigns based on cohort behavior.

This analysis provides Alt Mobility with actionable intelligence on how to retain customers, optimize revenue, and improve end-to-end operational health.
