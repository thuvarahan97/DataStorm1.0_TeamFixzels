# DataStorm1.0_TeamFixzels
Data Storm 1.0 - Business Problem - Team Fixzels  
  
* Use case definition - A default can occur when a borrower is unable to make timely payments, misses payments, or avoids/stops making payments  
* Business problem - As a result of credit card default, bank accounts close, non-performing loans and bad debts get written-off. Therefore, the bank needs help in predicting and preventing credit card default to improve their Bottom line.  
* Key Objective - Finding out priority clients who have the highest risk of credit card default.  
  
###### File descriptions  
* credit_card_default_train.csv - the training set  
* credit_card_default_test.csv - the test set  
  
###### Data fields  
* Client_ID - customer id  
* Balance_Limit_V1 - credit card limit given  
* Gender - F = female, M = male  
* EDUCATION_STATUS - education status of the customer  
* MARITAL_STATUS - 1= single, 2 = married, 3 = others  
* AGE - Age of customer  
* PAY_JULY,PAY_AUG,PAY_SEP,PAY_OCT,PAY_NOV,PAY_DEC - "History of past payments" (-2 = paid two months in advance), (-1 = paid one month in advance), (0 = payment due current month), ( 1 = payment delay for one month), (2 = payment delay for two months), (8 = payment delay for eight months), (9 = payment delay for nine months and above)  
* DUE_AMT_JULY, DUE_AMT_AUG, DUE_AMT_SEP, DUE_AMT_OCT, DUE_AMT_NOV, DUE_AMT_DEC - "Due amount of bill statements"  
* PAID_AMT_JULY, PAID_AMT_AUG, PAID_AMT_SEP, PAID_AMT_OCT, PAID_AMT_NOV, PAID_AMT_DEC - "Amount paid in each month"  
* NEXT_MONTH_DEFAULT - target variable - Predict if next month payment is a default payment or not  
  
Data Storm 1.0 Competition Link : https://www.kaggle.com/c/data-storm-10/
