# Diabetes Prediction using Machine Learning Classifiers

This project applies multiple machine learning algorithms to the **Pima Indians Diabetes Database** to predict whether a patient has diabetes based on medical diagnostic measurements.  

## 📂 Dataset
The dataset used is the well-known **Pima Indians Diabetes Database**, which contains several health-related attributes such as glucose level, blood pressure, BMI, age, and more. The target variable is `Outcome` (0 = no diabetes, 1 = diabetes).

Before modeling, some preprocessing was done:
- Dropped the columns with excessive missing/zero values (`Insulin`, `SkinThickness`)
- Split the dataset into **train (80%)** and **test (20%)**

## 🤖 Models Implemented
The following classifiers were trained and evaluated:
- Logistic Regression
- Random Forest
- Support Vector Machine (SVM, RBF kernel)
- K-Nearest Neighbors (KNN)
- AdaBoost

Gradient Boosting was intentionally excluded to focus on other ensemble methods.

## 📊 Evaluation Metrics
Each model was evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

A comparison table was generated to show the performance of all models side by side.

## 🚀 Results
- The models achieved varying levels of performance.
- Random Forest and AdaBoost generally performed better in terms of balance between precision and recall.
- Logistic Regression and SVM provided solid baseline results.
- KNN worked well after applying feature scaling.

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## 📌 How to Run
1. Clone this repository  
   ```bash
   git clone https://github.com/yourusername/diabetes-classification.git
   cd diabetes-classification
