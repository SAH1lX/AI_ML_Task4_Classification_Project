# Breast Cancer Classification using Machine Learning

## Project Overview

This project focuses on building and evaluating machine learning classification models for breast cancer prediction using the Breast Cancer Wisconsin dataset.

The project demonstrates:
- Classification modeling
- Evaluation metrics
- ROC Curve & AUC analysis
- Handling imbalanced data
- Model comparison
- Feature importance analysis

---

## Dataset Information

The dataset was loaded using the built-in Breast Cancer dataset from scikit-learn.

### Target Classes
- 0 → Malignant
- 1 → Benign

The dataset contains 569 samples and 30 medical features.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Machine Learning Models Used

### 1. Logistic Regression
Used as the baseline classification model.

### 2. Decision Tree Classifier
Used for model comparison and rule-based classification.

### 3. Random Forest Classifier
Used to improve predictive performance using ensemble learning.

---

## Evaluation Metrics

The following metrics were used to evaluate model performance:

- Accuracy
- Precision
- Recall
- F1-score
- ROC Curve
- AUC Score
- Confusion Matrix

---

## Key Features of the Project

- Exploratory Data Analysis (EDA)
- Feature Scaling using StandardScaler
- ROC Curve Visualization
- Confusion Matrix Heatmaps
- Imbalanced Data Handling
- Feature Importance Analysis
- Model Comparison

---

## Results Summary

| Model | Accuracy |
|---|---|
| Logistic Regression | 98.24% |
| Decision Tree | 91.22% |
| Random Forest | 95.61% |

Logistic Regression achieved the best overall balance between accuracy, interpretability, and stability.

---

## Project Structure

```text
AI_ML_Task4_Classification_Project/
│
├── AI_ML_Task4_Classification.ipynb
├── AI_ML_Task4_Classification.pdf
└── README.md
```

---

## Conclusion

This project demonstrates the importance of proper evaluation metrics in medical classification problems.

The study highlights how:
- ROC-AUC improves classification evaluation
- Recall is critical in medical diagnosis
- Imbalanced data handling improves prediction reliability
- Different machine learning models perform differently on the same dataset

---

## Author

Sahil Bhatti
