# **Project Proposal**

[Lending Club Loan Dataset Link](https://www.kaggle.com/urstrulyvikas/lending-club-loan-data-analysis)

I find this dataset intriguing because it’s interesting to see why Americans borrow loans and the differences in interest rates.  This dataset consists of Lending club data from 2007 to 2015, with 9,578 records (rows) and 14 columns: Credit.policy(Categorical-Integer): If the customer meets the credit underwriting policy of Lendingclub.com, the value is “1”, otherwise, it’s “0”; Purpose (Continuous-String); Int.rate (continuous variable-decimal); Installment (continuous variable-integer); Log.annual.inc (continuous variable-integer); Dti (continuous variable-integer); fico(continuous variable-integer)
days.with.cr.line(continuous variable-integer; Revol.bal (continuous variable-integer); Revol.util (continuous variable-integer);Inq.last.6mths (continuous variable-integer); Delinq.2yrs (continuous variable-integer);Pub.rec (continuous variable-integer); not.fully.paid (categorical-integer): If the customer’s fully paid off, the value is “1”, otherwise, it’s “0”.

 This analysis will benefit the general public (especially future borrowers) considering applying for a loan.  This analysis will help determine their chances of approval and approximately how much interest rate they will be charged.

## **Research Questions**

### **Hypothesis 1:**
Does the purpose of the loan affect the interest rate?

H0: µ1-µ2=0  : There is no difference between the average sample mean of interest rates for small_business sample and the average sample mean of interest rate for major_purchase sample.

Ha: µ1-µ2≠0: There is a difference between the average sample mean of interest rates of small_business sample and the average sample mean of interest rate of major_purchase. 
 
Two sample t-test assuming unequal variances and the confidence intervals will be done between sample 1(interest rates of small business loans) and sample 2 (interest rate of major purchase loans).


### **Hypothesis 2:**
Does the FICO score influence whether or not the borrower meets the credit underwriting policy?

H0: µ1-µ2=0 : There is no difference between the average sample mean of FICO scores that meet Lending Club’s underwriting policy and the average sample mean of FICO scores do not meet Lending Club’s underwriting policy.

Ha: µ1-µ2≠0: There is a difference between the average sample mean of FICO scores that meet Lending Club’s underwriting policy and the average sample mean of FICO scores do not meet Lending Club’s underwriting policy.

Two sample t-test assuming unequal variances and the confidence intervals will be done between sample 1(FICO scores that meet underwriting policy) and sample 2 (FICO scores that do not meet underwriting policy).



