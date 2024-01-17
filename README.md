# Project Name
> The Case Study is to analyse the Customer Finance Company applicants data by doing a EDA on all the customer attributes, loan attributes and to come up with driving factors which influence the Company's Loan Lending Risks.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Lending Club Case Study.
- Business Use case
	- Consumer Finance Company (CFC) specialises in lending various types of loans to urban customers. When the company receives a loan application,the company has to make a decision for loan approval based on the applicant’s profile. Borrowers who default cause the largest amount of loss to the lenders. One has to identify these risky loan applications, then such loans can be reduced by cutting down the credit loss. The company wants to understand the driving factors behind the loan default.
- What is the business probem that your project is trying to solve?
	- Loan Dataset.csv - (https://github.com/GopalS1208/gopalsprojects/blob/master/lcc_loan.csv)
	- Data Dictionary - (https://github.com/GopalS1208/gopalsprojects/blob/master/Data_Dictionary.xlsx)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Univariate Analysis
- The above analysis with respect to "Charged-OFF" loans for each variable suggests the following. There is a more probability of defaulting when: 
	- Applicants who are purchasing loans by being in "RENT" house.
	- Applicants who are having employment length period of >=10 years(Basically 10+ years, remember that we have imputed all the 10+ years as 10 years).
	- Applicants who take loan to consolidate & clear off Other Loans (Debt Consolidation, & then Credit Card).
	- Applicants who have an income of range around 31K-51K (56K is 50 percentile).
	- Applicants who have dti is between 12-18 (13.58 is 50 percentile).
	- Applicants who are in Grade-'B'. And specifically Sub Grade - 'B5' level.
	- Applicants whose loan is sanctioned for interest rate - 13-17%.
	- Applicants whose Funding amount by Investor is in range of 5K-10K.
	- Applicants whose Loan amount by Investor is in range of 5K-10K.
	- Applicants whose installments are between 145-274.
- Bivariate Analysis
	- On Annual income
		- Applicants of all the Annual Income groups have "Charged Off" more than "Fully Paid" for all the Loan Amounts.
		- Applicants taking loan for 'Home Improvement' and have income of 60k -70k.
		- Applicants whose home ownership is 'MORTGAGE and have income of 60-70k. But in all the Home Ownership categories we can find "Fully Paid" customers are more than "Charged Off".
		- Applicants who receive interest at the rate of "21-24%" and have an income of 70k-80k.
	- On Loan Amount
		- For all the Interest Rates, Home Ownership categories, the probability of more Loan Amounts getting "Charged Off" is more than "Fully Paid".
		- In Debt Consolidation, Small Business & Credit Card, probability of Loan Amounts getting "Charged Off" is more.
		- For all the Employee Lengths the probability of Loan amounts getting "Charged Off" is less than "Fully Paid".
		- Irrespective of Verification Status, the Loan amount gets "Charged Off" when compared to "Fully Paid".
		- For Grade A & G, "Fully Paid" Loan Amounts are more than "Charged Off" Loan Amounts. For Other Grades (B, C, D, E, F) it is otherwise.
		- In all the months & years, the "Charged Off" Loan Amounts are more than "Fully Paid".

## Technologies Used
- Pandas
- NumPy
- MatPlotLib
- Seaborn

## Acknowledgements
This project was developed as part of IIIT B UpGrad Artificial Intelligence & Machine Learning Programme. This is a case study with respect to Exploratory Data Analysis.


## Contact
Created by [GopalS1208] - feel free to contact me!