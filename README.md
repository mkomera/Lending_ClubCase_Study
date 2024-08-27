# CaseStudy-LendingClub
> This club case study aims to identify risky loan applicants using exploratory data analysis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The task is to identify patterns in loan default behaviour using EDA. Two risks are involved in loan approval:
    - Loss of business if a repayable loan is denied.
    - Financial loss if a defaulting loan is approved

- We have performed an exploratory data analysis to derive insights from the lending club loan data set.
- The steps used in EDA are:
    - Data cleaning
    - Univariate Analysis
    - Segmented univariate analysis
    - Bivariate Analysis


## Conclusions
- The following factors effect the probability of defaulting a loan:
    - Interest Rates
    - Loan Amount
    - Credit Grades
    - Home Ownership
    - Public derogatory records
- Higher interest rates are strongly associated with higher default rates, irrespective of loan tenure and verification status.
- Borrowers with high revolving credit utilization face higher interest rates and tend to default more frequently.
- Larger loan amounts, particularly in small business and home loan categories, are associated with higher default rates.
- Lower credit grades (F and G) are associated with higher default rates and larger loan amounts. Borrowers in these grades have higher public derogatory records
- Borrowers with mortgage ownership have higher incomes but also higher loan amounts, which correlates with higher default rates.
- Borrowers with 4 public derogatory records are predominantly in the mortgage ownership category and "Not Verified" status.


    
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - 3.12
- pandas
- numpy
- Matplotlib
- SeaBorn





## Contributors
- Maruthi Komera
- Shriya Magadal
