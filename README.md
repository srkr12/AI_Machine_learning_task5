# Breast Cancer Classification using Logistic Regression

## Project Overview

This project focuses on building a Logistic Regression model to classify breast cancer tumors as either benign or malignant. The dataset was explored, preprocessed, and used to train a machine learning model. The model was then evaluated using different classification metrics to understand its performance.

---

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Dataset

The project uses the Breast Cancer Wisconsin dataset, which contains different medical measurements of breast cancer tumors. The goal is to predict whether a tumor is **benign (non-cancerous)** or **malignant (cancerous)**.

---

## Steps Performed

- Imported the required libraries.
- Loaded and explored the dataset.
- Checked the dataset information and summary statistics.
- Checked for missing values.
- Converted the target column into numerical values (if required).
- Split the dataset into training and testing sets.
- Standardized the feature values using StandardScaler.
- Trained a Logistic Regression model.
- Made predictions on the test data.
- Evaluated the model using:
  - Confusion Matrix
  - Precision
  - Recall
  - ROC-AUC Score
- Plotted the ROC Curve.
- Performed threshold tuning to compare precision and recall at different decision thresholds.

---

## Observations

- The dataset contains medical features that help classify breast cancer tumors.
- The Logistic Regression model was able to classify most samples correctly.
- The confusion matrix showed only a small number of incorrect predictions.
- The model achieved good precision and recall, indicating reliable classification performance.
- The ROC Curve stayed well above the diagonal line, showing that the model can effectively distinguish between the two classes.
- Changing the decision threshold affected the balance between precision and recall, showing the trade-off between these evaluation metrics.

---

## Sigmoid Function

Logistic Regression uses the **Sigmoid Function** to convert the model's output into a probability value between **0 and 1**. Based on a selected threshold (usually **0.5**), the model decides whether a sample belongs to the benign or malignant class.

---

## Project Structure

```
Task_four_logistic_regression/
│
├── Task_four.ipynb
├── data.csv
├── README.md
└── images/
    ├── prediction matrix.png
    └── roc curve.png
```

---

## Conclusion

In this project, I learned how to build a Logistic Regression model for a binary classification problem. I explored and prepared the dataset, trained the model, and evaluated its performance using different classification metrics. I also learned how the sigmoid function works, how the ROC curve is used to measure model performance, and how changing the decision threshold affects precision and recall.