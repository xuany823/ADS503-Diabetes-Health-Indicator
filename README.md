# ADS503 Project

## Predicting Diabetes Risk Using Behavioral and Health Indicators from the BRFSS Dataset

This project is part of the ADS-503 course in the Applied Data Science Program at the University of San Diego.

## Project Status 

Completed – June 2024

## Installation

This project was developed using RStudio and executed using .Rmd and .R scripts. To run this project:

1. Clone this repository from GitHub:
   ```bash
   git clone https://github.com/your-username/diabetes-risk-prediction.git
2.	Open the R project or primary .Rmd file in RStudio.
3.	Install the required packages:
   install.packages(c("tidyverse", "caret", "glmnet", "randomForest", 
                   "xgboost", "pROC", "DMwR", "nnet", "MASS", 
                   "kernlab", "e1071", "C50", "gbm"))
4.	Run each code section sequentially to reproduce data preprocessing, model training, and evaluation.

## Project Intro/Objective

The objective of this project is to predict diabetes status using the Behavioral Risk Factor Surveillance System (BRFSS) dataset, which includes over 70,000 observations and 20+ health-related variables. The target variable indicates whether a person has ever been told by a doctor that they have diabetes.

The project aims to develop accurate predictive models to support public health outreach and personalized prevention strategies.

## Partner(s)/Contributor(s)
	•	Michelle Wang
	•	Maria Mora Mora
	•	Shrey Goyal

All team members contributed to data cleaning, exploratory analysis, modeling, evaluation, and final documentation.

## Methods Used
	•	Data Cleaning & Preprocessing
	•	Exploratory Data Analysis (EDA)
	•	Feature Engineering (e.g., composite risk scores, lifestyle clusters)
	•	SMOTE (to address class imbalance)
	•	Logistic Regression
	•	Penalized Logistic Regression (GLMNET)
	•	LDA, QDA, MDA
	•	Random Forest
	•	XGBoost
	•	K-Nearest Neighbors (KNN)
	•	Support Vector Machine (SVM)
	•	Neural Network (NNet)
	•	Decision Trees (CART, C5.0)
	•	Gradient Boosting (GBM)
	•	Model Tuning (Grid Search)
	•	Cross-Validation
	•	ROC/AUC, Accuracy, F1, Sensitivity/Recall

## Technologies
	•	R
	•	RStudio
	•	caret
	•	glmnet
	•	DMwR
	•	pROC
	•	randomForest
	•	xgboost
	•	nnet
	•	gbm
	•	C50
	•	e1071

## Project Description

We used the 2022 BRFSS dataset with ~71,000 rows and 21 variables. The data includes demographic, behavioral, and clinical variables linked to diabetes risk. The target variable is binary (Diabetes_binary: 1 = diabetes, 0 = no diabetes).

### Dataset Source:
	Kaggle: https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset

### Target Variable:
	Diabetes_binary

### Analysis Focus:
	•	Understanding correlations between physical health, mental health, and behavioral patterns with diabetes diagnoses
	•	Constructing new features such as:
	•	Metabolic Syndrome Score
	•	Age × BMI interaction
	•	Composite Lifestyle Score
	•	Balancing the dataset using SMOTE due to class imbalance
	•	Building and comparing 14 classification models
	•	Identifying top performers (e.g., XGBoost, Random Forest, GLMNET)
	•	Evaluating and tuning based on ROC-AUC, sensitivity, F1 score
	•	Presenting insights with interactive visualizations and APA-formatted tables

### License
	•	MIT License: https://opensource.org/licenses/MIT

## Acknowledgments

We thank Professor An Tran for mentorship throughout the ADS-503 course.
Thanks to the Kaggle community and BRFSS for providing access to the dataset.


