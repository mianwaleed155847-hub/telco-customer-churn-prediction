#  Telco Customer Churn Prediction

A complete Machine Learning project to predict which telecom customers are likely to churn.

##  Problem Statement
Telecom companies lose millions due to customer churn. This model predicts churners in advance so the company can take retention action before losing the customer.

##  Dataset
- Source: IBM Telco Customer Churn (Kaggle)
- Rows: 7,043 customers
- Features: 21 columns
- Target: Churn (Yes/No)

##  Tech Stack
- Python 3.x
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Imbalanced-learn (SMOTE)
- Matplotlib, Seaborn

##  Models Used
| Model | ROC-AUC | Recall | F1-Score |
|-------|---------|--------|----------|
| Logistic Regression | 0.84 | 0.80 | 0.62 |
| Random Forest | 0.82 | 0.59 | 0.59 |
| XGBoost | 0.83 | 0.63 | 0.59 |

##  Best Model
**Logistic Regression**
- ROC-AUC: 0.84
- Recall: 80%
- Misses only 76 out of 374 churners

##  Key Findings
- Contract type is #1 churn predictor
- 2-year contract customers almost never churn
- Fiber optic users have highest churn risk
- Electronic check payment users churn more
- New customers (low tenure) churn the most

##  Project Structure
telco-churn-prediction/
├── churn_prediction.ipynb
├── README.md
└── requirements.txt

##  How to Run
pip install -r requirements.txt
jupyter notebook churn_prediction.ipynb

##  Requirements
pandas
numpy
scikit-learn
xgboost
imbalanced-learn
matplotlib
seaborn
jupyter

##  Business Impact
- Identified top churn risk factors
- Model saves ~$38,000/month vs no model
- Recommendation: Offer long-term contracts to high-risk customers

##  Author
**Waleed Ahmad**
BSDS Student(2nd Semester) — Riphah International University Faisalabad
[GitHub](https://github.com/mianwaleed155847-hub)
