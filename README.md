
# 🫀 Heart Disease Prediction Using Machine Learning

This project implements a complete and efficient **machine learning pipeline** to predict the risk of heart disease. By combining **data analysis, visualization, statistical testing, and supervised learning**, the project analyzes key medical features to identify patients at high risk, supporting early detection and timely intervention.

---

## 📌 **Project Overview**

Heart disease is a leading cause of mortality worldwide. Early detection and accurate risk prediction are critical for improving patient outcomes. This project leverages medical features such as:

* Age
* Cholesterol levels
* Resting blood pressure
* Maximum heart rate
* ECG results
* Other clinically relevant parameters

Using these features, the pipeline builds predictive models to classify whether a patient is likely to have heart disease.

---

## 🛠️ **Tools and Libraries Used**

1. **Python** – High-level programming language for data science and machine learning.
2. **Pandas** – Data loading, cleaning, manipulation, and tabular analysis.
3. **NumPy** – Efficient numerical operations and array computations.
4. **Matplotlib & Seaborn** – Exploratory Data Analysis (EDA) and visualization, including histograms, boxplots, count plots, and correlation heatmaps.
5. **SciPy (`scipy.stats`)** – Performs **statistical hypothesis testing**. The **independent t-test** is applied to determine whether features such as cholesterol levels significantly differ between patients with and without heart disease.
6. **Scikit-Learn** – Core ML library for train-test splitting, model training, and evaluation. Models used:

   * Logistic Regression
   * Random Forest Classifier
     Evaluation metrics: Accuracy, Precision, Recall, F1-score, Confusion Matrix.
7. **Jupyter Notebook** – Interactive environment for executing code, visualizing results, and documenting the workflow.
8. **CSV Dataset** – `cleaned_merged_heart_dataset.csv` containing patient features used for training and testing models.

---

## 📊 **Workflow**

1. Load and preprocess the dataset
2. Perform EDA using visualizations
3. Conduct **statistical analysis using t-tests** to validate significant differences in key features
4. Train supervised machine learning models
5. Evaluate model performance using metrics and confusion matrices

---

## 🚀 **Outcome**

* Reliable prediction of heart disease risk
* Insights into key medical features affecting heart health
* Statistically validated findings through t-tests
* Reproducible and scalable healthcare analytics pipeline

---

## 📁 **Project Structure**

```
|-- dataset/
|   └── cleaned_merged_heart_dataset.csv
|
|-- notebooks/
|   └── heart_disease_analysis.ipynb
|
|-- src/
|   ├── preprocessing.py
|   ├── model.py
|
└── README.md
```

---

