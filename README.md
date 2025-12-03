>>📊 Data Analytics Learning Journey — Udemy Course

Welcome to my repository!
This repo documents everything I learned during my Udemy Data Analytics Course, including hands-on practice, notes, exercises, and Python/SQL operations.
---
#🚀 Course Summary

Throughout this course, I explored the complete data analytics workflow using Python, Pandas, NumPy, Matplotlib, Seaborn, and SQL.
This repository contains my practice notebooks, case studies, and examples.

🧠 Topics I Learned
🔹 1. Python Basics for Data Analysis

Variables, data types

Conditional statements

Loops (for, while)

Functions

List, Tuple, Dictionary operations

📘 2. Pandas Fundamentals
✓ Data Structures

Series

DataFrame

✓ Importing Data
pd.read_csv()
pd.read_excel()
pd.read_json()

✓ Data Viewing / Exploring

.head(), .tail(), .shape, .info()

.describe()

.value_counts()

✂️ 3. Data Slicing & Filtering
Row slicing
df[0:10]
df.loc[0:5]
df.iloc[0:5]

Column selection
df['column']
df[['col1', 'col2']]

Conditional filtering
df[df['Age'] > 30]
df[(df['Gender'] == 'Male') & (df['Salary'] > 50000)]

🧼 4. Data Cleaning

Handling missing values

df.isnull().sum()
df.fillna()
df.dropna()


Duplicates removal

df.drop_duplicates()


Data type conversions

df['date'] = pd.to_datetime(df['date'])

🔧 5. Data Transformation

Applying functions (apply, map, lambda)

Grouping and aggregation

df.groupby('Department')['Salary'].mean()


Sorting

df.sort_values(by='Salary', ascending=False)

📉 6. Data Visualization

Using Matplotlib & Seaborn:

Line chart

Bar chart

Histogram

Boxplot

Heatmaps

Example:

sns.boxplot(x='Department', y='Salary', data=df)

🗄️ 7. SQL for Data Analysis

SELECT, WHERE, GROUP BY

ORDER BY, LIMIT

JOIN operations

Aggregations

Subqueries

Example:

SELECT department, AVG(salary)
FROM employees
GROUP BY department;

📁 Repository Structure
📦 data-analytics-udemy-learning
 ┣ 📂 datasets
 ┣ 📂 notebooks
 ┣ 📂 practice
 ┣ 📄 README.md

🎯 Goal of This Repo

To track my progress in Data Analytics

To build strong foundations in Python, SQL, and data handling

To prepare for Data Analyst roles

To showcase my learning journey

🙌 Connect With Me
