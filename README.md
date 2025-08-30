# Diabetes Prediction with Machine Learning

## Overview
This project demonstrates a classic machine learning pipeline for predicting diabetes outcomes using the **Pima Indians Diabetes Dataset**. 

## Description
The workflow includes:
- Handling missing data using **three imputation methods**: Simple Imputer (mean), KNN Imputer, and Autoencoder (PyTorch).
- Data preprocessing: Standardization and **PCA** dimensionality reduction + **MDS** for visualization purposes
- Supervised ML classification using:
  - Random Forest
  - Support Vector Machine (SVM)
  - Naive Bayes
- Model evaluation using metrics such as **Accuracy, F1-score, ROC-AUC, Precision-Recall (AUPRC)** on the best combination of imputation and classification algorithm.
- Visual interpretation:
  - Random Forest feature importances
  - ROC and Precision-Recall curves

## Dataset
The dataset is from [Kaggle: Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database).
> Note: The dataset is **not included in this repository**. The notebook downloads the dataset automatically from Kaggle using the Kaggle API.

## Quick Start
- Clone this repository: git clone https://github.com/ignsagita/diabetes-pima-ml.git cd diabetes-pima-ml
- Install dependencies pip install -r requirements.txt
- Place your Kaggle API token (kaggle.json) in ~/.kaggle/ or follow the [Kaggle API instructions](https://www.kaggle.com/docs/api).
- Run the notebook: jupyter notebook diabetes-pima.ipynb

---
