# Termination Wizard

Termination payments can be calculated automatically in Business Central Payroll using the Termination Wizard calculation function.

The Termination Wizard has been designed to cater for the following types of termination payments;

*	Voluntary resignation
*	Termination by notice given by the employer
*	Termination of a fixed term employment contract
*	Death of an employee
*	Breach of contract, including employee misconduct
*	Redundancy
*	Invalidity
*	Retirement to an approved retirement scheme

It is recommended that Ordinary and Termination payments are processed on separate pay advices and preferably after the main pay has been processed.  This will ensure that the leave accrual is updated correctly prior to calculating the employee’s final payment.

Further information relating to the calculation of termination payments can be located on the ATO website at www.ato.gov.au.

Prior to processing Termination payments, you will need to ensure the following setup has been completed;

*	Termination Reason Codes have been established,
*	The relevant Pay Transaction Types has been established,
*	Termination Pay Transactions have been defined on the Termination FastTab on Payroll Setup card.

## Termination Payment Processing Overview

The Termination Wizard will assist you in calculating an employee’s final payment upon termination.  

The following is a guideline to the recommended steps of processing:

1.	Finalise Ordinary payment including worked hours, etc. on Pay Advice 1, if applicable.
2.	If the payment for Worked hours has not yet been posted, you will need to calculate out the accrual for these hours to include in your calculations.
3.	Calculate the termination payment for unused annual leave, etc. using the Termination Wizard.
4.	Transfer the termination payment from the wizard to the pay journal using the **“Create Journal”** function.
5.	Calculate the employee’s pay
6.	Select the **“Close & Copy”** icon, this will update the Employee card with the Termination date and Termination reason.
7.	Create the EFT bank file
8.	Post the journal lines and print pay advices.

To open the Termination Wizard window

1.  In the **Search** box, enter **Termination Wizard**, and choose the related link.  Or go to the following menu: *Departments/Payroll/Payroll Processing/Termination Wizard*

### Standard Termination 

The following steps will demonstrate how a termination payment is calculated for an employee who resigns of their own record and is not entitled to an ETP.

#### Employee Form

1.  Complete the initial screen with the employee’s details such as employee number, the reason and date for termination.

|Field	|Comments|
|---|---|
|**Employee No.**|	Enter in the employee no. or select from the **ArrowDown**. |
|**Name**	|This will automatically default from the Employee No. that you select.|
|**Reason for Termination**	|Select from the **ArrowDown** the reason the employee is terminating.|
|**Date of Termination**	|Enter in the date of termination for the employee.|

2.  Select **Next** when you have completed this section.

#### Outstanding Long Service Leave Form

3.  Long Service Leave entitlements will automatically calculate from the Employee’s start date to the finish date.  If the employee is not entitled to this leave entitlement, then override this value by entering zero.
 

|Field	|Comments|
|---|---|
|**Accrued Before 16/08/78**	|The value of this accrual is identified as a Lump B payment and is taxed accordingly.  If the employee has any unused Long Service Leave accrued before the 16th August 1978 the value of service will appear in this field.|
|**Accrued After 15/08/78 but Before 18/08/93**	|The value of this accrual is identified as a Lump A payment and is taxed accordingly.  If the employee has any unused Long Service Leave accrued after 15th August 1978 and before the 18th August 1993 the value of service will appear in this field.|
|**Accrued After 17/08/93**	|The value of this accrual is identified as Gross Salary & Wages and is taxed accordingly.  If the employee has any unused Long Service Leave accrued after 17th August 1993 the value of service will appear in this field.  As noted above Long Service Leave is automatically calculated and may need to be adjusted or overridden.

4.  Select **Next** when you have completed this section.

##### Outstanding Annual Leave Form

5.  Annual Leave entitlements are transferred from the Employee’s Leave Accrual card. 

|Field	|Comments|
|---|---|
|**Before 18/08/93**|	
|**Accrued Trans. Type**	|The value of this accrual is identified as a Lump A payment and is taxed accordingly.  If the employee has any unused Annual Leave accrued before the 18th August 1993 the value of service will appear in this field.|
|**Loading Trans.** |Type	The value of this accrual is identified as a Lump A payment and is taxed accordingly.  If the employee has any unused Leave Loading accrued before the 18th August 1993 the value of service will appear in this field.|
|**After 17/08/93**	|
|**Accrued Trans. Type**	|The value of this accrual is identified as Gross Salary & Wages and is taxed accordingly.  If the employee has any unused Annual Leave accrued after 17th August 1993 the value of service will appear in this field. | 
|**Loading Trans. Type**	|The value of this accrual is identified as Gross Salary & Wages and is taxed accordingly.  If the employee has any unused Leave Loading accrued after 17th August 1993 the value of service will appear in this field.|  
|**Tax Free Lump Sum D**|This will be discussed in the next section as it relates to ETP or Redundancy payments.|

6.  Select **Next** when you have completed this section.


#### Employee Termination Request Form

7.  The Employee Termination Payment screen allows you to enter in the components for the Employee Termination Payments.  For this exercise, select **Next** as this will be discussed in the following section of this document.


#### Termination Payment Summary Form

8.  The Termination Payment Summary Window provides you with a breakdown of the unused leave payments calculated.


#### Termination Report Form

9.  Select the **Reports** button to preview and/or print the Termination Calculation Report.
 
[GoToTop](#termination-wizard)

### Redundancy/Retirement/Invalidity Termination 

The following steps will demonstrate how a termination payment is calculated for an employee who is terminated due to a Bona Fide Redundancy, Invalidity or Retirement.

#### Employee Form

1.  Complete the initial screen with the employee’s details such as employee number, the reason and date for termination. 


|Field	|Comments|
|---|---|
|**Employee No.**	|Enter in the employee no. or select from the **ArrowDown**. |
|**Reason for Termination**|Select from the **ArrowDown** the reason the employee is terminating.|
|**Date of Termination**|Enter in the date of termination for the employee.|

2.  Select **Next** when you have completed this section.


#### Outstanding Long Service Leave Form

3.  Long Service Leave entitlements will automatically calculate from the Employee’s start date to the finish date.  If the employee is not entitled to this leave entitlement, then you can override the value by entering zero.   **Note:** the value of Long Service Leave is categorised as a Lump A payment and appears in the “Accrued After 15/08/78 but Before 18/08/93” section.  Lump A tax rulings will be calculated and applied accordingly.


|Field	|Comments|
|---|---|
|**Accrued Before 16/08/78**|The value of this accrual is identified as a Lump B payment and is taxed accordingly.  If the employee has any unused Long Service Leave accrued before the 16th August 1978 the value of service will appear in this field.|
|**Accrued After 15/08/78 but Before 18/08/93**	|The value of this accrual is identified as a Lump A payment and is taxed accordingly. If the employee has any unused Long Service Leave accrued after 15th August 1978 and before the 18th August 1993 the value of service will appear in this field.|
|**Accrued After 17/08/93**	|The value of this accrual is identified as Gross Salary & Wages and is taxed accordingly.  If the employee has any unused Long Service Leave accrued after 17th August 1993 the value of service will appear in this field.  As noted above Long Service Leave is automatically calculated and may need to be adjusted or overridden.|

4.  Select **Next** when you have completed this section.

#### Outstanding Annual Leave Form

5.  Annual Leave entitlements will transferred from the Employee’s Leave Accrual card.  **Note:** the value of Annual Leave is categorised as a Lump A payment and appears in the “Before 18/08/93” section.  Lump A tax rulings will be calculated and applied accordingly.

|Field	|Comments|
|---|---|
|**Accrued Trans. Type**	|The value of this accrual is identified as a Lump A payment and is taxed accordingly.  If the employee has any unused Annual Leave accrued before the 18th August 1993 the value of service will appear in this field.|
|**Loading Trans. Type**	|The value of this accrual is identified as a Lump A payment and is taxed accordingly.  If the employee has any unused Leave Loading accrued before the 18th August 1993 the value of service will appear in this field.|
|**Accrued Trans. Type**	|The value of this accrual is identified as Gross Salary & Wages and is taxed accordingly.  If the employee has any unused Annual Leave accrued after 17th August 1993 the value of service will appear in this field. | 
|**Loading Trans. Type**	|The value of this accrual is identified as Gross Salary & Wages and is taxed accordingly.  If the employee has any unused Leave Loading accrued after 17th August 1993 the value of service will appear in this field.|  
|**Tax Free Lump Sum D**|Select the “Pay Transaction Type” for the Lump Sum D payment from the **ArrowDown**.  Enter in any bona fide redundancy or approved early retirement scheme amount that falls under the “Tax Free” amount defined by the ATO.|

6.  Select **Next** when you have completed this section.


#### Employee Termination Request Form

7.  The Employee Termination Payment window allows you to enter in the components for the Employee Termination Payments.  Select the **“checkbox”** to the right to enter in the appropriate amounts.

 
#### Employee Termination Payment Form

8.  The Employee Termination Payment Screen is where you will enter in the Employee Termination Payment information for your employee.  As this information can vary between employees, you will need to manually enter this information into this window.

|Field	|Comments|
|---|---|
|**Tax-Free Component (Pre-July 1983 Component Amount)**	|Select the pay transaction type from the **ArrowDown** to record your transactions.| 
||**Hours** – Enter in the hours accordingly.  The Value of this transaction will update automatically and is based on the employee’s current base rate.|
|**Taxable Component (Post June 1983 Untaxed Amount)**	|Select the pay transaction type from the **ArrowDown** to record your transactions.|
||**Hours** – Enter in the hours accordingly.  The Value of this transaction will update automatically and is based on the employee’s current base rate.|
|**Tax-Free Component (Post June 1994 Invalidity Amount)** |Select the pay transaction type from the **ArrowDown** to record your transactions.|
||**Hours** – Enter in the hours accordingly.  The Value of this transaction will update automatically and is based on the employee’s current base rate.|

9.  Select **Next** when you have completed this section.

#### Employee Termination Payment Summary Form

10. The Employee Termination Payment Summary form provides a breakdown of the Employee Termination Payment.  

11. You must select the **ETP Code** from the **ArrowDown** so that the appropriate tax treatment will be applied to the Employee Termination payment. 

|Field	|Comments|
|---|---|
|**ETP Code**	|The ATO provided a number of categories to identify the treatment of tax associated with Employee Termination Payments.  Select the ETP Code from the **ArrowDown**.|

12. Select **Next** when you have completed this section.


#### Termination Payment Summary Form

13. The Termination Payment Summary Window provides you with a breakdown of the unused leave payments calculated.  You **must** update the **“Payment Date”** field particularly if this termination payment involves a payout of an Employee Termination Payment as the Payment Date information will appear on the Employee Termination Payment Summary.  


#### Termination Report Form

14. Select the **Reports** button to preview and/or print the Termination Calculation Report.

 
#### Creating the Pay Journal

15. The transactions will be processed within the Pay Journal for the employee.  To transfer this information to the appropriate pay journal, select the **Create Journal** button.


#### Select the Payroll

16. Select the Payroll No. that the employee belongs to from the Payroll List and select **OK**.


#### Pay Journal

17. The entries entered via the Termination Wizard will populate the appropriate journal, ready for you to calculate.  Upon calculation of this payment, no PAYG tax should calculate as the entries are calculated within the Termination Report.


18. After you have finished transferring the information to the pay journal and calculated the pay, go back to the Termination Wizard Summary screen to finalise the transaction.


### Finalising the Transactions

19. On the Termination Summary Screen, the **Close and Copy** button updates the relevant areas to update the Termination Date and Reason and if an ETP exists, updates the Employee Termination Payment area of the Payroll Employee card.


#### Employee Card – Administration Tab

The Status, Termination Date and Reason fields are updated accordingly.


#### Payroll Employee Card – Employee Termination Payment

The Employee Termination Payment area of the Payroll Employee card is updated.  To access this area, go to the Payroll Employee Card, select [Employee Termination Payment](au-payroll-create-payroll-employee-employee-termination-payment.md) on the Navigate ribbon.

 
[GoToTop](#termination-wizard)
 
 
