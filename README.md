# Loans in US exploration
## by Ivan Ramos 

## Dataset

The dataset contains approximately 114,000 entries of loans with 81 variables, only a subset of those variables were collected for simplicity:
- Loan Identifier
- Creation date
- Term
- Borrower rate
- Borrower APR rate
- Estimated return
- Prosper rating
- Prosper score
- Employment status
- Is borrower home owner
- Date of first recorded credit line
- Delinquencies in last 7 years
- Bank card utilization
- Income range
- Previous prosper loans
- Loan amount

Data was subject of cleaning process before start investigation. Most common clean operations included removal of duplicates, discard entries without prosper scores, change of types to categories/dates when appropriate.

## Summary of findings

Principal outcome from investigation is that given scores by Prosper LLC for each loan are the most deterministic factors for interest ratings along with loan amount and income range.

Variables like delinquencies, bank card utilization or credit history with other banks didn´t influenced enough to be considered as key factors.

Estimated return is associated to the risk of the loan, the more risk the more return an investor gets.

Mode of interest rate distribution was 32%, which we can see applied for High Risk loans only as a standard rate.

As I wanted to create a short concise presentation, I just focused on main factors with evident inference on interest rates. More details of exploration of other variables can be found of course on the notebook report.


## Feedback

My girlfriend contributed with her appreciable feedback. Zafiro is not really used to investment concepts, however she could understand purpose for each depicted chart. I only had to change text sizes on some charts, explain better variables as I introduced them during slides and provide quick example as I explain a concept.
She also mentioned  she would like Interest distribution to get painted in different colors to associate cold colors with low rates and hot with high ones. I explained her data/ink ratio and why that is not a good idea :).


## Resources

Matplot lib 2.x by Example,  Allen Chi Shing Yu, Claire Yik Lok Chung - Pack publish

[Seaborn Documentation](https://seaborn.pydata.org/)

[Pandas sheet](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf)

[Matplotlib docs](https://matplotlib.org/api/markers_api.html)

Udacity Mentor Support, Thank you guys!!! special thanks to Miles C.
