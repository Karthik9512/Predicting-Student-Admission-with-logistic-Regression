# Student Admission Prediction

Predicting whether a student will be **admitted** (1) or **not admitted** (0) into a graduate program based on their exam scores using **Logistic Regression**.

---

## 📌 Project Overview

This project demonstrates a **binary classification task** using **Logistic Regression** in Python.  
It includes:

- Dataset preparation (100+ rows of Exam1 & Exam2 scores)
- Data analysis and visualization
- Model building and evaluation
- Prediction for new students

---

## 🛠 Technologies Used

- Python 3.x  
- Jupyter Notebook / Python script  
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

---

## 📊 Data Analysis

- Visualized exam scores vs admission results
- Found correlation between Exam1 and Exam2 scores
- Explored relationship between exam scores and admission probability

---

## ⚙ Model Building

- Split dataset into **training** and **testing** sets
- Trained **Logistic Regression** model using `sklearn`
- Evaluated using:
  - Accuracy
  - Confusion matrix
  - Precision, Recall, F1-score
  - ROC curve and AUC

---

## 🔮 Prediction

Example prediction for a new student:

| Exam1 Score | Exam2 Score | Predicted Admission |
|-------------|-------------|------------------|
| 58          | 67          | Yes / No |

---
```bash
git clone https://github.com/YOUR-USERNAME/student-admission-prediction.git
