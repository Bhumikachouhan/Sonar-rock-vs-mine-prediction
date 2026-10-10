# Sonar Rock vs Mine Prediction (ML Project)

TA machine learning project in Python that classifies sonar signals as Rock (R) or Mine (M) using Logistic Regression (Scikit-learn).

---

## Objective
The objective of this project is to build a machine learning model that can classify whether an object is a rock or a mine using sonar signals.

---

## Dataset
The dataset contains 60 numerical features representing sonar signals.
- Dataset used: Sonar Dataset
- Number of features: 60
- Target classes:
  - R → Rock (97 samples)
  - M → Mine (111 samples)

---

## Tools Used

* Python
* NumPy
* Pandas
* Scikit-learn
* VS Code

---

## Project Workflow

1. Import required libraries
2. Load dataset
3. Data preprocessing
4. Train-test split (90% train / 10% test, stratified, random_state=1)
5. Model training using Logistic Regression
6. Model evaluation using accuracy score
7. Prediction system for new sonar readings
 
---

## Model Used

Logistic Regression

---

## Train-Test Split
Training samples: 187
Test samples: 21

---

## Result
The model successfully predicts whether the object is a rock or a mine with good accuracy.
| Metric | Value |
|---|---|
| Training accuracy | 83.4% |
| Test accuracy | 76.2% |



---
## Findings
This project demonstrates how logistic regression can be used for binary classification problems.

---

## How to Run
```
pip install -r requirements.txt
python rock_mine_prediction.py
```
