# Exploration of the Loan Data From Prosper By Adedayo Adediran

For this project, I analyzed the Loan Data From Prosper dataset. This dataset contains 113,937 loans with 81 variables on each loan from 2005 to 2014. Some of the key variables in the dataset include loan amount, borrower rate (also know as the interest rate), Loan Status, Borrower Income, Borrower APR, TermProsperScore, Borrower State, Employment Status, Occupation, Loan Original Amount, etc. The dataset can be found [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1554484977406000). The data dictionary explaining the variables in the data set can can be accessed [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).

To begin with, I cleaned the data by looking at the data types, and converting them where necessary based on the information provided in the data dictionary. Next, I calculated the percentage of missing rows for each column to evaluate which columns were worth dropping using the sixty-percent rule i.e. columns with at least 60% of its rows missing were dropped. Based on this step, 11 columns were dropped which meant I was left with 70 columns. Of these 70 variables, I chose 13 variables which were important to the my research question. Summarily, for my analysis, I evaluated the dataset based on 113,937 loans with 13 variables.

These variables are: Loan Status, Loan Original Amount, Borrower APR, Term, Prosper Score, Borrower State, Borrower Rate, Employment Status, Occupation, Is Borrower Homeowner, Stated Monthly Income, Debt To Income Ratio, and Loan Origination Date.

### Research Question: What affects the borrower’s APR or interest rate?


## Summary of Findings

My analysis threw up a number of interesting findings about the dataset.

The total sum of money that was given out by Prosper within the years in view is $949,894,347. The lowest amount given out in a specific time was $1,000 and the highest amount was $35000. The average loan amount is $8337. Less than 25% of the lenders have received $12000 and above since the inception of the business indicating that the business over that specific period was more targetted at people with small / medium-scale financial needs. 

Borrowers with lower monthly income who are unemployed received the lowest loan amounts. For those who are employed, loan amounts seem to increase with higher monthly incomes, with those making between 8,000 to 10,000 dollars receiving the highest amounts of all the borrowers. The other employment status are pretty average with very few number of borrowers who fall in the categories receiving up to 30,000 dollars in loan amounts. This is in line with conventional finance. Borrowers with stable source of incomes are considered more qualify for higher amounts. Interestingly, Borrowers who have high debt to income ratio and low prosper score (1-5) tend to receive less amounts when compared with those with low debt to income ratio and high prosper score. Further more, those with low debt to income ratio and high prosper score tend to receive the highest amount. While those with high debt to income ratio and low prosper score seem to receive the least amount.

Outside of the main variables of interest, I found that as Prosper Score increases, the Borrower APR decreases, though there were outliers. This relationship compares positively with basic finanical knowledge, that borrowers with better credit score generally better terms including lower APR and Interest Rates. Also, borrowers with higher prosper score also have higher stated monthly income. This makes sense in real world sense given that people who make more money typically have better credit score, thanks to their financial stability which makes it easy for them to boost their credit score over time.



## Key Insights for Presentation

For the presentation, I focused on variables that could affect the loan amount, which are Debt To Income Ratio, Employment Status, Stated Monthly Income, Term, Origination Year, Home ownership, Loan Status and Prosper Score. I started by showing the distribution of the Loan amounts. Then, I showed the relationship between the Loan Amount and Loan Amount Versus Prosper Score as well as Loan Amount vs. (Debt To Income Ratio, Term, Stated Monthly Income, Borrower APR) versus Loan Amount. I also investigated the joint effects of Prosper Score and Debt To Income Ratio on Loan Amounts, as well as the effect of Loan Month and Employment Status on Loan Amounts.
