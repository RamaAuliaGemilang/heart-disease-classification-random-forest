# Heart Disease Classification using Random Forest ❤️

## 📌 Project Overview

Project ini merupakan eksperimen **klasifikasi penyakit jantung menggunakan algoritma Random Forest**. Tujuannya adalah mengevaluasi kemampuan Random Forest dalam mengklasifikasikan risiko penyakit jantung berdasarkan berbagai karakteristik pasien.

## 📊 Dataset

Dataset yang digunakan adalah **Heart Disease Prediction Dataset** dari Kaggle, dengan **2.181 data dan 14 kolom**.

Target:

* `0` → lebih rendah risiko serangan jantung
* `1` → lebih tinggi risiko serangan jantung

## 🔎 Analysis Process

* Exploratory Data Analysis (EDA)
* Missing Value Checking
* Data Type Conversion
* Duplicate Checking
* Outlier Checking
* Feature Selection menggunakan Random Forest
* Train-Test Split **80:20**
* Random Forest Classification
* Hyperparameter Tuning
* Evaluation menggunakan Accuracy, Precision, Recall, F1-Score, dan Confusion Matrix

## 🤖 Model & Experiment

Algoritma yang digunakan:

**Random Forest Classifier**

Hyperparameter yang diuji:

* `n_estimators`: 5, 10, 20, 50, 100
* `max_depth`: 2, 3, 4, 5, 10, None
* `max_features`: 1, 2
* `random_state`: 42

Eksperimen dilakukan pada 4 skenario:

1. Data asli
2. Data tanpa duplikasi
3. Data dengan seleksi fitur
4. Data tanpa duplikasi dan dengan seleksi fitur

## 📈 Best Result

Performa terbaik diperoleh pada **skenario data asli** dengan:

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

Confusion Matrix:

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
