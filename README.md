Data Science Salary Analysis (SQL + Python Project)

Overview

This project explores what factors influence salaries in data science roles using a real-world Kaggle dataset. The goal was to understand how experience level, job title, company size, and remote work affect compensation.

I used a combination of SQL, Python (pandas, matplotlib), and exploratory data analysis techniques to uncover trends and present insights in a clear, visual way.

Dataset

The dataset contains data science job salaries including:

Job title
Experience level (EN, MI, SE, EX)
Salary (USD)
Company size (S, M, L)
Remote ratio (0%, 50%, 100%)
Employment type
Company location

Source: Kaggle “Data Science Job Salaries” dataset

Tools & Technologies
Python (Pandas, NumPy, Matplotlib)
SQL (SQLite)
Jupyter Notebook
Data visualization (Matplotlib)
🔍 Key Questions Explored
How does salary change with experience level?
Do certain job titles pay significantly more than others?
Does company size impact salary?
Are remote jobs associated with higher pay?
What are the highest-paying roles in the dataset?
📊 Analysis Performed
1. Experience Level vs Salary

Used SQL aggregation to calculate average salaries by experience level.

Finding:
Salary increases significantly with experience:

Entry-level (EN) → lowest average salary
Executive (EX) → highest average salary
2. Job Title Analysis

Grouped salaries by job title and experience level.

Finding:
Roles like:

Data Engineer
Data Scientist
Machine Learning Scientist
tend to have the highest earning potential.
3. Company Size Impact

Analyzed salary differences across small, medium, and large companies.

Finding:
Large companies generally show higher average salaries compared to smaller organizations.

4. Remote Work vs Salary

Compared salaries across remote (0%, 50%, 100%) roles.

Finding:
Fully remote roles show higher average salaries in this dataset, though this may be influenced by role distribution.

Example Visualizations
Salary by experience level (bar chart)
Salary by company size
Salary by remote ratio
Top-paying job titles
Key Insights
Experience level is the strongest predictor of salary
Job title has a major impact on earning potential
Large companies tend to pay more on average
Remote work shows interesting salary variation patterns
Salary distributions are highly skewed, with some high-end outliers

What I Learned

This project helped me strengthen my skills in:

Writing SQL queries for real-world analysis
Performing exploratory data analysis in Python
Cleaning and transforming datasets
Communicating insights through visualizations
Thinking like a data analyst (not just coding)

Future Improvements
Build an interactive dashboard (Power BI or Tableau)
Add geographic analysis (salary by country)
Explore regression modeling for salary prediction
Include more advanced statistical analysis
