# Epileptic Seizure Classification with Machine Learning & Explainable AI (XAI)

This project builds a machine-learning pipeline to classify epileptic seizures from EEG data using multiple models, supported by Explainable AI for transparent and interpretable predictions.

- Overview

Uses the Epileptic Seizure Recognition Dataset

Trains and compares multiple ML models

Applies Stratified 5-Fold Cross-Validation

Integrates SHAP, Permutation Importance, and Partial Dependence Plots

Saves performance metrics and XAI visualizations

- Features
Machine Learning Models

Logistic Regression

SVM

Random Forest

Gradient Boosting

KNN

Explainability

SHAP values for feature contribution

Permutation importance for sensitivity

PDP for feature–outcome relationships

- Outputs

results_multiclass.csv

results_binary.csv

XAI visualizations (SHAP, PIR, PDP)


If SHAP is missing:

pip install shap


Run the notebook:

jupyter notebook seizure_multimodel_XAI.ipynb

- Results

Models are evaluated using:

Accuracy

F1-Macro

Cross-validation scores

(Add your final accuracy/F1 once finalized.)

- Future Work

Deep learning (CNN/LSTM)

Hyperparameter tuning

Real-time prediction pipeline


