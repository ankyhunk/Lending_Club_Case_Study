# EDA - Lending Club Case Study
> Lending Club is a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
* If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
* If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 
- Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 
- If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
- In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 

## Conclusions
The Probability of an Applicant defaulting on the Loan is high when -
- They don't own their home (Mortgage or Rent) and have High Annual Income (Range 60K to 70K).
- The Loans are disbursed with Interest Rates between 9% to 17%.
- They are having Annual Income between 35K to 70K and availing Loan for Debt Consolidation.
- They have >10 years of Experience and Loan Amount is >10K with Interest Rate > 10%.
The Indicators for Loan defaulters are -
- Annual Income, Home Ownership, Purpose of Loan, Loan Amount, Interest Rate

## Technologies Used
- Python
- Jupyter Notebook
- Libraries
    - Numpy - version 1.24.0
    - Pandas - version 1.5.2
    - Matplotlib - version 3.6.2
    - Seaborn - version 0.12.1

## Acknowledgements
Reference
- https://github.com/
- https://stackoverflow.com/