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

This analysis is based on a dataset containing complete loan data from 2007 to 2011, accompanied by a data dictionary. The EDA reveals several key findings:

Strong correlations exist between loan amount, investor amount, and funding amount.
A negative correlation is observed between annual income and the debt-to-income (DTI) ratio.
Charged-off customers tend to have lower annual incomes compared to those who fully repaid their loans within the same loan grade (interest rate range). This suggests implementing loan amount thresholds and shorter repayment tenures for such applicants.
Loan grades are effective indicators of default risk, highlighting the need for more thorough borrower assessments, especially for lower-grade (G to A) loans.
Controlling loan volumes in high-risk regions (e.g., CA, FL, NY) could improve profitability.
Borrowers with mortgages tend to take larger loans and experience higher default rates, suggesting the need for stricter lending criteria or additional safeguards for this group.
Shorter repayment tenures could reduce the percentage of charged-off applications.
The presence of public derogatory records increases the likelihood of bankruptcy and default.
Loans for small businesses, debt consolidation, and credit card refinancing represent significant portions of the loan portfolio and warrant focused analysis, particularly for loan amounts exceeding $12,000.
The analysis was conducted using Python (version 3.10.5) with libraries such as NumPy, Pandas, Seaborn, and the re and platform modules. This project was tasked by Upgrad and was carried out by Elangathir G.
