# Telco Customer Churn Prediction

This project builds a machine learning pipeline to predict customer churn for a telecommunications company using the Telco Customer Churn dataset from Kaggle.

---

## Dataset

- Source: [Telco Customer Churn - Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn)
- The dataset contains customer demographics, services subscribed, and account information.

---

## Project Overview

- **Exploratory Data Analysis (EDA):** 
  - Summary statistics, distributions, and visualizations to understand the data.
  - Checked for missing values and handled them.

- **Data Cleaning:**
  - Converted `TotalCharges` to numeric.
  - Filled missing values.
  - Dropped irrelevant columns (`customerID`).
  - Encoded categorical features using `LabelEncoder`.

- **Feature Engineering:**
  - No additional feature creation; used original features.

- **Model Training:**
  - Trained multiple classifiers including Logistic Regression, Random Forest, XGBoost.
  - Built a Voting Classifier ensemble using top models.

- **Evaluation:**
  - Evaluated models using accuracy score.
  - Voting Classifier improved prediction accuracy.

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/telco-customer-churn.git
   cd telco-customer-churn

2.Install dependencies:

pip install -r requirements.txt


3.Run the notebook or script:

Open churn_prediction_pipeline.ipynb in Jupyter Notebook or JupyterLab.

Follow the cells to explore, preprocess, train, and evaluate models.

---

Result

| Model               | Accuracy |
| ------------------- | -------- |
| Random Forest       | 0.79     |
| Logistic Regression | 0.79     |
| XGBoost             | 0.79     |
| Voting Classifier   | 0.80+    |

---

Future Work


Hyperparameter tuning for each model.

Add feature engineering and selection.

Deploy as a web app for live predictions.

Use advanced evaluation metrics (ROC-AUC, F1 score).

---

Author

Asgarali Malpara 

[GitHub](https://github.com/asgarali429) | [LinkedIn](https://www.linkedin.com/in/asgarali-malpara-5a78462a9/)
