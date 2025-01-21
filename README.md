
# Lending Club Case Study

## Problem Statement

You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

    (1) If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
    (2) If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

## Constraints
When a person applies for a loan, there are two types of decisions that could be taken by the company: 
    
    1 Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:     
        - Fully paid: Applicant has fully paid the loan (the principal and the interest rate) 
        - Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'. 
        - Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan
    
    2 Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

## Objectives
- Identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

## Steps
Step 1: Data Cleaning 
    
    (a) To Check if there is any headers / footers or summary details rows are there and delete it 
    (b) Delete the Uneccessary Columns
Step 2: Data Conversion

Step 3: Dropping / Imputing the rows

Step 4: Derived Columns

Step 5: Exploratory Data Analysis 

    (a) Univariate Analysis 
    (b) Bivariate Analysis 
    (c) Segmented Univariate Analysis

## Technologies Used
- Python - Version 3.12.0
- Numpy - Version 2.2
- Pandas - Version 2.2.3
- Matplotlib - Version 3.10.0
- Seaborn - Version 0.12.0

## Summary
Following files has been included as a part of solutions:

    1. READ.me file for Problem discriptions
    2. Lending_Club_Case_Study.ipynb File For Performing EDA Process
    3. Leanding_Club_Case_Study.pdf About the Analysis And Conclusions of EDA Performed
    4. loan.zip File




