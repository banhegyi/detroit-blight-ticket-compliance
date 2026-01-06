<<<<<<< HEAD
# Detroit Blight Ticket Compliance Prediction

## 📌 Project Overview
This project predicts whether a blight violation fine issued by the City of Detroit
will be paid on time. The goal is to improve fine collection efficiency by identifying
cases with low compliance probability.

The dataset contains violation records between 2004–2011, including financial,
administrative, geographic, and temporal features.

## 🎯 Objective
- Predict probability of on-time payment (compliance)
- Evaluation metric: ROC AUC
- Target performance: AUC ≥ 0.75

## 🧪 Machine Learning Workflow
- Data cleaning & preprocessing
- Leakage-aware feature selection
- Feature engineering
- Model training & comparison
- Evaluation with ROC AUC
- Visualization & dimensionality reduction (PCA)

## 📊 Models Tested
| Model                | ROC AUC |
|---------------------|---------|
| Logistic Regression | ~0.81   |
| Random Forest       | ~0.82   |
| Gradient Boosting   | **0.83** |

Gradient Boosting achieved the best performance while avoiding data leakage.

## 🔍 Key Insights
- Financial variables are correlated but not sufficient alone
- Repeated violations strongly reduce compliance probability
- PCA reveals clear structure among violation types
- Careful leakage handling is crucial for realistic performance

## 📁 Files
- `notebook/`: Jupyter Notebook with full analysis
- `reports/`: HTML and PDF reports
- `figures/`: Key visualizations

## 🚀 How to Run
```bash
pip install -r requirements.txt
jupyter notebook
=======
# detroit-blight-ticket-compliance
End-to-end Data Science project: data cleaning → feature engineering → leakage handling → modeling → evaluation.
>>>>>>> 19a044f3c496b8ea29854e3976ed51e8d824a197
