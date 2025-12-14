
# Data Job Market Analysis (Excel Analytics Project)

## Overview
This project analyzes the global data job market using real-world job posting data from 2023.  
The goal is to understand how **skills, job roles, and geography** influence salary levels, using Excel as an enterprise analytics tool.

The project demonstrates end-to-end analytical workflows including **ETL, data modeling, DAX, and insight-driven visualization**.

---

## Business Questions
1. Do roles requiring more skills offer higher pay?
2. How do salaries differ between US and Non‑US markets?
3. What skills are most in demand for data professionals?
4. Which skills are associated with the highest salaries?

---

## Tools & Techniques
- Microsoft Excel
- Power Query (ETL)
- Power Pivot (Data Modeling)
- DAX (Measures)
- PivotTables & PivotCharts
- Advanced Data Visualization

---

## Data Preparation (ETL)

### Power Query
Raw job posting data was cleaned and transformed using Power Query:
- Standardized job titles and locations
- Normalized skills into a relational table
- Cleaned salary fields and dates
- Built reusable queries for refreshable analysis

**Power Query – Job Data**

![Power Query Job Data](images/Screenshot1.png)

**Power Query – Skills Table**

![Power Query Skills](images/Screenshot2.png)

---

## Data Modeling

A relational data model was built using Power Pivot:
- `data_jobs_all` (job-level data)
- `data_jobs_skills` (skill-level data)
- One-to-many relationship on `job_id`

**Data Model Relationship**

![Data Model](images/Screenshot3.png)

**Power Pivot Interface**

![Power Pivot](images/Screenshot4.png)

---

## Key Insights

### 1. Skills vs Salary
There is a positive relationship between the number of required skills and median salary, particularly for senior and engineering-focused roles.

![Skills vs Salary](images/chart1.png)

---

### 2. Salary by Region
US-based data roles command higher median salaries compared to Non‑US roles, especially in senior positions.

![Salary by Region](images/chart2.png)

---

### 3. Most In-Demand Skills
SQL and Python dominate job requirements, followed by cloud technologies such as AWS and Azure.

![Top Skills](images/chart3.png)

---

### 4. Pay of Top Skills
Technical skills like Python and SQL are associated with higher median salaries, while general office tools show lower compensation impact.

![Top Skill Pay](images/chart4.png)

---

## Why This Project Matters
This project reflects real-world analytical practices:
- Business-driven questioning
- Clean, scalable data models
- Insight-focused storytelling
- Corporate-ready documentation

It is suitable for showcasing Excel analytics skills to recruiters and hiring managers.

---

## Author
**Pawat Kusonchukul**  
Data Analyst | Analytics Graduate
