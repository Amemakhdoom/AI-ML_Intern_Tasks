# AI/ML Internship Task 3: Heart Disease Prediction

## Task Objective
The objective of this project is to build a machine learning classification model that predicts whether a person is at risk of heart disease based on their medical and health-related data. The goal is to apply data preprocessing, exploratory data analysis (EDA), classification modeling, and evaluation techniques.

## Dataset Used
The Heart Disease UCI Dataset (available on Kaggle) was used for this project.  
The dataset contains patient health information such as:
- Age
- Sex
- Resting blood pressure
- Cholesterol level
- Chest pain type
- Maximum heart rate
- Other clinical attributes

The target variable indicates:
- 0 → No heart disease
- 1 → Presence of heart disease

## Data Preprocessing
- Loaded dataset using pandas
- Checked and handled missing values
- Verified data types and cleaned inconsistencies
- Split dataset into training and testing sets

## Exploratory Data Analysis (EDA)
- Analyzed feature distributions using visualizations
- Explored relationships between medical features and heart disease
- Identified patterns and potential outliers

## Models Applied
- Logistic Regression
- Decision Tree Classifier

## Model Evaluation
The models were evaluated using:
- Accuracy Score
- Confusion Matrix
- ROC Curve
- ROC-AUC Score

## Key Results and Findings
- The classification model successfully predicted heart disease risk with good accuracy.
- ROC-AUC analysis showed effective class separation.
- Important features influencing prediction included cholesterol level, chest pain type, maximum heart rate, and blood pressure.
- Feature importance analysis improved model interpretability.

## Skills Demonstrated
- Binary classification
- Medical data analysis and interpretation
- Model evaluation using ROC-AUC and confusion matrix
- Feature importance and explainability
- Data preprocessing and EDA using pandas, matplotlib, and seaborn
