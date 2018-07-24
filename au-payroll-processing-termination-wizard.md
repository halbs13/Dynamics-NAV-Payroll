# 4.9.2	Termination Wizard
Termination payments can be calculated automatically in Dynamics NAV Payroll using the Termination Wizard calculation function.

The Termination Wizard has been designed to cater for the following types of termination payments;

*	Voluntary resignation
*	Termination by notice given by the employer
*	Termination of a fixed term employment contract
*	Death of an employee
*	Breach of contract, including employee misconduct
*	Redundancy
*	Invalidity
*	Retirement to an approved retirement scheme

It is recommended that any Ordinary and Termination payments be processed on separate pay advices and preferably after the main pay has been processed.  This will ensure that the leave accrual is updated correctly prior to calculating the employee’s final payment.

Further information relating to the calculation of termination payments can be located on the ATO website at www.ato.gov.au.

Prior to processing Termination payments, you will need to ensure the following setup has been completed;

*	Termination Reason Codes have been established,
*	The relevant Pay Transaction Types has been established,
*	Termination Pay Transactions have been defined on the Termination FastTab on Payroll Setup card.

# 4.9.2.1	Termination Payment Processing Overview
The Termination Wizard will assist you in calculating an employee’s final payment upon termination.  

The following is a guideline to the recommended steps of processing:

1.	Finalise and Ordinary payment including worked hours, etc. on Pay Advice 1, if applicable.
2.	If the payment for Worked hours has not yet been posted, you will need to calculate out the accrual for these hours to include in your calculations.
3.	Calculate the termination payment for unused annual leave, etc. using the Termination Wizard.
4.	Transfer the termination payment from the wizard to the pay journal using the **“Create Journal”** function.
5.	Calculate the employee’s pay
6.	Select the **“Close & Copy”** icon, this will update the Employee card with the Termination date and Termination reason.
7.	Create the EFT bank file
8.	Post the journal lines and print pay advices.
To open the Termination Wizard window

Departments/Payroll/Payroll Processing/Termination Wizard

# 4.9.2.2	Standard Termination 
The following steps will demonstrate how a termination payment is calculated for an employee who resigns of their own record and is not entitled to an ETP.

# 4.9.2.2.1	Employee Form
Complete the initial screen with the employee’s details such as employee number, the reason and date for termination.

|Field	|Comments|
|---|---|
|Employee No.|	Enter in the employee no. or select from the “ArrowDown”. |
|Name	|This will automatically default from the Employee No. that you select.|
|Reason for Termination	|Select from the “ArrowDown” the reason the employee is terminating.|
|Date of Termination	|Enter in the date of termination for the employee.|
|Select “Next” when you have completed this section.|


# 4.9.2.2.2	Outstanding Long Service Leave Form
Long Service Leave entitlements will automatically calculate from the Employee’s start date to the finish date.  

If the employee is not entitled to this leave entitlement, then override this value by entering zero.
 

|Field	|Comments|
|---|---|
|Accrued Before 16/08/78	|The value of this accrual is identified as a Lump B payment and is taxed accordingly.|
||If the employee has any unused Long Service Leave accrued before the 16th August 1978 the value of service will appear in this field.|
|Accrued After 15/08/78 but Before 18/08/93	|The value of this accrual is identified as a Lump A payment and is taxed accordingly.|
||If the employee has any unused Long Service Leave accrued after 15th August 1978 and before the 18th August 1993 the value of service will appear in this field.|
|Accrued After 17/08/93	|The value of this accrual is identified as Gross Salary & Wages and is taxed accordingly.|
||If the employee has any unused Long Service Leave accrued after 17th August 1993 the value of service will appear in this field. | 
||As noted above Long Service Leave is automatically calculated and may need to be adjusted or overridden.
|Select “Next” when you have completed this section.|

 
# 4.9.2.2.3	Outstanding Annual Leave Form
Annual Leave entitlements are transferred from the Employee’s Leave Accrual card. 

|Field	|Comments|
|---|---|
|Before 18/08/93|	
|Accrued Trans. Type	|The value of this accrual is identified as a Lump A payment and is taxed accordingly.|
||If the employee has any unused Annual Leave accrued before the 18th August 1993 the value of service will appear in this field.|
|Loading Trans. |Type	The value of this accrual is identified as a Lump A payment and is taxed accordingly.|
||If the employee has any unused Leave Loading accrued before the 18th August 1993 the value of service will appear in this field.
|After 17/08/93	|
|Accrued Trans. Type	|The value of this accrual is identified as Gross Salary & Wages and is taxed accordingly.|
||If the employee has any unused Annual Leave accrued after 17th August 1993 the value of service will appear in this field. | 
|Loading Trans. Type	|The value of this accrual is identified as Gross Salary & Wages and is taxed accordingly.|
||If the employee has any unused Leave Loading accrued after 17th August 1993 the value of service will appear in this field.|  
|Tax Free Lump Sum D	|This will be discussed in the next section as it relates to ETP or Redundancy payments.|
|Select “Next” when you have completed this section.|

# 4.9.2.2.4	Employee Termination Request Form
The Employee Termination Payment screen allows you to enter in the components for the Employee Termination Payments.  For this exercise, select “Next” as this will be discussed in the following section of this document.

# 4.9.2.2.5	Termination Payment Summary Form
The Termination Payment Summary Window provides you with a breakdown of the unused leave payments calculated.

# 4.9.2.2.6	Termination Report Form
Select the “Reports” button to preview and/or print the Termination Calculation Report.
 
# 4.9.2.3	Redundancy/Retirement/Invalidity Termination 
The following steps will demonstrate how a termination payment is calculated for an employee who is terminated due to a Bona Fide Redundancy, Invalidity or Retirement.

# 4.9.2.3.1	Employee Form
Complete the initial screen with the employee’s details such as employee number, the reason and date for termination. 

|Field	|Comments|
|---|---|
|Employee No.	|Enter in the employee no. or select from the “ArrowDown”. |
Reason for Termination	|Select from the “ArrowDown” the reason the employee is terminating.|
|Date of Termination	|Enter in the date of termination for the employee.|
|Select “Next” when you have completed this section.|

# 4.9.2.3.2	Outstanding Long Service Leave Form
Long Service Leave entitlements will automatically calculate from the Employee’s start date to the finish date.  If the employee is not entitled to this leave entitlement, then you can override the value by entering zero.  

**Note:** the value of Long Service Leave is categorised as a Lump A payment and appears in the “Accrued After 15/08/78 but Before 18/08/93” section.  Lump A tax rulings will be calculated and applied accordingly.

|Field	|Comments|
|---|---|
|Accrued Before 16/08/78	|The value of this accrual is identified as a Lump B payment and is taxed accordingly.|
||If the employee has any unused Long Service Leave accrued before the 16th August 1978 the value of service will appear in this field.|
|Accrued After 15/08/78 but Before 18/08/93	|The value of this accrual is identified as a Lump A payment and is taxed accordingly.|
||If the employee has any unused Long Service Leave accrued after 15th August 1978 and before the 18th August 1993 the value of service will appear in this field.|
|Accrued After 17/08/93	|The value of this accrual is identified as Gross Salary & Wages and is taxed accordingly.|
||If the employee has any unused Long Service Leave accrued after 17th August 1993 the value of service will appear in this field. | 
||As noted above Long Service Leave is automatically calculated and may need to be adjusted or overridden.|
|Select “Next” when you have completed this section.|

# 4.9.2.3.3	Outstanding Annual Leave Form
Annual Leave entitlements will transferred from the Employee’s Leave Accrual card.  

**Note:** the value of Annual Leave is categorised as a Lump A payment and appears in the “Before 18/08/93” section.  Lump A tax rulings will be calculated and applied accordingly.

|Field	|Comments|
|---|---|
|Accrued Trans. Type	|The value of this accrual is identified as a Lump A payment and is taxed accordingly.|
||If the employee has any unused Annual Leave accrued before the 18th August 1993 the value of service will appear in this field.|
|Loading Trans. Type	|The value of this accrual is identified as a Lump A payment and is taxed accordingly.|
||If the employee has any unused Leave Loading accrued before the 18th August 1993 the value of service will appear in this field.|
|Accrued Trans. Type	|The value of this accrual is identified as Gross Salary & Wages and is taxed accordingly.|
||If the employee has any unused Annual Leave accrued after 17th August 1993 the value of service will appear in this field. | 
|Loading Trans. Type	|The value of this accrual is identified as Gross Salary & Wages and is taxed accordingly.|
||If the employee has any unused Leave Loading accrued after 17th August 1993 the value of service will appear in this field.|  
|Tax Free Lump Sum D	|Select the “Pay Transaction Type” for the Lump Sum D payment from the “ArrowDown”.|
||Enter in any bona fide redundancy or approved early retirement scheme amount that falls under the “Tax Free” amount defined by the ATO.|
|Pay Transaction Type||
|Value	||
|Select “Next” when you have completed this section.|

# 4.9.2.3.4	Employee Termination Request Form
The Employee Termination Payment window allows you to enter in the components for the Employee Termination Payments.  Select the **“checkbox”** to the right to enter in the appropriate amounts.

 

# 4.9.2.3.5	Employee Termination Payment Form
The Employee Termination Payment Screen is where you will enter in the Employee Termination Payment information for your employee.  

As this information can vary between employees, you will need to manually enter this information into this window.

|Field	|Comments|
|---|---|
|Tax-Free Component (Pre-July 1983 Component Amount)	|Select the pay transaction type from the “ArrowDown” to record your transactions.| 
||Hours – Enter in the hours accordingly.  The Value of this transaction will update automatically and is based on the employee’s current base rate.|
|Taxable Component (Post June 1983 Untaxed Amount)	|Select the pay transaction type from the “ArrowDown” to record your transactions.|
||Hours – Enter in the hours accordingly.  The Value of this transaction will update automatically and is based on the employee’s current base rate.|
|Tax-Free Component (Post June 1994 Invalidity Amount) |Select the pay transaction type from the “ArrowDown” to record your transactions.|
||Hours – Enter in the hours accordingly.  The Value of this transaction will update automatically and is based on the employee’s current base rate.|
|Select “Next” when you have completed this section.|

# 4.9.2.3.6	Employee Termination Payment Summary Form
The Employee Termination Payment Summary form provides a breakdown of the Employee Termination Payment.  

You must select the “ETP Code” from the “ArrowDown” so that the appropriate tax treatment will be applied to the Employee Termination payment. 

|Field	|Comments|
|---|---|
|ETP Code	|The ATO provided a number of categories to identify the treatment of tax associated with Employee Termination Payments. |
||Select the ETP Code from the “ArrowDown”|
|Select “Next” when you have completed this section.|

# 4.9.2.3.7	Termination Payment Summary Form
The Termination Payment Summary Window provides you with a breakdown of the unused leave payments calculated. 

You **must** update the **“Payment Date”** field particularly if this termination payment involves a payout of an Employee Termination Payment as the Payment Date information will appear on the Employee Termination Payment Summary.  

# 4.9.2.3.8	Termination Report Form
Select the “Reports” button to preview and/or print the Termination Calculation Report.
 
# 4.9.2.4	Creating the Pay Journal
The transactions will be processed within the Pay Journal for the employee.  To transfer this information to the appropriate pay journal, select the “Create Journal” button.

# 4.9.2.4.1	Select the Payroll
Select the Payroll No. that the employee belongs to from the Payroll List and select “OK”.

# 4.9.2.4.2	Pay Journal
The entries entered via the Termination Wizard will populate the appropriate journal, ready for you to calculate.  Upon calculation of this payment, no PAYG tax should calculate as the entries are calculated within the Termination Report.


After you have finished transferring the information to the pay journal and calculated the pay, go back to the Termination Wizard Summary screen to finalise the transaction.

# 4.9.2.5	Finalising the Transactions
On the Termination Summary Screen, the “Close and Copy” button updates the relevant areas to update the Termination Date and Reason and if an ETP exists, updates the Employee Termination Payment area of the Payroll Employee card.


# 4.9.2.5.1	Employee Card – Administration Tab
The Status, Termination Date and Reason fields are updated accordingly.

# 4.9.2.5.2	Payroll Employee Card – Employee Termination Payment
The Employee Termination Payment area of the Payroll Employee card is updated.  To access this area, go to the Payroll Employee Card, select “Employee Termination Payment” on the Navigate ribbon.

 

 
