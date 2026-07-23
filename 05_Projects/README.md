# ML Projects

## 1. Customer Churn Prediction
Predicting which telecom customers will leave using Machine Learning.

**Dataset:** Telco Customer Churn — 7,043 customers, 21 features

**Results:**
| Model | F1 Score | Recall |
|-------|----------|--------|
| Decision Tree | 0.617 | 0.807 |
| Logistic Regression | 0.613 | 0.780 |
| XGBoost | 0.599 | 0.679 |
| Random Forest | 0.597 | 0.655 |

**Key Findings:**
- Month-to-month customers churn 3x more than 2-year contract customers
- 60% of churn happens within first 10 months
- Top predictors: TotalCharges, Tenure, MonthlyCharges

**Tech:** Python, Pandas, Scikit-learn, XGBoost, Matplotlib

---

## 2. House Price Prediction
Predicting California house prices using Linear Regression.

**Dataset:** California Housing — 20,640 rows  
**R² Score:** 0.61  
**Tech:** Python, Pandas, Scikit-learn, Matplotlib
