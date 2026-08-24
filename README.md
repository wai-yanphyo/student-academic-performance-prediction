# Student Academic Performance Prediction Using Machine Learning

## Master's Research Project – Dublin Business School

This repository contains the research paper, machine learning implementation, analysis, and results for my Master's research project at **Dublin Business School (DBS)**.

The research investigates the use of machine learning techniques to predict undergraduate student academic performance using the **Student Performance Dataset**.

The study compares three classification algorithms:

- Logistic Regression
- Random Forest
- Decision Tree

The models are evaluated using multiple performance metrics, including Accuracy, Precision, Recall, F1-Score, AUC-ROC, and Confusion Matrix.

---

## Research Objective

The main objective of this research is to investigate which machine learning model provides the most accurate prediction of undergraduate student academic performance.

The research focuses on predicting the final student grade (**G3**), which is converted into a binary classification problem:

- **Pass:** G3 ≥ 10
- **Fail:** G3 < 10

---

## Research Question

> **Which machine learning model provides the most accurate prediction of student final academic performance (G3) using the Kaggle Student Performance Dataset?**

---

## Dataset

The research uses the **Student Performance Dataset**, originally collected from the **UCI Machine Learning Repository** and available through Kaggle.

The dataset contains:

- **395 student records**
- **33 variables**
- Academic, demographic, family, and behavioural attributes

Examples of variables include:

- G1 – First period grade
- G2 – Second period grade
- G3 – Final grade
- Study time
- Previous failures
- Absences
- Parental education
- Family support
- Internet access
- Social and behavioural factors

After preprocessing and feature selection, **20 features** were used for model training and evaluation.


---

## Methodology

The research follows a systematic machine learning workflow:

```text
Data Collection
      ↓
Data Cleaning
      ↓
Data Preprocessing
      ↓
Feature Encoding
      ↓
Feature Selection
      ↓
Train/Test Split
      ↓
Model Development
      ↓
Hyperparameter Tuning
      ↓
Model Evaluation
      ↓
Cross-Model Comparison
