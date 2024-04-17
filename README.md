# Disease Prediction from Medical Data
This repository contains code for building a disease prediction model using machine learning algorithms and neural networks.

# Overview
The aim of this project is to develop a predictive model that can assist in identifying the likelihood of a disease based on various symptoms and patient profiles. The dataset used contains information about symptoms, patient profiles, and disease outcomes.

# Dataset
Dataset contains information about symptoms, patient profiles, and disease outcomes. It serves as the foundation for building the disease prediction model. "https://www.kaggle.com/datasets/uom190346a/disease-symptoms-and-patient-profile-dataset". It includes the following columns:
- Age: The age of the patient.
- Gender: The gender of the patient (e.g., Male, Female).
- Fever: Indicates whether the patient has fever (Yes/No).
- Cough: Indicates whether the patient has a cough (Yes/No).
- Fatigue: Indicates whether the patient experiences fatigue (Yes/No).
- Difficulty Breathing: Indicates whether the patient experiences difficulty breathing (Yes/No).
- Blood Pressure: The blood pressure level of the patient.
- Cholesterol Level: The cholesterol level of the patient.
- Disease: The specific disease diagnosed in the patient.
- Results: The outcome variable indicating whether the patient is diagnosed with the disease (Yes/No).

# Contents
Disease_symptom_and_patient_profile_dataset.csv: Dataset containing symptom, patient profile, and outcome variables.
disease_prediction_model.ipynb: Jupyter Notebook containing the code for data preprocessing, model building, and evaluation.
README.md: This README file providing an overview of the project and instructions.

# Dependencies
Python 3.x
Libraries:
Pandas
NumPy
Plotly Express
Scikit-learn
Keras

# Model Evaluation
The predictive model is evaluated using the following metrics:

- Accuracy
- Confusion Matrix
- Precision Score
