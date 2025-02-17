# Logistic Regression Study

## Overview
This project is a study on **Logistic Regression**, where I analyze a dataset related to social network ads. The goal is to predict whether a user will purchase a product based on their **age**, **estimated salary**, and **gender**.

## Key Steps in the Analysis

1. **Exploratory Data Analysis (EDA)**
   - Checked for missing values
   - Visualized data distributions using boxplots and scatter plots
   - Examined correlations between features and the target variable

2. **Data Preprocessing**
   - Removed unnecessary columns (e.g., `User ID`)
   - Encoded categorical variables (Gender) using **Label Encoding**
   - Handled class imbalance using the **SMOTE** technique
   - Standardized numerical features (Age, Estimated Salary) using **Standard Scaler**

3. **Model Training and Evaluation**
   - Split the dataset into **training** and **test** sets using `train_test_split`
   - Trained a **Logistic Regression** model using `sklearn`
   - Evaluated performance using metrics such as:
     - Accuracy
     - Precision
     - Recall
     - F1-score
   - Identified issues related to recall imbalance and improved model performance with **SMOTE**

## Key Findings
- There was a **weak correlation** between age and salary.
- Gender did **not significantly impact** the purchase decision.
- The dataset was **imbalanced** (64% class 0, 36% class 1), which affected model performance.
- **SMOTE** was applied to balance the dataset and improve recall for the minority class.
- **Standard Scaling** helped prevent the dominance of higher-value features like salary over age.

## Next Steps
- Experiment with other **classification models** (Decision Tree, Random Forest, SVM, etc.).
- Tune hyperparameters of Logistic Regression.
- Remove low-impact features to improve efficiency.

## Technologies Used
- **Python**
- **Pandas**, **Matplotlib**, **Seaborn** for EDA
- **Scikit-Learn** for machine learning
- **Imbalanced-Learn** for SMOTE

---
### Author
This project was conducted as part of a study on **Logistic Regression and Data Preprocessing**.

