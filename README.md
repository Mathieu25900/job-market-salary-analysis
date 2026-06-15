# 📊 Data Science Salary Analysis (SQL + Python Project)

## 🧠 Overview

This project explores what factors influence salaries in data science roles using a real-world Kaggle dataset. The goal is to understand how **experience level, job title, company size, and remote work arrangements** relate to compensation.

I used SQL, Python (pandas, matplotlib), and exploratory data analysis techniques to analyze trends and communicate insights visually.

Rather than just looking at raw numbers, I focused on understanding patterns that can help explain how data roles are valued in the job market.

---

## 📂 Dataset

The dataset contains job-related salary information for data science roles, including:

- Job title  
- Experience level (EN, MI, SE, EX)  
- Salary (converted to USD)  
- Company size (S, M, L)  
- Remote ratio (0%, 50%, 100%)  
- Employment type  
- Company location  
- Work year  

**Source:** Kaggle – Data Science Job Salaries dataset

---

## 🛠 Tools & Technologies

- Python (Pandas, NumPy, Matplotlib)  
- SQL (SQLite via `sqlite3`)  
- Jupyter Notebook  
- Data visualization (Matplotlib)  

---

## ❓ Key Questions Explored

I approached this analysis by asking:

- How does salary change with experience level?
- Which job titles tend to pay the most?
- Does company size influence compensation?
- Is remote work associated with higher or lower salaries?
- Which combinations of job title and experience level are most valuable?

---

## 🗄️ SQL Workflow

To make the analysis more structured, I loaded the dataset into a SQLite database and used SQL queries to explore trends.

### Example SQL Query:

```sql
SELECT
    experience_level,
    AVG(salary_in_usd) AS avg_salary
FROM salaries
GROUP BY experience_level;
```

---

## 📊 Key Insights

From the analysis, a few clear patterns emerged:

- Experience level is the strongest factor influencing salary  
- Senior roles (SE, EX) earn significantly more than entry-level positions  
- Job title plays a major role in salary differences  
- Larger companies tend to offer higher average compensation  
- Remote work shows mixed but interesting patterns depending on role type  

Overall, salary is driven by a combination of experience, specialization, and company structure.

---

## 📈 Visualizations

The following visualizations were created using Python:

- Salary distribution by experience level  
- Average salary by company size  
- Salary comparison across job titles  
- Remote ratio vs salary analysis  
- Top-paying job titles  

These visuals helped translate raw data into meaningful insights.

---

## 🧠 Conclusion

This project demonstrates how SQL and Python can be used together to analyze real-world salary trends in the data science industry.

The analysis highlights that experience level and job title are the strongest predictors of salary, while company size and remote work also contribute interesting variations.

---

## 👤 Author

**Mathieu Sze**  
B.A. Computer Science & Mathematics (Statistics Concentration)  
Aspiring Data Analyst
