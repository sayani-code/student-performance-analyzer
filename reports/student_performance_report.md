# Student Performance Analysis Report

## 1. Project Overview

This project analyzes a student-performance dataset to identify factors associated with exam performance.

The analysis includes data cleaning, exploratory data analysis, relationship analysis, visualization, and interpretation of the findings.

## 2. Dataset

The dataset contains **6,607 student records and 20 original variables**.

The target variable is `Exam_Score`.

The dataset contains both numerical and categorical variables covering areas such as attendance, study time, previous scores, parental involvement, access to resources, tutoring, motivation, and peer influence.

## 3. Data Cleaning

The dataset was checked for missing values, duplicate records, invalid numerical values, and unusual observations.

Missing values were identified in `Teacher_Quality`, `Parental_Education_Level`, and `Distance_from_Home`.

There were no duplicate rows.

Numerical variables such as attendance, study hours, sleep hours, previous scores, and exam scores were checked for sensible ranges.

After cleaning, `Exam_Score` ranged from 55 to 100.

## 4. Exploratory Analysis

The exam scores had a mean of approximately **67.24** and a median of **67**.

Among the numerical variables, `Attendance` had the strongest observed linear relationship with exam performance, with a correlation of **0.58**.

`Hours_Studied` had the second strongest relationship, with a correlation of **0.45**.

`Previous_Scores` and `Tutoring_Sessions` showed weaker positive relationships.

## 5. Categorical Factors

Among the categorical variables, `Access_to_Resources` showed the largest difference in average exam scores between its highest and lowest groups, at approximately **1.89 points**.

`Parental_Involvement` showed the second-largest difference, at approximately **1.73 points**.

Other categorical variables showed smaller differences in average exam scores.

## 6. Key Findings

The analysis identified four factors that stood out most:

* **Attendance**
* **Hours Studied**
* **Access to Resources**
* **Parental Involvement**

Attendance and study time were the strongest numerical factors, while access to resources and parental involvement showed the largest categorical group differences.

## 7. Recommendations

Based on the findings, schools could focus on improving attendance, supporting effective study habits, ensuring equitable access to learning resources, and encouraging constructive parental involvement.

These recommendations should be treated as areas for further investigation rather than proven causal interventions.

## 8. Limitations

This analysis is based on observational data, so the relationships identified do not establish causation.

Some categorical groups are imbalanced, and missing values were present in several variables.

Correlation and differences in group means are also different statistical measures and should not be treated as directly comparable measures of importance.

The analysis identifies associations in this dataset rather than definitive causes of exam performance.

## 9. Conclusion

The exploratory analysis suggests that attendance and study time have the strongest observed numerical associations with exam performance.

Access to resources and parental involvement also show meaningful differences between groups.

However, no single factor explains student exam performance completely. Exam outcomes are likely associated with multiple student, family, school, and behavioral factors.

Further analysis using statistical modeling could help determine whether these relationships remain important when multiple factors are considered simultaneously.

