# (Proper Loan Data Exploration)
## by (Carolyne Masaku)


## Dataset

> This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. 
The features documentation is available here :https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0.


## Summary of Findings

> In the exploration, I found that the current loan status has the highest number of loans followed by completed loans. Defaulted loans comes fourth with 5018 out of 113,937 loans, an implication that, Proper Loan does proper background check to its clients before giving them a loan to avoid bad debts.
I used a bar plot to check the distribuiton of **EmploymentStatus**. From the plot, most of the people taking up loans are the Employed, with the least being the retired.
The investigation into **IncomeRange** shows that the highest number of people taking up loans have an Income range of between $25,000 and $49,999, followed closely by those earning between $50,000 and $74,999.
For **Borrower APR** , a smaller binsize gives a more defined distribution of the APR. The distribution looks unimodal.

Looking at the relationship between IsBorrowerHomeowner and LoanStatus, there is an even distribution of the Loan Status and whether a borrower is a homeowner or not. This implies that, a borrower owning or not owning a home does not affect their ability to pay for a loan or willingness to take up one.
I used a clustered bar plot to check the relationship between **IncomeRange** and **IncomeVerifiable**- There seems to be a small number of persons whose income is not verifiable. Generally, most of the persons who took a loan have there income verifiable. A violin plot of **IncomeRange** and **BorrowerAPR** shows that persons who are not employed seem to have a higher modal BorowerAPR as compared to those in other Income ranges.
A boxplot of **Term** and **LoanOriginalAmount** indicates that smaller amounts loans have a shorter term(12 months) with a few outliers with bigger loans having a longer term period.

In the relationship between IncomeVerifiable, LoanStatus and LoanOriginalAmount, persons whose Income is verifiable get bigger amounts of loans possibly because it is easier for such people to settle their loans without a lot of back and forth.


## Key Insights for Presentation

> In the exploration, I found that the current loan status has the highest number of loans followed by completed loans. Defaulted loans comes fourth with 5018 out of 113,937 loans, an implication that, Proper Loan does proper background check to its clients before giving them a loan to avoid bad debts.

Looking at the relationship between IsBorrowerHomeowner and LoanStatus, there is an even distribution of the Loan Status and whether a borrower is a homeowner or not. This implies that, a borrower owning or not owning a home does not affect their ability to pay for a loan or willingness to take up one.

In the relationship between IncomeVerifiable, LoanStatus and LoanOriginalAmount, persons whose Income is verifiable get bigger amounts of loans possibly because it is easier for such people to settle their loans without a lot of back and forth.