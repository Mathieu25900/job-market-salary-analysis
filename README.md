# job-market-salary-analysis
## 📊 Overview

This project explores salary trends in the data science and analytics job market using a dataset of global job postings. The goal is to understand how factors such as experience level, job title, and remote work percentage influence salary distribution.

The analysis focuses on identifying patterns in compensation while also considering data reliability through sample sizes and distribution statistics.

---

## 🎯 Objectives

- Understand how salary varies by **experience level**
- Analyze salary differences across **job titles**
- Explore the relationship between **remote work and compensation**
- Compare **mean vs median salaries** to detect outliers
- Evaluate **data reliability using sample size**

---

## 📁 Dataset

- Source: Data Science Job Salaries Dataset (Kaggle)
- Records: ~600+ job entries
- Features include:
  - Job title
  - Salary in USD
  - Experience level
  - Remote ratio
  - Company location
  - Employment type

---

## 🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib

---

## 📊 Key Analysis

### 1. Salary vs Experience Level
We compare average salary across different experience levels to understand how career progression impacts earnings.

```python
df.groupby("experience_level")["salary_in_usd"].mean()
