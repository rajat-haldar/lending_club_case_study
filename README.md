# Project Name
> Lending Club Case Study with Loan related data


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

### Project Information
- The assigment is based on EDA methodolgy that uses the lending club data set to analyse whether a loan will be defaulted or not.

### Project Background
- This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. Like most other lending companies, lending loans to risky applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.

### Project Statement
- The Lending company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment.

### Data Set
- One CSV file 'loan.csv' conataing loan data excluding rejected loan application is used for the case study.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Major Driving factor which can be used to predict the chance of defaulting and avoiding Credit Loss:
  1. DTI
  2. Grades
  3. Verification Status
  4. Annual income
  5. Pub_rec_bankruptcies
- Other considerations for 'defaults' :
  1. Burrowers from large urban cities like california, new york, texas, florida etc.
  2. Burrowers having annual income in the range 50000-100000.
  3. Burrowers having Public Recorded Bankruptcy.
  4. Burrowers with least grades like E,F,G which indicates high risk.
  5. Burrowers with very high Debt to Income value.
  6. Burrowers with working experience 10+ years.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas - version 1.5.3
- NumPy - version 1.23.5
- Seaborn - version 0.12.2
- MatplotLib - version 3.7.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by upGrad and IIIT-B
- This project was based on [this tutorial](https://www.lendingclub.com/).


## Contact
Created by [@rajat-haldar] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->