# Heart-Disease-Prediction Using Machine Learning


## Abstract

This project focuses on developing a heart disease prediction model using machine learning techniques. The dataset includes variables such as age, gender, chest pain type, blood pressure, cholesterol levels, and various cardiovascular indicators. The process involves dataset exploration, data visualization, feature engineering, and data preprocessing to handle categorical features and ensure proper feature scaling. The model-building phase includes three classifiers: K-Nearest Neighbors (KNN), Decision Tree, and Random Forest, evaluated for their predictive performance. This project aims to enhance the accuracy and interpretability of heart disease predictions using a diverse set of features.

## Data

The Heart Disease dataset from the UC Irvine Machine Learning Repository contains 14 variables and 303 instances related to physiological parameters and medical indicators.

## Methodology

We employ three machine learning algorithms: K-Nearest Neighbors (KNN), Decision Tree, and Random Forest. Each model is trained and evaluated using cross-validation to assess accuracy.

### Model Building

1. **K-Nearest Neighbors (KNN):**
   - Uses scikit-learn's KNeighborsClassifier.
   - Optimizes the number of neighbors (k) through cross-validation.
   - Best k value is 12.

2. **Decision Tree:**
   - Uses scikit-learn's DecisionTreeClassifier.
   - Optimizes maximum depth through cross-validation.
   - Best maximum depth is 3.

3. **Random Forest:**
   - Uses scikit-learn's RandomForestClassifier.
   - Optimizes the number of estimators through cross-validation.
   - Best number of estimators is 90.

### Model Evaluation

Accuracy is the primary evaluation metric. The models' accuracy scores are:
- KNN: 83.94%
- Decision Tree: 82.46%
- Random Forest: 86.89%

## Conclusion

The Random Forest classifier is the top performer with the highest accuracy rate of 86.89%, demonstrating its potential as a robust model for heart disease prediction. This project highlights the importance of evaluating multiple algorithms to identify the most effective approach for predictive healthcare analytics.
