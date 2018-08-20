# End of Month Processing Work Cover

Work Cover is used to:

- [Create the Workers Compensation Ledger entries](#create-work-cover-ledger-entries)
- [Calculate the Workers Compensation Expense](#calculate-work-cover-expense)
- [Post the Workers Compensation Expense to the General Ledger](#post-work-cover-expense)


## Create Work Cover Ledger Entries

Workers Compensation is calculated as a percentage of the Employee's Pay.  The amounts are calculated on Pay Transaction Types that are flagged as "Apply to Work Cover".  This amount is recorded as the "Gross Value Applicable to Work Cover".

Pay transactions that are not applicable to Work Cover are calculated and stored as "Value of Gross not applicable to Work Cover".  The Rate of contribution factor is then calculated using the percentage stored in the Work Cover Rate record.

1.  In the **Search** box, enter **Create Ledger Entries**, and choose the related link. Or go to the following menu: *Department/Payroll/EOM Processing/Work Cover Processing/Create Ledger Entries*
 
2.  On the **Options** FastTab, fill the fields as described in the following table.

|Field	|Filter|
|---|---|
|**External Document No.**|	This field is Mandatory.  |Enter a meaningful document name or number to help you identify where the transactions have come from when you review the transactions in the General Ledger.
|**Report Only**	|Select this field if you want to preview or print the information in “Report Only” mode.
|**Include Calculated**|	Select this field if you want to include already calculated transactions.
|**Consolidate Dates**	|Select this field if you want the transactions to be consolidated by date.
|**Consolidate Employees**|	Select this field if you want the transactions to be consolidated by employee.


3.  On the **Employee Ledger Entry** FastTab, fill the fields as described in the following table.

|Field|	Filter|
|---|---|
|**Tax Year**|	Enter the Tax Year you wish to process.
|**Period No.**|	Enter the Pay Period(s) you wish to process.
|**Work Cover Code**|	Enter the Workers Comp. Code you wish to process


## Create Work Cover Ledger Entries Report

The fields on the Create Work Cover Ledger Entries Report are:

|Report Field	|Field No.|	Obtained from|
|---|---|---|
|**Employee No.**	|(1)|	This is the Employee No. field.
|**Name**	|(2)|	This is the Name of the employee.
|**Work Cover Rate Code**	|(3)|	This is the value of the Work Cover Rate Code as established in the setup.
|**Description**	|(4)|	This is the Description of the Work Cover Rate as established in the Work Cover Rate Code.
|**Work Cover Location Code**	|(5)|	This is the value of the Work Cover Location Code as established in the setup.
|**Description**	|(6)|	This is the Description of the Work Cover Location as established in the Work Cover Location Code.
|**Value of Gross Not Applicable to Work Cover**	|(7)|	This is the sum of the transactions which are not applicable to Work Cover.
|**Gross Value Applicable to Work Cover**|(8)|	This is the sum of the transactions which are applicable to Work Cover.
|**Levy %**|(9)|	This is the Levy percentage of the Work Cover Rate as established in the setup.
|**Work Cover Contribution**	|(10)|	This is the sum of the Work Cover Contribution for the reporting period.

[GoToTop](#end-of-month-processing-work-cover)

## Calculate Work Cover Expense

The Calculate Work Cover Expense process calculates the Work Cover Expense to post to the General Ledger.

Work Cover is calculated as a percentage of the Employee's Pay.  The value used in the calculation is any Pay Transaction Type that is flagged as "Apply to Work Cover.".  This amount is recorded as the "Gross Value Applicable to Work Cover".

Pay transactions that are not applicable to Work Cover are also calculated and stored as "Value of Gross not applicable to Work Cover ".  
The Rate of contribution factor is then calculated using the percentage stored in the Work Cover Rate record.

1.  In the **Search** box, enter **Calculate Work Cover Expense**, and then choose the related link.  Or go to the following menu:  *Departments/ Payroll/Periodic Activities/Work Cover/Calculate Expense*
 
 2.  On the **Options Entry** FastTab, fill the fields as described in the following table.

|Field	|Comments|
|---|---|
|**Date of Calculation**|	The “Date of Calculation” is the date the provision is calculated.
|**Calculate Levy Rate**	|- Current Configuration
||- Originally Created
||- Updated from Setup

3.  On the **Work Cover Ledger Entry** FastTab, fill the fields as described in the following table.

|Field	|Filter|
|---|---|
|**Document Date**|	Enter in Document Date as a filter.


[GoToTop](#end-of-month-processing-work-cover)

### Post Work Cover Expense

The Post Work Cover Provision Report will post the Calculated Work Cover Provision to the General Ledger Granule in NAV Financials.

To open the Post Work Cover Provision window, 

*Departments/Payroll/Periodic Activities/Work Cover/Post Expense*
 
#### Post Work Cover Expense – Options FastTab

|Field	|Comments|
|---|---|
|Posting Date	|The “Posting Date” of the expense.
|Document No.	|The “Document No.” of the expense.
|Report Only	|Select this option to produce a report to review entries before you post them.
||Leave this option blank to produce a report and to post workers compensation ledger entries to the General Ledger.  


#### Post Work Cover Expense – Work Cover Ledger Entry FastTab

|Field	|Filter|
|---|---|
|Only the standard fields are covered.  A full list of fields available as filters can be used by selecting the first blank line and selecting the “ArrowDown”.
|Document Date|	The “Document Date” range of the Work Cover Ledger Entries to be processed.

 
 [GoToTop](#end-of-month-processing-work-cover)
