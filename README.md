# Accounts-Excel-Spreadsheets-for-Educate-and-Donate-LTD
**Cleaning Data, Formulas and Functions, Tabulation**
![image](https://github.com/insights000/Accounts-Excel-Spreadsheets-for-Educate-and-Donate-LTD/assets/150028138/b22ce576-3493-449e-ad5a-5a3b47e46e32)

https://educateanddonate.co.uk/
Educate and Donate is a micro limited company ran by a teacher who has veteran experience teaching a wide variety of subjects to students, private limited. The company asked me to do some work on their accounts and this project will involve me going through what I did to help them improve their sheet and the deductions that I made in cleaning and organizing their data, for the purpose of confidenality and data protection and GDPR regulations I cannot share the Excel Spreadsheet that contains the information of the said statement on it there however, I can walkthrough what exactly I did for them.

**Step 1**
The first stage involved adding up in the transactions made to the account there and the transactions made outside of the account, thus the values that were made inside and gained were marked by positive values there, the revenue that was coming into the business and the revenue that was coming out was marked by - there, denoted by the transactions made in and out across the overball balance of the account, thus the loss and gains already denoted for the entire columnn the first value that needed to be worked out was the profit. We used the SUM FORMULA here in the total bar there, the formula for the Excel SUM FUNCTION was: **=SUM(Table2[Amount(GPB)])** where amount was the column that was being added with the currency values in which returned to me the profit value.

![image](https://github.com/insights000/Accounts-Excel-Spreadsheets-for-Educate-and-Donate-LTD/assets/150028138/fcb94376-342f-49ab-9559-f5cd4c20a9a9)

**Step 2**
The second part of the task involved calculating the individual revenue and expenditure values. All the losses within the column there that was transacted out of the account denote the expenditure and all the positives denote the gain of what went in. The problem is that we need to seperate these values, With a given formula, I devised a formula to make it work, I used the SUMIF formula where the condition was for all values that were higher than 0, that the sum be returned within the given cell. Similarly for the expenditure, I used ta formula conditional being less than 0, this denoted anything that was minus within the column would also be added up in a seperate cell.

![image](https://github.com/insights000/Accounts-Excel-Spreadsheets-for-Educate-and-Donate-LTD/assets/150028138/f4686cc7-cd66-4417-9fa3-be3a5a1a5ea9)


![image](https://github.com/insights000/Accounts-Excel-Spreadsheets-for-Educate-and-Donate-LTD/assets/150028138/0969ce1a-b150-48f2-af6f-78ed79b1aac6)

**Step 3**
**Creating IN AND OUT Columns**
I created a column in the Excel table that would make it easier to determine what transaction went in and what transaction went out creating a new measure. The formula I used to achieve this was another if conditional whereby the indicator was either "IN" or "OUT" and the condition was if the cell is less than 0, then "OUT", otherwise IN, take a look below at an example of the formula that was dragged down through the column to form the IN AND OUT column.

![image](https://github.com/insights000/Accounts-Excel-Spreadsheets-for-Educate-and-Donate-LTD/assets/150028138/506a4f81-ffef-4011-89df-ad99f86e4ddf)

**Which resulted in this column being created:**

![image](https://github.com/insights000/Accounts-Excel-Spreadsheets-for-Educate-and-Donate-LTD/assets/150028138/b803fdf5-0649-4066-a942-c3d8020263c1)

**Step 4**
The next part of the task invovled sorting how much of the revenue that went out and got spent belonged to each subset, in a column there indicated whether each value was EQUIPMENT, CHARITY, CORPORATION TAX, CLIENT_REFUNDS, PROFESSIONAL_SERVICES, STAFF. Therefore I needed to make a formula that would add up all the individual amounts of expenditure going out and return it to the cell for that given subset.

Here is the column, the indicator of which subset of spending the expenditure was given to.

![image](https://github.com/insights000/Accounts-Excel-Spreadsheets-for-Educate-and-Donate-LTD/assets/150028138/d795cb2e-4ec4-4bd9-9ffa-aa465dc27225)


































