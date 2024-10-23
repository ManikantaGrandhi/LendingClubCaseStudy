# Project Name
> Leading club case study.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.
In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.
If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
In other words, the company wants to understand the driving factors (or driver variables) behind loan default, ie . the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.


## Conclusions

Summary of data
-The annual income of most of the loan applicants is between 40, 000 - 75, 000 USD
-The loan amount of most of the loan applicants is between 5, 000 - 15, 000 
-The funded amount of most of the loan applicants is between 5, 000 - 14, 000 USD
-The funded amount by investor for most of the loan applicants is between 5, 000 - 14, 000 USD
-The interest rate on the loan is between 9% - 14%
-The monthly instalment amount on the loan is between 160 - 440
-The debt-to-income ratio is between 8 – 18

Summary of Ordered Categorical Variables
-Grade B had the highest number of "Charged off" loan applicants, with a total of 1,352 applicants, indicating that applicants with this credit grade faced challenges in repaying their loans.
-Short-term loans with a duration of 36 months were the most popular among "Charged off" applicants, with 3,006 applications. This suggests that a significant portion of applicants who experienced loan default chose shorter repayment terms.
-The year 2011 recorded the highest number of "Charged off" loan applications, totalling 3,152, signalling a positive trend in the number of applicants facing loan defaults over the years. This could be indicative of economic or financial challenges during that year.
-"Charged off" loans were predominantly taken during the 4th quarter, with 2,284 applications, primarily in December. This peak in loan applications during the holiday season might suggest that financial pressures during the holidays contributed to loan defaults.

Summary of Unordered Categorical Variables
-Debt consolidation was the primary loan purpose for most "Charged off" loan applicants, with 2,633 applicants selecting this option. The lending company needs to exercise caution when approving loans for debt consolidation purposes, as it was the primary loan purpose for many "Charged off" applicants.
-The majority of "Charged off" loan participants, totalling 2,715 individuals, lived in rented houses. The lending company must assess the financial stability of applicants living in rented houses, as they may be more susceptible to economic fluctuations.
-A significant number of loan participants, specifically 5,317 individuals, were loan defaulters, unable to clear their loans. The lending company should enhance risk assessment practices, including stricter credit checks and lower loan-to-value ratios, for applicants with a history of loan defaults. They should offer financial education and support services to help borrowers manage their finances and improve loan repayment outcomes.

Summary of Quantitative variables
-1,561 loan applicants who charged off had annual salaries less than 40,000 USD. The lending company should exercise caution when lending to individuals with low annual salaries. They should implement rigorous income verification and assess repayment capacity more thoroughly for applicants in this income bracket.
-Among loan participants who charged off (2,025), a considerable portion belonged to the interest rate bucket of 13%-17%. To reduce the risk of default, the lending company should consider offering loans at lower interest rates when possible.
-1,695 loan participants who charged off received loan amounts of 15,000 USD and above. The lending company should evaluate applicants seeking higher loan amounts carefully. They should ensure the applicants must have a strong credit history and repayment capability to handle larger loans.
-1,608 loan participants who charged off received funded amounts of 15,000 USD and above. The lending company should ensure that the funded amounts align with the borrower's financial capacity. They should conduct thorough credit assessments for larger loan requests.


Summary of Bivariate Analysis
-The loan applicants belonging to Grades B, C, and D contribute to most of the "Charged Off" loans.
-Loan applicants belonging to Sub Grades B3, B4, and B5 are more likely to charge off.
-Loan applicants applying for loans with a 60-month term are more likely to default than those taking loans for 36 months.
-Most loan applicants have ten or more years of experience, and they are also the most likely to default.
-The number of loan applicants has steadily increased from 2007 to 2011, indicating a positive trend in the upcoming years.
-December is the most preferred month for taking loans, possibly due to the holiday season.
-The fourth quarter (Q4) is the most preferred quarter for taking loans, primarily because of the upcoming holiday season.
-Debt consolidation is the category where the maximum number of loans are issued, and people have defaulted the most in the same category.
-Loan applicants who live in rented or mortgaged houses are more likely to default.
-A significant portion of loan applicants who defaulted received loans with interest rates falling within the range of 13% to 17%.

Summary of Multivariate Analysis
-Tendency to default the loan is likely with loan applicants belonging to B, C, D grades.
-Borrowers from sub grade B3, B4 and B5 have maximum tendency to default.
-Loan applicants with 10 years of experience has maximum tendency to default the loan.
-Borrowers from states CA, FL, NJ have maximum tendency to default the loan.
-Borrowers from Rented House Ownership have highest tendency to default the loan.
-The borrowers who are in lower income groups have maximum tendency to default the loan and it generally decreases with the increase in the annual income.
-The tendency to default the loan is increasing with increase in the interest rate.



## Technologies Used
Python
Matplotlib
Numpy
Pandas
Seaborn


## Contact
Created by [@ManikantaGrandhi] - feel free to contact me!
