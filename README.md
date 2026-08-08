# Heart Disease Classification using Random Forest ❤️

## 📌 Project Overview

This project is an experiment on **heart disease classification using the Random Forest algorithm**. The objective is to evaluate the ability of Random Forest to classify heart disease risk based on various patient characteristics.

## 📊 Dataset

The dataset used is the **Heart Disease Prediction Dataset** from Kaggle, containing **2,181 records and 14 columns**.

Target:

* `0` → Lower risk of heart attack
* `1` → Higher risk of heart attack

## 🔎 Analysis Process

* Exploratory Data Analysis (EDA)
* Missing Value Checking
* Data Type Conversion
* Duplicate Checking
* Outlier Checking
* Feature Selection using Random Forest
* Train-Test Split **80:20**
* Random Forest Classification
* Hyperparameter Tuning
* Evaluation using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix

## 🤖 Model & Experiment

Algorithm used:

**Random Forest Classifier**

Hyperparameters tested:

* `n_estimators`: 5, 10, 20, 50, 100
* `max_depth`: 2, 3, 4, 5, 10, None
* `max_features`: 1, 2
* `random_state`: 42

Four experimental scenarios were evaluated:

1. Original data
2. Data without duplicates
3. Data with feature selection
4. Data without duplicates and with feature selection

## 📈 Best Result

The best performance was achieved using the **original dataset** with:

```text
n_estimators = 100
max_depth = None
max_features = 2
```

| Metric    |  Score |
| --------- | -----: |
| Accuracy  | 96.57% |
| Precision | 95.96% |
| Recall    | 97.27% |
| F1-Score  | 96.61% |

### Confusion Matrix

```text
[[208, 9],
 [  7, 213]]
```

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook
* Kaggle Dataset

## 📁 Files

```text
├── Heart_Diasease_AI.ipynb
├── README.md
```

## 🎓 Project Information

* **Project:** Heart Disease Classification
* **Algorithm:** Random Forest
* **Type:** Machine Learning Classification
* **Dataset:** Heart Disease Prediction Dataset
* **Author:** Rama Aulia Gemilang
