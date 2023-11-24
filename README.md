# FinancialDistressPrediction

Introduction to Financial Distress:
Forecasting financial distress is crucial for assessing a company's financial stability. It aims to differentiate between stable companies and those facing potential financial trouble. This prediction not only aids companies in early risk identification and strategic adjustments but also helps investors gauge financial risks for wiser investment choices. Regulators benefit by gaining timely insights into companies' financial health, enabling effective supervision to uphold financial market stability. Consequently, effective prediction of financial distress has become a focal point in both academic and business realms.

Introduction to problem statement:
We've received four data files: training, testing, sample submissions, and a data dictionary. Using this information, our aim is to predict whether someone might face financial distress in the upcoming two years. The objective here is to construct a model that borrowers can utilize to make informed financial choices. To achieve this, we'll train our model with a substantial amount of labeled data and optimize its accuracy through hyperparameter tuning. Ultimately, we'll use this model to predict outcomes on test data and preserve both the predictions and the model itself.


Column Description :
SeriousDlqin2yrs : 90 days past due delinquency or worse
RevolvingUtilizationOfUnsecuredLines : Total balance on credit cards and personal lines of credit except real estate and no installment debt like car loans divided by the sum of credit limits
age : Age of borrower in years
NumberOfTime30-59DaysPastDueNotWorse : Number of times borrower has been 30-59 days past due but no worse in the last 2 years.
DebtRatio : Monthly debt payments, alimony,living costs divided by monthy gross income
MonthlyIncome : Monthly income
NumberOfOpenCreditLinesAndLoans : Number of Open loans (installment like car loan or mortgage) and Lines of credit (e.g. credit cards)
NumberOfTimes90DaysLate : Number of times borrower has been 90 days or more past due.
NumberRealEstateLoansOrLines : Number of mortgage and real estate loans including home equity lines of credit
NumberOfTime60-89DaysPastDueNotWorse : Number of times borrower has been 60-89 days past due but no worse in the last 2 years.
NumberOfDependents : Number of dependents in family excluding themselves (spouse, children etc.)




