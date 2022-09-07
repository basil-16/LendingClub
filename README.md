# Lending Club case study
> We will develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.
> The Lending Club is a company which provides different types of loans online at very less interest rates. If the company is able to identify the risky applicants before sanction of loan, then they can save a huge sum of money.
> The aim of this case study is to use EDA techniques in order to find them by understanding the driving factors responsible for defaulting. The company can use this knowledge for its portfolio and risk assessment.

## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
          * If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.
          * If the applicant is not likely to repay the loan then approving the loan may lead to a financial loss for the company. 
- In this case study, we use EDA to understand how consumer attributes and loan attributes influence the tendency of defaulting a loan and we try to identify those.
- We have been given information about past loan applicants and whether they ‘defaulted’ or not. We identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending at a higher interest rate, etc.
- The given dataset contains the complete loan data for all loans issued through the time period 2007 to 2011 and contains all the details like customer ID, loan ID, annual income, purpose of loan, interest rate etc.

## Conclusions
- After loading the datatset into our environment we explored the data and cleaned it, removed all the rows and columns which werent helpful in our analysis and performed univariate, bivariate and multi variate analysis
- Having being done all the analysis we ended up with the following feauturs which best suited for our business goals
1. Loan Amount
2. Interest Rate
3. Annual Income
4. Term
5. Revol_util(%)
6. Grade
7. Purpose

## Technologies Used
- Python 
- Numpy library 
- Pandas library 
- Matplotlib library 
- Seaborn library 
- Anaconda navigator

## Group Information:
### Group facilitator - Vernon Basil Msacarenhas; github username - @basil-16
### Group member - Anand Joshi github username - @abj-16
