Posting Group Setup
This section covers the setup of Payroll Posting Groups, Transaction Posting Groups, and the relationships to each other, Branch Codes, Division Codes, and to General Ledger Accounts.

•	Payroll Posting Groups
•	Transaction Posting Groups
•	Payroll Posting Setup

  
 
10.5.1	Payroll Posting Groups 
Payroll Posting Groups define the Bank Account to pay the employee from for the payroll.  They also are used to determine the General Ledger accounts used for posting.  Each Payroll is assigned to a Payroll Posting Group.  More than one Payroll Posting Group may be setup depending on your General Ledger requirements. (E.g. Employees, Contractors)

To open the Payroll Posting Groups window,

Departments/Payroll/Setup/Payroll Setup/Posting Group Setup/Payroll Posting Group  
 

Field	Comments
Code	The “Code” is used to identify this Payroll Posting Group.
Description	The “Description” is used to name this Payroll Posting Group. 
Bank Account No.	The “Bank Account No” is selected from a list of bank accounts set up in the General Ledger Granule.  
The “Bank Account No.” selected is the default bank account used to pay the employees by EFT 

The “Setup” button opens the “Payroll Posting Setup”.  The Payroll Posting Setup is specific to the selected Payroll Posting Group on this nested form.



 
10.5.2	Transaction Posting Groups
Transaction Posting Groups are used to determine the General Ledger accounts used for posting.  Each Pay Transaction Type is assigned to a Transaction Posting Group. Together with Payroll Posting Groups, Branch and Divisions you can direct transactions to post to different GL Accounts

To open the Transaction Posting Groups window  

Departments/Payroll/Setup/Payroll Setup/Posting Group Setup/Transaction Posting Group
 


Field	Comments
Code 	This field is used to uniquely identify the Transaction Posting Group.
Description	This field is used to name the Transaction Posting Group.

 
10.5.3	Payroll Posting Setup
The Payroll Posting Setup card is used to post to specific GL Accounts in the General Ledger Granule.

This card is used to establish relationships between Payroll Posting Groups, Transaction Posting Groups, Branches, Divisions, and General Ledger Accounts.  The first four of these fields are used to direct the General Ledger account used for posting a pay transaction.

The sources fields used to select the General Ledger account are as follows.

•	Payroll Posting Group - Payroll card
•	Transaction Posting Group - Transaction Type
•	Branch - Employee card
•	Division - Employee card

You can enter specific Transaction Posting Groups, Branches or Divisions if the Payroll transactions go to different General Ledger accounts.  Otherwise they can be left blank to include all Payroll transactions for the Transaction Posting Groups, Branches and Divisions for the same General Ledger account.  

For example if you want Branch number “1” to go to General Ledger Account 12345 but all other Branches to go to General Ledger Account 54321 then you would enter “1” in the Branch column against Pay Account 12345.
In addition to their role in determining the General Ledger accounts used for posting payroll transactions, the Branch and Division are used for sorting data in many reports and document.

To open the Payroll Posting Setup window 

Departments/Payroll/Setup/Payroll Setup/Posting Group Setup/Payroll Posting Group
 

Field	Comments
Transaction Posting Group	Select the Transaction Posting Group from the “ArrowDown”.
Payroll Posting Group	The “Payroll Posting Group” is optional and can be selected from the “ArrowDown”.
Branch Code	The “Branch Code” is optional and can be selected from the “ArrowDown”.
Division Code	The “Division Code” is optional and can be selected from the “ArrowDown”.
Pay Account	The “Pay Account” identifies the GL account the transaction will post to and can be selected from the “ArrowDown”.
Account Name	The name of the General Ledger Account selected.

Related Tasks 
Posting Group Setup
