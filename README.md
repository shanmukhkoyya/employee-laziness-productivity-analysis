# Employee Productivity & Work Pattern Analysis

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:14243B,100:00C9D8&height=180&section=header&text=EMPLOYEE%20WORK%20PATTERN%20ANALYSIS&fontSize=27&fontColor=ffffff&fontAlignY=40&desc=POWER%20BI%20%7C%20DAX%20%7C%20DATA%20ANALYTICS&descAlignY=65" width="100%" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/DAX-4479A1?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Data_Visualization-00A6A6?style=for-the-badge" />
  <img src="https://img.shields.io/badge/CSV-14243B?style=for-the-badge" />
</p>

## 1. Project Overview

This project analyses 200 sample employee activity records using Microsoft Power BI.

It explores work patterns, task completion, working hours, missed deadlines, meetings, idle time, breaks and work modes through an interactive dashboard.

The project also uses a custom, project-defined Laziness Index to demonstrate how calculated metrics can be explored through data visualisation.

> **Important:** The dataset and index are designed for portfolio analysis. The index is not a scientifically validated HR measure and must not be used to judge individual employees.

## 2. Business Problem

Organisations may want to understand how work patterns and task-related indicators vary across departments and working arrangements.

This project demonstrates how a sample activity dataset can be analysed to explore these patterns and present descriptive findings through Power BI.

## 3. Project Objectives

- Explore the supplied employee activity dataset.
- Compare work patterns across departments.
- Analyse Office and Work From Home records.
- Examine task completion and missed deadlines.
- Explore login hours, active hours, idle time and breaks.
- Create and analyse a project-defined index.
- Build interactive Power BI reports.
- Communicate descriptive findings while recognising dataset limitations.

## 4. Dataset Overview

The project uses a sample dataset containing 200 employee activity records.

The dataset includes:

- Department and work mode.
- Login hours and active hours.
- Idle time and break duration.
- Tasks assigned and completed.
- Missed-deadline status.
- Meeting hours and social-media usage.
- Performance rating and salary level.
- Project-defined index and productivity category.

**[View the CSV Dataset](Laziness_Analysis_200_Records.csv)**

## 5. Analytical Questions

- How does the project-defined index vary across departments?
- How do Office and Work From Home averages compare?
- How are task completion and missed deadlines represented?
- What patterns appear in idle time, break duration and meeting hours?
- How does the index vary across the sample's productivity categories?
- What can be explored using employee-level dashboard filters?

## 6. Dashboard Screenshots

The following are the four existing dashboard screenshots stored in this repository.

### Dashboard 1 — Main Dashboard

![Main Power BI Dashboard](screenshots/Dashboard1.png)

### Dashboard 2 — Employee Details

![Employee Details Dashboard](screenshots/Dashboard2.png)

### Dashboard 3 — Index Breakdown

![Index Breakdown Dashboard](screenshots/Dashboard3.png)

### Dashboard 4 — Analytical Insights

![Analytical Insights Dashboard](screenshots/Dashboard4.png)

## 7. Key Descriptive Findings

The following results are calculated from the 200 records supplied with this project.

### KPI summary

| Measure | Result |
|---|---:|
| Total records | 200 |
| Average project-defined index | 0.391 |
| Records with index ≥ 0.40 | 86 |
| Highest department average | Sales — 0.406 |
| Lowest department average | Finance — 0.376 |
| Office average | 0.392 |
| Work From Home average | 0.390 |

### Work-mode comparison

The Office and Work From Home averages are very close in this sample.

The difference is descriptive only. It does not establish that a particular work arrangement improves or reduces employee performance.

### Additional observation

| Group | Average social-media usage |
|---|---:|
| Records marked as having missed a deadline | 3.34 hours |
| Records not marked as having missed a deadline | 3.52 hours |

This comparison does not establish a relationship of cause and effect.

## 8. Power BI Dashboard Features

The report includes:

- KPI cards and department comparisons.
- Work-mode and productivity-category views.
- Login hours versus completed tasks.
- Employee-level details and filters.
- Decomposition Tree for exploring the project-defined index.
- What-If parameter for a hypothetical break-time change.
- Analytical views comparing different groups.

## 9. Tools and Technologies

| Tool | Purpose |
|---|---|
| Microsoft Power BI | Dashboard development and reporting |
| DAX | Measures and calculated analytical metrics |
| CSV | Dataset storage and data input |

## 10. How to Run the Project

**Prerequisite:** Microsoft Power BI Desktop.

1. Clone or download this repository.
2. Open `Laziness_Analysis_200_Records.csv` to inspect the sample data.
3. Open `laziness_data.pbix` in Power BI Desktop.
4. Explore the report pages.
5. Use the available slicers and filters.
6. Review the project-defined index before interpreting the dashboard results.

**[Open Power BI Report](laziness_data.pbix)**

## 11. Project Structure

```text
employee-laziness-productivity-analysis/
│
├── Laziness_Analysis_200_Records.csv
├── laziness_data.pbix
│
├── screenshots/
│   ├── Dashboard1.png
│   ├── Dashboard2.png
│   ├── Dashboard3.png
│   └── Dashboard4.png
│
└── README.md
```

## 12. Scope and Limitations

- The dataset contains 200 sample activity records.
- The index and category thresholds are defined for this project exercise.
- The index is not a validated organisational or HR standard.
- Group comparisons are descriptive and do not establish cause and effect.
- Results should not be generalised to all employees or workplaces.
- The term "Laziness" in the project name refers only to the defined sample metric, not a verified judgement about any person.

## 13. Author

**Shanmukh Koyya**

- **GitHub:** [shanmukhkoyya](https://github.com/shanmukhkoyya)
- **LinkedIn:** [linkedin.com/in/shanmukh-koyya](https://www.linkedin.com/in/shanmukh-koyya/)
- **Email:** [shanmukhkoyya1234@gmail.com](mailto:shanmukhkoyya1234@gmail.com)