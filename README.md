# Breast Cancer Prediction

This project demonstrates how to predict whether a breast tumor is malignant or benign using machine learning, specifically Logistic Regression. The model is trained on the Wisconsin Breast Cancer dataset and evaluated using accuracy and cross-validation techniques.

## Introduction

Breast cancer is one of the most common types of cancer. Early detection is crucial for effective treatment. In this project, we utilize machine learning algorithms to predict whether a tumor is malignant or benign using patient data such as tumor size, shape, and texture.

## Libraries and Tools

The following libraries are used in this project:

- `pandas` – for data manipulation and analysis.
- `scikit-learn` – for machine learning algorithms and tools.
  - `LogisticRegression` – for classification.
  - `train_test_split` – for splitting the dataset into training and testing sets.
  - `cross_val_score` – for k-fold cross-validation.
  - `confusion_matrix`, `accuracy_score` – for model evaluation.

## Dataset
The dataset used for this project is **breast_cancer.csv**. It contains features and labels for predicting the presence of breast cancer. 

You can download the dataset from [Dataset Source Link](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic).

Make sure to place the dataset file in the root directory before running the code.

## Results
- **Confusion Matrix**:  
  Provides insight into the model's predictions by showing the number of correct and incorrect classifications for each class. In this project, the Confusion Matrix resulted in:
This indicates high accuracy in predicting malignant and benign cases.

- **Accuracy Score**:  
Reflects the overall performance of the model. The Logistic Regression model achieved an accuracy of **95.62%** on the test dataset.

- **Cross-Validation Accuracy**:  
Ensures consistency across multiple subsets of the training data. Using k-Fold Cross Validation, the model demonstrated an average accuracy of **96.70%** with a standard deviation of **1.97%**.



