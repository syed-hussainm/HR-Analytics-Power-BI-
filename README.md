# HR-Analytics-Power-BI-

The goal of this project is to pinpoint the primary factors contributing to employee attrition and provide actionable insights to enhance workforce retention within an organization. The dashboard created offers valuable insights into organizational attrition, aiding the HR team in their subsequent analyses.

Throughout this project, I have had the opportunity to:
Delve deeply into HR data to extract meaningful insights.
Create interactive dashboards to visualize essential HR metrics.
Offer data-driven recommendations for strategic decision-making.
Steps Followed:
Data Gathering:

Imported raw data from a .csv file into Power BI and transformed it using the Power Query editor for cleaning and processing.
Data Cleaning:

Removed empty columns, duplicates, and errors.
Replaced values in columns with appropriate names.
Used the auto-detect data type function in Power Query editor to identify data types for each column.
Data Processing:

Created a new column named "AttritionCount" in the Power Query editor using the conditional column feature, based on the condition (IF attrition = 'Yes' then 1, Else 0).
Utilized this new column to generate various KPIs and charts.
Calculated the Attrition Rate by applying DAX queries and adding a new measure (Attrition Rate = SUM([AttritionCount])/SUM([EmployeeCount])) in %.
Data Analysis:

Developed a variety of visual representations, including bar charts, key performance indicators (KPIs), table charts, pie charts, and other relevant visualizations.
These visual tools were used to derive insights and present data in a clear and accessible manner. 

   KEY INSIGHTS

> Total Employees: The organization has significantly expanded, now employing 1,470 individuals, demonstrating substantial growth and scale.
> 
> Attrition Analysis: A total of 237 employees have left the organization, with 150 males and 87 females, indicating a higher attrition rate among males.
> 
> Departmental Attrition: The Research and Development Department experienced the highest attrition rate at 56.13%, highlighting a need for improved employee retention strategies in this area.
> 
> Education Field Impact: Employees in the life sciences field had the highest attrition rate, suggesting the need to address retention challenges specific to this field.
> 
> Job Role Affected: The sales role exhibited the highest attrition rate, indicating the necessity for targeted retention efforts in this department to decrease turnover.
> 
> Education-wise Attrition: The attrition rate for employees with only a high school education is 18.24%, the highest among all education levels.
> 
> Attrition Rate by Gender and Age Group: The highest attrition count is among the 25-34 age group, with 112 employees leaving, which is the maximum among all age groups.












