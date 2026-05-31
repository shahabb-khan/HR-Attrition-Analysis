# HR Attrition Analysis (Google Sheets)

## Objective
Identify factors associated with employee attrition (resignation) and highlight departments / roles most at risk using an Excel-first workflow in Google Sheets.

## Dataset
IBM HR Analytics Employee Attrition dataset (Kaggle) — 1470 employees.

## Tools Used
- Google Sheets (pivot tables, formulas, conditional formatting, charts)
- Basic data cleaning & feature engineering (bands/flags)

## Key Metrics
- Attrition Rate = Attrition Yes / Total Employees
- At-risk group = attrition rate above overall attrition rate

## Key Findings
- Highest-risk department: **Sales (~20%)**
- OverTime is a strong risk factor: **Yes 30.53% vs No 10.44%**
- Highest-risk job role: **Sales Representative 39.76%**
- Early tenure is highest risk: **0–1 years 34.88%**

## What I would do next (if more time)
- Build a simple “risk score” model in Sheets
- Validate results using train/test split in Python
- Add statistical testing / confidence intervals for small groups
