# Credit Scoring Model 📊

This repository contains a machine learning pipeline designed to predict an individual's creditworthiness based on financial history. This project was developed as part of the CodeAlpha Machine Learning Internship.

## 🎯 Objective
To build a robust classification model that accurately evaluates credit risk, minimizing false positives (approving bad credit risks) by optimizing for the ROC-AUC metric and handling severe class imbalances.

## 🛠️ Tech Stack & Methodology
* **Language:** Python
* **Libraries:** Scikit-learn, Pandas, Imbalanced-learn
* **Algorithm:** Random Forest Classifier (optimized with balanced class weights)
* **Preprocessing:** Automated numerical scaling and categorical One-Hot Encoding using `sklearn.pipeline.Pipeline` and `ColumnTransformer`.

## 📈 Dataset
The model is trained on the **German Credit Dataset** (fetched dynamically via OpenML API), which evaluates individuals across various financial and demographic metrics to classify them as 'good' or 'bad' credit risks.

## 🚀 How to Run
This project is designed to run seamlessly in a Jupyter/Colab environment.
1. Open the `Credit_Scoring_Pipeline.ipynb` notebook.
2. Run the cell. The script will automatically fetch the data, preprocess it, train the model, and output the performance metrics (Precision, Recall, F1-Score, ROC-AUC).

---
*Developed by Muhammad Zeeshan | AI/ML Engineer*
