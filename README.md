# 💧 Water Potability Prediction Using Machine Learning

## 📌 Project Overview
Access to safe drinking water is essential for human health and environmental sustainability. 
This project applies machine learning techniques to predict water potability using physicochemical water quality parameters.

## Objective
The objective of this project is to evaluate the performance of different machine learning models in predicting whether water is safe for human consumption and identify the most suitable model.  
The goal is to identify the most robust model based on evaluation metrics such as accuracy, precision, recall, F1-score and ROC-AUC.

## 📊 Dataset
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
  - 1 = Potable (safe to drink) 
  - 0 = Not potable

## ⚙️ Methodology
The project follows a structured data science workflow:

	1.	Data Understanding
	2.	Exploratory Data Analysis (EDA)
	3.	Data Cleaning and Preprocessing
	4.	Feature Engineering
	5.	Model Training
	6.	Model Evaluation

## 🤖 Machine Learning Models
The following machine learning models were evaluated:

	•	Logistic Regression
	•	K-Nearest Neighbours (KNN)
	•	Support Vector Machine (SVM)
	•	Random Forest
	•	Gradient Boosting

## 📈 Evaluation Metrics
The performance of the models was evaluated using the following metrics:

	•	Accuracy
	•	Precision
	•	Recall
	•	F1-score
	•	ROC-AUC

## 🔍 Key Insights
	•	Most variables show overlapping distributions between potable and non-potable water
	•	Individual features are not sufficient to classify water quality
	•	Machine learning models are required to capture complex relationships

## 🚀 Results

The models were compared based on performance metrics, highlighting the strengths and limitations of each approach.

## 📁 Repository Structure
	•	water_potability_prediction.ipynb → Main notebook
	•	README.md → Project overview
	•	LICENSE → Usage terms

## 📌 Author

Anany Casas
:::
