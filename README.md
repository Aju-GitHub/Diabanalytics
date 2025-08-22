# Diabetes Analytics

This project analyzes a diabetes dataset to predict whether a patient is diabetic based on various health indicators using machine learning models. The goal is to understand key factors impacting diabetes diagnosis and provide an accurate prediction system.

**Repository Structure:**

Diabetes_Analytics/

/- Diabetes_Analytics_2025.pdf - Full report

/- Diabetics_Analytics.ipynb - Full Python code

/- README.md - Documentation

/- diabetes.csv - Dataset

# Features and Data Cleaning

- Initial exploration revealed some features had missing values encoded as zeros.

- These were replaced with mean or median values to improve data quality.

- Histograms were used to visualize data distributions before and after imputation.

- Outcome classes are balanced approximately 2:1 between non-diabetic and diabetic patients.

# Methodology

- Data was scaled using StandardScaler.

- The dataset was split into training and testing sets (67:33).

- Four machine learning models were trained and evaluated:

- Random Forest (highest accuracy: 76%)

- Decision Tree

- XGBoost

- Support Vector Machine (SVM)

# Results

- Model accuracy and evaluation metrics (precision, recall, F1-score) were computed.

- Confusion matrices visualized classification performance for each model.

- Feature importance was analyzed from the Random Forest model to identify influential factors.

# Interactive Prediction

- A command-line interface allows entering patient data to predict diabetes likelihood in real time using the trained Random Forest model.

# How to Run
1) Load the dataset.
2) Preprocess data by replacing missing values and scaling features.
3) Train and evaluate models.
4) Save the best model for future predictions.
5) Use the input loop for interactive prediction.

# Dependencies

- Python 3.x
- pandas, numpy, matplotlib, seaborn
- scikit-learn
- xgboost (optional for XGBoost model)

**Rights and Usage:**

All reports, documentation, and related artifacts are the intellectual property of Ajmal M S.

Shared resources are provided solely as a record of my involvement, competencies, and learning outcomes.

No content from this repository may be copied, altered, shared, or reused without explicit permission.

© Ajmal M S, 2025
