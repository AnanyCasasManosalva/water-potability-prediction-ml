# Water Potability Prediction Using Machine Learning

## Project Overview
Access to safe drinking water is essential for human health and environmental sustainability. 
This project applies machine learning techniques to predict water potability using physicochemical water quality parameters.

## Objective
The objective of this project is to evaluate the performance of different machine learning models in predicting whether water is safe for human consumption.  
The goal is to identify the most robust model based on evaluation metrics such as accuracy, precision, recall, F1-score and ROC-AUC.

## Dataset
The dataset used in this project comes from the **Water Potability Dataset** available on Kaggle.

Each observation represents a water sample described by several physicochemical parameters:

- pH
- Hardness
- Solids
- Chloramines
- Sulfate
- Conductivity
- Organic carbon
- Trihalomethanes
- Turbidity

Target variable:
- **Potability**  
  - 1 = Potable  
  - 0 = Not potable

## Data Preprocessing
The data preprocessing pipeline includes:

- Handling missing values using class-based mean imputation
- Outlier detection using Z-score
- Feature transformation for skewed variables
- Train/validation/test split
- SMOTE applied to the training dataset
- Feature scaling using StandardScaler

## Machine Learning Models
The following machine learning models were evaluated:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Random Forest
- Gradient Boosting

Model performance was evaluated using several metrics including accuracy, precision, recall, F1-score and ROC-AUC.

## Project Goal
This project aims to demonstrate how machine learning can support data-driven analysis of water quality parameters to help identify potentially potable water sources.
