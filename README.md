# Student Performance Analysis: Python & Pandas Basics

A beginner project from the Tech4Youth Data Analytics Programme. I used Python and Pandas to explore, clean and summarise a dataset of student academic performance.

## Objective
Practise loading, inspecting, cleaning and summarising data with Pandas, and use it to find patterns in student scores.

## Dataset
`student_performance.csv` is a **synthetic (fictional) dataset** created for practice. It has 40 students and 12 columns: Student_ID, Student, Gender, Department, Level, Study_Hours_Weekly, Attendance_Percent, and scores in Mathematics, English, Chemistry, Physics and Biology.

Five values were left missing on purpose (2 in Attendance_Percent, 1 in English, 2 in Physics) to practise data cleaning.

## Skills Demonstrated
- Loading data with `pd.read_csv()`
- Inspecting data with `head()`, `shape`, `info()` and `describe()`
- Finding missing values with `isnull().sum()`
- Filling missing values with the median using `fillna()`
- Creating a new column (`Average`) from existing ones
- Grouping and aggregating with `groupby()`
- Measuring relationships with `corr()`
- Filtering rows (top performers)

## Key Findings
- The overall average score was about **58.4**.
- Average score by department: Computer Education **63.1**, Arts Education **57.6**, Mathematics Education **56.9**, Integrated Science **55.7**.
- Study hours and average score had a strong positive correlation (**0.93**). Attendance also correlated with scores (**0.72**).
- Five students averaged 70 or above, led by Victor (80.0).

**Note:** these patterns come from fictional data, so they show how the analysis works rather than real-world conclusions.

## Tools
- Python 3
- Pandas
- Google Colab

## Files
- `python_pandas_basics.ipynb`: main analysis notebook
- `student_performance.csv`: dataset

## Author
Daniel Onyedikachi Eze
Integrated Science Education Undergraduate, University of Nigeria, Nsukka
