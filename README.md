# Power BI Dashboard: Healthcare Employee Attrition Analysis

### Overview

This Power BI dashboard provides insights into employee attrition within the healthcare industry. By leveraging Power BI's powerful data visualization and analytical capabilities, this dashboard enables HR professionals to understand attrition trends, identify key factors influencing employee turnover, and make data-driven decisions to improve retention strategies.

![Power BI Dashboard](https://github.com/user-attachments/assets/471a4542-113e-4454-a0f3-3a651d0064b1)

### Key Features

- Interactive Visualizations: Users can filter and explore data based on various attributes such as age, department, job role, and business travel.
- Attrition Rate Analysis: A KPI indicator displays the overall attrition rate.
- Demographic Breakdown: Charts showing attrition rates by age, gender, education field, and department.
- Salary and Experience Analysis: Insights into how salary, total working years, and job satisfaction impact attrition.
- Custom DAX Measures: Calculated fields using DAX for deeper insights, such as average tenure of employees who left vs. those who stayed.

### Data Source

The dataset used for this analysis is an HR attrition dataset that includes the following key columns:

- EmployeeID: Unique identifier for each employee
- Attrition: Indicates whether an employee has left (Yes/No)
- Age, Gender, Marital Status: Demographic details
- Department, JobRole, BusinessTravel: Work-related information
- Salary, YearsAtCompany, WorkLifeBalance: Compensation and work experience details
- PerformanceRating, JobSatisfaction: Employee feedback metrics

### Data Cleaning & Preparation

Before importing the data into Power BI, the following preprocessing steps were performed in Microsoft Excel and Power Query:

- Converted Attrition column into binary format (Yes = 1, No = 0).
- Removed redundant columns (e.g., EmployeeCount, StandardHours, Over18).
- Standardized categorical values for consistency.
- Handled missing values by imputing or removing inconsistent data.

### Power BI Capabilities Demonstrated

- Data Modeling: Establishing relationships between tables and defining calculated columns.
- Power Query: Cleaning and transforming raw data before visualization.
- DAX (Data Analysis Expressions): Creating custom calculations such as attrition percentage, tenure averages, and salary trends.
- Dynamic Filters & Slicers: Allowing users to explore different segments of the workforce.
- Drill-Down Reports: Providing detailed breakdowns when interacting with visualizations.

### Source

https://www.kaggle.com/datasets/jpmiller/employee-attrition-for-healthcare?select=watson_healthcare_modified.csv
