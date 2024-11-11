# Credit Card Fraud Detection Project

## Project Overview
This project builds a machine learning model to detect fraudulent credit card transactions, using transaction data to identify patterns associated with fraud. The model helps in reducing potential losses from fraudulent activities by accurately classifying transactions.

- **Dataset**: [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) on Kaggle

## Key Learning Points

### 1. Data Preprocessing
- **Libraries Used**: `Pandas`, `NumPy`
- Cleaned and prepared the dataset by handling missing values, normalizing numerical data, and encoding categorical variables.
- Leveraged `Pandas` and `NumPy` for efficient data transformation and structuring, preparing it for machine learning models.

### 2. Feature Engineering and Selection
- **Libraries Used**: `Pandas`, `NumPy`, `scikit-learn`
- Engineered additional features based on transaction characteristics to improve model accuracy.
- Applied feature selection techniques using `scikit-learn` to retain impactful variables, simplifying the model and enhancing interpretability.

### 3. Model Development
- **Library Used**: `scikit-learn`
- Built classification models, including Logistic Regression, Decision Trees, and Random Forests using `scikit-learn`, to classify transactions as fraudulent or legitimate.
- Compared various algorithms and evaluated performance to find the most effective model for fraud detection.

### 4. Imbalanced Data Handling
- **Technique Used**: SMOTE (Synthetic Minority Over-sampling Technique)
- Addressed class imbalance by using SMOTE to oversample the minority (fraudulent) class, enabling the model to learn effectively from limited fraud cases.
- Compared sampling techniques to optimize model performance on the minority class.

### 5. Model Evaluation
- **Library Used**: `scikit-learn`
- Assessed models using precision, recall, and F1-score, focusing on maximizing fraud detection and minimizing false negatives.
- Used confusion matrices and ROC-AUC scores to confirm model effectiveness in detecting fraudulent transactions.

## Conclusion
This project enhanced my skills in data preprocessing, feature engineering, and classification modeling for fraud detection, along with strategies for handling imbalanced datasets. It provided valuable experience in applying machine learning to a finance-related problem.

## Technologies Used
- **Languages**: Python
- **Libraries**: `Pandas`, `NumPy`, `scikit-learn`

---

This project provided hands-on experience in data preprocessing, model selection, and fraud detection, using a publicly available [Kaggle dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).
