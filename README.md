# Unlocking-Financial-Insights-in-Banking-Data-PowerBI
## Background
As a data analyst at FinInsight Group, a consultancy specializing in banking analytics, you are equipped with two comprehensive datasets: 'Banking Transactions' and 'Customer Account Details'. The 'Banking Transactions' dataset records detailed transaction data, including types, amounts, dates, and branch information. The 'Customer Account Details' dataset provides insights into account holders, covering account types, balances, interest rates, credit scores, and loan amounts. Your expertise is crucial in a sector where financial data drives strategic decisions in customer relationship management, risk assessment, and product offerings.

### **Objective**
Your task is to employ Power BI to analyze these banking datasets, aiming to unravel the intricate patterns and behaviors within the data. This involves in-depth data cleaning, robust data modeling, and strategic use of DAX for complex analytics. Your goal is to create a comprehensive, interactive dashboard that not only illustrates transactional trends and customer profiles but also offers a holistic view of the banking ecosystem. This analysis should include understanding customer transaction behaviors, identifying relationships between account characteristics and financial health, and exploring factors influencing credit scores and loan management. Your insights will guide FinInsight Group in advising banking institutions on optimizing their services, enhancing customer satisfaction, and managing financial risks effectively.

## Dataset
Banking Dataset1:- https://docs.google.com/spreadsheets/d/1JY8yDRmXEtAJbNvc3cJ2mW8EbFhBAZ7K/edit?usp=sharing&ouid=117472857107078715100&rtpof=true&sd=true

Banking Dataset2:- https://docs.google.com/spreadsheets/d/1jSTrlBp2o0ujuag-Zdi1JEzcTvEBTtv2/edit?usp=sharing&ouid=117472857107078715100&rtpof=true&sd=true

The "BankingDataset1.xlsx" file contains the following columns:

1. **TransactionID**: A unique identifier for each transaction. 
2. **AccountNumber**: The account number associated with the transaction. (Foreign Key)
3. **TransactionType**: The type of transaction (e.g., Transfer, Deposit, Withdrawal, Payment).
4. **Amount**: The amount of money involved in the transaction.
5. **TransactionDate**: The date when the transaction occurred.
6. **BranchCode**: The code of the bank branch where the transaction took place.
7. **Currency**: The currency in which the transaction was made.
8. **TransactionTime**: The time of day when the transaction occurred (in hours).

The "BankingDataset2.xlsx" file contains the following columns:

1. **AccountNumber**: A unique identifier for each account, corresponding to 'AccountNumber' in "BankingDataset1.xlsx". (Primary Key)
2. **AccountHolder**: The name of the account holder.
3. **AccountType**: The type of account (e.g., Credit, Loan, Checking).
4. **Balance**: The current balance of the account.
5. **InterestRate**: The interest rate applicable to the account.
6. **CreditScore**: The credit score of the account holder.
7. **OpeningDate**: The date when the account was opened.
8. **LoanAmount**: The amount of loan associated with the account (if applicable).
9. **AccountHolderDetails:** Details about account holders - employment sector, years at current residence, and city of residence etc.

## Dashboard
![PowerBI Dashboard imp](https://github.com/Atharva070799/Unlocking-Financial-Insights-in-Banking-Data-PowerBI/assets/130131832/08a1ac76-0a12-4218-ad75-6c1dfaf76819)

