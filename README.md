# Project-1-Data-201

# Data 201-Project1

## Project Overview
This project uses classification models to predict whether a patient has heart disease based on selected precictors. The analysis was completed in Python using a Google Colab notebook.

## Dataset
The dataset contains patient information, including age, sex, resting blood pressure (`trestbps`), cholesterol (`chol`), and a target variable indicating whether heart disease is present.

## Methods
The project explores the dataset through statistics and visualizations, then compares four classification models:

- Logistic Regression
- Linear Discriminant Analysis (LDA)
- Quadratic Discriminant Analysis (QDA)
- K-Nearest Neighbors (KNN)

Model performance is evaluated using classification metrics, including accuracy, precision, recall, specificity, F1 score, and ROC-AUC.

## Main Findings
Using a classification threshold of 0.35, Logistic Regression achieved approximately 67.3% accuracy, 94.1% recall, and a 0.745 ROC-AUC. It identified most patients with heart disease in the test set, but also incorrectly flagged many patients without heart disease.

KNN achieved the highest ROC-AUC among the models, at approximately 0.816. The results illustrate the trade-off between detecting heart disease and generating false positives.

## Files
- `Data201_Project1.ipynb` — notebook containing the code, visualizations, model evaluation, and analysis.
- `heart.csv` — dataset used for the analysis.
- `README.md` — project description and main findings.

## Limitations
The models are based on a set of predictors  Model performance may also be affected by duplicate observations and the method used to select the classification threshold.
