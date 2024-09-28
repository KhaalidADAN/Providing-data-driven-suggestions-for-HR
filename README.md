**Employee Retention Analysis Using Random Forest Model**

**Project Overview**

This project addresses employee retention for Salifort Motors by predicting which employees are most likely to leave. We analyzed data related to employee evaluations, workload, and tenure to provide actionable insights to improve retention rates. We used a Random Forest model to identify key factors influencing employee turnover and proposed strategies based on our findings.

**Business Understanding**

Salifort Motors has a high turnover rate and is keen on improving employee retention. The key business question was: "What’s likely to make the employee leave the company?"

Stakeholders:
Salifort Motors Human Resources team
The objective is to provide data-driven insights to guide HR policies that enhance employee satisfaction and retention.

**Data Understanding**

The data includes various employee attributes such as:

Last evaluation score
Number of projects
Tenure (years)
Overworked (hours worked per month)
Salary levels (categorical)
We used data from Salifort Motors' employee records. Some limitations of the data include:

Lack of qualitative insights such as employee feedback.
Certain factors like personal reasons for leaving were not captured.

_Exploratory Data Analysis (EDA) Highlights:_

Employees with high evaluation scores who worked 200+ hours per month are more likely to leave.
Employees with low salary and overworked are also at a higher risk.

**Modeling and Evaluation**

We tested several models, but the Random Forest model outperformed others, including logistic regression and decision tree models. The Random Forest achieved better accuracy in predicting employee turnover by focusing on key variables like:

Last evaluation
Tenure
Number of projects
Overworked
Salary (low)
Model Results:
Random Forest Model had the best performance with a slight edge over the Decision Tree Model.

**Conclusion**

We identified key areas for HR to focus on to improve employee retention:

Limit the number of projects employees handle.
Investigate why employees with four years of tenure are dissatisfied and address these issues.
Reward employees for working longer hours or reduce workload expectations.

**Next Steps:**

HR Policy Adjustments: Implement a cap on projects and reconsider workload expectations.
Further Research: Conduct surveys or qualitative research to better understand employee dissatisfaction.
