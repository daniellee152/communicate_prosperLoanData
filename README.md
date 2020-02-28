# Analysis Prosper Loan Data
## Dataset
The dataset consisted of borrower APRs and attributes of 113,937 loans. The attributes included original loan amount, borrower's Prosper rating, employment status, borrower's stated monthly income, as well as many other features such as debt to income ratio, current loan status etc. Main features that I focus on dataset are:
BorrowerAPR, LoanOriginalAmount, DebtToIncomeRatio, CurrentCreditLines, StatedMonthlyIncome, EmploymentStatus, IsBorrowerHomeowner, IncomeVerifiable
## Main Findings 
The distributions of stated monthly income is highly right screwed. Most stated monthly incomes are less than 20k, but some of them are incredibly high, like greater than 100k. Surprisingly, most of borrowers with greater than 100k monthly income often have small loan. Most of people are employed or have a full-time job, which prosper rating are in range from D to A.
The borrower APR is negatively associated with the loan original amount, which mean the more the loan amount, the lower the APR. It also shows that at different size of the loan amount, the APR has a large range, but the range of APR decrease with the increase of loan amount. The Prosper rating also has a strong effect on the borrower APR, which decreases with the better rating.
The loan original amount is positively correlated with the stated monthly income, it makes sense since borrowers with more monthly income could loan more money. It also shows that borrowers with better rating also have larger monthly income and loan amount.
## Presentation
In presentation slides, I only focus on the effects of features on BorrowerAPR. Start by looking the distribution of BorrowerAPR,
LoanOriginalAmount and StatedMonthlyIncome. Followed up is the comparasion between BorrowerAPR and LoanOriginalAmount,  BorrowerAPR and ProsperRating. The investigation of Prosper Rating Effect on Relationship between APR and Loan Amount and EmploymentStatus effect on the relationship between StatedMonthlyIncome and ProsperRating (Alpha) have been conducted to gain an understanding about the effect of other features on BorrowerAPR
