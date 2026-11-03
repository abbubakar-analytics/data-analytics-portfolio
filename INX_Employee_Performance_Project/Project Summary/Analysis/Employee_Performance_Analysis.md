# INX Future Inc. -Employee Performance Analysis
## 1. Project Overview
## 2. Data Processing and Preparation

The employee dataset contains 1,200 rows and 28 columns. The data was loaded using Pandas and checked for missing values,duplicate records, and basic statistical information. No missing value or duplicate records were found in the dataset.

## 3. Department-Wise Performance Analysis

The average performance rating was calculated for each department to compare employee performance. Development had the highest average rating of approximately 3.09, followed by Data Science at 3.05. Finance had the lowest average rating at approximately 2.78.

## 4. Important Factors Affecting Employee Performance

The analysis identified three important factors associated with employee performance: Employee Last Salary Hike Percent, Employee Environment Statisfaction, and Years Since Last Promotion. These factors were ranked using muutual information scores to understand their relationship with employee performance ratings.

## 5. Machine Learning Model And Evaluation

A Random Forest Classifier was trained to predict employee performance ratings. The dataset was divided into training and testing sets, with 80% used for training and 20% used for testing. Categorical features were achieved an accuracy of approximately 94.58% on the test dataset, with a weighted F1-score of 0.94.

## 6. Feature Importance

The Random Forest model identified Employee Environment Statisfaction as the most important feature, followed by Employee Last Salary Hike Percent and Years Since Last Promotion. These features had the highest importance scores in the trained model. The results help identify employee-related factors that are useful for predicting performance ratings.

## Recommendations for Improving Employee Performance

Based on the analysis, the company should review employee satisfaction and salary hike practices, provide appropriate recognition for employee contributions, and offer career development opportunities. Regular feedback and fair promotion policies may also help employees improve their performance. The company should focus on helping employee improve their performance and providing a better working environment.
