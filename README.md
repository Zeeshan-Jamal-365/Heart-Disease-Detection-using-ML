# Heart Disease Detection Using Machine Learning Techniques

The **Heart Disease Detection** project is an essential tool for early detection of heart disease in individuals. This repository contains Python code for implementing various machine learning algorithms, data preprocessing, and evaluation techniques to predict heart disease based on medical attributes. The project is designed to be informative and user-friendly, providing insights into data exploration, model training, and performance evaluation.

## Overview

Heart disease is a significant health concern, and timely detection can save lives. This project utilizes machine learning algorithms to analyze medical data and make predictions about the presence of heart disease. The main algorithms used in this project are:

- Zero R
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Decision Tree
- Logistic Regression

## Features

- **Data Preprocessing**: The project includes thorough data cleaning and standardization processes. The `MinMaxScaler` is applied to normalize data, and missing values are checked using `df.isnull().sum()`.

- **Exploratory Data Analysis**:
  - Heatmap and boxplot showcase the age distribution based on different chest pain levels for both target outcomes (0 and 1).
  - Another boxplot illustrates the gender-wise age distribution for target outcomes 0 and 1.
  - Unique values for each feature are displayed, focusing on those with less than 10 unique values.

- **Cholesterol Variation Visualization**:
  - The project generates `lmplot` visuals to depict how cholesterol levels vary with age, differentiating between genders.

## Evaluation

The effectiveness of the implemented algorithms is evaluated through various metrics, including:

- ROC AUC Curve
- K Fold Cross Validation
- Accuracy, Precision, Recall, F-measure
- ROC (Receiver Operating Characteristic) Curve

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   $ git clone https://github.com/your-username/heart-disease-detection.git
   $ cd heart-disease-detection



