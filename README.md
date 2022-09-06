# Prosper Loan Data Exploration
![this](https://user-images.githubusercontent.com/102169299/188697436-074d3052-d68e-4910-b881-a140e876a633.jpg)



## by Sharon Dim


## Dataset

Prosper Marketplace, Inc. is a San Francisco, California-based company in the peer-to-peer lending industry.Prosper Funding LLC, one of its subsidiaries, operates Prosper.com, a website where individuals can either invest in personal loans or request to borrow money.
This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.


## Summary of Findings

1) BorrowerAPR and BorrowerRate have a very strong correlation coefficient of 0.99. This is Great!. Having a high APR typically means borrowers will be paying more interest on their loans.

2) The correlation coefficient of borrower APR and loan original amount is -0.323, the scatter plot also shows that these two variables are negatively correlated, that is the more the loan amount, the lower the APR.

3) Deducing from the statistics; The higher the LoanOriginalAmount, the higher the MonthlyLoanPayment.

4) The correlation coefficient of the LoanOriginalAmount and StatedMonthlyIncome is 0.20 showing a very slight positive relationsip between the two variables.

5) Very strong positive correlation between loan original amount and monthlyloan payment

6) In the distribution of rating and loanterm correlation; over 10000 borrowers who who took a 36month (3years) term loan, rated "A" which was the highest rating followed by "C" (rated by same 36month term borrowers) and closely followed by "D".

7) The highest number of borrowers(8000) who took the 60month term plan (5 years) rated "C", followed by about 6000 borrowers from the 60month term who rated "B".

8) Very few people (< 500) opted for the 12month plan and there was no significant difference in the ratings for it.

9) Only about 6000 borrowers(36 months term) gave a HR rating, while about 4500 borrowers(36month term) gave an AA rating, while less than 1000 borowers (60 months term) gave an AA rating.This shows that about 50% of the customer population from the 36month term attest to the company's extremely strong capacity to meet its financial commitments.

10) In the Distribution of income range and loanterm correlation; Over 25000 borrowers with income range of  25,000− 49,999 opted for the 36months term plan which depicted the highest peak in the chart, followed by about 23000 borrowers within the salary range of  50,000− 74,999 (36months term).The highest peak for the 60months term had an income range of  50,000− 74,999, followed closely by an income range of  25,000− 49,999.

11) From the statistics; it was shown those with 0 income range only take loans for 36 months, while extremely few people(below 50) with an income range of  25000− 100000+ opted for the 12month plan.


## Steps taken

The Steps I took to carry out this project are:

1)Loading of Python Frameworks for data analysis and Dataset

2) Did some preliminary wrangling, explored the data for informations about the dataset

3)Analyzed Dataset using univariate, bivariate and multivariate visualization techniques

4) Drew insights from the findings, communicated them and concluded analysis.


## Key Insights for Presentation

For the presentation, I focused on features that could affect the borrower APR, which are original loan amount, loan term, Prosper rating and income range. I showed the distribution of the borrower APR, loan original amount, loan term, employment status and ProsperRating (Alpha) variables. I showed univariate visualizations and the key insights derived from them, bivariate relationships between APR vs. loan, loan vs income range, loan vs Prosper rating and Borrower Rate by Income Range and Employment Status.  I also showed the multivariate relationship between rating, loan term, Original loan amount and APR.
