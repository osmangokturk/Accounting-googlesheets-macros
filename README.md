# Accounting-googlesheets-macros
This repsoitoy will provide a easy and practical way for book keping and financial reportings for small associations, individuals and companies. 
Assuming your most transactions are made over one or more bank accounts, this can help you a lot to automatize the accounting process for you.

# you have a banc account, 
you have an banc account that you annotate in a collumn easly each transaction a like rent payment, sales,..(Account X, Accout Y, Cash withdrawal,...
we are going to make use of this bank account to make our job easier. 
![image](https://github.com/user-attachments/assets/a60e6da1-4f49-4489-9d4d-fc4490ebdb8e)



## Cash Account. 
most probably you will have a cash account too. In order to avoid double accounting, we will use two terms carefully. Cash withdrawals  are written as cash withdrawal (not caisse), and in the caise account we will use the same term. we will revert the sign for this cash withdrawals to the cash account.  Any cash withdrawal or physical cas reception or cash payment have to be maintained in this cahs account 

![image](https://github.com/user-attachments/assets/de1d7dfe-ed79-4675-b862-a81c779f9f42)

## create a reference table
Create a reference table like this:
![image](https://github.com/user-attachments/assets/8a658af2-3159-4f94-ba44-d30e135d44ec)

 AS we are going to produce a sheet per account in a single googleSheet document, I prefered short names so that on my windows I can see as much as sheets as possible. 

#SCRIPTS
##1-produce sheets per account shortly name the sheet and populate the header,and format the hater. 
Alos at the 10th row add the column titles like date, reference, account name, amount

##2-start distribute transaction based on the bank account and cashier account to each individual account. we will erase from the bank and cashier account to be sure of transmission. Later for the new transaction, we will redo for the new data. 

#SCRIPTS for AGREGATED finals: income statement and balance sheet. 

