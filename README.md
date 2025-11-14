# Machine-Failure-Prediction-Model-
using Gaussian Naive Bayes and KNN

This project focuses on building a predictive model to classify whether an industrial machine is working or broken based on sensor readings and operational parameters.

The workflow includes:

Data Loading & Cleaning:
Removed inconsistent records such as rows with zero values in critical numeric fields. Simplified complex IDs (e.g., Product ID reduced to its prefix).

Feature Engineering:
Separated numerical and categorical features. Applied appropriate preprocessing pipelines:

Categorical → Imputed using most-frequent strategy

Numerical → Imputed using Iterative Imputer + Robust Scaler

Model Training:
Trained and evaluated multiple classification models, including:

K-Nearest Neighbors (KNN)

Gaussian Naive Bayes

Model Evaluation:
Generated predictions and assessed model performance using:

Accuracy

Precision & Recall

F1-score

Classification reports

This end-to-end pipeline demonstrates a complete ML workflow — from data cleaning and feature engineering to model training and evaluation — suitable for real-world predictive maintenance applications.
