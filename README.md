# Accounting-googlesheets-macros
This repsoitoy will provide a easy and practical way for book keping and financial reportings for small associations, individuals and companies. 
Assuming your most transactions are made over one or more bank accounts, this can help you a lot to automatize the accounting process for you.

# Assume the Association has a banc account 
Assuming you have a main bank account that the incoming and outgoing funds are made through.
Peridically you you take the account recepts and you annotate in an additional column  like rents, payments, sales,..(Account X, Accout Y, Cash withdrawal,...
we are going to make use of this bank account to make our job easier. 
![image](https://github.com/user-attachments/assets/a60e6da1-4f49-4489-9d4d-fc4490ebdb8e)



## Cash Account 
Most probably you will have a cash account too. For this cash account you have bank withdrawals and money collections. 
Money collections will be registered in the cash account as it is (like other revenues).   
We have to avoid double account with respect to bank withdrawals. For this we  will use one term  carefully: 
cash withdrawals both for the exit from bank account and entry in the cash account.  
Cash withdrawals  are written as cash withdrawal (not caisse), and in the caise account we will use the same term. 
We will revert the sign for this cash withdrawals in the the cash account.  Any cash withdrawal or physical cas reception or cash payment have to be maintained in this cahs account 

![image](https://github.com/user-attachments/assets/de1d7dfe-ed79-4675-b862-a81c779f9f42)

## Create a reference table for the account sheets
Create a reference table like this:
![image](https://github.com/user-attachments/assets/8a658af2-3159-4f94-ba44-d30e135d44ec)

 Since we will produce a sheet for each account in a single Google Sheet document, I preferred using short names to maximize the number of visible sheets in my Excel window.

#SCRIPTS
## 1-Create sheets(short named), populate the headers (long names) and other titles
produce sheets per account shortly name the sheet and populate the header,and format the them. 
Also at the 10th row add the column titles like date, reference, account name, amount

## 2-Distribute transactions
start distribute transaction based on the bank account and cashier account to each individual account. we will erase from the bank and cashier account to be sure of transmission. Later for the new transaction, we will redo for the new data. 

#SCRIPTS for AGREGATED finals: income statement and balance sheet. 

