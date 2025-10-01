# Bachelor Thesis: Privacy Concerns and Customer Churn Prediction

This repository contains the Jupyter Notebooks and code for my bachelor thesis on **customer churn intention in online services**, with a focus on **privacy, trust, anonymity, coping strategies, and emotions** as predictors.

---

## 📖 Thesis Overview
Unlike traditional churn research that relies mainly on behavioral or transactional data, this study analyzed **self-reported survey data (N = 307 respondents)** to capture users’ perceptions and attitudes.

### Methods
- **Clustering analysis**: K-Means, Agglomerative Clustering, Spectral Clustering  
- **Cluster validation**: Elbow Method, Silhouette Score, Gap Statistic  
- **Predictive modeling**: Logistic Regression, Random Forest, XGBoost, Multi-layer Perceptron (MLP)  

### Key Findings
- **Best predictive model**: XGBoost (F1 = 0.585, ROC-AUC = 0.701)  
- Strongest churn predictors: **privacy tools usage, positive emotions, false information sharing, age, privacy invasion**  
- Identified three user clusters:  
  1. Pragmatic users – low privacy concern, moderate churn risk  
  2. Concerned copers – high privacy invasion, active coping strategies, moderate churn risk  
  3. Empowered leavers – high tool usage and discontinuation intentions, strongest churn risk  

---

## ⚙️ Requirements
- Python 3.9+  
- Jupyter Notebook  
- Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `plotly`, `xgboost`  

