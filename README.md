# HR Analytics Dashboard | Power BI

An interactive Power BI report that analyses an organisation's workforce: headcount, gender mix, age profile, salary spread, education qualifications, and hiring trends over time.

---

## Project Overview

HR teams need a quick, reliable view of who works in the organisation, how they are paid, and how the workforce has grown. This dashboard brings employee data together in one place so that HR and management can answer questions such as:

- How many employees are there in each job title?
- What is the gender distribution across the workforce?
- Which age groups make up most of the headcount?
- How do average, minimum, and maximum salaries differ by job title?
- How does salary vary with educational qualification?
- How has headcount grown over time based on joining dates?

---

## Tools Used

| Tool | Purpose |
|------|---------|
| Power BI Desktop | Data modelling, DAX measures, and report design |
| DAX | Calculated measures (headcount, cumulative headcount, salary statistics) |
| Power Query | Data loading and cleaning |

---

## Dataset

The report uses an employee dataset (table: `data`) linked to an education lookup table (`Education Qualification`).

**Key fields**

| Field | Description |
|-------|-------------|
| `Emp ID` | Unique employee identifier |
| `Name` | Employee name |
| `Gender` | Employee gender |
| `Job Title` | Role held by the employee |
| `Salary` | Employee salary |
| `Date of Join` | Date the employee joined |
| `Age` / `Age (bins)` | Employee age and age-group buckets |
| `Qualification` / `Qualification ID` | Education level (from the lookup table) |

---

## Key Measures

| Measure | What it shows |
|---------|---------------|
| `Headcount` | Number of employees |
| `cumulative Headcount` | Running total of employees by joining date |
| `Avg.salary` | Average salary per job title |
| `min.salary` | Lowest salary per job title |
| `max.salary` | Highest salary per job title |

---

## Dashboard Pages

The report has 7 pages, each focused on one view of the workforce.

| Page | Visual(s) | Insight |
|------|-----------|---------|
| 1. Overview | Funnel, pie, column, scatter, and line charts | One-page summary of headcount by job title, gender, age, qualification, and joining trend |
| 2. Gender Split | Pie chart + Job Title slicer | Gender distribution, filterable by job title |
| 3. Age Distribution | Column chart | Headcount by age bins |
| 4. Salary Summary | Table | Average, minimum, and maximum salary and headcount per job title |
| 5. Job Title Breakdown | Clustered bar chart + employee table | Headcount by job title with employee-level details (Emp ID, name, gender, salary) |
| 6. Salary vs Qualification | Scatter chart | Total salary compared across education qualifications |
| 7. Hiring Trend | Line chart | Headcount and cumulative headcount by date of joining |


---

## Author

**Abhay Sharma**
Data Analyst | Excel, Power BI, SQL
GitHub: [sharmaabhay2181-rgb](https://github.com/sharmaabhay2181-rgb)
