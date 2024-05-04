# Lending Club Case Study

**Lending Club** is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

![image](https://github.com/subhomoyganguli/Lending_Club_Case_Study/assets/67957101/7f54e0b2-fb29-416c-9e2e-06caf68a7f38)

## Table of Contents
* [Project Description](#project-description)
* [Methodologies Used](#methodologies-used)
* [Technologies Used](#technologies-used)
* [Recommendations](#recommendations)
* [Contributors](#Contributors)

## Project Description
Lending Club is a **consumer finance company** which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. **Two types of risks** are associated with the bank’s decision:
 
 * If the applicant is **likely to repay the loan**, then not approving the loan results in a **loss of business** to the company
 * If the applicant is **not likely to repay the loan**, i.e. he/she is likely to default, then approving the loan may lead to a **financial loss** for the company

The data contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. 

In this case study, we will use EDA to understand how **consumer attributes** and **loan attributes** influence the tendency of default.

![Loan_image](https://github.com/subhomoyganguli/Lending_Club_Case_Study/assets/67957101/1b606720-fb24-4ae2-a2e3-d4888bf44600)

When a person applies for a loan, there are **two types of decisions** that could be taken by the company:

* **Loan accepted**: If the company approves the loan, there are 3 possible scenarios described below:

  * **Fully paid**: Applicant has fully paid the loan (the principal and the interest rate)
  * **Current**: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
  * **Charged-off**: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has **defaulted** on the loan 

* **Loan rejected**: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

## Methodologies Used
* Data cleaning
* Exploratory Data Analysis(EDA)
* Data Visualization 

## Technologies Used
- Pandas
- Matplotlib
- Seaborn
- Numpy

## Recommendations

1) Lending Club (LC) should keep on approving more loans of A or B grade than other grades
2) LC should be careful before lending to small businesses as they have high default rate
3) LC should avoid approving borrowers with prior public record or incidences of delinquency
4) LC should charge higher rates to borrower with 20+ debt to income ratio as they are more likely to default
5) LC should prefer 3 years loan over 5 years, as they are less likely to default

# Contributors
* Subhomoy Ganguli
* Swati Gupta Jain
