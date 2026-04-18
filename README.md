                                    Telecom Customer Churn Analysis

 Excel, SQL and Power BI analysis of telecom customer data to understand churn behavior, customer patterns, and retention opportunities.

📊 Project Overview

This project focuses on analyzing telecom customer data to understand why customers are leaving and what the business can do to retain them.

I Used Excel for data cleaning, SQL for data analysis and Power BI for visualization, I explored customer behavior, contract types, payment methods, and churn patterns to generate meaningful insights.

The goal of these project is simple:
i. Understand churn
ii. Identify at-risk customers
iii. Suggest practical ways to reduce customer loss

Tools I Used:
 Excel, Microsoft SQL Server and Power BI

Skills Demonstrated:
Data cleaning, aggregation, CASE statements, Subquery, churn analysis, data visualization, dashboard design, business thinking

Business Objectives:
To Understand overall customer churn that why are we lossing customers and key drivers
To also Identify high-risk customers likely to leave
To Analyze how contract type affects churn
Evaluate the impact of payment methods on churn
Study customer behavior (tenure, charges, services)
lastly, Provide actionable recommendations to improve retention

📁 Repository Structure
excel-analysis/ → Data cleaning, calculated metrics, Formulas and pivot tables
sql-queries/ → business questions with SQL queries, insights, and recommendations
dashboard/ → Power BI dashboard screenshots
README.md → Project documentation

📊 Excel Analysis

File 1: Raw Data
Original telecom dataset with customer records

File 2: Cleaned Data with Calculated Metrics
I cleaned dataset (removed inconsistencies, handled missing values)
I also added calculated columns for better analysis

File 3: Pivot Tables
Summary of customer distribution
Early insights into churn patterns
  
     Key Findings
   Churn Behavior
Most of our customers leave without clearly stating any reason
Some customers leave for competitors,attitude, showing possible gaps in value or service

   Contract Type
Most customers are on Month-to-Month contracts
These customers are more flexible but also more likely to leave

  Payment Method
Our Bank Withdrawal has the highest number of churned customers (due to large user base)
Meanwhile our cailed Check has the highest churn rate, meaning customers using this payment method  are more likely to leave

   Customer Value Risk
Some new customers (≤12 months) are already paying above average
These customers are high-value but still leaving early

   Customer Behavior
Customers with short tenure and high charges are more likely to churn
Lack of additional services also increases churn risk

Dashboard Preview
1. Churn Customer Analysis Dashboard

Shows:
Total customers
Churned customers
Churn rate
Churn by contract type
Churn by payment method
Churn ny City
Tenure distribution
Churn by Internert Type
Churn Category

The above helpsus to  quickly identify where churn is happening and understand why customers are leaving

  Technical Approach
Data Processing
I cleaned the  dataset using Excel
I structured data for analysis
I created calculated columns (age group, churn indicators)

SQL Analysis
I used GROUP BY, CASE,aggregate functions,subquery
I Identified churn patterns and customer segments
I answered question that most employer and non stakholders would asked

Power BI
I built interactive dashboards
I created DAX measures (Churn Rate, Total Customers, Churned Customers)
I designed visuals for non-technical understanding

 Business Recommendations
1. Improve Customer Feedback

Different teams should introduce exit surveys and follow-ups to understand why customers leave without giving reasons

2. Convert Month-to-Month Customers to Long term Customers

Business should encourage customers to move to longer contracts using discounts or incentives to reduce churn

3. Focus on High-Risk Payment Methods

Business should investigate why customers using mailed check are leaving more and improve their experience

4. Retain High-Value New Customers

Business should alos provide better onboarding and early engagement for new customers paying high charges

5. Improve Service Value by reviewing price, service quality, and customer experience to stay competitive

    Key Takeaway
This project shows that churn customers  is not just about numbers,it’s about understanding customer behavior and acting early.



Connect With Me
Winner Donald
📧 winnerdonald158@gmail.com
🔗 LinkedIn
💻 GitHub
📍 Abuja, Nigeria

📝 Notes
This is a portfolio project created for learning and demonstration purposes.
All insights are based on the dataset and are meant to show analytical thinking and problem-solving skills.


