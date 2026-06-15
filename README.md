# Data Science Salary Analysis (SQL + Python Project)

## Overview

This project explores what factors influence salaries in data science roles using a real-world Kaggle dataset. The goal is to understand how **experience level, job title, company size, and remote work arrangements** relate to compensation.

I used **SQL, Python (pandas, matplotlib)**, and exploratory data analysis techniques to analyze trends and communicate insights visually.

---

## Dataset

The dataset contains job-related salary information for data science roles, including:

- Job title  
- Experience level (EN, MI, SE, EX)  
- Salary (converted to USD)  
- Company size (S, M, L)  
- Remote ratio (0%, 50%, 100%)  
- Employment type  
- Company location  
- Work year  

Source: Kaggle – Data Science Job Salaries dataset

---

## Tools & Technologies

- Python (Pandas, NumPy, Matplotlib)
- SQL (SQLite via `sqlite3`)
- Jupyter Notebook
- Data visualization (Matplotlib)

---

## Key Questions Explored

- How does salary vary by experience level?
- Which job titles have the highest salaries?
- Does company size affect compensation?
- Does remote work influence salary levels?
- What combinations of job title and experience pay the most?

---

## SQL Workflow

The dataset was loaded into a SQLite database to enable structured querying.

Example:

```sql
SELECT
    experience_level,
    AVG(salary_in_usd) AS avg_salary
FROM salaries
GROUP BY experience_level;
