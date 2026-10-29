# Profit vs Fairness in Automated Loan Approval

## About this project
This project explores a key question:

When a loan approval system is optimized for profit, does fairness get affected in the process?

I wanted to look beyond model performance and understand how these systems make mistakes, which groups may be affected differently, and what we can learn from those patterns. 

## What I analyzed
- How applicant features relate to credit risk
- How logistic Regression and Random Forest compare
- Whether model errors differ across demographic and financial groups
- How changing the decision threshold affects false positives and false negatives
- Which features influence model predictions

## What I did
- Cleaned and explored the dataset
- Performed exploratory data analysis (univariate + bivariate)
- Compared credit risk across different groups
- Identified patterns that may indicate imbalance or bias
- Trained and tune classification models
- Evaluated models using precision, recall, F1 score and ROC-AUC
- Compared error rates across different groups
- Used SHAP and permutation importance to understand model behavior

## Approach
Instead of only asking “what does the data show?”, the analysis focuses on:
- whether real-world decision systems could be fair
- whether optimization for accuracy/profit can introduce bias
- where disparities appear across groups

## Key Findings

- Logistic Regression achieved an F1 score of 0.658 and ROC-AUC of 0.81
- Changing the decision threshold affected the balance between false positives and false negatives.
- Error rates differed across demographic and financial groups, although some groups had small sample sizes.
- Checking-account status, credit history and loan duration were among the influential features.

## Conclusion 

Good model performance doesn't automatically mean fair decisions. The results showed differences in model errors across groups, which need further investigation before considering real-world use. 

## Tools used
- Python
- Pandas & NumPy
- Matplotlib / Seaborn
- Google Colab
- Scikit-learn
- SHAP

## Motivation
Loan approval systems affect real people, not just data points.  

I wanted to explore how model performance, the features used and the decisions made by these systems can have ethical implications.
