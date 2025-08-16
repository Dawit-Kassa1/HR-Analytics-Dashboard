# HR Analytics Interactive Dashboard (Power BI)

An end-to-end **Power BI** dashboard that gives HR leaders an executive view of workforce health and trends. Tracks **headcount, attrition %, average salary, and average age** with drill-through and slicers for self-service analysis. Built as a governed **single source of truth (SSOT)** with a KPI catalog, naming standards, refresh cadence, and documented data lineage.

## Objective
Create a governed HR analytics SSOT in Power BI with standardized KPI definitions, reliable refresh, and clear lineage, so leadership can review trusted workforce insights in minutes, not hours.

## Dataset Used
- <a href="https://github.com/Dawit-Kassa1/HR-Analytics-Dashboard/blob/main/HRDataset_v14.xlsx">Dataset</a>

## Why this exists
- **Problem:** Fragmented spreadsheets, inconsistent KPI formulas, slow reconciliation  
- **Solution:** A governed SSOT with standardized definitions, a refresh cadence, and documented data lineage  
- **Result:** Faster reviews, fewer follow-ups, and consistent workforce KPIs for leadership

## Key questions answered
- What is the current headcount and how is it trending?  
- What is the attrition rate and how has it changed over time?  
- How is the workforce distributed by department, age group, and recruitment source?  
- What are the average salary and age demographics?

- Power BI Dashboard Interaction <a href="https://github.com/Dawit-Kassa1/HR-Analytics-Dashboard/blob/main/HR%20Dashboard%20Project.pbix">View Project </a>

## Features
- KPI cards for headcount, attrition count, attrition rate, average salary, and average age  
- Departmental breakdowns and age group visualizations  
- Attrition trends and headcount growth over time  
- Interactive slicers for department, position, employment status, state, and gender  
- Drill-through to detailed employee-level data  
- Exportable tables for Excel and CSV reporting  
- Governed model with consistent naming, DAX standards, and KPI documentation

## Tech stack
Power BI • Power Query • DAX • Data Modeling • (sample) Excel dataset

## KPI definitions
- **Headcount (Active):** Count of active employees in the selected period.  
- **Attrition Count:** Number of separations in the selected period.  
- **Attrition %:** *Separations during period* ÷ *average headcount for the period*.  
- **Average Salary / Age:** Mean values across the filtered population.

> All metrics are consistently defined in a centralized KPI catalog

## Build process 

- Import and inspect the Excel dataset in Power BI Desktop  
- Clean and transform data using Power Query: typed columns, text cleanup, null handling  
- Model and calculate KPIs with DAX and build an organized Measures table  
- Design visual layout with aligned charts, slicers, tooltips, and labels  
- Configure drill-through navigation and validate total vs. detail calculations  
- Document refresh cadence, naming conventions, and lineage to support governance

## Dashboard
<img width="1487" height="1717" alt="HR Dashboard Screenshot" src="https://github.com/user-attachments/assets/583c0155-14b5-439f-a326-9727ff90fa5a" />

### Key Insights

- **High Attrition Rate (33.44%)**  
  A significant portion of the workforce has left the organization, suggesting potential issues with employee satisfaction, retention strategies, or onboarding processes.

- **Departmental Distribution Imbalance**  
  The **Production department** alone accounts for over **67%** of total headcount (209 out of 311), indicating possible over-reliance on one function or potential risk exposure in staffing.

- **Age Demographics Concentrated (36–45)**  
  Nearly **50% of employees** fall into the **36–45 age bucket**, with much smaller representation in younger or older age groups. This can impact succession planning and long-term workforce sustainability.

- **Recruitment Channels Are Skewed**  
  Majority of hires come from just three sources: **Indeed, LinkedIn, and Google Search** — suggesting an opportunity to diversify recruiting channels for better talent reach.

- **Gender & Marital Status Breakdown**  
  Gender representation across marital statuses appears relatively balanced, though further DEI analysis could be conducted to ensure equitable hiring and promotion practices.

- **Attrition Spikes Around 2011**  
  The time series visualization shows a sharp spike in attrition during 2011, which may require historical context or further investigation into internal or external factors.

- **Gradual Growth in Headcount**  
  Yearly cumulative headcount shows healthy long-term growth, indicating expansion and increasing workforce investment over the years.

### Business Conclusion

- The dashboard reveals a high attrition rate in the Production department, indicating potential issues with working conditions, compensation, or management practices. Heavy reliance on a few recruitment channels may limit access to diverse talent. Age and tenure trends emphasize the importance of succession planning and knowledge transfer. By integrating interactive slicers, drill-through analysis, and exportable data views, the dashboard empowers HR teams with self-service analytics, improves reporting efficiency, and supports strategic decision-making. This project will help HR proactively address workforce challenges and align talent strategies with organizational goals.





