# task-11
 SVM – Breast Cancer Classification
Breast Cancer Classification using SVM
Project Overview:
This project implements Support Vector Machine (SVM) models to classify breast tumors as Malignant or Benign using the Breast Cancer Wisconsin dataset. The workflow includes data preprocessing, model training, hyperparameter tuning, evaluation, and saving the trained model for reuse.

Objectives:
Understand dataset features and label distribution.
Normalize feature values using StandardScaler.
Train and compare SVM models with different kernels.
Optimize model performance using GridSearchCV.
Evaluate results using classification metrics and ROC-AUC.
Save the trained pipeline for deployment or reuse.

Tools & Libraries Used:
Python
Pandas, NumPy
Matplotlib
Scikit-learn
Joblib
Google Colab / Jupyter Notebook

Workflow Steps:
Load and inspect dataset.
Preprocess data and encode labels.
Apply feature scaling.
Split data into training and testing sets.
Train baseline SVM with Linear kernel.
Train SVM with RBF kernel and compare performance.
Tune hyperparameters (C, gamma) using GridSearchCV.
Evaluate model using confusion matrix, classification report, ROC curve, and AUC score.
Save final model pipeline (scaler + SVM).

Results:
The tuned SVM model achieves high classification accuracy and AUC, effectively distinguishing malignant and benign tumors.

Project Deliverables:
Jupyter Notebook with implementation
ROC curve and AUC score
Saved model pipeline file (svm_breast_cancer_model.pkl)
README documentation

Outcome:
This project demonstrates how kernel-based SVM models can be applied to medical datasets for accurate classification and how hyperparameter tuning improves performance.
