

## 📌 Project Overview

This project demonstrates a complete machine learning pipeline for binary classification using Logistic Regression. It includes data preprocessing, feature scaling, model training, evaluation, and threshold tuning.

---

## 🚀 Features

* Data loading from CSV file
* Data cleaning and preprocessing
* Handling missing and non-numeric values
* Feature scaling using StandardScaler
* Logistic Regression model training
* Model evaluation using:

  * Confusion Matrix
  * Precision
  * Recall
  * ROC-AUC Score
* Threshold tuning for better performance

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn

---

## 📂 Dataset

Dataset used: `data.csv`
Location: `C:\Users\M B Chinmay\Downloads\data.csv`

---

## ⚙️ Workflow

1. Load dataset
2. Preprocess data (handle missing values, encoding)
3. Split features and target
4. Standardize features
5. Train Logistic Regression model
6. Evaluate model performance
7. Tune threshold for improved results

---

## 📊 Evaluation Metrics

* Confusion Matrix
* Precision
* Recall
* ROC-AUC Score

---

## 🎯 Threshold Tuning

Different thresholds (e.g., 0.3, 0.5, 0.7) are tested to balance precision and recall.

---

## 📈 Sigmoid Function

Logistic Regression uses the sigmoid function to convert predictions into probabilities:

σ(z) = 1 / (1 + e^(-z))

---

## ▶️ How to Run

1. Clone the repository
2. Install required libraries:

   ```
   pip install pandas numpy scikit-learn
   ```
3. Run the Python script:

   ```
   python main.py
   ```

---

## 📌 Results

The model outputs evaluation metrics and shows how performance changes with different thresholds.

---

## 🤝 Acknowledgment

This project is part of an AI & ML Internship task.

---

## 📎 Author

MB Chinmay
