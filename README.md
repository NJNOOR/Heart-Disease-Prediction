# Heart-Disease-Prediction


This project focuses on predicting the presence of heart disease based on behavioral, demographic, and health-related factors using three machine learning models. It incorporates data preprocessing, class balancing, EDA, and model evaluation.

## Models Used:
#### Logistic Regression

#### Random Forest Classifier

#### XGBoost Classifier

## Dataset
heart_2020_cleaned.csv


Rows: 319,795

Columns: 17 features + target (HeartDisease)

Target Variable: HeartDisease (Yes/No)

Main Features:

Demographics: AgeCategory, Sex, Race

Lifestyle: Smoking, AlcoholDrinking, PhysicalActivity, SleepTime

Health: Diabetic, BMI, PhysicalHealth, MentalHealth

## Exploratory Data Analysis (EDA)

Missing value visualization with missingno

Class distribution of target variable

Correlation heatmaps and pairplots

Outlier and distribution analysis for numeric variables

## Preprocessing Steps
Label Encoding for categorical columns

Train-Test Split (80-20)

Standardization using StandardScaler

Class Imbalance handled with SMOTE

Feature Scaling applied after resampling

## Model Performance

#### Logistic Regression

Accuracy	0.70

Precision	0.18

Recall	0.70

F1-Score	0.29

AUC-ROC	0.76

#### Random Forest Classifier

Accuracy	0.71

Precision	0.23

Recall	0.30

F1-Score	0.26

AUC-ROC	0.77

#### LXGBoost Classifier

Accuracy	0.90

Precision	0.35

Recall	0.10

F1-Score	0.16

AUC-ROC	Not specified (could be added later)

 Although XGBoost had high accuracy, its recall was low, meaning it struggled to detect the minority (positive) class effectively.


## Visualizations

Confusion Matrix (for each model)

ROC Curves for Logistic Regression and Random Forest

Distribution plots for EDA

Correlation heatmaps

## How to Run

Open the Jupyter Notebook in Google Colab

Mount your Google Drive.

Upload the dataset .

Run all cells sequentially.

## Tech Stack

Python 3

Google Colab

Libraries Used: pandas, numpy, seaborn, matplotlib, scikit-learn, imbalanced-learn, missingno, xgboost



## License

This project is for educational and academic use only.


