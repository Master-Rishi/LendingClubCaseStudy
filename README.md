## Lending Club Case Study

### Project Description:
You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

The data given contains the information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

In this case study, we used EDA to understand how consumer attributes and loan attributes influence the tendency of default.

When a person applies for a loan, there are two types of decisions that could be taken by the company:

Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

**Fully paid:** Applicant has fully paid the loan (the principal and the interest rate)

**Current:** Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

**Charged-off**: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan

**Loan rejected:** The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset).


## Table of Contents
* [General Info](#general-information)
* [Business Objective](#business-objective)
* [Methodology Used](#methodology-used)
* [Technologies Used](#technologies-used)
* [Recommendations](#recommendations)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Lending Club is a marketplace for personal loans that matches borrowers
who are seeking a loan with investors looking to lend money and make 
returns.

- For lending companies, lending loans to risky applicants is the largest source of financial loss. The credit loss is the amount of money lost by the lender when the borrower defaults to a loan payment. In such a case, the concerned person is labelled as charged-of and defaulters.

- If one is able to identify such risky applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the primary objective of this case study.

- You can find the data at- "loan.csv" within this repo.

- Refer Data dictionary- "Data_Dictionary.xlsx" for in depth understanding of the dataset.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Business Objective
- Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders.

- Objective is to identify the risky loan applicants at the time of loan application so that such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

- In other words, to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment. And thus minimise the risk of losing money while lending to customers.

## Methodology Used
**1.Data Understanding**

**2.Data Cleaning & Manipulation**

**3.Datatype Conversion**

**4.Data Analysis**

    a.Univariate Analysis
    b.Segmented Univariate Analysis
    c.Bivariate Analysis
**5.Presentation & Recommendations**


## Technologies Used
- Python - version 3.9
- Jupyter Notebook - version 6.4.5
- Pandas - version 1.4.2
- Numpy - version 1.21.5
- Seaborn - version 0.11.2
- Matplotlib - version 3.5.1
- Anaconda - version 2.14 

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Recommendations
1. Chances of loan being charged off is high when loan amount is high therefore Lending club should consider accepting loans of  lower amount.                    

2. Lending Club should accept more loans of grade A and B and should be cautious of loans falling in grades E,F and G.

3. Lending Club should accept more loans from applicants whose annual income is greater than 100k as their probability of charge off is less.

4. Lending Club should accept more loans for term of 36 months as the of charged off loans is less and the number of loan applicants are more  for this term.

5. Year end months especially 'December' are quite critical as most of the loans are either fully paid or charged off at that time.

6. Lending Club should consider accepting more loans where interest rate is less than 10% as their probability of charge off is minimum.

7. Lending Club should do extra scrutiny for the applicants belonging to CA state, as tendency to default is high.

8. Lending Club should accept more loans for the purpose of Weddings, major purchase, car and credit card.

9. Lending Club should check thoroughly when purpose is debt consolidation as it has high tendency to default.

9. Lending Club should consider accepting more loans from people who owns a house.

10. Lending Club business is increasing every year as more number of loans are getting accepted as well as more  loans are getting                    charged off therefore they should expand their business more as demand for loans is high.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Acknowledgements
- The project reference course curriculam from Upgrad.


## Contact
Created by [@Master-Rishi] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
