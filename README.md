# Employee Attrition 

## 📑 Table of Contents  
- [Project Overview](#project-overview)  
- [Problem Statement](#problem-statement)  
- [Objectives](#objectives)  
- [Dataset](#dataset)  
- [Process & Analysis](#process--analysis)  
- [Dashboard Features](#dashboard-features)  
- [Key Insights](#key-insights)  
- [Tools Used](#tools-used)  
- [Conclusion](#conclusion)  
- [Future Improvements](#future-improvements)  

---

## Project Overview  
Employee turnover is one of the most pressing challenges organizations face. Beyond recruitment costs, high attrition impacts productivity, morale, and long-term business stability.  

To better understand the **drivers of attrition**, I built an **interactive Employee Attrition Dashboard** that provides a data-driven lens into why employees leave, how tenure affects exits, and what salary bands/roles are most vulnerable.  

This project is part of my portfolio to showcase **business-focused data storytelling** — transforming raw HR data into actionable insights.  

---

## Problem Statement  
Many organizations struggle to:  
- Identify which departments experience the highest turnover.  
- Understand the financial impact of attrition.  
- Recognize salary bands or tenure groups that are more likely to exit.  
- Uncover the main reasons why employees resign.  

Without these insights, HR leaders are often **reactive** instead of **proactive**, leading to costly employee replacement cycles.  

---

## Objectives  
The main goals of this project were to:  
1. Build an interactive dashboard to monitor attrition patterns.  
2. Provide HR and leadership with **clear visibility** into employee turnover.  
3. Pinpoint the **cost of attrition** by department.  
4. Discover correlations between **salary bands, tenure, and exit rates**.  
5. Highlight the **top exit reasons** for better policy and engagement strategies.  

---

## Dataset  
The dataset used simulates HR records containing:  
- Employee demographics  
- Department and job role  
- Tenure (years at company)  
- Salary band ($)  
- Exit reason (categorical)  
- Attrition flag (Exited / Still employed)  

**Dataset size**: 1,200 employees  
**Total exits**: 367 employees (≈31%)  

---

## Process & Analysis  
Steps taken in this project:  
1. **Data Cleaning** – handled missing values, standardized salary bands, and created tenure categories.  
2. **Exploratory Analysis** – segmented attrition by department, salary, tenure, and reasons.  
3. **KPI Design** – created key HR metrics such as:  
   - Attrition Rate  
   - Average Tenure at Exit  
   - Cost of Attrition by Department  
4. **Visualization** – built interactive charts in Excel to make the findings accessible and business-friendly.  

---
## Dashboard Features 
The dashboard highlights:  
- **KPI Cards**: Total Employees, Total Leavers, Attrition Rate, Average Tenure at Exit.  
- **Top Exit Reasons**: Visualizes the leading causes of attrition such as work-life balance, manager issues, and career growth.  
- **Attrition by Department**: Shows department-level turnover, with Finance experiencing the highest (37%).  
- **Attrition by Tenure Group**: Categorizes exits into career stages:  
  - 0–1 years (new hires)  
  - 2–5 years (short stay)  
  - 6–10 years (mid stay)  
  - 11–20 years (long stay)  
  - 20+ years (very long stay / outliers)  
- **Attrition by Salary Band**: Displays how turnover varies across different pay brackets.  
- **Cost of Attrition by Department**: Quantifies the financial loss due to employee exits, with Finance ($532K) and Marketing ($513K) being most impacted.

<img width="979" height="537" alt="Employee atrrition" src="https://github.com/user-attachments/assets/af4071d1-30d3-42dc-aa87-ef3eaf412542" />

---

## Key Insights  
- **Finance Department** leads in attrition with **37% turnover**.  
- **Work-life balance** is the top driver of employee exits.  
- New hires (**0–1 years**) account for the largest share of leavers.  
- Employees in salary bands **300–800** and **2800–3300** face the highest attrition (35%).  
- Attrition costs are most severe in **Finance ($532K)** and **Marketing ($513K)**. 
---

## Tools Used  
- **Excel** – Data cleaning, modeling, visualization, and dashboard design.  
- **Pivot Tables & Charts** – For aggregated analysis.  
- **Conditional Formatting** – To highlight trends and outliers.  

---

## Conclusion  
This project demonstrates how HR data can be transformed into a **decision-support tool**. With clear KPIs and insights, HR leaders can:  
- Develop better retention strategies.  
- Address department-specific issues.  
- Improve salary/benefit competitiveness.  
- Target interventions at early-career employees most likely to leave.  

---

## Future Improvements  
- Incorporate predictive modeling to forecast attrition risk.  
- Expand dashboard to include employee satisfaction survey data.  
- Automate updates using Power BI or Tableau for real-time insights.  
