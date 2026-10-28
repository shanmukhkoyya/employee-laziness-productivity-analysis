# Employee Productivity & Work Pattern Analysis

**Tools:** Power BI · DAX · CSV

This project explores 200 sample employee activity records through a Power BI dashboard. It compares work patterns, task completion, missed deadlines, work mode, and a project-defined **Laziness Index**.

> The dataset and index are for portfolio analysis. The index is not a validated HR measure and should not be used as a formal judgement of individual employees.

## Questions explored
- How does the project-defined index vary across departments?
- How do the sample's Office and Work From Home averages compare?
- How are task completion, meetings, idle time, breaks, and social-media usage represented?
- What patterns appear when records are grouped by missed-deadline status?
- What can the dashboard show, and where are the limits of the sample?

## Dashboard screenshots
### Main dashboard
![Main Dashboard](screenshots/Dashboard1.png)

### Employee details
![Employee Details](screenshots/Dashboard2.png)

### Index breakdown
![Index Breakdown](screenshots/Dashboard3.png)

### Analytical insights
![Analytical Insights](screenshots/Dashboard4.png)

## Dataset and files
The CSV contains 200 activity records. Fields include department, work mode, login and active hours, idle and break time, tasks assigned and completed, missed-deadline status, meetings, social-media usage, performance rating, salary level, index, and productivity category.

| File | Purpose |
|---|---|
| [Power BI report](laziness_data.pbix) | Dashboard file |
| [Dataset](Laziness_Analysis_200_Records.csv) | Sample activity data |
| [Main dashboard screenshot](screenshots/Dashboard1.png) | Dashboard images |

## Selected descriptive results
Calculated from the 200 records supplied with the project:

| Measure | Result |
|---|---:|
| Records | 200 |
| Average project-defined index | 0.391 |
| Records with index ≥ 0.40 | 86 |
| Highest department average | Sales — 0.406 |
| Lowest department average | Finance — 0.376 |
| Office average | 0.392 |
| Work From Home average | 0.390 |

The Office and Work From Home averages are close in this sample. The data does not support a strong claim that one work mode is materially associated with a higher index.

Average social-media usage is 3.34 hours for records marked as having missed a deadline and 3.52 hours for records not marked as having missed a deadline. This descriptive comparison does not establish causation.

## What the dashboard contains
- KPI cards and department comparisons
- Work-mode and productivity-category views
- Login hours versus completed tasks
- Employee-level details and filters
- Decomposition Tree for exploring the project-defined index
- What-If parameter for a hypothetical break-time change
- Analytical views comparing groups

## How to review
1. Open laziness_data.pbix in Power BI Desktop.
2. Explore each report page and use the available slicers.
3. Compare the visuals with the descriptive results above.
4. Review the CSV and the index definition before interpreting the results.

## Limitations
- The dataset contains 200 project records.
- The index and category thresholds are defined for this exercise, not validated organisational standards.
- Group comparisons are descriptive and do not establish cause and effect.
- Results should not be generalised to all employees or workplaces.
- The word “laziness” in the project name refers to the defined sample metric, not a verified judgement about a person.

## Author
**Shanmukh Koyya** · [GitHub](https://github.com/shanmukhkoyya) · [LinkedIn](https://www.linkedin.com/in/shanmukh-koyya/) · [Email](mailto:shanmukhkoyya1234@gmail.com)
