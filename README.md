#AtliQO Bank: Credit Card Launch Analysis and A/B Testing


**Project Overview**
AtliQO Bank aims to expand its market share by launching a new credit card. The objective of this project was to analyze customer demographics and spending patterns to identify a high-potential "Untapped Market" and validate the launch strategy using statistical methods.

Phase 1: Data Cleaning and Preparation
The raw data contained several inconsistencies that required careful handling before analysis:

Age Filtering: Restructured the dataset to include only valid age groups between 18 and 64 years.

Handling Invalid Transactions: Identified over 4,700 transactions with a zero value in the Electronics category. These were corrected using the Median value of similar transactions to maintain data integrity.

Outlier Treatment: Implemented the Interquartile Range (IQR) method to detect and handle extreme transaction amounts that could have skewed the final results.

Phase 2: Exploratory Data Analysis (EDA) and Key Discovery
By visualizing the cleaned data, a significant business opportunity was identified within the 18-25 age group:

Market Share: This segment represents approximately 26% of the total customer base.

Spending Habits: High engagement was observed in Electronics, Fashion, and Beauty categories.

The Opportunity: Despite their high spending, this group had the lowest credit card penetration, making them the ideal target for a new product.

Phase 3: A/B Testing Framework
To validate the business hypothesis, a controlled experiment was conducted over a two-month period:

Control Group: 40 customers continuing with existing payment methods.

Test Group: 40 customers provided with the new Trial Credit Card.

Conversion Metric: The trial achieved a 40% conversion rate, indicating strong interest from the target demographic.

Phase 4: Statistical Validation (Hypothesis Testing)
To ensure the results were not due to random chance, a Two-Sample Z-Test was performed on the transaction amounts:

Z-Statistic: 2.76

Critical Z-Value: 1.64 (at 5% significance level)

P-Value: 0.0

Decision: Since the Z-score (2.76) is significantly higher than the Critical Value (1.64), we reject the Null Hypothesis.

Final Conclusion and Recommendation
The statistical evidence confirms that the new credit card significantly increased the average transaction amount for the 18-25 age group. Based on these findings, it is recommended that AtliQO Bank proceeds with a full-scale launch of the credit card tailored for young professionals and students.

Tech Stack
Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Statsmodels

Methodologies: Data Cleaning, EDA, Hypothesis Testing, A/B Testing
