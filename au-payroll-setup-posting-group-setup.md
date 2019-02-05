# To setup Payroll Posting Groups

Payroll Posting Groups define the Bank Account to pay the employee from for the payroll.  They are also used to determine the General Ledger accounts used for posting.

Each Payroll is assigned to a Payroll Posting Group.  More than one Payroll Posting Group may be setup depending on your General Ledger requirements, e.g. Employees, Contractors.

1. In the **Search** box, enter **Payroll Posting Group**, and then choose the related link, or go to the following menu: *Posting Group Setup/Payroll Posting Groups*

2.  To create a new record, click on the **New** button.
  
|Field|Description|  
| :--- | :--- |  
|**Code**| Enter in a code to identify the Payroll Posting Group.|
|**Description**| Enter in a description to identify the Payroll Posting Group.|
|**Bank Account No.**| The “Bank Account No” is selected from a list of bank accounts set up in the General Ledger Granule. The “Bank Account No.” selected is the default bank account used to pay the employees by EFT.|

3.  Click on the **OK** button after you have completed your selection.
  
The **Setup** icon opens the [Payroll Posting Setup](#to-setup-payroll-posting-setup).  The Payroll Posting Setup is specific to the selected Payroll Posting Group on this nested form.

The **Dimensions** link on the *Process* menu allows for Dimensions to be setup and used to default when posting Leave Transactions with missing dimensions.

[GoToTop](#how-to-setup-payroll-posting-groups)


# To setup Transaction Posting Groups

Transaction Posting Groups are used to determine the General Ledger accounts used for posting.  Each Pay Transaction Type is assigned to a Transaction Posting Group. Together with Payroll Posting Groups, Branch and Divisions you can direct transaction to post to different GL accounts.


1. In the **Search** box, enter **Transaction Posting Groups**, and then choose the related link, or go to the following menu: *Posting Group Setup/Transaction Posting Groups*

2.  To create a new record, click on the **New** button.
  
|Field|Description|  
| :--- | :--- | 
|**Code**| Enter in a code to identify the Transaction Posting Group.|
|**Description**| Enter in a description to identify the Transaction Posting Group.|

3.  Click on the **OK** button after you have completed your selection.

The **Setup** link opens the [Payroll Posting Setup](#to-setup-payroll-posting-setup) from the *Actions* menu.  The Payroll Posting Setup is specific to the selected Payroll Posting Group on this nested form.

[GoToTop](#how-to-setup-payroll-posting-groups)


## To setup Payroll Posting Setup

The Payroll Posting Setup card is used to post to specific GL Accounts in the General Ledger granule.  

This card is used to establish relationships between Payroll Posting Groups, Transaction Posting Groups, Branches, Divisions and General Ledger Accounts.  The first four of these fields are used to direct the General Ledger account used for posting a pay transaction. 

The source fields used to select the General Ledger account are as follows:

- Payroll Posting Group – Payroll Card 
- Transaction Posting Group – Transaction Type
- Branch – Payroll Employee Card
- Division – Payroll Employee Card

You can enter specific Transaction Posting Groups, Branches or Divisions if the Payroll transactions go to different General Ledger accounts.  Otherwise they can be left blank to include all Payroll transactions for the Transaction Posting Groups are used to
determine the General Ledger accounts used for posting.  Each Pay Transaction Type is assigned to a Transaction Posting Group.  Together with Payroll Posting Groups, Branch and Divisions you can direct transaction to post to different GL accounts.

1.  To access the Payroll Posting Setup, go to the following menu: *Posting Group Setup/Payroll Posting Setup*

2.  To create a new record, click on the **New** button.
  
|Field|Description|  
| :--- | :--- |
|**Transaction Posting Group**| Select the Transaction Posting Group from the **ArrowDown**.|
|**Payroll Posting Group**| The “Payroll Posting Group” is optional and can be selected from the **ArrowDown**.|
|**Branch Code**| The “Branch Code” is optional and can be selected from the **ArrowDown**.|
|**Division Code**| The “Division Code” is optional and can be selected from the **ArrowDown**.|
|**Pay Account**| The “Pay Account” identifies the GL account the transaction will post to and can be selected from the **ArrowDown”**.|
|**Account Name**| The name of the General Ledger Account selected will appear in this field.|


[GoToTop](#how-to-setup-payroll-posting-groups)


