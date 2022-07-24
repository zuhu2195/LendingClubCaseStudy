# Lending Club Case Study
> Given Data Set for loan applicants which contains data about whether they ‘defaulted’ or not, our aim is to determine what all factors affect the loan defaulting.
Any Loan can either be accpeted or rejected. If it is accepted then there are three possibilities. First being it is fully paid, Second being it is in current payment process, and third being it has been Charged Off, meaning applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan. Our Aim is to identify what all factors affect the third case.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 
- Understanding of risk analytics in banking and financial services and understanding how data is used to minimise the risk of losing money while lending to customers is very crucial.
- If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study. In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment. 
- The dataset contains the complete loan data for all loans issued through the time period 2007 t0 2011 for the company.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Loan is usually borrowed in 2.5k intervals by most number of people, spikes at 2.5k intervals say so.
- People whose term is 36 months are more likely to default than those who have term as 60 months.
- People who are in mortgage agreement or in rent are more likely to default than people who have own houses with maximum number of defaults coming from people who live in rented homes.
- Not verified people are more likely to default than verified and verified ones are more likely to default than ones whose source of income is verified
- Grades B,C and D account for most number of defaults.
- Mortgage-Verified and Rent-Not Verified are the most defaulting categories, though Mortgage-Verified is a peculiar category, indicating that it might be possible that verification is not done properly for Mortgage category of customers.
- People who are staying in rented homes and have grades B, C and D are more likely to default. Same applies for people staying in mortgage homes.
- The people who are Charged Off have least overall annual income.
- The average interest rate of Charged Off customers is more than that off Fully Paid customers(ignoring the Current Segment). Therefore it can be said that high interest rate loans are more likely to default. The same trend can be seen for monthly installment as well, i.e Charged Off people tend to have higher monthly installments.
- We see that as loan_amnt increases, the monthly installment also increases, and people often tend to take hefty loans and fail to pay their monthly installment and default on loan.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Jupyter Notebook(Anaconda 3) - version 6.4.8
- Python3 - version 3.10
- numpy - version 1.21.5
- pandas - version 1.4.2
- matplotlib - version 3.5.1
- seaborn - version 0.11.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by UpGrad EDA course
- References - google.com, quora.com, stackoverflow.com


## Contact
Created by zuhu2195 - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
