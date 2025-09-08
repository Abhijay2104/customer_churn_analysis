Customer Churn Analysis – Executive Summary
Objective
To analyze customer churn behaviour across various dimensions—particularly payment methods—using Python, and derive actionable insights to improve retention strategies.
Tools and Methodology
•	Libraries Used: pandas, matplotlib, seaborn
•	Techniques: Grouping and aggregating churn data, visualizing categorical distributions, calculating churn percentages
•	Visual Assets: Bar charts, count plots, and comparative churn breakdowns across multiple features
Key Findings from Data Visualizations
1. Churn by Payment Method
		
		
		
		
		
•	Insight: Customers using electronic checks are over twice as likely to churn compared to those using automatic payment methods.
•	Interpretation: Manual payment methods may introduce friction or reflect lower digital engagement.
2. Churn by Contract Type
		
		
		
		
•	Insight: Longer contracts significantly reduce churn. Two-year contracts show the highest retention at 97.2%.
•	Interpretation: Commitment level is a strong indicator of customer loyalty.
3. Churn by Tenure
•	Trend: Customers with tenure less than 12 months have a churn rate exceeding 50%.
•	Retention improves steadily with tenure, dropping below 10% for customers with over 60 months of service.
•	Insight: Early-stage customers are at highest risk.
•	Recommendation: Focus retention efforts on onboarding and first-year experience.
4. Churn by Internet Service Type
		
		
		
		
•	Insight: Fiber optic users churn at more than double the rate of DSL users.
•	Interpretation: May reflect service quality issues or pricing concerns.
5. Churn by Customer Support Features
•	Online Security: Customers without online security churn at 46.7%, compared to 15.3% with it.
•	Tech Support: Absence of tech support correlates with a churn rate of 42.4%, versus 14.8% for those with support.
•	Insight: Value-added services like security and support significantly reduce churn.
•	Recommendation: Bundle these features or promote them during onboarding.
Risk Factors Identified
1.	Electronic Check Payments – Highest churn rate among payment methods (43.6%)
2.	Month-to-Month Contracts – Churn rate of 43.9%, indicating low commitment
3.	Low Tenure – Customers in their first year are most likely to leave
4.	Fiber Optic Users – Elevated churn possibly due to service expectations
5.	Lack of Support Services – Absence of online security or tech support correlates with churn rates above 40%
Strategic Recommendations
•	Promote Automatic Payments: Encourage bank transfer or credit card auto-pay to reduce churn.
•	Incentivize Long-Term Contracts: Offer discounts or perks for one- and two-year plans.
•	Enhance Onboarding: Focus on first-year experience to retain new customers.
•	Bundle Support Services: Offer online security and tech support as part of standard packages.
•	Segment and Target: Use churn-prone profiles to guide personalized retention campaigns.
Technical Highlights
•	Used groupby() and value_counts() for segmentation
•	Visualized churn patterns with seaborn.barplot() and countplot()
•	Calculated churn percentages for categorical features
•	Optional integration with Power BI for interactive dashboards




