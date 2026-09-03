#  Skin Disease Disorder Prediction

A machine learning project for predicting skin disease categories using clinical and histopathological features.

The project explores multiple classification algorithms, different missing-value imputation techniques, feature scaling, model evaluation, and hyperparameter tuning to identify a suitable machine learning model for multiclass skin disease classification.

---

##  Project Overview

Skin diseases can exhibit similar clinical characteristics, making accurate classification challenging.

This project uses machine learning techniques to classify patients into one of **six skin disease categories** based on clinical and histopathological attributes.

The dataset contains:

- **366 patient records**
- **35 columns**
- **34 input features**
- **1 target variable (`class`)**
- Six disease classes

The task is formulated as a **supervised multiclass classification problem**.

---

##  Objectives

The main objectives of this project are:

- Explore and understand the skin disease dataset
- Perform data cleaning and preprocessing
- Identify and handle missing values
- Compare different imputation techniques
- Apply feature scaling where required
- Train multiple machine learning classification models
- Evaluate models using accuracy, precision, recall, F1-score, confusion matrix, and ROC-AUC
- Perform hyperparameter tuning using GridSearchCV
- Identify the best-performing model

---

##  Dataset

The project uses the following dataset:

```text
dataset_35_dermatology.csv
