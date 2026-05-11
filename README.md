# Data Job Market Analysis with Python

A Python-based exploratory data analysis project focused on job market trends, technical skill demand, salary distribution, and high-value skills across data-related roles.

The project uses Jupyter Notebooks, pandas, matplotlib, and seaborn to analyze job postings and identify which skills are most common, which roles pay more, and which technical skills provide the best balance between demand and salary.

## Project Overview

This project analyzes the data job market using a dataset from Luke Barousse's Python course. The dataset includes job titles, salaries, locations, and required skills.

The main goal of the project is to practice Python-based data analysis while extracting useful insights about the job market for Data Analysts, Data Scientists, Data Engineers, and related roles.

## Key Questions

This project answers four main questions:

1. What skills are most in demand for the top data roles?
2. How are in-demand skills trending for Data Analyst roles?
3. How do salaries differ across data-related jobs and skills?
4. What are the most optimal skills to learn based on both demand and salary?

## Tech Stack

- Python
- pandas
- matplotlib
- seaborn
- Jupyter Notebook
- VS Code
- Git and GitHub

## Project Structure

```text
data-job-market-analysis-python/
│
├── 3_Project/
│   ├── images/              # Generated visualizations
│   └── notebooks/           # Jupyter notebooks with analysis steps
│
└── README.md
```

## Analysis Sections

### 1. Skill Demand by Role

This section analyzes the most demanded skills for the most common data roles, including Data Analyst, Data Scientist, and Data Engineer.

Notebook:

```text
3_Project/notebooks/2_Skill_Demand.ipynb
```

![Skill demand by role](3_Project/images/skill_demand_all_data_roles.png)

Key findings:

- SQL is one of the most important skills for Data Analyst roles.
- Python is strongly demanded across Data Scientist and Data Engineer roles.
- Data Engineer roles require more specialized tools such as cloud platforms and big data technologies.

### 2. Data Analyst Skill Trends

This section analyzes how demand for Data Analyst skills changes over time.

Notebook:

```text
3_Project/notebooks/3_Skills_Trend.ipynb
```

![Data Analyst skill trends](3_Project/images/skill_trend_DA.png)

Key findings:

- SQL remains one of the most consistent skills in Data Analyst job postings.
- Excel, Tableau, Power BI, and Python appear frequently in job listings.
- Skill demand changes over time, so tracking market trends is useful for career planning.

### 3. Salary Analysis

This section compares salary distributions across different data-related job titles.

Notebook:

```text
3_Project/notebooks/4_Salary_Analysis.ipynb
```

![Salary distribution](3_Project/images/salary_boxplot.png)

Key findings:

- Senior and more specialized roles generally have higher salary ranges.
- Data Analyst roles show more stable salary distributions compared with senior technical roles.
- Data Scientist and Data Engineer roles often have higher compensation ceilings.

### 4. Salary and Skill Analysis

This section compares skills by salary and demand to identify which technical skills are both valuable and practical to learn.

Notebook:

```text
3_Project/notebooks/5_Salary_Skills_Analysis.ipynb
```

Key findings:

- Some specialized technical skills are associated with higher salaries.
- Common tools such as SQL, Excel, Tableau, and Python remain important because they appear frequently in job postings.
- The most valuable skills are those that combine strong market demand with strong salary potential.

### 5. Optimal Skills to Learn

This section identifies skills that offer a strong balance between job market demand and salary potential.

Key findings:

- Programming and database skills tend to be associated with stronger salary outcomes.
- SQL remains one of the most practical skills because it combines high demand with broad applicability.
- Python is valuable because it supports analysis, automation, data processing, and more advanced technical work.

## What I Practiced

Through this project, I practiced:

- exploratory data analysis with Python
- data cleaning and transformation with pandas
- grouping, filtering, and aggregating data
- visualizing data with matplotlib and seaborn
- working with Jupyter Notebooks
- analyzing job market data
- presenting technical findings in a structured GitHub repository

## Possible Improvements

Future improvements could include:

- converting repeated notebook logic into reusable Python modules
- adding a `requirements.txt` file
- adding a cleaner data folder structure
- creating a single summary notebook
- exporting the final analysis as an HTML or PDF report
- turning the analysis into an automated job market tracking pipeline
