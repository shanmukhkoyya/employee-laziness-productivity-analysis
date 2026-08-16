# 📊 Employee Laziness & Productivity Analysis

A Power BI dashboard project analyzing **employee productivity, workplace laziness, work patterns, and behavioral factors** using 200 employee activity records.

The project uses **Power BI and DAX** to transform employee activity data into interactive dashboards and business-focused insights for productivity analysis and HR decision-making.

---

## 📌 Project Overview

This project analyzes employee activity data to identify productivity patterns and workplace laziness.

The dashboard calculates a **Laziness Index** and provides interactive analysis across:

- Employee productivity
- Department performance
- Work mode
- Login hours
- Active work hours
- Idle time
- Break time
- Social media usage
- Missed deadlines
- Meeting attendance
- Salary levels
- Task completion
- Employee-level performance

The main purpose is to understand employee work patterns and provide data-driven insights that can support HR and business decision-making.

---

## 🖥️ Dashboard Preview

### Main Dashboard

![Main Dashboard](screenshots/Dashboard1.png)

The main dashboard provides an overall view of employee productivity and workplace laziness.

### Employee Details

![Employee Details](screenshots/Dashboard2.png)

The Employee Details page provides employee-level information and productivity metrics.

### Laziness Drivers

![Laziness Drivers](screenshots/Dashboard3.png)

The Laziness Drivers page uses a **Decomposition Tree** to explore factors associated with the Laziness Index.

### Analytical Insights

![Analytical Insights](screenshots/Dashboard4.png)

The Analytical Insights page answers important business questions using Power BI visuals.

---

# 🎯 Objectives

The main objectives of this project are:

- Analyze employee productivity
- Identify departments with higher laziness levels
- Compare WFH and Office work modes
- Analyze social media usage and missed deadlines
- Compare salary levels and productivity
- Identify highly productive employees
- Identify departments requiring HR attention
- Explore relationships between employee work patterns and productivity
- Support data-driven HR decision-making

---

# 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **DAX**
- **CSV**
- **Data Analysis**
- **Data Visualization**
- **Business Intelligence**

---

# 📊 Dashboard Features

The Power BI report includes:

- KPI Cards
- Average Laziness by Department
- Productivity Category by Work Mode
- Productivity Category Distribution
- Login Hours vs Tasks Completed
- Top Lazy Employees
- Interactive Slicers
- Employee Drillthrough
- Decomposition Tree
- What-If Analysis
- Realistic Employee Scenarios
- Analytical Insights
- Conditional Formatting
- Dynamic Dashboard Title

---

# 📑 Dashboard Pages

## 1. Laziness & Productivity Dashboard

The main dashboard provides an overall view of employee productivity and laziness.

### Key Metrics

- Total Employees
- Average Task Completion
- High Laziness Employees
- Average Laziness

### Key Visuals

- Average Laziness by Department
- Productivity Category by Work Mode
- Productivity Category Distribution
- Login Hours vs Tasks Completed
- Top Lazy Employees
- Interactive Filters

### Purpose

This page provides a quick overview of employee productivity and laziness patterns across the organization.

---

## 2. Employee Details

The Employee Details page provides employee-level information for detailed analysis.

### Employee Information

- Employee ID
- Department
- Work Mode
- Login Hours
- Active Work Hours
- Idle Time Hours
- Break Time Hours
- Tasks Assigned
- Tasks Completed
- Deadline Missed
- Meetings Attended
- Social Media Usage Hours
- Performance Rating
- Salary Level
- Laziness Index
- Productivity Category
- Task Completion %

### Purpose

This page allows users to examine individual employee performance and work behavior.

---

## 3. Laziness Drivers

The Laziness Drivers page uses a **Decomposition Tree** to explore factors contributing to the Laziness Index.

The analysis can be explored through:

- Department
- Work Mode
- Idle Time Hours
- Break Time Hours
- Social Media Usage Hours
- Login Hours

A **What-If Parameter** is also included to analyze the potential impact of reducing break time.

### Purpose

This page allows users to explore different employee and workplace factors associated with Laziness Index values.

---

## 4. Realistic Twist

The Realistic Twist page presents realistic employee-level scenarios and supporting tables for business analysis.

The analysis includes:

- Social Media Usage
- Laziness Index
- Task Completion
- Tasks Assigned
- Tasks Completed
- Missed Deadlines

### Purpose

This page provides detailed employee-level information for practical business analysis.

---

## 5. Analytical Insights

The Analytical Insights page answers important business questions using visual analysis.

---

### Q1. Which department has the highest average laziness?

**Finding:** Sales has the highest average Laziness Index at approximately **0.41**.

**Business Insight:** Sales may require additional HR attention to understand the factors associated with its higher Laziness Index.

---

### Q2. Is WFH more associated with laziness?

**Finding:** The dashboard compares average laziness between Office and WFH employees.

The displayed analysis shows approximately **0.39 average Laziness Index for both work modes**.

**Business Insight:** The dashboard does not show a meaningful difference in average laziness between Office and WFH employees in the displayed analysis.

---

### Q3. Does salary level impact productivity?

**Finding:** Average task completion differs across salary levels:

| Salary Level | Average Task Completion |
|---|---:|
| Low | 72.88% |
| High | 71.61% |
| Medium | 65.81% |

**Business Insight:** The Low salary group has the highest average task completion, while the Medium salary group has the lowest in this dataset.

This shows a difference across salary groups, but the dashboard does not establish that salary itself causes the difference.

---

### Q4. What is the relationship between social media usage and missed deadlines?

**Finding:** The dashboard compares social media usage hours between employees who missed and did not miss deadlines.

Displayed totals:

| Deadline Status | Social Media Usage |
|---|---:|
| No | 464 |
| Yes | 227 |

**Business Insight:** Employees who did not miss deadlines have a higher total social media usage value in this dataset.

Therefore, the displayed analysis does not support the assumption that higher social media usage automatically results in missed deadlines.

---

### Q5. Who are the top 5 most productive employees?

**Finding:** Employee productivity is evaluated using **Task Completion %**.

Several employees achieve **100% task completion** in the dashboard.

**Business Insight:** Employees with high task completion can be studied to identify productive work patterns and practices that may support productivity improvement.

> Multiple employees have the same 100% task completion value, so the dashboard identifies employees with the highest completion performance rather than a unique top-five ranking.

---

### Q6. Is meeting attendance affecting task completion?

**Finding:** Meeting attendance is compared with task completion percentage using a scatter plot.

The displayed values do not show a simple consistent upward or downward pattern.

**Business Insight:** The visual does not show a clear linear relationship between meeting attendance and task completion in this dataset.

---

### Q7. Which department needs HR intervention?

**Finding:** Sales has the highest average Laziness Index at approximately **0.41**.

**Business Insight:** Sales can be considered a priority department for further HR analysis to understand productivity barriers and identify appropriate improvement strategies.

---

# 📁 Dataset

The dataset contains **200 employee activity records**.

## Main Fields

- Employee ID
- Department
- Work Mode
- Login Hours
- Active Work Hours
- Idle Time Hours
- Break Time Hours
- Tasks Assigned
- Tasks Completed
- Deadline Missed
- Meetings Attended
- Social Media Usage Hours
- Performance Rating
- Salary Level
- Laziness Index
- Productivity Category
- Task Completion %

---

# 📌 Laziness Index

The project uses the **Laziness Index** to classify employee productivity.

| Laziness Index | Category |
|---|---|
| `< 0.25` | Productive |
| `0.25 – 0.40` | Moderate |
| `≥ 0.40` | High Laziness |

### Classification

- **Productive:** Index < 0.25
- **Moderate:** Index 0.25–0.40
- **High Laziness:** Index ≥ 0.40

This classification is used throughout the dashboard to analyze employee productivity patterns.

---

# 🔍 Advanced Analysis

The project includes several Power BI features:

- Dynamic Dashboard Title
- Conditional Formatting
- Employee Drillthrough
- Decomposition Tree
- What-If Parameter
- Interactive Slicers
- Realistic Employee Scenarios
- Analytical Insights

These features allow users to explore employee productivity from multiple perspectives.

---

# 🌳 Decomposition Tree Analysis

The Decomposition Tree is used to explore the Laziness Index through multiple dimensions.

The analysis can be explored by:

```text
Laziness Index
│
├── Department
│
├── Work Mode
│
├── Idle Time Hours
│
├── Break Time Hours
│
├── Social Media Usage Hours
│
└── Login Hours
