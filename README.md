# ML_Heart_Attack_Risk_Prediction
# 💓 Heart Attack Risk Prediction using Machine Learning

## 📘 Project Overview

This project explores the application of machine learning algorithms to predict the risk of heart attacks using clinical and demographic data. With heart disease being one of the leading causes of death globally, early and accurate prediction is crucial for preventive healthcare. We developed and compared models including **Logistic Regression**, **Random Forest**, and **XGBoost**, with the goal of identifying the most effective technique for risk prediction.

## 📁 Table of Contents
- [Project Overview](#-project-overview)
- [Dataset](#-dataset)
- [Technologies Used](#-technologies-used)
- [Installation & Setup](#-installation--setup)
- [Modeling Approach](#-modeling-approach)
- [Results](#-results)
- [Deployment](#-deployment)
- [Screenshots](#-screenshots)
- [Conclusion & Future Work](#-conclusion--future-work)
- [References](#-references)

---

## 📊 Dataset

- **Source**: [Kaggle Heart Disease Dataset](https://www.kaggle.com/datasets) *(update with exact URL if available)*
- **Features**: Age, Gender, Chest Pain Type, Cholesterol, Fasting Blood Sugar, Max Heart Rate, etc.
- **Target Variable**: `Heart Attack Risk` (0 = Low, 1 = High)
- **Preprocessing**:
  - Handling missing values
  - Encoding categorical features
  - Feature scaling using StandardScaler

---

## 🧰 Technologies Used

- Python
- Scikit-learn
- XGBoost
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook
- Joblib (for model serialization)

---

## ⚙️ Installation & Setup

1. Clone the repository:
```bash
git clone https://github.com/yourusername/heart-attack-risk-prediction.git
cd heart-attack-risk-prediction
