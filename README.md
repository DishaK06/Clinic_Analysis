# Clinic_Analysis

This Power BI dashboard provides an interactive and insightful view of clinic visitor data, enabling data-driven decision-making for healthcare professionals. By leveraging DAX and Power Query, the dashboard uncovers key trends in patient demographics and service utilization. It integrates data modeling best practices and multiple data sources to deliver meaningful KPIs and dynamic visualizations. This tool empowers users to optimize resources, enhance operational efficiency, and improve the overall quality of patient care through actionable business intelligence.


## Key Technologies and Skills
- Power BI
- Excel
- Power Query Editor
- Data Analysis Expressions (DAX)

## Features

### 📊Data Understanding
The dataset captures a range of attributes including Date, Visitor ID, Gender, Age, Race, Time of Visit (AM/PM), Day Type (Weekday/Weekend), Admin Flag (Patient/Non-Patient), Department Referrals, and Satisfaction Scores. These features provide a solid foundation for analyzing visitor demographics, visit timing patterns, and departmental engagement—enabling meaningful operational insights and trend analysis.

### 🛠️ Data Preprocessing
- Data Cleaning and Transformation:
The dataset was processed using Power Query through a structured ETL (Extract, Transform, Load) workflow. Data normalization was applied by splitting tables for improved clarity and structure. Missing values were handled using imputation techniques to maintain data integrity and consistency.

- Data Modeling and DAX Measures:
DAX (Data Analysis Expressions) was used to create calculated fields and aggregations, supporting advanced analytical capabilities. Relationships between tables were defined to build a robust data model, improving dashboard performance and depth of analysis.

### 📈 Visit Trends and Patterns
- Daily Trends:
Visitor numbers tend to rise gradually each month, peaking in the final week before dropping on the last day—indicating end-of-month surges.

- Monthly Trends:
Visitor counts increased between April and October, suggesting seasonal influences such as summer and rainy seasons impact clinic visits.

- Yearly Trends:
A 5.8% increase in visits from 2019 to 2020 points to growing healthcare demand or increased trust in clinic services.

- Quarterly Trends:
Q2 and Q3 reported 53.9% more visitors than Q1 and Q4, possibly due to seasonal health conditions leading to higher mid-year demand.

### ⏰ Time-Based Distribution
- AM/PM Visits:
Visitor traffic is evenly split between AM and PM slots, with a slight 0.6% preference for morning visits—indicating steady demand throughout the day.

- Weekday Trends:
Peak visits occur on Mondays and Wednesdays, with Fridays seeing the fewest visitors, suggesting a mid-week preference for appointments.

- Weekday vs. Weekend:
Weekday visits are 148.83% higher than weekends, likely due to reduced staffing or operating hours during weekends.

### ⏳ Visitor Wait Time Analysis
- Average Wait Time:
The average wait time is approximately 35 minutes. About 90.9% of visitors wait between 20 and 60 minutes—highlighting a key area for process improvement.

- Short Wait Times:
Only 9.1% of visitors experience wait times of 10–20 minutes, indicating a need to optimize service efficiency for better patient satisfaction.

### 👥 Demographic Insights
- Age Distribution:
All age groups up to 75 are represented evenly, while visitors aged 75+ make up only 5.04%, possibly due to lower mobility or demographic share.

- Race Distribution:
The majority of visitors are White and African American, with moderate representation from Asian patients. Pacific Islander and Native American groups together make up 11.37%, reflecting a diverse clinic population.

- Gender Distribution:
Male visitors outnumber females by 4.86%, and only 0.26% are classified as "Not Specified"—pointing to a slight gender gap worth exploring.

### ✅ Satisfaction and Departmental Insights
- Satisfaction Scores:
With an average score of 5 out of 10, most visitors report neutral satisfaction—highlighting areas for service quality improvement.

- Department Referrals:
General Practice and Orthopedics account for 30.75% of referrals, while departments like Physiotherapy and Cardiology comprise 10.64%. A significant 58.67% of visitors were not referred to any department, which may indicate walk-ins or non-medical visits.

- Admin Flag Analysis:
Just over half (50.04%) of visitors are registered patients, while the remaining 49.96% are non-patients or general visitors—revealing a balanced mix of clinical and non-clinical footfall.


