# Lending Club Case Study

## Table of Contents
* [General Info](#general-information)
* [Dataset](#dataset)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
The purpose of this project was to identify the driving factors behind defaults of consumer loans.  Specifcally, the analysis was focused on how consumer attributes and loan attributes influence the outcomes of loans.  By understanding the risk drivers behind loan defaults, the loan issuer can reduce the impact or exposure of bad loans.

## Dataset
The analyzed dataset was supplied as part of the UpGrad AI&ML programme.  The dataset can be found [here](https://learn.upgrad.com/course/2367/segment/19491/125703/384601/2002860).

Summary of the dataset:
- Loan issue period: 2007 - 2011
- Number of fully paid loans: 32950
- Number of defaulted loans (charged off): 5627

## Methodology
The supplied dataset was cleaned up and derived metrics were introduced.  Loans that have not been completed have been ommited from the analysis.  Univariate and bivariate analysis approached were utilized to find the driving factors behind loan defaults.  The data was visualized using Matplotlib and Seaborn.

## Conclusions
The following strong driving factors behind loan defaults have been identified:
- Loans issued for small business purposes
- Loans with high interest rates above approximately 19%
- Assigned LC loan grades: D, E, F, G
- Loan terms of 60 months
- Loans to applicants with annual incomes of $40k or less
- Loan amounts above $ 25000; specifically:
- Large loans (more than $10k) issued to applicants with home
ownership status of ‘other’
- Certain loans to issued applicants with annual incomes of more than

## Technologies Used
The following Python libraries were utilized:
- Pandas
- Statistics
- Numpy
- Seaborn
- Matplotlib

## Contact
Created by [@gertagenbag]
