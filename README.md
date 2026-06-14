# HR Analytics Dashboard 📊

## Overview
An interactive HR Analytics Dashboard built in Power BI using the IBM HR Employee Attrition dataset. This dashboard helps HR managers understand employee attrition patterns and take data driven decisions to improve employee retention.

## Dataset
- **Source:** IBM HR Analytics Employee Attrition & Performance
- **Records:** 1,470 employees
- **Columns:** 35 features including Age, Department, Job Role, Monthly Income, Attrition and more

## Tools Used
- **Power BI Desktop** — Dashboard building and visualization
- **DAX** — Data Analysis Expressions for calculated measures
- **Power Query** — Data transformation and cleaning

## Dashboard Pages

### Page 1 — Attrition Overview
- Total Employees, Attrition Count, Attrition Rate % and Avg Monthly Income KPI cards
- Attrition by Department — Donut chart
- Attrition by Job Role — Stacked bar chart

### Page 2 — Employee Demographics
- Attrition by Age Group — Clustered bar chart
- Attrition by Gender — Donut chart
- Attrition by Education Field — Bar chart
- Attrition by Distance from Home — Bar chart

### Page 3 — Job Satisfaction & Performance
- Attrition by Job Satisfaction — Stacked bar chart
- Attrition by Environment Satisfaction — Stacked bar chart
- Attrition by Work Life Balance — Stacked bar chart
- Attrition Rate by Overtime — Clustered bar chart

### Page 4 — Compensation & Tenure
- Monthly Income by Job Role — Clustered bar chart
- Attrition by Years at Company — Clustered bar chart
- Attrition Rate by Business Travel — Clustered bar chart
- Attrition by Years Since Last Promotion — Clustered bar chart

## DAX Measures Created
- Total Employees
- Attrition Count
- Attrition Rate %
- Active Employees
- Avg Monthly Income

## Key Insights
- Overall attrition rate is **16.1%** — 237 out of 1470 employees left
- Employees who work **overtime** leave at nearly double the rate of those who don't
- **Sales department** has the highest attrition rate compared to other departments
- Employees with **low job satisfaction scores** (1 and 2) leave significantly more
- Employees who **travel frequently** for business have a higher attrition rate
- Most attrition happens in the **first 1 to 3 years** of employment

## How to Use
1. Download the `HR_Analytics_Dashboard.pbix` file
2. Download the `WA_Fn-UseC_-HR-Employee-Attrition.csv` file
3. Open the .pbix file in Power BI Desktop
4. If prompted to find the data source, navigate to where you saved the CSV file
5. Explore the dashboard using the slicers to filter by Department, Gender and Job Role

## Author
**Vidapanakal Swetha**
ECE Student | Aspiring Data Analyst
📧 Connect with me on LinkedIn - https://www.linkedin.com/in/vidapanakal-swetha/
