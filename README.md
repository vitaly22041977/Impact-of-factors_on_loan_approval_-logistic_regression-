# Impact-of-factors_on_loan_approval_-logistic_regression-

Impact of factors on loan approval: logistic regression results based on Kaggle sample data: https://www.kaggle.com/datasets/taweilo/loan-approval-classification-data/data?select=loan_data.csv

A logistic regression was built to predict the probability of loan approval (loan_status) based on 36,000 loan applications.

Key findings:
The most significant factors:

Positive impact:
Housing rental (RENT: +0.90) and other types of tenure (OTHER: +0.86).

Interest rate (loan_int_rate: +0.30 per unit).

Negative impact:
Housing ownership (OWN: -1.10).
Applicant income (person_income: slightly negative effect).

Insignificant factors:
Gender (male), level of education (Bachelor, Master, etc.) and credit score (credit_score) do not have a statistically significant effect (p-value > 0.05).

Interpretation of probabilities:
Renters are ~20% more likely to be approved than homeowners (all other things being equal).

Each 1% increase in the interest rate increases the chances of approval by ~25% (relative change).

Model quality:
Pseudo R² = 0.247 — the model explains 24.7% of the data variation.

All significant coefficients have the expected signs (common sense check).
