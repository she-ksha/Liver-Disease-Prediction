# Liver Disease Prediction using Machine Learning

A machine learning project for predicting liver disease, classifying disease types, and estimating disease severity using clinical and symptom data.

## Features

* **Liver Disease Prediction** — Binary classification of disease vs. no disease.
* **Disease Classification** — Classifies patients into:

  * Hepatitis
  * Liver Cirrhosis
  * Fatty Liver
  * None
* **Severity Prediction** — Predicts a continuous disease severity score using patient symptoms with TF-IDF.

## Dataset

The dataset contains **12,000 patient records** with clinical and symptom-related information.

Main features include:

* Age
* Gender
* Total Bilirubin
* Direct Bilirubin
* ALP
* ALT (SGPT)
* AST (SGOT)
* Total Proteins
* Albumin
* Symptoms

## Models

Several machine learning algorithms were evaluated, including:

* Random Forest
* Gradient Boosting
* Hist Gradient Boosting
* AdaBoost
* XGBoost
* Linear Regression

Hyperparameter tuning and probability-threshold optimization were also performed to improve model performance.

## Results

| Task                               |         Best Result |
| ---------------------------------- | ------------------: |
| Binary Disease Prediction          | **90.21% Accuracy** |
| Multi-Class Disease Classification | **97.88% Accuracy** |
| Severity Score Prediction          |     **R² = 0.9917** |

The binary prediction task achieved its best reported performance using **Hist Gradient Boosting with threshold tuning**, while Gradient Boosting achieved the strongest reported multi-class and severity results.

## Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Matplotlib
* Seaborn

## 🚀 Installation

```bash
git clone https://github.com/your-username/liver-disease-prediction.git
cd liver-disease-prediction

pip install pandas numpy scikit-learn xgboost matplotlib seaborn
```

Run the Jupyter Notebook:

```bash
jupyter notebook
```

Then open the project notebook and run the cells.

## Disclaimer

This project is intended for **educational and research purposes only**. It is not a medical diagnostic tool and should not be used for clinical decision-making.
