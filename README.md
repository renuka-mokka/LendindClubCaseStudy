# Lending Club Case Study using EDA
> The large consumer finance company wants to understand the driving factors (or driver variables) behind loan default, i.e., the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 
This project is to help find the driving factors of loan default using past loan data of the company and help them in providing insights based on which they can take their decision to reduce the risk and increase the revenue.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information
- The large finance company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 
- ### Background
- Demonstration of EDA concepts to understand data, clean data, enhance the data, derive key insights and patterns from it and provide recommendations to business to help them in their risk analytics. If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
- ### Business Objective:
- We need to help a consumer finance company which specialises in lending various types of loans to urban customers in their risk analytics. This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures .
The input data contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending ( to risky applicants) at a higher interest rate, etc.
### Dataset
Past Loan data which contains the complete loan data for all loans issued through the time period 2007 t0 2011 is been given as input for analysis.

## Conclusions
- From the analysis of input data using EDA, we got the below key insights.
  
  1. Grade is a clear driving factor of loan default.The lower the grade -> the higher chances of getting charged off/loan default. G grade is most probable of defaulter and A grade is less probable to default 
   the loan.
  2. Employment Length having missing values has more chances to default the loan where as employees having 10+ years of working experience have considerbaly less probable to default the loan. So, it's     
  recommended to approve the loan for people who are working in stable jobs since considerably a good amount of time.
  3. The Interest rate shows a pattern where high interest rate -> higher chances of Charged Off. i.e., people who are willing to go for high interest rates, have more probability of being defaulted the loan.
  4. Loan default cases are attributable to Toal Principal received, Outstanding principle and last payment. A higher princple could imply ,higher risk of default.

## Technologies Used
- Anaconda Navigator
- Jupyter Notebook
- Git 2.41.0.3
  



## Contact
Created by [@renuka-mokka] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
