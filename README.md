# Exploratory data visualizations - Loan Data from Prosper
## by (Michèle Nkuimi)



## Dataset

This transcript explores a dataset containing loan data for 11,3937. The analysis focuses on the following variables:
•	A custom risk score built using historical data(ProsperScore); 
•	History of the borrower in terms of number of credit lines(TotalCreditLinespast7years) and timeliness of payments(DelinquenciesLast7Years); 
•	Income of the borrower or collateral to secure the loan (StatedMonthlyIncome, AvailableBankcardCredit, EmploymentStatus).
All related to the Borrower's interest rate for this loan(BorrowerRate).



## Files description:
To make the analysis, two csv files were provided by Udacity: 
•	Prosper Loan Data - Variable Definitions;
•	prosperLoanData.




## Summary of Findings

A quick summary of my findings can be found below: 

- The distributions of TotalCreditLinespast7years and DelinquenciesLast7Years are skewed to the right, meaning they have positive distributions. In other words, borrowers have fewer past credits and delinquencies.
- The monthly income the borrower stated at the time the listing was created takes on a very large range of values, from about $0 at the lowest, to about $1750003 at the highest. Plotted on a logarithmic scale, the distribution of monthly income looks unimodal. This shows that data near the mean are more frequent in occurrence than data far from the mean.
- There is a higher occurrence of interest rate between 0.35 and 0.37.
- Most borrowers indicate to be employed and to be working full time.
- Looking at the frequencies of loan status, the majority of loans in the dataset are either completed or currently being paid back.
- The maximum amount of loan is $35,000 while the minimum is $1,000. However, most of loans are under $15,000. I have noticed particular frequencies of loans around  $3000  $10000, $15000, $20000 and even $25000.
- The borrower’s interest((BorrowerRate)) rate was very low around 2005, steadily increased in 2006, dropped a bit in 2007 and increased again. It reached a peak somewhere around 2010 and dropped again.





## Key Insights for Presentation

From the correlation matrix (Correlation coefficient between variables) I can see that there is no strong relationship between my selected variables. Most of the correlation coefficients 
are weak or negligible. The one and only moderate correlation coefficient(-0.65) is between ProsperScore and BorrowerRate. This indicates that when ProsperScore increases, BorrowerRate decreases which is in 
this context good. It is less risky for Prosper to loan money to people with a good credibilty.


The stripplot (BorrowerRate vs ProsperScore throughout years) is quite interesting; from this figure one can see that in 2013 Prosper granted a huge amount of loans and 
all the borrowers had a prosper score from 5 and above at different interest rates, either very high or very low.

During the years 2008 up until 2011 the amount of loans must have been extremely low. Loans granted at the highest interest rate took place in 2007 to, not surprisingly, borrowers with a lower prosper rate.


