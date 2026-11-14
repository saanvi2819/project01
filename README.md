# Credit Card Fraud Detection

Finds fraudulent credit card transactions and compares two models.

## Dataset
Kaggle: Credit Card Fraud Detection. 283,726 transactions after
removing 1,081 duplicates. Only about 0.17% are fraud.

## Models
1. Random Forest
2. Logistic Regression (with scaling)

## Results (fraud class)
| Model | Precision | Recall |
|---|---|---|
| Random Forest | 0.97 | 0.71 |
| Logistic Regression | 0.06 | 0.87 |

## Key learning
Accuracy is misleading here, because fraud is very rare. Random Forest
gives very few false alarms but misses some fraud. Logistic Regression
catches more fraud but creates many false alarms.

## Tools
Python, pandas, scikit-learn, matplotlib, Google Colab
