# MIS 311 
## Introduction to Business Analytics
Data Analysis and Insight

## Student Exam Performance Analysis
### Introduction 

This report presents an Exploratory Data Analysis (EDA) of the Student Exam Performance dataset. The analysis aims to identify factors that may influence students’ academic performance, particularly final exam scores, using descriptive statistics and data visualization techniques.

### 1. Data Overview
**Sources of the data:** 
The dataset used in this analysis is the Student Exam Performance dataset provided for the MIS 311 assignment. 

**Number of rows and columns:** 
The dataset consists of approximately
- 10,001 rows (1 header and 10000 observations) 
- 23 columns (23 variables) 
Each row represents a student, and each column represents a specific feature related to academic performance and learning behavior. 

**The context or background of the data:**
The dataset contains information related to students’ demographic background, study habits, lifestyle factors, and academic performance.
Key variables include:
- Study hours per day
- Attendance rate
- Sleep hours
- Final exam scores
- Grade Category
The purpose of the dataset is to examine how different factors may influence students’ academic outcome and overall performance.

### 2. Data Cleaning
Data cleaning was conducted to ensure the accuracy and consistency of the analysis. The dataset was checked for missing values and duplicate records before performing statistical analysis.

- **Missing Values:** Inspection of the 23 variables across all 10,000 observations revealed zero missing values, requiring no data imputation or deletion.
- **Duplicate Rows:** No duplicate rows were detected; each record represents a unique student, ensuring data independence.
- **Data Types Verification:** The dataset features a well-structured mix of numerical variables (such as scores, study hours, … and attendance rates) and categorical variables (such as gender, parental education, study environment, … and pass/fail status), all correctly formatted for analysis.

**Data Cleaning Conclusion:**
*After an inspection process for missing value and duplicate, the dataset is fully intact, verified clean, and ready for advanced statistical analysis and visualization.*

### 3. Descriptive Statistics
Descriptive statistics were used to summarize the main characteristics of the dataset and provide an overview of student performance patterns.

Hình

The average final exam score is approximately 50, indicating moderate academic performance overall. Students spend an average of around 3 hours studying per day, while attendance rates remain relatively high around 84.7 across the dataset.


**Grade Distribution**

The histogram below illustrates the distribution of students’ final exam scores across the dataset. The visualization provides an overall overview of academic performance and helps identify common score ranges among students.

The distribution appears to be relatively concentrated around the middle score ranges, indicating that most students achieved average academic performance. Only a smaller proportion of students achieved extremely high or low scores.

#### Insight 1: Study Hours and Final Exam Performance

Hình

The scatter plot demonstrates a positive relationship between study hours per day and final exam scores. Students who spend more time studying generally tend to achieve higher examination results.

This finding suggests that study habits play a significant role in academic performance. Consistent studying may improve students’ understanding of course materials and increase their likelihood of achieving better academic outcomes.

#### Insight 2: Attendance Rate and Academic Performance

Hình

The analysis indicates a positive relationship between attendance rate and final exam performance. Students with higher attendance rates generally achieve better examination scores compared to students with lower attendance levels.

Regular attendance may help students better understand lecture content, participate in classroom activities, and remain engaged with the learning process. This highlights the importance of classroom participation in supporting academic success.


**Grade Category Distribution**
Pivot table
Pivot chart 

The grade category distribution shows that most students achieved average performance levels, while a smaller proportion of students reached the highest grade categories. This distribution provides an overall overview of academic achievement within the dataset.


### Implications of the Findings
The findings of this analysis suggest that study habits and classroom attendance play important roles in students’ academic performance. Students who spend more time studying and attend classes regularly tend to achieve higher final exam scores.

These results imply that educational institutions may improve student performance by encouraging consistent study routines and increasing student engagement in class activities. In addition, providing academic support programs and promoting effective time management strategies may help students achieve better learning outcomes.

The analysis also demonstrates how data analytics can be used in the education sector to identify performance patterns and support data-driven decision-making.

### Conclusion
In conclusion, the exploratory data analysis identified several factors associated with student academic performance. The findings indicate that both study hours and attendance rates have positive relationships with final exam scores.

These results suggest that consistent study habits and regular class attendance are important contributors to academic success. The analysis also demonstrates how business analytics techniques such as descriptive statistics and data visualization can be used to uncover meaningful insights from educational data.

### References
