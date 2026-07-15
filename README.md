# SMART-HEART-DIEASE-PREDICTION

# ❤️ Heart Failure Prediction Using Machine Learning

## 📌 Project Overview

This project predicts the likelihood of heart failure using machine learning techniques. The objective is to build an accurate classification model that can assist in the early detection of heart disease by analyzing patient clinical records.

To improve prediction performance and handle class imbalance, the project applies **SMOTE (Synthetic Minority Over-sampling Technique)** before training machine learning models.



## 🎯 Objectives

- Predict heart failure based on clinical features.
- Handle class imbalance using SMOTE.
- Compare the performance of Random Forest and CatBoost classifiers.
- Evaluate models using multiple performance metrics.

-

## 📂 Dataset

**Dataset Name:** Heart Failure Clinical Records Dataset

The dataset contains medical information collected from heart failure patients.

### Features

- Age
- Anaemia
- Creatinine Phosphokinase (CPK)
- Diabetes
- Ejection Fraction
- High Blood Pressure
- Platelets
- Serum Creatinine
- Serum Sodium
- Sex
- Smoking
- Time
- DEATH_EVENT (Target Variable)

---

## 🛠 Technologies Used

- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)
- CatBoost
- Random Forest

---

## 📊 Project Workflow

1. Import required libraries
2. Load the dataset
3. Perform data preprocessing
4. Handle missing values (if any)
5. Exploratory Data Analysis (EDA)
6. Split dataset into training and testing sets
7. Apply SMOTE to balance the training data
8. Train Random Forest model
9. Train CatBoost model
10. Evaluate model performance
11. Compare results
12. Visualize ROC Curve and Confusion Matrix

---

## 🤖 Machine Learning Models

### Random Forest Classifier

- Ensemble learning algorithm
- Reduces overfitting
- Handles non-linear relationships efficiently

### CatBoost Classifier

- Gradient Boosting algorithm
- Handles categorical data efficiently
- High prediction accuracy
- Robust against overfitting

---

## ⚖ Handling Imbalanced Data

This project uses **SMOTE (Synthetic Minority Over-sampling Technique)** to balance the minority and majority classes in the training dataset.

Benefits:
- Reduces model bias
- Improves recall
- Enhances overall classification performance

---

## 📈 Model Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix
- ROC Curve

---

## 📷 Output Visualizations

The project includes:

- Confusion Matrix
- ROC Curve
- Classification Report
- Feature Importance (Random Forest)
- Model Accuracy Comparison

---

## 📁 Repository Structure

```
Heart-Failure-Prediction/
│
├── Dataset/
│   └── heart_failure_clinical_records_dataset.csv
│
├── Notebook/
│   └── Heart_Disease_Prediction.ipynb
│
├── Images/
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   └── feature_importance.png
│
├── README.md
└── requirements.txt
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Heart-Failure-Prediction.git
```

Move into the project directory

```bash
cd Heart-Failure-Prediction
```

Install required libraries

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

---

#Required Libraries

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
imbalanced-learn
catboost
````



# Results

- Successfully balanced the dataset using SMOTE.
- Compared Random Forest and CatBoost classifiers.
- Evaluated performance using multiple metrics.
- Generated ROC Curve and Confusion Matrix for performance analysis.
- CatBoost demonstrated strong predictive performance for heart failure classification.



## Future Enhancements

- Hyperparameter optimization using GridSearchCV or Optuna.
- Deploy the model as a web application using Flask or Streamlit.
- Integrate real-time patient data.
- Explore advanced ensemble learning techniques.



##Author

**Varadaboyina Veena Sree**

B.Tech – Artificial Intelligence

GitHub: https://github.com/veenasri16

LinkedIn: https://www.linkedin.com/in/varadaboina-veenasri-2566b4344



## 📜 License

This project is developed for educational and academic purposes
