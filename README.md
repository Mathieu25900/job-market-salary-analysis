# Data Science Job Market Salary Analysis
## 📊 Overview

This project explores salary trends in the data science and analytics job market using a dataset of global job postings. The goal is to understand how factors such as experience level, job title, and remote work percentage influence salary distribution.

The analysis focuses on identifying patterns in compensation while also considering data reliability through sample sizes and distribution statistics.

---

## 🎯 Objectives

- Understand how salary varies by **experience level**
- Analyze how salary varies across different job titles
- Explore the relationship between **remote work and compensation**
- Compare **mean vs median salaries** to detect outliers
- Evaluate **data reliability using sample size**

---

## 📁 Dataset

- Source: Data Science Job Salaries Dataset (Kaggle)
- Approximately 600 job records
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
# Average salary by experience level to understand career progression impact
df.groupby("experience_level")["salary_in_usd"].mean()
```

Key Insights
Salary increases significantly with experience level, showing a clear career progression trend.
Mean salaries are often higher than median values, indicating the presence of high-income outliers.
Job titles with higher salaries tend to have smaller sample sizes, making them less statistically reliable.
Data Scientist, Data Engineer, and Data Analyst roles represent the most stable and well-represented salary groups.
Remote work shows variation in salary but is less consistent compared to experience level and job title.
