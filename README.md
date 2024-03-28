# Liver Disease Prediction using PyCaret and PCA

## Overview
This project focuses on predicting liver disease using a dataset containing 416 liver patient records and 167 non-liver patient records. The dataset was collected from test samples in the North East of Andhra Pradesh, India. The 'is_patient' attribute serves as the class label, dividing the patients into liver patients or non-liver patients. The dataset includes 441 male patient records and 142 female patient records. We utilized the PyCaret package along with Principal Component Analysis (PCA) to compare and evaluate different machine learning models. The Random Forest model achieved the highest accuracy of 72.4%.

## Key Components

### 1. Data Collection and Preprocessing
- Collected data from test samples in the North East of Andhra Pradesh, India.
- Preprocessed the data, handling missing values, encoding categorical variables, and performing feature scaling.

### 2. Model Comparison and Evaluation
- Utilized PyCaret to compare various machine learning models including Random Forest, Logistic Regression, Decision Tree, and others.
- Evaluated the models using performance metrics such as accuracy, precision, recall, and F1-score.

### 3. Feature Reduction with PCA
- Applied Principal Component Analysis (PCA) to reduce the dimensionality of the dataset while retaining important information.
- Analyzed the variance explained by each principal component and selected the optimal number of components.

## Result
After comparing and evaluating multiple machine learning models, the Random Forest model emerged as the best performer with an accuracy of 72.4%. This predictive capability enables early detection and intervention for liver disease, facilitating better patient outcomes.
