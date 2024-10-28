# Work-Life Balance and Employee Engagement Dashboard
# Project Overview
This project analyzes key metrics related to employee work-life balance and engagement to provide actionable insights for improving well-being and reducing attrition risk. The Power BI dashboard visualizes metrics like work-life balance rating, job involvement, relationship satisfaction, and overtime distribution, helping stakeholders identify areas for improvement within the organization.

# Dataset
The dataset includes anonymized employee data with key attributes such as:

Work-Life Balance Rating: Employee self-rated balance score.
Job Involvement: Engagement level in assigned roles.
Relationship Satisfaction: Satisfaction with workplace relationships.
Overtime: Indicator of employees working overtime.
The data was provided for the purpose of analyzing engagement and well-being, and the focus is on improving organizational policies based on these insights.

# Dashboard Components
The dashboard includes the following components:

Average Work-Life Balance Rating: Displays the average score across all departments.
Average Job Involvement: Shows the level of engagement employees feel in their roles.
Average Relationship Satisfaction: Provides insight into the quality of workplace relationships.
Overtime Work Distribution: A visual distribution of employees working overtime versus those who are not.
Each component is interactive, allowing users to filter by department, role, and other demographics.

# DAX Measures
Key metrics calculated using DAX:

Average Work-Life Balance: Avg_WorkLifeBalance = AVERAGE('WA_Fn-UseC_HR-Employee-Attrition'[WorkLifeBalance])
Average Job Involvement: Avg_JobInvolvement = AVERAGE('WA_Fn-UseC_HR-Employee-Attrition'[JobInvolvement])
Average Relationship Satisfaction: Avg_RelationshipSatisfaction = AVERAGE('WA_Fn-UseC_HR-Employee-Attrition'[RelationshipSatisfaction])

