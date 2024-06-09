# HR-Analytics-Power-BI-
Objective
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







