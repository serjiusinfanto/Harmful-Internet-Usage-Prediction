
---

### GitHub README for **Problematic Internet Usage Detection**

```markdown
# Problematic Internet Usage Detection

## Overview
This project predicts the severity of Problematic Internet Usage (PIU) among teenagers using machine learning models. By analyzing features like physical activity, sleep patterns, and internet usage, the system classifies PIU into four severity levels: None, Mild, Moderate, and Severe.

## Features
- **Classification Models**:
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Random Forest Classifier
- **Class Imbalance Handling**: Used SMOTE to oversample minority classes.
- **Feature Selection**: Boruta algorithm selected 33 significant features.
- **Preprocessing**:
  - KNN imputation for missing values
  - Outlier detection and handling
  - Correlation analysis for feature relationships

## Dataset
- **Source**: Healthy Brain Network Dataset
- **Details**:
  - 5,000 participants (training) and 3,800 participants (testing)
  - 81 features, including BMI, sleep disturbances, and internet usage behavior

## Key Technologies
- **Programming Languages**: Python
- **Libraries**:
  - Pandas, NumPy, Scikit-learn
  - SMOTE for class imbalance
  - Boruta for feature selection
- **Evaluation Metrics**:
  - Accuracy
  - Precision, Recall, F1-score
  - Quadratic Weighted Kappa (QWK)

## Results
- **Best Model: Random Forest Classifier**
  - Accuracy: 99.43%
  - QWK Score: 0.9953
  - Precision/Recall/F1-score: 0.99 (macro average)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/serjiusinfanto/Harmful-Internet-Usage-Prediction.git

## Future Enhancements
1. Incorporating sentiment analysis to refine predictions
2. Expanding the dataset to include more diverse demographic groups
3. Developing an interactive dashboard for visualizing PIU trends
