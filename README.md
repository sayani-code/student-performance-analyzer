# Student Performance Analyzer

An exploratory data analysis project investigating factors associated with student exam performance.

## 📌 Project Overview

This project analyzes student-performance data to understand which academic, behavioral, family, and school-related factors are most strongly associated with `Exam_Score`.

The project was completed as an independent analysis rather than following a step-by-step tutorial.

## 🎯 Objectives

* Clean and validate the dataset
* Explore the distribution of exam scores
* Analyze relationships between numerical variables and exam performance
* Compare exam scores across categorical groups
* Identify the strongest observed factors associated with exam scores
* Communicate findings through visualizations
* Develop evidence-based conclusions and recommendations

## 📊 Dataset

The dataset contains:

* **6,607 student records**
* **20 original variables**
* Numerical and categorical features
* `Exam_Score` as the target variable

The variables include:

* Hours studied
* Attendance
* Previous scores
* Sleep hours
* Tutoring sessions
* Parental involvement
* Access to resources
* Motivation level
* Teacher quality
* Peer influence
* Learning disabilities
* Family income
* Distance from home
* And other student characteristics

## 🧹 Data Cleaning

The dataset was checked for:

* Missing values
* Duplicate records
* Invalid numerical values
* Unusual exam scores
* Data types and categorical values

Missing values were found in:

* `Teacher_Quality`
* `Parental_Education_Level`
* `Distance_from_Home`

No duplicate rows were identified.

After cleaning, exam scores ranged from **55 to 100**.

## 🔍 Exploratory Data Analysis

The analysis examined:

* Exam score distribution
* Numerical correlations
* Attendance and exam performance
* Study time and exam performance
* Tutoring sessions
* Parental involvement
* Access to resources
* Teacher quality
* Motivation
* Peer influence
* Learning disabilities

## 📈 Key Findings

### Numerical Factors

| Factor            | Correlation with Exam Score |
| ----------------- | --------------------------: |
| Attendance        |                    **0.58** |
| Hours Studied     |                    **0.45** |
| Previous Scores   |                        0.18 |
| Tutoring Sessions |                        0.16 |

Attendance showed the strongest observed linear relationship with exam performance, followed by hours studied.

### Categorical Factors

The largest differences in average exam scores were observed for:

| Factor                |      Difference |
| --------------------- | --------------: |
| Access to Resources   | **1.89 points** |
| Parental Involvement  | **1.73 points** |
| Learning Disabilities |     1.08 points |
| Peer Influence        |     1.06 points |

## 📊 Visualizations

### Attendance vs Exam Score

![Attendance vs Exam Score](visualizations/attendance_vs_exam_score.png)

### Hours Studied vs Exam Score

![Hours Studied vs Exam Score](visualizations/hours_studied_vs_exam_score.png)

### Access to Resources vs Exam Score

![Access to Resources vs Exam Score](visualizations/access_to_resources_vs_exam_score.png)

### Parental Involvement vs Exam Score

![Parental Involvement vs Exam Score](visualizations/parental_involvement_vs_exam_score.png)

### Top Numerical Factors

![Top Numerical Factors](visualizations/top_numerical_factors.png)

## 💡 Recommendations

Based on the exploratory findings:

1. Encourage consistent student attendance.
2. Support structured and effective study habits.
3. Improve equitable access to learning resources.
4. Encourage constructive parental involvement.
5. Use further statistical analysis before making causal claims.

## ⚠️ Limitations

This is an observational analysis. Therefore, the relationships identified do not prove that any factor directly causes higher or lower exam scores.

The analysis also uses different measures for numerical and categorical variables, so their effect sizes should not be directly compared.

Some categorical groups are imbalanced, and missing values were present in the original dataset.

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
* Git & GitHub

## 📁 Project Structure

```text
student-performance-analyzer/
│
├── data/
│   ├── raw/
│   │   └── student_performance.csv
│   └── cleaned/
│       └── student_performance_cleaned.csv
│
├── notebooks/
│   └── student_performance_analysis.ipynb
│
├── visualizations/
│   ├── attendance_vs_exam_score.png
│   ├── hours_studied_vs_exam_score.png
│   ├── access_to_resources_vs_exam_score.png
│   ├── parental_involvement_vs_exam_score.png
│   └── top_numerical_factors.png
│
├── reports/
│   └── student_performance_report.md
│
├── README.md
├── requirements.txt
└── .gitignore
```

## 📄 Report

A concise project report is available in:

`reports/student_performance_report.md`

## 🔬 Future Improvements

Future analysis could use:

* Multiple linear regression
* Statistical significance testing
* Feature importance analysis
* Cross-validation
* Predictive modeling
* Interaction effects between factors

These methods could provide a deeper understanding of whether the observed relationships remain important when multiple variables are considered simultaneously.

