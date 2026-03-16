# Machine Learning Projects

This repository contains two Machine Learning projects:
1. Diabetes Prediction
2. Rock vs Mine Prediction

Both projects are implemented using Python and trained using real-world datasets.

--------------------------------------------------

# 1. Diabetes Prediction using Machine Learning

## Project Overview
This project predicts whether a person has diabetes or not using Machine Learning. The model is trained using the Pima Indians Diabetes Dataset.

## Objective
To build a machine learning model that can predict diabetes based on medical parameters.

## Dataset
Dataset: Pima Indians Diabetes Dataset (CSV)

Features:
- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

Target:
- 0 → Non-Diabetic
- 1 → Diabetic

## Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Jupyter Notebook / Google Colab

## Algorithm Used
Support Vector Machine (SVM)

## Workflow
1. Import required libraries
2. Load the dataset
3. Data preprocessing
4. Train-test split
5. Model training using SVM
6. Model evaluation
7. Prediction system

## Output
The system predicts whether a person is Diabetic or Non-Diabetic based on the input data.

--------------------------------------------------

# 2. Rock vs Mine Prediction using Machine Learning

## Project Overview
This project classifies objects detected by sonar signals as Rock or Mine using machine learning.

## Objective
To build a classification model that can identify underwater objects.

## Dataset
Dataset: Sonar Dataset (CSV)

Features:
- 60 numerical sonar attributes representing sound energy signals.

Target:
- R → Rock
- M → Mine

## Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Google Colab / Jupyter Notebook

## Algorithm Used
Logistic Regression

## Workflow
1. Import libraries
2. Load dataset
3. Data preprocessing
4. Train-test split
5. Model training using Logistic Regression
6. Model evaluation
7. Prediction system

## Output
The model predicts whether the detected object is a Rock or Mine.

--------------------------------------------------

## Future Improvements
- Improve model accuracy
- Use advanced machine learning algorithms
- Deploy the model using Flask or a web application
