# Student Performance Indicator

This project analyzes how various attributes influence student performance using a dataset containing exam scores and demographic information. The analysis includes exploratory data analysis, data preprocessing, and visualization.

---

## Life Cycle of the Machine Learning Project

1. **Understanding the Problem Statement**  
   Analyze how student performance is affected by various factors such as gender, parental education, and test preparation.

2. **Data Collection**  
   - **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)  
   - **Details**: The dataset contains 1000 rows and 8 columns.

3. **Data Checks to Perform**  
   - Check for missing values  
   - Check for duplicates  
   - Analyze data types  
   - Determine unique values in each column  
   - Review statistical summaries  

4. **Exploratory Data Analysis (EDA)**  
   - Distribution analysis of categorical and numerical features  
   - Visualizations for insights on gender, parental education, race/ethnicity, and lunch preferences.

5. **Data Preprocessing**  
   - Add derived attributes like `Total Score` and `Average Score`.  
   - Normalize or encode data as needed for model training.

6. **Model Training**  
   - Train and evaluate models on preprocessed data.  
   - Choose the best-performing model based on evaluation metrics.

---

## Problem Statement

The objective is to understand how student performance is influenced by attributes such as gender, parental education, test preparation, and demographic factors.

---

## Dataset Overview

### Columns
- **Gender**: Male or Female  
- **Race/Ethnicity**: Groups A to E  
- **Parental Level of Education**: High school, some college, bachelor’s degree, etc.  
- **Lunch**: Standard or free/reduced  
- **Test Preparation Course**: Completed or none  
- **Math Score, Reading Score, Writing Score**: Exam scores  

---

## Key Insights from EDA

1. **Gender**  
   - Female students perform better overall, but male students slightly outperform in math.

2. **Parental Education**  
   - Students whose parents hold a master’s or bachelor’s degree tend to perform better.

3. **Race/Ethnicity**  
   - Students in Group E perform the best, while those in Group A perform the least.

4. **Test Preparation**  
   - Students who completed the test preparation course scored higher on average.

5. **Lunch Type**  
   - Students with a standard lunch perform better than those with free/reduced lunch.

---

## Visualizations

1. **Histogram and KDE Plots**  
   - Distribution of total and average scores across genders.  
   - Impact of lunch type on average scores.

2. **Bar Plots**  
   - Average scores for each race/ethnicity group.  
   - Correlation between parental education and student performance.

3. **Pie Charts**  
   - Gender distribution.  
   - Distribution of race/ethnicity, parental education, lunch type, and test preparation.

4. **Violin Plots**  
   - Score distribution across math, reading, and writing.

---

## Insights from Analysis

1. **Performance by Gender**  
   - Female students generally perform better, except in math.

2. **Performance by Race/Ethnicity**  
   - Groups A and B perform the lowest, while Group E performs the best.

3. **Impact of Parental Education**  
   - Higher parental education correlates with better student performance.

4. **Test Preparation Impact**  
   - Completing the test preparation course significantly improves scores.

---

## Conclusion

This analysis provides valuable insights into the factors influencing student performance. These insights can guide targeted interventions, such as additional support for underperforming groups or promoting test preparation courses to improve outcomes.

---

