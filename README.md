# Employee Laziness & Productivity Analysis

A Power BI dashboard project analyzing employee productivity, workplace laziness, work patterns, and behavioral factors using 200 employee activity records.

---

## 📌 Project Overview

This project analyzes employee activity data to identify productivity patterns and workplace laziness.

The dashboard uses **Power BI and DAX** to calculate a Laziness Index and provide business-focused insights related to employee productivity, work mode, social media usage, deadlines, meetings, salary levels, and departmental performance.

---

## 📊 Dashboard Preview

![Employee Laziness & Productivity Dashboard](screenshots/Dashboard1.png)

---


## 🎯 Objectives

- Analyze employee productivity
- Identify departments with higher laziness
- Compare WFH and Office work modes
- Analyze social media usage and missed deadlines
- Compare salary levels and productivity
- Identify highly productive employees
- Identify departments requiring HR attention

---

## 🛠️ Tools & Technologies

- **Power BI**
- **DAX**
- **CSV**
- **Data Analysis**
- **Data Visualization**
- **Business Intelligence**

---

## 📊 Dashboard Features

The Power BI report includes:

- KPI Cards
- Average Laziness by Department
- Work Mode vs Productivity Category
- Productivity Category Distribution
- Login Hours vs Tasks Completed
- Top 10 Lazy Employees
- Interactive Slicers
- Employee Drillthrough
- Decomposition Tree
- What-If Analysis
- Realistic Employee Scenarios
- Analytical Insights
- Conditional Formatting
- Dynamic Dashboard Title

---

## 📈 Dashboard Pages

### 1. Laziness & Productivity Dashboard

The main dashboard provides an overall view of employee productivity and laziness.

Key elements include:

- Total Employees
- Average Task Completion
- High Laziness Employees
- Average Laziness
- Average Laziness by Department
- Productivity Category by Work Mode
- Productivity Category Distribution
- Login Hours vs Tasks Completed
- Top Lazy Employees
- Interactive filters

---

### 2. Employee Details

The Employee Details page provides employee-level information including:

- Employee ID
- Department
- Work Mode
- Login Hours
- Tasks Completed
- Social Media Usage Hours
- Performance Rating
- Salary Level
- Laziness Index
- Task Completion %

---

### 3. Laziness Drivers

The Laziness Drivers page uses a **Decomposition Tree** to explore factors contributing to the Laziness Index.

The analysis can be explored through dimensions such as:

- Department
- Work Mode
- Idle Time Hours
- Break Time Hours
- Social Media Usage Hours
- Login Hours

A What-If parameter is also included to analyze the impact of reducing break time.

---

### 4. Realistic Twist

This page presents realistic employee-level scenarios and supporting tables for business analysis.

It includes analysis related to:

- Social Media Usage
- Laziness Index
- Task Completion
- Tasks Assigned
- Tasks Completed
- Missed Deadlines

---

### 5. Analytical Insights

The Analytical Insights page answers important business questions using visual analysis.

#### Q1. Which department has the highest average laziness?

Sales has the highest average Laziness Index at approximately **0.41**.

#### Q2. Is WFH more associated with laziness?

The dashboard compares average laziness between **Office** and **WFH** employees to identify differences between work modes.

#### Q3. Does salary level impact productivity?

Productivity is compared across **Low, Medium, and High** salary levels using average task completion percentage.

#### Q4. What is the relationship between social media usage and missed deadlines?

The dashboard compares social media usage with employees who **missed** and **did not miss** deadlines.

#### Q5. Who are the top 5 most productive employees?

Employee task completion percentages are used to identify employees with the highest productivity.

#### Q6. Is meeting attendance affecting task completion?

Meeting attendance is compared with task completion percentage to identify potential patterns.

#### Q7. Which department needs HR intervention?

The dashboard highlights departments with higher laziness levels that may require additional HR attention.

---

## 📂 Dataset

The dataset contains **200 employee activity records**.

### Main Fields

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

## 📌 Laziness Index

The project uses the **Laziness Index** to classify employee productivity.

| Laziness Index | Category |
|---|---|
| `< 0.25` | Productive |
| `0.25 – 0.40` | Moderate |
| `≥ 0.40` | High Laziness |

---

## 🔍 Advanced Analysis

The project includes several Power BI features:

- Dynamic Dashboard Title
- Conditional Formatting
- Employee Drillthrough
- Decomposition Tree
- What-If Parameter
- Interactive Slicers
- Realistic Employee Scenarios
- Analytical Insights

---

## 📸 Dashboard Screenshots

### Main Dashboard

![Dashboard 1](screenshots/Dashboard1.png)

### Employee Details

![Dashboard 2](screenshots/Dashboard2.png)

### Laziness Drivers

![Dashboard 3](screenshots/Dashboard3.png)

### Analytical / Insights Dashboard

![Dashboard 4](screenshots/Dashboard4.png)

---

## 📁 Project Files

| File | Description |
|---|---|
| `laziness_data.pbix` | Power BI project file |
| `Laziness_Analysis_200_Records.csv` | Source dataset |
| `screenshots/` | Dashboard screenshots |
| `README.md` | Project documentation |

---

## 💡 Key Business Value

This analysis can help organizations:

- Identify departments with higher laziness levels
- Monitor employee productivity
- Compare different work modes
- Understand behavioral productivity factors
- Identify employees requiring attention
- Support HR decision-making
- Explore potential relationships between work habits and performance

---

## 🚀 How to Use

1. Download the `.pbix` Power BI file.
2. Open the file using **Microsoft Power BI Desktop**.
3. Explore the dashboard pages.
4. Use the available slicers and filters.
5. Interact with the visuals to analyze employee productivity.
6. Use the drillthrough and decomposition tree features for deeper analysis.

---

## 👤 Author

**Shanmukh Koyya**

Aspiring Data Analyst | Power BI | SQL | Python | Excel

---

## ⭐ Project Highlights

**Domain:** Employee Productivity Analytics  
**Tool:** Power BI  
**Dataset:** 200 Employee Records  
**Focus:** Productivity, Laziness, Work Patterns & HR Insights
