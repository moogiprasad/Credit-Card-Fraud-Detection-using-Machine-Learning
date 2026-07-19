# 💳 Credit Card Fraud Detection using Machine Learning

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-5B8FA8?style=for-the-badge)
![SMOTE](https://img.shields.io/badge/SMOTE-Imbalanced--Learn-success?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

An end-to-end Machine Learning project for detecting fraudulent credit card transactions using **Logistic Regression**, **Decision Tree**, and **Random Forest**. The project addresses severe class imbalance using **SMOTE** and evaluates models using **Precision, Recall, F1-Score, and ROC-AUC**.
---

## 📌 Problem Statement

Credit card fraud causes significant financial losses worldwide. Since fraudulent transactions are extremely rare compared to legitimate ones, traditional machine learning models often struggle to identify them accurately.

The objective of this project is to build a robust fraud detection model capable of identifying fraudulent transactions while minimizing false positives.

---

## 🎯 Objectives

- Perform data preprocessing and cleaning
- Analyze transaction patterns using EDA
- Handle class imbalance using SMOTE
- Train multiple machine learning models
- Compare model performance
- Select the best-performing model
- Save the trained model for future predictions

---

## 📂 Dataset

**Dataset:** Credit Card Fraud Detection Dataset

Source:

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

Dataset Information:

- 284,807 Transactions
- 31 Columns
- Binary Classification
- Target:
  - 0 → Legitimate
  - 1 → Fraud

**Note:** The dataset is not included in this repository because of GitHub file size limitations.

---

# 🚀 Project Highlights

| Metric | Value |
|---------|------:|
| Dataset Size | 284,807 Transactions |
| Features | 30 Input Features |
| Target Variable | Binary Classification |
| Fraud Cases | 492 |
| Legitimate Cases | 284,315 |
| Best Performing Model | Random Forest |
| Sampling Technique | SMOTE |
| Model Serialization | Joblib (.pkl) |

---

# 🛠 Tech Stack

| Category | Technologies |
|-----------|--------------|
| Programming Language | Python |
| Data Manipulation | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Imbalanced Learning | SMOTE (imbalanced-learn) |
| Model Persistence | Joblib |
| Development Environment | Jupyter Notebook |
| Version Control | Git & GitHub |
---

# 🏆 Model Performance

| Model | Accuracy | Precision | Recall | F1 Score |
|-------|---------:|----------:|--------:|---------:|
| Logistic Regression | 0.9889 | 0.1162 | **0.8526** | 0.2045 |
| Decision Tree | 0.9965 | 0.0442 | 0.0526 | 0.0481 |
| **Random Forest** | **0.9993** | **0.9394** | 0.6526 | **0.7702** |

---

### Key Observation

- Logistic Regression achieved the highest Recall but produced many false positives due to low Precision.
- Decision Tree showed poor generalization on the imbalanced dataset.
- Random Forest achieved the best overall balance between Precision and Recall, resulting in the highest F1 Score and Accuracy.

---

# 📊 Project Workflow

```
Dataset
    ↓
Data Cleaning
    ↓
Exploratory Data Analysis
    ↓
Feature Scaling
    ↓
SMOTE
    ↓
Train-Test Split
    ↓
Model Building
    ↓
Model Evaluation
    ↓
ROC Curve
    ↓
Feature Importance
    ↓
Model Saving
```

---

# 📈 Exploratory Data Analysis

The following analyses were performed:

- Class Distribution
- Transaction Amount Distribution
- Correlation Heatmap
- Fraud vs Legitimate Analysis

### Class Distribution

![Class Distribution](images/class_distribution.png)

---

### Amount Distribution

![Amount Distribution](images/amount_distribution.png)

---


### Time Distribution

![Time Distribution](images/time_distribution.png)

---


# 🤖 Machine Learning Models

The following models were trained and evaluated:

- Logistic Regression
- Decision Tree
- Random Forest

Evaluation Metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

---

# 📉 Confusion Matrix

![Confusion Matrix](images/confusion_matrix_rf.png)

---

# 📈 ROC Curve

![ROC Curve](images/roc_curve.png)

---

# ⭐ Feature Importance

![Feature Importance](images/feature_importance.png)

---

# 📁 Project Structure

```
Credit-Card-Fraud-Detection/
│
├── notebook/
├── images/
├── model/
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

# 🚀 How to Run

Clone the repository

```bash
git clone https://github.com/moogiprasad/Credit-Card-Fraud-Detection.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Run

```
Fraud_Detection.ipynb
```

---

# 📌 Future Improvements

- Add XGBoost
- Hyperparameter Tuning
- Deploy using Streamlit
- Real-time Fraud Detection API

---

# 💡 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Machine Learning
- Data Visualization
- Model Evaluation
- Fraud Detection
- Feature Scaling
- SMOTE
- Model Serialization

---

# 👨‍💻 Author

**Moogi Prasad**

B.Tech Artificial Intelligence & Machine Learning

GitHub: https://github.com/moogiprasad

LinkedIn: https://linkedin.com/in/moogiprasad

---

⭐ If you found this project useful, consider giving it a star!
