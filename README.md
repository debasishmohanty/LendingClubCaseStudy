# Lending Club Case Study
> This project focuses on analyzing historical loan data from Lending Club, a consumer finance company, to identify patterns associated with loan defaults. By leveraging Exploratory Data Analysis (EDA), the aim is to help the company minimize financial losses by identifying high-risk applicants and understanding the factors that drive defaults.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- This project involves analyzing the loan dataset provided by Lending Club, a consumer finance company that specializes in various types of loans.

Background
- Lending Club facilitates personal and business loans through an online platform. While it allows easy access to loans, lending to risky applicants can result in significant credit loss. Borrowers who default (fail to repay loans) pose a major challenge for the company.

Business Problem
- The aim of this project is to identify the driving factors behind loan defaults using Exploratory Data Analysis (EDA). Understanding these patterns will help the company:

- Minimize credit loss by reducing loans to risky applicants.
- Optimize interest rates and loan amounts for high-risk customers.

Dataset
- The dataset contains historical data on loans issued from 2007 to 2011. The variables include customer demographics, loan attributes, and repayment history. Customers who failed to pay their loans (labeled as Charged-Off) are considered defaulters.

## Conclusions
Key insights derived from the dataset:

1- Annual Income:

- Borrowers with lower annual incomes are more likely to default.

2- Debt-to-Income Ratio (DTI):

- Higher DTI values indicate a greater likelihood of defaulting.
Interest Rate:

3- Defaulters are generally charged a higher interest rate, likely due to their higher risk profiles.

4- Verification Status:

- Borrowers whose incomes are verified show a higher tendency to default, possibly due to tighter scrutiny and reporting.

5- Sub-Grade Analysis:

- Borrowers in lower-risk sub-grades (e.g., A1) default less.
- High-risk sub-grades (e.g., F5) are associated with significantly higher default rates.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python - version 3.12.4
- matplotlib: version 3.8.4
- seaborn - version 0.13.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This project was inspired by real-world business scenarios in risk analytics and the    financial services domain.
- Special thanks to Lending Club for providing the dataset used in this analysis


## Contact
Created by [@debasishmohanty] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->