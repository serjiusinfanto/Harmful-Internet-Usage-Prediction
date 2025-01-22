# Problematic Internet Usage Detection

## Overview
This project explores the early detection of Problematic Internet Usage (PIU) among teenagers using machine learning techniques. By analyzing behavioral, physical, and demographic data, the project aims to classify the severity of PIU and provide actionable insights to mitigate mental, physical, and social risks.

## Motivation
With the increasing prevalence of internet dependency, particularly among adolescents, PIU is linked to mental health issues like anxiety and depression, physical health concerns such as obesity, and social development challenges. This project seeks to identify early indicators of PIU, enabling timely interventions to promote healthier digital habits.

## Features
- **Severity Classification**: Predicts PIU levels (`None`, `Mild`, `Moderate`, `Severe`) based on the Severity Impairment Index (SII).
- **Machine Learning Models**:
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Random Forest Classifier
- **Data Preprocessing**:
  - Handled missing values using KNN imputation.
  - Addressed class imbalance with SMOTE.
  - Selected 33 key features using the Boruta feature selection algorithm.
- **Evaluation Metrics**:
  - Quadratic Weighted Kappa (QWK)
  - Accuracy, Precision, Recall, and F1-Score

## Dataset
- **Source**: Healthy Brain Network Dataset
- **Key Details**:
  - Participants: 5,000 (training), 3,800 (testing), aged 5–22 years
  - Features: 81, including physical activity, sleep patterns, BMI, and internet usage behaviors
  - Target Variable: SII (categorized into four severity levels)

## Technologies Used
- **Programming Languages**: Python
- **Libraries**:
  - Pandas, NumPy for data preprocessing
  - Scikit-learn for model training, evaluation, and feature selection
  - KNN Imputer for handling missing values
  - SMOTE for oversampling minority classes
- **Visualization**:
  - Correlation heatmaps and feature importance plots
- **Evaluation Tools**:
  - QWK and classification metrics to assess model performance

## Results
- **Random Forest Classifier**:
  - Accuracy: 95%
  - QWK Score: 0.9753
  - Precision/Recall/F1-Score: 0.99 (macro average)
- **Support Vector Machine (SVM)**:
  - Accuracy: 95.65%
  - QWK Score: 0.9624
- **Logistic Regression**:
  - Accuracy: 93.76%
  - QWK Score: 0.94

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/serjiusinfanto/Harmful-Internet-Usage-Prediction.git

## Future Enhancements
* Incorporating sentiment analysis from internet usage questionnaires for more nuanced predictions.
* Expanding the dataset to include diverse demographic groups for generalization.
* Building an interactive dashboard to visualize PIU trends and provide personalized recommendations.
