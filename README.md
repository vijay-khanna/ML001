# Project Name
> This project is an Exploratory Data Analysis of the Lending Card Case Study.
> The Aim of the project is to explore data using Python, and figure co-relations of different parameters

> Business Challenge : Lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. Identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default




## Approach for the Analysis
* Research on the Lending Domain, Understand Business challenges. Read Research Papers which show co-relations for similar businesses. 
* Initial Analysis using Excel Pivots and Graphs to make sense of data. 
* Expore data using Python, Visuazlize
* Create Insights from data.

## Key Patterns for Loan Default Identification - Based on Finance Industry Whitepapers.
- Credit History and Scores: Analyze borrowers' past credit behavior and scores. e.g. FICO
- Income Stability: Assess the stability and adequacy of the borrower's income.
- Debt-to-Income Ratios: Evaluate borrowers' existing debts against their income.
- Employment History: Consider the consistency and length of employment.
- Age and Demographics: Understand the risk profile based on age group and other demographic factors.
- Loan Purpose and Amount: Scrutinize the purpose of the loan and the amount requested.
- Current Financial Behavior: Monitor current spending patterns and financial commitments.
- Homeownership: Owning a home, particularly with a mortgage, can correlate with lower expected loss.
- Loan Purpose: Different loan purposes exhibit varying levels of risk.
  

## Conclusions
- People with longer employment length & Average Loan Amount seem to have more Charge off.
- People with employment length >10 years (and less than a year) have higher count/instances of Charge off.
- Average Annual Income is co-related to defaults. Lower average income has more defaults.
- High debt to income ratio shows a strong correlation to defaults.
- Loan Purpose of Debt_Consolidation, credit_card payments and Small_business have most defaults.
- There seems to be a correlation between the fields loan_amount, annual_inc, Dti, Months_since_last_record. These may be able to provide early insights into upcoming default.
- The Box Plot shows that the Average Loan Size for Charged Off segment is Higher than Fully Paid. This also leads to the insight that the Current average is much higher, which could point to upcoming loan defaults, and the company should proactively work on working with those customers and monitor the triger signals better.


## Technologies Used
- Python version: 3.10.12 
- Pandas version: 2.1.3
- Matplotlib version: 3.8.1
- Seaborn version: 0.13.0


## Acknowledgements
- References :
* Commercial Banks and Consumer Instalment Credit . John M. Chapman NBER 
https://www.nber.org/system/files/chapters/c4732/c4732.pdf

* Credit Risk Management of Consumer Finance Based on Big Data
https://downloads.hindawi.com/journals/misy/2021/8189255.pdf

* Investigation on Consumer Finance Risk Management – Case Study
https://www.atlantis-press.com/article/125908355.pdf

* Drivers of Performance in Unsecured Personal Loans
https://hl.com/media/rn2hx2od/drivers-of-performance-in-unsecured-personal-loans.pdf


## Contact
Created by [@vijay-khanna] - feel free to contact me!

