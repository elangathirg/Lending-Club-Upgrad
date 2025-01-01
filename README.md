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


The analysis was conducted using Python (version 3.10.5) with libraries such as NumPy, Pandas, Seaborn, and the re and platform modules. This project was tasked by Upgrad and was carried out by Elangathir G.
