# Customer Churn Analysis – Power BI Dashboard
Overview
This project presents a Customer Churn Analysis Dashboard built using Microsoft Power BI.
The goal is to analyze customer behavior and identify patterns that contribute to customer churn (customers leaving a service).

By visualizing churn-related metrics, the dashboard helps businesses understand:
Why customers leave
Which customer segments are most likely to churn
Key factors influencing churn
The insights can help organizations improve customer retention strategies.

Objectives
The dashboard focuses on answering these questions:
What is the overall churn rate?
Which customer segments churn the most?
How do factors such as tenure, contract type, and services influence churn?
Which groups of customers should businesses target to reduce churn risk?

Dataset
The dataset contains information about customers and their subscription details.

Typical fields included in the analysis:
Customer demographics
Contract type
Monthly charges
Tenure (duration with company)
Services subscribed
Payment method
Churn status (Yes / No)
These attributes are used to identify relationships between customer characteristics and churn behavior.

Dashboard Features
Key Performance Indicators (KPIs)

The dashboard highlights important metrics such as:
Total Customers
Total Churned Customers
Churn Rate
Average Monthly Charges
Average Customer Tenure
Visual Insights

The dashboard includes multiple interactive visuals:
  1. Churn Distribution
    Shows the proportion of customers who stayed vs churned.
  2. Churn by Contract Type
    Identifies whether monthly contracts or long-term contracts experience higher churn.
  3. Churn by Payment Method
    Helps determine if certain payment methods correlate with higher churn.
  4. Churn by Tenure
    Shows whether new customers or long-term customers are more likely to leave.
  5. Service Usage Analysis
    Examines how subscribed services affect churn probability.

Tools & Technologies
Power BI Desktop – Data modeling and visualization
Power Query – Data cleaning and transformation
DAX (Data Analysis Expressions) – Calculated measures and KPIs

How to Use the Dashboard
Download the .pbix file.
Open it using Power BI Desktop.
Navigate through the report pages.

Use filters and slicers to explore:
Customer segments
Service categories
Contract types
Interact with visuals to uncover churn insights.
Key Insights (Example Findings)

Some typical insights derived from churn analysis include:
Customers with month-to-month contracts tend to churn more frequently.
Short-tenure customers are more likely to leave compared to long-term customers.
Higher monthly charges may correlate with increased churn risk.
Certain service bundles improve customer retention.

Project Structure
Customer-Churn-PowerBI/
│
├── Customer_Churn_PowerBI_Joy_Gras.pbix
├── README.md

Future Improvements
Possible enhancements for the project:
Add predictive churn modeling using Python or ML
Integrate real-time data sources
Include customer segmentation clustering
Add more advanced DAX measures
