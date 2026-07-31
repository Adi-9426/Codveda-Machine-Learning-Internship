# Task 2: Support Vector Machine (SVM) for Classification

## Objective

The objective of this task is to implement Support Vector Machine (SVM) classifiers using Linear and RBF kernels, compare their performance, visualize the decision boundary, and evaluate the model using standard classification metrics.

## Dataset

- **Dataset:** Breast Cancer Wisconsin Dataset
- **Source:** scikit-learn (`load_breast_cancer`)
- **Problem Type:** Binary Classification
- **Target Variable:** Malignant / Benign

## Tools & Libraries

- Python
- Google Colab
- pandas
- NumPy
- scikit-learn
- matplotlib

## Methodology

- Loaded the Breast Cancer Wisconsin dataset.
- Standardized the features using StandardScaler.
- Split the dataset into training and testing sets.
- Trained SVM models with:
  - Linear Kernel
  - RBF Kernel
- Compared model performance.
- Visualized the decision boundary using PCA.
- Evaluated the model using classification metrics.

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- AUC


## Outcome

Successfully implemented Support Vector Machine classifiers using Linear and RBF kernels. The models were evaluated using multiple performance metrics, and the decision boundary visualization provided insight into the classifier's behavior on reduced-dimensional data.


## Repository Contents

```
Task-2-Support-Vector-Machine/
│
├── Support_Vector_Machine.ipynb
├── svm_decision_boundary.png
└── README.md
```

