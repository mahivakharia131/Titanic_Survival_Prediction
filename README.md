# Titanic Survival Prediction using Machine Learning

## 📌 Project Overview

This project predicts whether a passenger survived the Titanic disaster using supervised machine learning techniques. The workflow includes data exploration, preprocessing, feature engineering, model training, evaluation, and comparison to identify the best-performing classification model.

---

## 🎯 Project Objectives

- Explore and understand the Titanic dataset.
- Handle missing values and preprocess the data.
- Encode categorical variables for machine learning.
- Train multiple classification models.
- Compare model performance using evaluation metrics.
- Identify the best-performing model and analyze important features.

---

## 📂 Dataset

- **Dataset:** Titanic - Machine Learning from Disaster
- **Source:** https://www.kaggle.com/competitions/titanic/data

The dataset contains passenger information such as:
- Passenger Class (Pclass)
- Sex
- Age
- Fare
- Embarked
- Number of Siblings/Spouses (SibSp)
- Number of Parents/Children (Parch)
- Survival Status (Target Variable)

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

- Handled missing values
  - Age → Filled using Median
  - Embarked → Filled using Mode
  - Cabin → Removed due to a large number of missing values
- Encoded categorical variables using Label Encoding
- Removed irrelevant features:
  - PassengerId
  - Name
  - Ticket
- Split the dataset into Training (80%) and Testing (20%) sets

---

## 🤖 Machine Learning Models

The following classification models were trained and evaluated:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

---

## 📊 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report
- Confusion Matrix

---

## 🏆 Model Comparison

| Model | Accuracy |
|--------|---------:|
| Logistic Regression | **81.01%** |
| Decision Tree | **78.21%** |
| Random Forest | **82.12%** |

---

## ⭐ Best Model

**Random Forest Classifier**

Reasons:
- Highest Accuracy (82.12%)
- Highest Precision
- Best overall performance
- Good generalization on unseen data

---

## 📈 Feature Importance

The most influential features were:

1. Sex
2. Fare
3. Age
4. Pclass
5. SibSp
6. Parch
7. Embarked

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook / Google Colab

---

## 📌 Conclusion

Random Forest achieved the best overall performance among the three classification models. Proper data preprocessing, feature engineering, and model evaluation significantly improved prediction quality. The project demonstrates a complete end-to-end machine learning workflow for solving a real-world classification problem.

---

## 👤 Author

**Mahi Vakharia**

AI & ML Internship Project
