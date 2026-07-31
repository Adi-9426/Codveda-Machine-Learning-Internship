# Task 1: Random Forest Classifier

## Objective

The objective of this task is to build a Random Forest classifier for a classification problem, perform hyperparameter tuning, evaluate model performance, and analyze feature importance.

## Dataset

- **Dataset:** Breast Cancer Wisconsin Dataset
- **Source:** scikit-learn (`load_breast_cancer`)
- **Problem Type:** Binary Classification
- **Target Variable:** Target (Malignant / Benign)

## Tools & Libraries

- Python
- Google Colab
- pandas
- NumPy
- scikit-learn
- matplotlib

## Methodology

- Loaded the Breast Cancer Wisconsin dataset.
- Explored and preprocessed the data.
- Split the dataset into training and testing sets.
- Trained a Random Forest classifier.
- Tuned hyperparameters such as the number of trees and maximum depth.
- Evaluated the model using cross-validation and classification metrics.
- Analyzed feature importance.

## Evaluation Metrics

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Cross-validation

## Feature Importance

The Random Forest model ranks the importance of input features, helping identify which attributes contribute most to the classification.


## Outcome

A Random Forest classifier was successfully implemented and evaluated. Hyperparameter tuning and feature importance analysis improved understanding of the model and its predictions.


## Repository Contents

```
Task-1-Random-Forest/
│
├── Random_Forest_Classifier.ipynb
└── README.md
```

