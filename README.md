# Employee Attendance Analysis using Excel

**Data analytics project from the TNSDC Data Analytics program — turning raw attendance records into actionable workforce insights.**

<p>
<img src="https://img.shields.io/badge/Microsoft%20Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white" />
<img src="https://img.shields.io/badge/Power%20Query-217346?style=flat-square&logo=microsoft&logoColor=white" />
<img src="https://img.shields.io/badge/Data%20Analysis-1F6FEB?style=flat-square&logo=databricks&logoColor=white" />
</p>

---

## Overview

Organizations rely on attendance data to measure punctuality, manage schedules, and reduce absenteeism. This project analyzes employee attendance records in Microsoft Excel to identify patterns, trends, and anomalies, and to produce clear visual reports that support HR and management decisions.

The complete analysis is documented in [`GOKUL.pptx`](GOKUL.pptx).

## Objective

- Identify attendance trends and recurring patterns over time.
- Detect absenteeism, late arrivals, early departures, and outliers.
- Summarize attendance by employee, department, and period.
- Provide actionable recommendations for workforce management.

## Dataset

An employee dataset sourced from Kaggle. Of the original 26 features, the following 8 were selected:

| Feature | Type |
|---|---|
| Employee ID | Numerical |
| Name | Text |
| Employee type | Text |
| Performance level | Text |
| Gender | Categorical |
| Employee Rating | Numerical |
| Employee status | Numerical |
| Business unit | Text |

## Approach

- **Data import and transformation** with Power Query (filtering, merging, handling missing values, automated refresh).
- **Data cleaning** using conditional formatting and filters to flag missing values.
- **Aggregation** with PivotTables and PivotCharts by employee, department, and time period.
- **Calculated metrics** with Excel formulas for attendance levels, hours worked, and absence rates (`COUNTIF`, `COUNTIFS`, `AVERAGE`, `STDEV`, `DATEDIF`, `TEXT`).
- **Visualization** through charts, conditional formatting, and dynamic dashboards.
- **Modelling** including descriptive statistics, trend and seasonality analysis, and forecasting (`FORECAST.LINEAR`, `LINEST`).

## Key Insights

- Peak absenteeism periods and frequent late arrivals were identified across departments.
- Attendance patterns correlate with departmental performance and business units.
- Recommendations include flexible scheduling, stronger time-management practices, and clearer attendance policies.

## Tools

| Tool | Purpose |
|---|---|
| Microsoft Excel | Analysis, formulas, PivotTables, dashboards |
| Power Query | Data import, transformation, automation |
| Kaggle | Dataset source |

## Author

**Gokulakrishnan G**
[GitHub](https://github.com/Gokulgk6) · [LinkedIn](https://linkedin.com/in/gokulgk64)
