# Capstone Project 20.1: Initial Report and Exploratory Data Analysis (EDA)

**Creation of Machine Learning Models for Predicting Weight Loss using Exercise and Dietary Information**

**Author:** Rudy Silva Mera

## Executive Summary

Machine learning (ML), a branch of artificial intelligence, offers the potential to predict weight loss by analyzing patterns in behavior, such as changes in exercise and dietary habits. This project aims to leverage ML to create personalized weight loss plans, revolutionizing traditional approaches.

## Rationale

Weight loss is crucial for health, self-esteem, and life expectancy. This project addresses the need for effective weight loss strategies by utilizing ML to understand patterns in exercise and dietary data.

## Research Question

Several research questions will be explored, including the impact of specific exercises, the role of diet, and the influence of factors such as age, weight, and gender on weight loss.

## Data Sources

The project will utilize datasets from Fitbit weight loss and dietary information, available at:
- [Fitbit Weight Loss Dataset](https://www.kaggle.com/datasets/arashnic/fitbit)
- [Dietary Information Dataset](https://www.kaggle.com/datasets/tombenny/foodhabbits)

## Methodology

Machine learning models such as Linear Regression and Decision Trees will be employed to predict weight loss based on exercise and dietary data. Additionally, classifiers like K Nearest Neighbors (KNN), Logistic Regression, and Support Vector Machines (SVC) will be compared for accuracy.

## Results

### Notebook 1 - Linear Regression Model

- Examined the [foodDiet.csv] dataset.
- Built Linear Regression models with training accuracy of 49.28% and testing accuracy of 22.52%.
- Tested models with sample Fitbit user profiles, revealing some unrealistic predictions.

### Notebook 2 - Decision Tree Classifier Model

- Created Decision Tree models predicting weight loss (weightloss) based on daily calorie records.
- Achieved training accuracy of 69.49% and testing accuracy of 60.62%.
- Used Grid Search for model optimization, highlighting the best-performing parameters.

### Notebook 3 - Comparing Classifiers

- Compared Logistic Regression, KNN, and SVM using default parameters.
- Conducted Grid Search to optimize parameters and evaluated performance.
- Logistic Regression exhibited the fastest training time, while SVM achieved the highest score.

### Project Outline

- [Notebook 1 - Linear Regression]
- [Notebook 2 - Decision Tree Classifier]
- [Notebook 3 - Comparing Classifiers]

