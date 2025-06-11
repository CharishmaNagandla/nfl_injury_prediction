# NFL Injury Prediction 🏈

This project focuses on predicting player injuries in the NFL using machine learning techniques on historical player and game data.

---

## 📂 Project Files

- `nfl_injury_prediction.py`: Main Python script that loads data, preprocesses features, trains machine learning models, and evaluates their performance.
- `data/`: Folder containing datasets used for training and testing:
  - `Injury.csv`
  - `PlayList.csv`
  - **Player Track Data** (not included due to large size;)
- datasets can be downloaded from [Kaggle](https://www.kaggle.com/competitions/nfl-playing-surface-analytics/overview# Iris Flower Classification)).

---

## 🧰 Tools & Libraries Used

- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn (for data visualization)
- Scikit-learn (for feature engineering, model training, and evaluation)

---

## 🔍 Project Overview

- Collect and clean NFL player and game data.
- Engineer features relevant to injury risk (e.g., play counts, player position, previous injuries).
- Handle missing values and encode categorical variables.
- Address class imbalance in injury data using techniques such as oversampling to improve model performance.
- Train classification models (e.g., Logistic Regression, Random Forest, XGBoost, Neural Networks).
- Evaluate models using accuracy, precision, recall, F1 score, and ROC-AUC.
- Predict the likelihood of injury for players in upcoming games.

---
