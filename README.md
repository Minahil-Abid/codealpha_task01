# Credit Scoring Model

This project predicts an individual's creditworthiness based on financial and credit history data. By applying classification algorithms such as Logistic Regression, Decision Tree, and Random Forest, it demonstrates how machine learning can assist in risk assessment and loan decision-making for financial institutions.

## Features
- Performed Exploratory Data Analysis (EDA) to understand distributions and correlations
- Cleaned and preprocessed data (handled outliers, missing values, and categorical encoding)
- Trained multiple classification models:
  - Logistic Regression
  - Decision Tree
  - Random Forest
- Compared model performance using Accuracy, Precision, Recall, F1-score, and ROC–AUC
- Tuned hyperparameters to improve model robustness
- Interpreted feature importance and key predictors of default risk

## Dataset
- **Source:** Public credit scoring dataset (simulated loan applicant data)
- **Features:** `person_income`, `person_emp_length`, `loan_amnt`, `loan_int_rate`, `loan_percent_income`,
`cb_person_default_on_file`, `cb_person_cred_hist_length`, and `encoded categorical variables`.
- **Target:** `loan_status` → (1 = default, 0 = non-default)

## Models & Results

| Model | Accuracy | Precision | Recall | F1-score | ROC–AUC |
|--------|-----------|------------|----------|-----------|-----------|
| Logistic Regression | 0.7846 | 0.5010 | 0.7680 | 0.6064 | 0.8523 |
| Decision Tree | 0.8947 | 0.7540 | 0.7606 | 0.7573 | 0.8461 |
| Tuned Decision Tree | 0.8895 | 0.7401 | 0.7526 | 0.7463 | 0.9008 |
| **Random Forest** | **0.8971** | **0.7556** | **0.7739** | **0.7646** | **0.9253** |

✅ **Random Forest** achieved the best overall performance, with the highest ROC–AUC and balanced precision–recall, making it the most reliable model for predicting loan default risk.


## Run the Project
```bash
git clone https://github.com/Minahil-Abid/codealpha_task01.git
cd codealpha_task01
pip install -r requirements.txt
jupyter notebook codealpha_task01.ipynb
```

## License

MIT License – free to use and share.

