# customer-churn-prediction
Customer churn prediction using XGBoost and GridSearch - 86% Recall



## Overview
Machine learning model to predict customer churn 
for a telecom company using XGBoost and GridSearch optimization.

## Results
| Model | Accuracy | Recall |
|---|---|---|
| Random Forest | 84% | 67% |
| XGBoost | 85% | 75% |
| XGBoost + GridSearch | 81% | 86% |

**Final model : 86% Recall — detects 86 churners out of 100**

## Dataset
- IBM Telco Customer Churn
- 7043 customers, 47 features

## Key Findings
- New customers churn the most (low tenure)
- High monthly charges increase churn risk
- Senior customers (+64) churn more than younger ones
- Month-to-Month contracts have highest churn rate

## Tech Stack
- Python, Pandas, Seaborn, Matplotlib
- Scikit-learn, XGBoost, Imbalanced-learn
- Google Colab

## Author
Data Scientist | Open to Remote Work Worldwide
