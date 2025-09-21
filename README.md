# Keras API Project Exercise
This project was created as the final project of the Udemy course "Python for Data Science and Machine Learning Bootcamp" by Jose Portilla.
To use deep learning framework.
All codes were done by me as part of completing the project.

## Overview
Given historical data on loans given out with information on whether or not the borrower defaulted (charge-off), can we build a model that can predict wether or nor a borrower will pay back their loan? This way in the future when we get a new potential customer we can assess whether or not they are likely to pay back the loan. Keep in mind classification metrics when evaluating the performance of your model!
The "loan_status" column contains our label.


## Dataset
We will be using a subset of the LendingClub DataSet obtained from Kaggle: https://www.kaggle.com/wordsforthewise/lending-club
NOTE: Do not download the full zip from the link! We provide a special version of this file that has some extra feature engineering for you to do.

## Features
- loan_amnt	The listed amount of the loan applied for by the borrower. If at some point in time, the credit department reduces the loan amount, then it will be reflected in this value.
- term	The number of payments on the loan. Values are in months and can be either 36 or 60.
- int_rate	Interest Rate on the loan
- installment	The monthly payment owed by the borrower if the loan originates.
- grade	LC assigned loan grade
- sub_grade	LC assigned loan subgrade
- emp_title	The job title supplied by the Borrower when applying for the loan.*
- emp_length	Employment length in years. Possible values are between 0 and 10 where 0 means less than one year and 10 means ten or more years.
- home_ownership	The home ownership status provided by the borrower during registration or obtained from the credit report. Our values are: RENT, OWN, MORTGAGE, OTHER
- annual_inc	The self-reported annual income provided by the borrower during registration.
- verification_status	Indicates if income was verified by LC, not verified, or if the income source was verified
- issue_d	The month which the loan was funded
- loan_status	Current status of the loan
- purpose	A category provided by the borrower for the loan request.
- title	The loan title provided by the borrower
- zip_code	The first 3 numbers of the zip code provided by the borrower in the loan application.
- addr_state	The state provided by the borrower in the loan application
- dti	A ratio calculated using the borrower’s total monthly debt payments on the total debt obligations, excluding mortgage and the requested LC loan, divided by the borrower’s self-reported monthly income.
- earliest_cr_line	The month the borrower's earliest reported credit line was opened
- open_acc	The number of open credit lines in the borrower's credit file.
- pub_rec	Number of derogatory public records
- revol_bal	Total credit revolving balance
- revol_util	Revolving line utilization rate, or the amount of credit the borrower is using relative to all available revolving credit.
- total_acc	The total number of credit lines currently in the borrower's credit file
- initial_list_status	The initial listing status of the loan. Possible values are – W, F
- application_type	Indicates whether the loan is an individual application or a joint application with two co-borrowers
- mort_acc	Number of mortgage accounts.
- pub_rec_bankruptcies	Number of public record bankruptcies

## Tools & Libraries
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- tensorflow
- keras

## Models
Sequential + Dense layers to build neural network

## How to Run
1. Clone the repository
2. Install required libraries: `pip install -r requirements.txt`
