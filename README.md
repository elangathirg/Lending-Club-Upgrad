# Lending-Club-Upgrad
**CASE STUDY FOR LENDING - BY UPGRAD
**Lending Club Case Study - UPGRAD

This document details an exploratory data analysis (EDA) conducted on a loan dataset to identify factors contributing to loan defaults. The analysis was performed from the perspective of a consumer finance company specializing in various loan types for urban customers.

When evaluating a loan application, the company faces a dual risk: rejecting a creditworthy applicant results in lost business, while approving a high-risk applicant can lead to financial losses through defaults. The provided dataset contains historical loan data, including information on past applicants and their loan repayment status (defaulted or not). The primary objective of this analysis is to uncover patterns and indicators of potential default. This information can then be used to inform lending decisions, such as loan denial, loan amount reduction, or adjusted interest rates for higher-risk borrowers.

This case study uses EDA to examine the influence of consumer and loan attributes on default probability. The possible outcomes of a loan application are:

Loan Accepted: This can further result in:
Fully Paid: The loan is repaid in full, including principal and interest.
Current: The loan is still being repaid according to the agreed schedule.
Charged-off: The borrower has defaulted on the loan by failing to make payments for an extended period.
Loan Rejected: These applications are not included in the dataset as no loan transaction occurred.
The business objective is to minimize credit loss, the financial loss incurred when borrowers default. In this context, "charged-off" loans represent defaults and are the primary focus of this analysis. By identifying characteristics of likely defaulters, the company aims to reduce credit loss and improve portfolio performance. The analysis seeks to pinpoint the key drivers of loan default, providing valuable insights for risk assessment and portfolio management.

The EDA reveals the following key findings:
Small business, Educational and Renewal Energy are riskier purposes for Loan disbursal
We can recommend to increase loan disbursal for wedding and home improvement
We can strongly observe higher default risk associated with longer repayment duration
We observe the following states having relatively higher defaulting rates
SD: South Dakota AK: Alaska FL: Florida NV: Nevada
The higher the loan enquiries especially at the higher end of greater than 6 enquiries default rates is higher
Leaving out the low and high extremes there is a linear correlation between Default rate and Ratio of Debt to Income
Using Bivariate Analysis certain postulates are checked for:
Higher loan amounts are associated with longer terms (e.g., 60 months), strong association exists as postulated
Higher loan amounts tend to have higher interest rates, strong association exists as postulated
Borrowers with higher income utilize less revolving credit, contrary to the postulate the high income group utilizes greater revolving credit
Correlation exists between interest rate and installment duration, so the default risk is countered with higher interest rates
With higher interest rate loans we recommend approving shorter repayment term 

The analysis was conducted using Python (version 3.10.5) with libraries such as NumPy, Pandas, Seaborn, and the re and platform modules. This project was tasked by Upgrad and was carried out by Elangathir G.
