# Machine Learning Project for Titanic data

---

## 📌 Overview

Titanic prediction using machine learning classification models, preprocessing, model tuning, and evaluation.

---

## 📊 about Dataset 

* Number of Columns : 12
* Number of Rows : 891
* Number of Duplicates : 0
* Number of Nan Values : 866
* Columns : [PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked]
* Columns That Don`t Matter : [Name, PassengerId, Ticket, Cabin]
* Target : Survived
* Classification Problem


---

## Why Delete Columns That Don`t Matter?
Because There Are Extra Information And It Doesn`t Affect The Target

---

## 🧠 Models
Models Used :

* Random Forest 
* XGBoost 
* LightGBM
* CatBoost

---

## ⚙️ Preprocessing

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Scaling
* Missing Value Imputation
* Hyperparameter Tuning
* Model Evaluation
* Evaluation Metrics

---

## 🛠️ Technologies

* Numpy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost
* LightGBM
* CatBoost
* Joblib

---

## 📊 Model Evaluation
- The model Evaluated by Accuracy, F1, Precision, Recall, roc_auc

---

## 📈 Results


| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
| :--- | ---: | ---: | ---: | ---: | ---: |
| Random Forest | 73.09% | 65.47% | 63.95% | 64.70% | 81.70% |
| XGBoost | 78.92% | 81.96% | 58.13% | 68.02% | 82.59% |
| LightGBM | 78.92% | 78.26% | 62.79% | 69.67% | 80.55% |
| CatBoost | 73.09% | 64.13% | 68.60% | 66.29% | 82.42% |

---

## 📂 Project Structure

```text
.
├── catboost_info
├── data/
├── images/
├── models/
├── .gitignore
├── Titanic.ipynb
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

Install requirements :
```text

pip install -r requirements.txt

```
then run ipynb file
