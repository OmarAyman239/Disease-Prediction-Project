**Predictive Modeling for Disease Diagnosis
****Project Overview**
Healthcare professionals often rely on various diagnostic tests and biomarkers to assess an individual's health status and diagnose diseases. This project aims to develop a predictive model that can classify individuals as diseased or healthy based on their health attributes. The goal is to create a reliable tool that healthcare providers can use to assist in disease diagnosis and prognosis.


**Dataset
**The dataset consists of multiple health-related attributes such as cholesterol levels, blood cell counts, hormone levels, and other physiological measurements. The target variable is a binary indicator of disease status (1: Diseased, 0: Healthy).

**Attributes:**
Cholesterol
Hemoglobin
Platelets
White Blood Cells (WBC)
Red Blood Cells (RBC)
Hematocrit
Mean Corpuscular Volume (MCV)
Mean Corpuscular Hemoglobin (MCH)
Mean Corpuscular Hemoglobin Concentration (MCHC)
Insulin
BMI (Body Mass Index)
Systolic Blood Pressure (SBP)
Diastolic Blood Pressure (DBP)
Triglycerides
HbA1c (Glycated Hemoglobin)
LDL (Low-Density Lipoprotein) Cholesterol
HDL (High-Density Lipoprotein) Cholesterol
ALT (Alanine Aminotransferase)
AST (Aspartate Aminotransferase)
Heart Rate
Creatinine
Troponin
C-reactive Protein (CRP)
Disease (Target: 1 for Diseased, 0 for Healthy)


**Load and preprocess data:**

Encode the target variable.
Handle missing values.
Scale the features.
Handle imbalanced data using SMOTE.

**Model training** using Logistic Regression, SVM, and Naive Bayes with hyperparameter tuning via GridSearchCV.

**Model evaluation** on test data using accuracy, F1-score, precision, and recall metrics.

**Select the best model based on performance metrics.**

**Results**
The results of the model training and evaluation are displayed in terms of accuracy, F1-score, precision, recall, and confusion matrices for each model. The best model is selected based on the highest F1-score.
