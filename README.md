# Credit-Card-Default-Prediction
# Data set Information
In this dataset, we have 30000 observations that represent distinct credit card clients. Each observation has 25 attributes that contain information on default payments, demographic factors, credit data, history of payment, and bill statements of credit card clients in Taiwan from April 2005 to September 2005.This study reviewed the literature and used the following 25 variables as explanatory variables. We use this dataset to predict whether the credit card holders are defaulters or Non-defaulters. The Dataset and its attributes are described below:

This variables contains personal information of client:
1.)	ID: ID of each client
2.)	LIMIT_BAL: Amount of given credit in NT dollars:it includes both the individual consumer credit and his/her family (supplementary) credit.
●	SEX: Gender (1=male, 2=female)
●	EDUCATION: (1=graduate school, 2=university, 3=high school, 4=others)
●	MARRIAGE: Marital status (1=married, 2=single, 3=others)
●	AGE: Age in years
This variables contains information about the delay of the past payment referred to a specific month:
●	PAY_0: Repayment status in September, 2005 (-2=already paid ,-1=pay duly, 1=payment delay for one month, 2=payment delay for two months, ... 8=payment delay for eight months, 9=payment delay for nine months and above)
●	PAY_2: Repayment status in August, 2005 (scale same as above)
●	PAY_3: Repayment status in July, 2005 (scale same as above)
●	PAY_4: Repayment status in June, 2005 (scale same as above)
●	PAY_5: Repayment status in May, 2005 (scale same as above)
●	PAY_6: Repayment status in April, 2005 (scale same as above)
This is information about bill statement amount of specific month:
●	BILL_AMT1: Amount of bill statement in September, 2005 (NT dollar)
●	BILL_AMT2: Amount of bill statement in August, 2005 (NT dollar)
●	BILL_AMT3: Amount of bill statement in July, 2005 (NT dollar)
●	BILL_AMT4: Amount of bill statement in June, 2005 (NT dollar)
●	BILL_AMT5: Amount of bill statement in May, 2005 (NT dollar)
●	BILL_AMT6: Amount of bill statement in April, 2005 (NT dollar)
The following variables consider the amount of previous payment in a specific month:
●	PAY_AMT1: Amount of payment in September, 2005 (NT dollar)
●	PAY_AMT2: Amount of payment in August, 2005 (NT dollar)
●	PAY_AMT3: Amount of payment in July, 2005 (NT dollar)
●	PAY_AMT4: Amount of payment in June, 2005 (NT dollar)
●	PAY_AMT5: Amount of payment in May, 2005 (NT dollar)
●	PAY_AMT6: Amount of payment in April, 2005 (NT dollar)
This is our Target variable which one to be predicted:
●	default payment next month: The target variable indicating default of payment (1=default, 0=non-default)
