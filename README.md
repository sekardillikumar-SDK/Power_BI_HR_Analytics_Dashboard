Power BI HR Analytics Project Explanation
Project Overview
This project focuses on analyzing Human Resources data to gain insights into employee attrition, satisfaction, performance, and other key HR metrics. Using Microsoft Power BI, we create interactive dashboards that help HR departments make data-driven decisions to improve employee retention and organizational effectiveness.

The primary goal is to identify patterns in employee turnover, understand factors contributing to attrition, and provide actionable insights for HR strategies.

Dataset Information
The dataset (HR_Analytics.csv) contains employee information with the following key attributes:

Key Columns
EmpID: Unique employee identifier
Age & AgeGroup: Employee age and age category
Attrition: Whether the employee left the company (Yes/No)
BusinessTravel: Frequency of business travel
Department: Employee's department (Sales, Administration, etc.)
Education & EducationField: Education level and field of study
JobRole: Specific job position
JobSatisfaction & EnvironmentSatisfaction: Satisfaction ratings
MonthlyIncome & SalarySlab: Compensation information
PerformanceRating: Employee performance score
TotalExperience(Years): Years of work experience
YearsAtCompany: Tenure at current company
OverTime: Whether employee works overtime
The dataset includes approximately 1,000+ employee records with comprehensive HR metrics.

Architecture
The Power BI HR analytics solution follows a standard BI architecture:

Data Source: Employee records from HR_Analytics.csv
Data Preparation: Power Query for cleaning, type conversion, and creating calculated columns
Data Model: Data modeling with relationships, hierarchies, and supporting tables
Measure Layer: DAX measures for KPIs like attrition rate, average income, and satisfaction scores
Visualization: Interactive dashboard components in Power BI Desktop
Sharing/Publishing: Optional deployment to Power BI Service for collaboration and distribution
Architecture Diagram
data/ Hr_Analytics.csv

dashboard/ HR_Analytics_Dashboard.pbixl

images/ HR_Analytics_Dashboard Preview.png

README.md

Tools and Technologies
Microsoft Power BI: Primary tool for data visualization and dashboard creation
Power Query: Data cleaning and transformation
DAX (Data Analysis Expressions): For calculated measures and KPIs
Power BI Service: For sharing and collaboration
Dashboard Features
The dashboard follows the layout shown in the preview image above and includes the following features:

KPI Cards
Total Employee count
Active Employee count
Attrition Count
Attrition Rate
Average Age
Average Experience
Filters and Slicers
Department selector
Age Group buttons
Key Visualizations
Attrition by Department: Donut chart showing attrition share by department
Attrition by Salary Slab: Bar chart comparing attrition count across salary ranges
Attrition by Job Role & Job Satisfaction: Matrix table combining job role and satisfaction levels
Age Group Distribution: Bar chart of employee counts by age category
Attrition by Gender: Pie chart comparing attrition counts for male and female employees
Attrition Trend by Experience: Line chart showing attrition count across total experience years
Department-wise Employee Count: Horizontal bar chart of headcount by department
Drill-Down Capabilities
Filter by department, job role, or age group
Experience-based trend analysis
Cross-filtering between KPIs and charts
Key Insights Section
Top attrition drivers by department and salary band
Satisfaction and experience correlations
High-risk groups for HR intervention
Departmental staffing imbalances and retention hotspots
Project Benefits
This Power BI dashboard enables HR teams to:

Predict potential attrition risks
Identify departments needing attention
Optimize compensation strategies
Improve employee satisfaction initiatives
Make informed hiring and retention decisions
Data Source
The analysis is based on the HR_Analytics.csv file containing anonymized employee data from a fictional organization.
