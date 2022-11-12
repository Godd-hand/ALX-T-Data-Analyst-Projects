# ALX-T & UDACITY DATA ANALYST NANODEGREE PROGRAM

> This was the third Data Analyst Nanodegree Project I carried out during the Program

## Prosper Credit 

## Author: George Thomas



## Dataset :file_folder:

> This data set contains information on peer to peer loans facilitated by credit company Prosper. It contains 113,937 loans and 81 variables. 

> Of the 81 variables, this analysis contains 13 of them, which are: 'Term', 'LoanStatus', 'BorrowerAPR', 'ProsperScore', 'ListingCategory (numeric)', 'EmploymentStatus', 'EmploymentStatusDuration', 'IsBorrowerHomeowner', 'DebtToIncomeRatio', 'StatedMonthlyIncome', 'LoanOriginalAmount', 'LoanOriginationDate', 'MonthlyLoanPayment'


## Summary of Findings :page_with_curl:

> - The company began operations in 2005. They had 22 loans at the time of starting their operations. The number of loans increased steadily until 2008 where it dropped from 11552 loans to 2047 loans in 2009. Then the loan steadily increases from 2010 with a record high number of loans in 2013. It then reduced in 2014.
 
> - The Borrowers annual percentage rate distribution appears to be multimodal. The loan amounts are mostly right skewed with different several peaks. The most frequently loaned amount is 4,000. The loan terms are split into 3 loan terms of 12 months, 26 months and 60 months with 36 months being the most frequently used term. Most of the Loans have a current status with another substantial amount of loans have been completed. The past due loans are split into 6 groups in respect to the number of days they have exceeded.The most frequently loan category applied for is Debt Consolidation. The distribution of monthly income is right skewed. The most frequent monthly income by borrowers seems to be about 5000 with most stated montly income less than 30000.

> - Borrower Rate is negatvely correlated with the loan original amount. The higher the loan amount obtained the lower the borrowers annual rate percentage. The higher the loan amount the higher the term status given for loan repayment. Borrowers with higher monthly income have higher loan amounts. Borrowers with higher monthly income are able to pay higher monthly loan repayments. The higher the loan amount the higher the monthly repayment amount. It is obvious that borrowers that own homes have more employment history than their counterparts and non-homeowners majorly loaned amounts between the ranges of 0 - 5000 with a max of 30000. While most home owners were spread across different amounts betwwen the range of 5000 and above.

> - The 36 months term loans have borrowers annual rate percentage between 0 - 0.4 with a few outliers going to 0.5, Loans for 60 months term are concentrated more on the higher loan amounts and borrowers APR between 0.1 - 0.35, while the 12 months loan term are majorly for lowe loan amounts with a borrowerAPR between 0 - 0.35. Although, the term didn't have a significant relationship to strentheng the effects on the Borrowers annual rate percentage.

> - The loan terms had interesting effects on the monthly loan payment plans. Loans with a maximum repayment of under a year had the highest monthly fees. This could be because it is for a shorter term. 



## Key Insights for Presentation :heavy_check_mark:

> This project focused on an exploration of the factors that affect the Borrowers annual rate percentage.

> 13 of the original 81 variables were selected.
Histogram plots were used to explore the distribution of the variables by using an histogram plot for the variables that are continuous and counplots for the variables that are discrete and nominal.

> For the bivariate analysis, a correlation map was used to give an overview of variables that may have some correlation with one another.
Following that was an exploration of those that had a correltation with magnitude greater than 0.2, and then investigated their relationships.

> The use of a regression plot of the loan amount and the borrowers annual rate percentage was done. In addition, other plots like boxplots, violin plots, barplots were employed to discover the relationship between variables.

> From the results of the bivariate analysis, it was identified that the major features that influence the Borrowers annaual rate percentage are the LoanOriginalAmount, StatedMonthlyIncome and the MonthlyLoanPayment.

> The insights are shown in the presentation

