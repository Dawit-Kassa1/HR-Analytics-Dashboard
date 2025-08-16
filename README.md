# HR Analytics Interactive Dashboard (Power BI)

An end-to-end **Power BI** dashboard that gives HR leaders an executive view of workforce health and trends. Tracks **headcount, attrition %, average salary, and average age** with drill-through and slicers for self-service analysis. Built as a governed **single source of truth (SSOT)** with a KPI catalog, naming standards, refresh cadence, and documented data lineage.

## Objective
Create a governed HR analytics SSOT in Power BI with standardized KPI definitions, reliable refresh, and clear lineage, so leadership can review trusted workforce insights in minutes, not hours.

## Dataset Used
- <a href="https://github.com/Dawit-Kassa1/HR-Analytics-Dashboard/blob/main/HRDataset_v14.xlsx">Sample Excel Dataset</a>
- <a href="https://github.com/Dawit-Kassa1/HR-Analytics-Dashboard/blob/main/HR%20Dashboard%20Project.pbix"> Power BI file (PBIX) </a>
  
## Why this exists
- **Problem:** Fragmented spreadsheets, inconsistent KPI formulas, slow reconciliation  
- **Solution:** A governed SSOT with standardized definitions, a refresh cadence, and documented data lineage  
- **Result:** Faster reviews, fewer follow-ups, and consistent workforce KPIs for leadership

## Key questions answered
- What is the current headcount and how is it trending?  
- What is the attrition rate and how has it changed over time?  
- How is the workforce distributed by department, age group, and recruitment source?  
- What are the average salary and age demographics?

## Features
- KPI cards for headcount, attrition count, attrition rate, average salary, and average age  
- Departmental breakdowns and age group visualizations  
- Attrition trends and headcount growth over time  
- Interactive slicers for department, position, employment status, state, and gender  
- Drill-through to detailed employee-level data  
- Exportable tables for Excel and CSV reporting  
- Governed model with consistent naming, DAX standards, and KPI documentation

## Outcomes & Impact

- **Standardized KPIs** across pages (SSOT) → fewer follow-ups and rework  
- **Faster HR reporting** (drill-through + exports) → less manual reconciliation  
- **Actionable visibility** (dept/age/source trends) → better hiring and retention decisions

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

- ## Key Insights

- **Elevated attrition (33.44%)**  
  One-third of the workforce left during the measured period. Priorities: review onboarding/retention, manager enablement, and exit themes.

- **Department concentration in Production (≈67%)**  
  Production accounts for **209 of 311** employees. This concentration increases workforce risk (single-function exposure) and capacity constraints.

- **Age profile is mid-career heavy (36–45 = 153 of 311, ~49%)**  
  Lower representation in early-career/late-career bands suggests succession planning and knowledge transfer should be monitored.

- **Recruitment mix is top-heavy in 2–3 sources**  
  The majority of hires come from a few channels (e.g., **Indeed, LinkedIn, Google Search** in the sample). Diversifying sourcing may broaden reach and reduce channel risk.

- **Headcount trend is steadily up (cumulative)**  
  Growth is consistent across years in the sample, which strengthens the case for proactive workforce planning and budget forecasting.

> *Counts and proportions are taken from the sample dataset included in this repo.*


### Conclusion

This dashboard centralizes HR reporting into a governed single source of truth and surfaces the few metrics leaders check first: **headcount, attrition %, salary, and age**. Insights show elevated attrition, heavy dependence on the Production function, and a mid-career-heavy age mix—pointing to actions in retention, sourcing diversification, and succession planning.  
With drill-through, slicers, and exportable detail, HR can answer follow-ups in minutes instead of hours and align decisions with consistent KPI math.






