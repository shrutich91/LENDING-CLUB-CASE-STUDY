#  LENDING-CLUB-CASE-STUDY
#  Project Name
When the lending club company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
- If the applicant is not likely to repay the loan, i.e., he/she is likely to default, then approving the loan may lead to a financial loss for the company
- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

The company wants to understand the driving factors (or driver variables) behind loan default, i.e., the variables which are strong indicators of default.  The company can utilize this knowledge for its portfolio and risk assessment. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- General Information
This project deals with doing exploratory data analysis and identify driving factors behind default.Identifying The variables which are strong indicators of default.  The company can utilize this knowledge for its portfolio and risk assessment. 

- Background
Exploratory data analysis need to be performed 

- Dataset
https://github.com/shrutich91/LENDING-CLUB-CASE-STUDY/blob/main/loan.csv

- Data Description
https://github.com/shrutich91/LENDING-CLUB-CASE-STUDY/blob/main/data_dictionary.xlsx


## Conclusions
<!-- ToDO after ppt -->
- 1. Loan Term: chance of charged off is double when term is 60 months
- 2. Purpose is  small business, higher chance of charged off
- 3. As grade increases (A to B to C and so on), higher chance of charged off . Within a grade as Subgrade increases (A1 to A5 ), higher chance of charged off. Chance of charged off is very high if subgrade is F5
- 4. Interest rate -  As interest rate increases, % charged off increases
- 5. Public record Bankruptcy is a driver and as this increases, chance of charged off increases
- 6. Annual Income: As Income increases, charged off% decreases, specifically higher chance of charged off if Income less than 60 k
- 7. Loan amount : Higher loan amount increases chance of charge off
- 8. Emp title : when emp title is not present, they have higher chance of charged of
 Analysis on multiple features
- 9. If loan applicant falls in Grade G and lesser annual Income chance of charged off  is high
- 10. When purpose is home improvement/major purpose/moving/small business and income is lower  then higher chance of charged of


## Technologies Used
- Pandas - 1.3.4 
- Numpy - 1.20.3 
- Seaborn - 0.11.2
- Matplotlib - 3.4.3
- WordCloud - 1.8.1
- Plotly - 5.7.0

## Acknowledgements
Give credit here.
- This project has been prepared from learning from EDA at https://www.learn.upgrad.com


## Contact
Created by [@Jeyashree/Shruti] - feel free to contact me!

