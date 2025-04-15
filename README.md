### Capstone-Project

# **Student's Performance and Learning style Analysis**

**Name** : Ambili A S

**Organisation** : Entri Elevate

**Overview** :
  Education plays a vital role in determining students' future opportunities, and identifying the factors that impact academic achievement can support the development of more effective teaching methods. This project focuses on analyzing student performance data along with their learning styles to build a regression model that predicts exam scores. By applying data science techniques, the goal is to uncover meaningful patterns and relationships that can help educators, students, and policymakers make data-driven decisions to enhance educational outcomes and support personalized learning.

  ## **Objectives**
*   To explore the relationship between learning styles and student performance.
*   To identify key features that influence Exam score.
*   To develop and evaluate the best machine learning model for predicting students' Exam score.
*   To provide insights that can help optimize teaching methodologies based on student learning behaviors.

**Dataset description**
#### **Source:**
   Dataset Link:
    https://www.kaggle.com/code/samayashar/student-performance-linear-regression-svm-93?select=student_performance_large_dataset.csv
#### **Features:**
1.  **Student_ID** - Unique identifier for each student
2.  **Age** - Student's age
3.  **Gender** - Gender of the student (Male/Female)
4.  **Study_Hours_per_Week** - Number of hours spent studying per week
5.  **Preferred_Learning_Style** - Student's preferred learning style (e.g., Visual, Auditory, Kinesthetic, Reading/Writing)
6.  **Online_Courses_Completed** - Number of online courses completed
7.  **Participation_in_Discussions** - Whether the student participates in class discussions (Yes/No)
8.  **Assignment_Completion_Rate (%)** - Percentage of assignments completed
9.  **Exam_Score (%)** - Score obtained in exams (percentage) (Target variable)
10. **Attendance_Rate (%)** - Percentage of attendance in classes
11.  **Use_of_Educational_Tech** - Whether the student uses educational technology (Yes/No)
12.  **Self_Reported_Stress_Level** - Student's self-reported stress level (Low/Medium/High)
13.  **Time_Spent_on_Social_Media (hours/week)** - Weekly hours spent on social media
14.  **Sleep_Hours_per_Night** - Average number of hours of sleep per night
15.  **Final_Grade** - The final grade obtained by the student

## Data Preprocessing -Data Cleaning:
### Loading and Cleaning Data:
- Loaded the dataset using pandas.
- Examined missing values and duplicates.
- Removed irrelevant features and duplicate entries.
- Outlier Detection and removal

## Exploratory Data Analysis (EDA):
  1) Univariate anlaysis using Histplot, Boxplot and BHoistogram for numerical variables
  2) Univariate analysis using Countplots for Categorical variables
  3) Bivariate analysis using Heatmap, Violine plot and Line plot
  4) Multivariate analysis using Pairplot
     
## Data Engineering 
1) Feature Encoding
2) Feature Selection
3) Feature Importance Analysis using Random Forest method
4) Data Splitting
5) Feature Scaling
6) Handling Imbalance Data

## Model Building

1. **Model Selection** – Choose different machine learning algorithms to compare performance.
2. **Training the Models** – Fit models to the training data.
3. **Evaluation Metrics** – Assess models using Mean Squared Error and R2Score
### Regression Algorithms applied:
- Linear Regression
- SVM
- Decision Tree
- Random Forest
- K-Nearest Neighbors
- Gradient Boost.

## Hyperparameter Tuning
## Selecting the best model
## Pipeline for Machine Learning
## Testing with unseen data
