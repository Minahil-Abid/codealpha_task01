# Credit Scoring Model

This project predicts an individual's creditworthiness using financial data such as income, debt, and credit history.

## Objective
To build a machine learning model that classifies individuals as likely to default or not.

## Models Used
- Logistic Regression
- Decision Tree
- Random Forest

## Steps
1. Data cleaning and preprocessing  
2. Feature encoding and scaling  
3. Model training and evaluation  
4. Performance comparison using Accuracy, Precision, Recall, F1-score, and ROC–AUC

## Results Summary

| Model | Accuracy | Recall | F1 | ROC–AUC |
|--------|-----------|--------|-----|----------|
| Logistic Regression | 0.78 | 0.77 | 0.61 | 0.80 |
| Decision Tree | 0.89 | 0.75 | 0.75 | 0.90 |
| Random Forest | 0.90 | 0.77 | 0.76 | 0.93 |

✅ Best Model: Random Forest (AUC = 0.93)

## Requirements
```bash
pip install -r requirements.txt
