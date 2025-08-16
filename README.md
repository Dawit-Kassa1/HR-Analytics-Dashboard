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
- Current **headcount** and how it’s trending  
- **Attrition rate** and trend over time  
- Workforce distribution by **department**, **age group**, and **recruitment source**  
- Compensation overview (**average salary**)

- Dashboard Interaction <a href="https://github.com/Dawit-Kassa1/HR-Analytics-Dashboard/blob/main/HR%20Dashboard%20Image.png">View Dashboard</a>

## Features
- **KPI cards:** Headcount, Attrition Count, **Attrition %**, Avg Salary, Avg Age  
- **Trend & composition pages:** Cumulative headcount, attrition trend, department/age breakdowns  
- **Interactivity:** Slicers (department, position, status, state, gender) + drill-through to detail  
- **Export:** Detail views exportable to Excel/CSV for ad-hoc reporting  
- **Governance:** KPI catalog, naming standards, refresh cadence, and data lineage (SSOT)

## Tech stack
Power BI • Power Query • DAX • Data Modeling • (sample) Excel dataset

## KPI definitions
- **Headcount (Active):** Count of active employees in the selected period.  
- **Attrition Count:** Number of separations in the selected period.  
- **Attrition %:** *Separations during period* ÷ *average headcount for the period*.  
- **Average Salary / Age:** Mean values across the filtered population.

> KPI math is standardized in the **KPI Catalog** and applied consistently across visuals.
