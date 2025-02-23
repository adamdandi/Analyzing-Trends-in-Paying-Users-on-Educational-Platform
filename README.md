### Project Title:  
Analyzing Trends in Paying Users on Educational Platform

### Analysis Type:  
Transaction Data Analysis & User Behavior Insights

### Tools Used:  
SQL, Python (Pandas, Matplotlib)

### Completion Date:  
December 27, 2024

### Company Industry:  
Education

### Company Name:  
Private
_____

### Overview Headline:  
**Uncovering Patterns in Paying User Behavior to Drive Growth Strategies**

### Overview:  
This project was focused on analyzing transaction data to understand the trends in paying users for an educational platform. The objective was to determine the number of new paying users, the cumulative number of paying users, and the recurring paying users on a monthly basis. The insights derived from this analysis aimed to support strategic decisions regarding user acquisition and retention.

### Data Details:  
The project utilized two main datasets:
1. **Platform Registration Data**: Contains information on 10,000 users, including their ID, registration date, and platform.
2. **Platform Transaction Data**: Contains 30,448 transactions, with details such as transaction ID, user ID, status, amount, and transaction date. Key variables include user ID, transaction status (success/failure), amount, and date.

### Problem Statement:  
The challenge was to analyze user behavior on the platform, specifically identifying:
- The number of new paying users each month.
- The cumulative number of paying users over time.
- The number of recurring paying users who made at least two successful transactions, and their growth over time.

### Solution:  
To address the problem, I followed these steps:

1. **Data Preparation**: The transaction and registration data were cleaned and formatted, including converting the transaction and registration dates into proper datetime formats for accurate monthly aggregation.

2. **SQL Queries**: I wrote a series of SQL queries to:
   - Identify **new paying users**: These are users who made their first successful transaction in a given month.
   - Track **cumulative paying users**: The total number of unique paying users up to each month.
   - Identify **recurring paying users**: Users who made at least two successful transactions, then calculate both new and cumulative recurring paying users.

3. **Data Aggregation**: I created monthly aggregates for both new and recurring paying users, ensuring the metrics captured fluctuations in user acquisition and retention.

4. **Trend Visualization**: Using Python and SQL, I visualized the growth rates and cumulative user counts through various plots, such as:
   - Growth rate comparisons for new paying users versus recurring paying users.
   - Identification of peak periods for both new paying and recurring users.
   - Cumulative trends, helping highlight longer-term user behavior patterns.

### Insight:  
Key findings from the analysis included:
- Peaks in new paying users during October 2019 and July 2020, likely due to external factors such as promotions or events.
- A steady increase in cumulative paying users, reaching 4,081 by May 2022.
- Recurring paying users grew slowly after 2021, indicating a need for strategies to boost retention.
- A slowdown in user growth was evident in 2022, signaling a shift in user engagement.

### Recommendation:  
Based on the insights, I recommended the following strategies:
1. **Enhance User Acquisition**: Investigate peak periods to replicate successful marketing campaigns. Use targeted marketing and optimize referral programs.
2. **Boost Recurring User Engagement**: Introduce loyalty programs, improve user experience, and use re-engagement strategies to reduce churn.
3. **Address 2022 Slowdown**: Explore market expansion, product innovations, and seasonal promotions to revive user interest.
4. **Continuous Data-Driven Monitoring**: Implement real-time analytics and A/B testing to adapt strategies dynamically based on user behavior.
