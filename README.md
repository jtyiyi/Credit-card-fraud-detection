# Credit Card Fraud Detection Project

## Project Overview
This project aims to build a machine learning model that detects fraudulent credit card transactions by analyzing transaction data. The model identifies patterns in fraudulent behavior, helping financial institutions reduce potential losses from fraudulent activities.

## Key Learning Points

### 1. Data Preprocessing
- **Libraries Used**: `Pandas`, `NumPy`
- Cleaned and prepared transaction data, handling missing values, normalizing numerical data, and encoding categorical features.
- Used `Pandas` and `NumPy` to efficiently structure and process data, making it ready for machine learning models.

### 2. Feature Engineering and Selection
- **Libraries Used**: `Pandas`, `NumPy`, `scikit-learn`
- Engineered additional features based on transaction characteristics to improve model accuracy.
- Employed feature selection techniques with `scikit-learn` to retain the most impactful variables, simplifying the model and enhancing interpretability.

### 3. Model Development
- **Library Used**: `scikit-learn`
- Built classification models including Logistic Regression, Decision Trees, and Random Forests using `scikit-learn` to classify transactions as fraudulent or legitimate.
- Experimented with different algorithms and evaluated model performance to identify the most effective approach for fraud detection.

### 4. Imbalanced Data Handling
- **Technique Used**: SMOTE (Synthetic Minority Over-sampling Technique)
- Tackled the class imbalance by using SMOTE to oversample the minority (fraudulent) class, helping the model learn effectively from a limited number of fraud cases.
- Compared the results of different sampling techniques to optimize performance on the minority class.

### 5. Model Evaluation
- **Library Used**: `scikit-learn`
- Evaluated models with precision, recall, and F1-score metrics, with a focus on maximizing fraud detection while minimizing false negatives.
- Used confusion matrices and ROC-AUC scores to ensure the model’s effectiveness in detecting fraudulent transactions.

## Conclusion
This project strengthened my knowledge of classification modeling, feature engineering, and handling imbalanced datasets. I developed a practical understanding of fraud detection techniques, preparing me for similar real-world applications in finance and security.

## Technologies Used
- **Languages**: Python
- **Libraries**: `Pandas`, `NumPy`, `scikit-learn`

---

This project provided hands-on experience in data preprocessing, feature engineering, model selection, and imbalanced data handling, applying machine learning techniques to fraud detection in a financial context.
