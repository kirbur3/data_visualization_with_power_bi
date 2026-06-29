# data_visualization_with_power_bi

## Repository Overview
Two Power BI projects covering interactive dashboard development and data visualization across professional survey data and entertainment industry data.

Projects in this repo:
- **Data Visualization and Reporting with Power BI**
- **Movies and TV Shows Personal Project**

---

## Data Visualization and Reporting with Power BI

This project is listed on my resume as "Data Visualization and Reporting with Power BI."

Power BI dashboard project following a guided tutorial, using a real data professional survey dataset. Source files: Power_BI_Final_Project_Before_Transformations.xlsx (raw) and Power_BI_Final_Project.xlsx (post-transformation). Both included to show the full data preparation process.

Tools: Power BI, Power Query

### Data Preparation (Power Query)
- Free-text columns for job title and favorite programming language cleaned using delimiter-based splitting to collapse inconsistent variants into usable categories
- Salary range column (e.g., "106k-125k") split by digit/non-digit boundaries, cleaned, and averaged into a single custom calculated column

### Dashboard
- Cards - KPI summaries (survey count, average salary, average age)
- Stacked bar chart and clustered column chart - salary and satisfaction comparisons across job titles and countries
- Treemap - proportional breakdown of favorite programming languages
- Gauges - work/life balance and salary satisfaction scores
- Donut chart - difficulty of breaking into the data field

This project was completed by following a structured guided tutorial to build practical, hands-on Power BI skills.

Extra Files: **Power_BI_Final_Project_Before_Transformations.xlsx, Power_BI_Final_Project.xlsx**

---

## Movies and TV Shows Personal Project

Personal Power BI project exploring Netflix's most-watched movies and TV shows using the flixpatrol dataset, built as a companion to the R version of the same analysis completed separately.

Tools: Power BI

### Dashboard
- Stacked column chart - watch time or title counts broken down by category
- Ribbon chart - ranking changes across categories over time
- Pie chart - proportional breakdown by type or genre
- Cards - KPI summaries
- Table - detailed title-level view

Extra Files: **flixpatrol.xlsx**
