# Heart Disease Prediction using Decision Tree and Random Forest

## Project Overview

This project focuses on predicting whether a person has heart disease using machine learning classification algorithms. Two models, Decision Tree and Random Forest, were trained and compared to understand their performance. The project also explores feature importance and model evaluation using cross-validation.

---

## Tools Used

- Python
- Pandas
- Matplotlib
- Scikit-learn

---

## Dataset

The project uses a Heart Disease dataset that contains information about different medical attributes such as age, sex, chest pain type, cholesterol level, blood pressure, and other health-related features. The target variable indicates whether a person has heart disease or not.

---

## Steps Performed

- Imported the required Python libraries.
- Loaded and explored the dataset.
- Checked the dataset information, summary statistics, and missing values.
- Removed unnecessary columns.
- Filled missing values in numerical and categorical columns.
- Converted the target column into binary values.
- Encoded categorical features using Label Encoding.
- Split the dataset into training and testing sets.
- Trained a Decision Tree Classifier.
- Visualized the Decision Tree.
- Trained another Decision Tree with limited depth to observe overfitting.
- Trained a Random Forest Classifier.
- Compared the accuracy of both models.
- Displayed the feature importance of the Random Forest model.
- Evaluated the model using 5-fold Cross-Validation.

---

## Observations

### Dataset
- The dataset contains different medical features related to heart disease.
- Missing values were handled before training the models.
- Categorical features were converted into numerical values using Label Encoding.

### Decision Tree
- The Decision Tree was able to classify patients based on different medical features.
- Limiting the maximum depth helped reduce overfitting while maintaining good performance.

### Random Forest
- The Random Forest model generally achieved better accuracy than the Decision Tree.
- Combining multiple decision trees improved the model's overall performance and reduced overfitting.

### Feature Importance
- Some features had a greater influence on predicting heart disease than others.
- Feature importance helped identify the most significant medical attributes used by the model.

### Cross-Validation
- Cross-validation provided a more reliable estimate of model performance.
- The model produced consistent accuracy across different folds, indicating stable performance.

---

## Project Structure

```
Task_five_decision_tree_random_forest/
│
├── Task_five.ipynb
├── heart_disease.csv
├── README.md
└── images/
    ├── decision_tree.png
    └── feature_importance.png
```

---

## Conclusion

In this project, I learned how Decision Tree and Random Forest classifiers work for classification problems. I explored and prepared the dataset, trained both models, compared their accuracy, and studied feature importance. I also learned how limiting the depth of a Decision Tree can help reduce overfitting and how cross-validation provides a more reliable evaluation of model performance.