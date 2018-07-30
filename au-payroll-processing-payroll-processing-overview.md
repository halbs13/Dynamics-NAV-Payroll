# Payroll Processing Overview
The following steps must be completed in sequence to successfully produce the payroll:

1.	Select a Payroll for processing
2.	Enter manual adjustments and exceptions in the Pay Journals and/or Transfer Timesheets
3.	Calculate pays
4.	Validate pay journal lines
5.	Create the payment 
6.	Run Pay Journal Reports
7.	Post and print the Payroll Journals
8.	Close the Pay period.

These steps do not include every task that can be performed to generate pays. 
End of Month processes must be performed after the pay(s) has been produced.

*	[Payroll Selection](au-payroll-processing-payroll-selection.md)
*	[Pay Journal](#pay-journal) 
* [End of Month](au-payroll-end-of-month-processing.md)

## Pay Journal
You can access the Pay Journal from the following menu:

*Departments/Payroll/Payroll Processing/Pay Journal*
 
The Pay Journal is used to enter payroll transactions for exceptions if the employee is automatically paid or Time sheet entry if the employee is not automatically paid.  

Various icons are used to calculate, validate, create payments, post, and report the pays.

You must select a Payroll if you have not previously selected a default Payroll. 

Once the Payroll has been selected on the Pay Journal form all payroll transactions required to create a pay are entered or automatically generated from the transactions you setup for each employee in their Payroll Employee card.  

Only the payroll transactions that change from pay to pay are manually entered (E.g. Personal and Annual Leave, bonus payments etc).  

From the Process section on the Home ribbon,  **"Calculate Pays”** must be selected to generate the transactions setup in the Payroll Employee card.  This function evaluates all the manually entered and pre-generated transactions and generates additional transactions for tax, superannuation, net pay dissections, deductions, etc.

Once the pay is calculated for the employee the transactions cannot be changed on the pay journal.  If changes are required you must use the **“Cancel Calculated Pays”** icon from the Functions section of the Actions ribbon.  

Once the pays have been cancelled you can then make the required changes to the Pay Journal Lines or Payroll Employee cards if required.  

Once you are satisfied with the manual entries run the **"Calculate Pays"** function again. This process can be repeated until you are satisfied the transactions are correct.

After you have finished this process you may create the payment and then post the pay journal to the General ledger.

 
#### Pay Journal 

|Field|	Comments|
|---|---|
|Batch|	This field displays the default Payroll Batch name|
|Payroll No.|	This field displays the Payroll selected for processing.|
|Tax Year/Period|	This field is used to select the “Tax Year” for the Payroll.  You can only select an open Tax Year.  |
|Tax Period|	This field is used to select the “Period” for the Payroll.  By default the current period (the next period after the last closed pay period) is displayed.  You can select a future period if you wish but you cannot post periods out of sequence. |
|Working Date Filter|This field is blank by default.|  
||It can be used as a filter by entering a date to limit the journal lines displayed.|
||If time sheets are entered daily, the date can be entered to limit the pay journals lines entered for a specific day.|
||**Note** To finalise a pay run you must set this field to blank to display every journal line for payroll processing.|
|Employee Filter|This field is blank by default.|
||It can be used as a filter to display journals lines for a specific employee.|
||You can enter an Employee Code. or select a code by selecting the “ArrowDown”.|
|Display Sequence|	This field is used to change the sequence of the displayed journal lines |
||Select an option by selecting the “Arrow Down”.|
||The fields described below may not be required by every organisation.  To select or hide columns in the Pay Journal Line by right clicking in the Journal Headings, select “Choose Columns” then select the columns you wish to Show or Hide.|
|Posting Date	|This field displays the posting date.  |
||The date must be the same for every record in this pay run.  Any records in the current pay run that have a different Posting Date will cause errors during payroll posting. | 
||This field is populated using the “Pay Date” entered when calculating the pays.|
|Document Date|	This field is used to select the Work date. | 
||The default date is the work date entered in the Work Date field.  If the Work date field is left blank then the current pay period end date is used.|
|From / To Date|	These fields are used to enter leave or specific transaction date ranges if required. | 
||A combination of the Document Date and the To Date for the Period prints on the Standard Pay Advice against the Leave Transaction.|
|Document No.|	This field displays the Document Number for the Document Type.|
|Document Type	|This field displays the Document Type (Superannuation, EFT, Pay Cheque or Cash).|
|Type	|This field displays the type (Employee, Bank Account or Gang).|
||**Note** Bank Account is system generated for EFT payments and represents the amount to be paid to the employer bank. | 
|No.	|This field is used to select the code for an employee or gang, dependant on the Type.  The “ArrowDown” is used for selection.|
|Shift Code	|This field is used to select the shift for this Pay Transaction.  This field may also be populated from the Calculate Payroll for employees on shift rosters.|
|Pay Advice No.	|This field is system generated but can be manually overridden.|  
||The “Pay Advice No.” starts from “1” (used for standard period pay) each pay period for each employee.  You can enter as many Pay Advice numbers as you wish for an employee for a pay run.|  
||E.g. Pay Advice 2 can be used to pay leave in advance because you wish the payment kept separate to the employee’s standard pay.|
|Superannuation Code	|This field displays the Super Company code for Superannuation Transaction Types.  You can edit this field when using the Superannuation document type|
|Transaction Type Code	|This field is used to select the Pay Transaction Type (e.g. Ordinary, Sick or Annual Leave etc).|
||To see the available Transaction types select the “ArrowDown”.|
|Associated Transactions	|This field indicates if the Pay Transaction Type has Associated transactions generated when ticked.|
|Description|	This field displays the Pay Transaction Type description.|
|Classification Code	|This field displays the default award classification for the employee.  It can be overridden to pay the employee a different Classification in this pay line |
|Branch Code|	When left blank, the payroll transaction uses the Branch Code entered on the Payroll Employee card.  |
||If a Branch code is entered, the payroll transaction uses the Branch Code entered.|
||Branch Codes are selected via the “ArrowDown” in the field.|
|Division Code	|When left blank, the payroll transaction uses the Division Code entered on the Payroll Employee card.  
||If a Division code is entered, the payroll transaction uses the Division Code entered.|
||Division Codes are selected via the “ArrowDown” in the field.|
|Payroll Posting Group	|The “Payroll Posting Group” defaults from the Payroll card.|
|Transaction Posting Group	|The “Transaction Posting Group” defaults from the Transaction Type.  You may override this field.
|Global Dimension 1 |This field is named in General Ledger Setup)	|When left blank the Pay Transaction takes the Global Dimension 1 from the default entered on the Payroll Employee card. |
||If a Global Dimension 1 is entered, it will be used. To see the Global Dimension 1 values, select the “ArrowDown” in the field.|
|Global Dimension 2 (This field is named in General Ledger Setup)	|When left blank the Pay Transaction takes the Global Dimension 2 from the default entered on the Payroll Employee card. If a Global Dimension 2 is entered, it will be used. 
||To see the Global Dimension 2 values, select the “ArrowDown” in this field.|
||If your organisation uses additional Dimensions you must add them by selecting the “Navigate ribbon/Dimensions” |
|Job No.|	If your organisation uses the Jobs Granule for Payroll enter the Job Number that the employee was working on. | 
||If left blank the default job from the Payroll Employee card is used.|
|Job Task No.|	This field is used to select the Task.  |
||When left blank, the payroll transaction uses the Task Code entered on the Payroll Employee card. |
||If a task code is entered, the payroll transaction uses the Task Code entered. |
||Task Codes are selected via the “ArrowDown” in the field.|
|Override Cost Allocations	|This field is used to override the Employee’s Cost Allocation percentage split for this pay journal line.|
|Start Time	|Enter a Start and End Time to automatically calculate the Hours / Mins and units|
|End Time|	Enter a Start and End Time to automatically calculate the Hours / Mins and units|
|Hrs: Mins	|Enter the hours and minutes worked and the system will calculate the number of units to be paid.|
|Units |	The “Units” field is only used for Transaction Types when a "Rate" is entered.|
||Unit can be Hours/Decimals, Kilometres, Number of occurrences, etc.|
|Rate of Pay	|This field displays the Rate from the Payroll Employee card and can be overridden.|
|Hourly Rate	|This field displays the hourly rate of pay for the transaction type and it can be overridden.|
|Amount	|This field displays the amount to pay to the employee for this pay transaction type.  The amount is calculated by the rules setup for the Pay Transaction Type. | 
||The amount field cannot be overridden when a value is entered in the Units field.|
|Currency Factor	|If your organisation is using multiple currencies the currency conversion factor is displayed in this field.|
|Currency Code	|If your organisation is using multiple currencies then the currency code is displayed.|
|Amount (LCY)	|This field displays the same value as the “Amount” field and is used by the system when posting the payroll transactions to the General Ledger.|
||The value in this field cannot be overridden.|
|Charge Hours|	If your organisation uses charge out rates for your employees enter the number of hours charged out.|
|Charge Rate	|If your organisation charges out your employees the “Charge Rate” from the Payroll Employee card is displayed.|
|Charge Amount|	If your organisation charges out your employees this field displays the amount of the charge out.|
|Work Gang No.|	If you have selected “Gang” in the “Type” field for this Pay Line you must enter or select the “Work Gang No.”.|
|Subtract From Permanent Hours|	This field is used to indicate the units entered are subtracted from the units of permanent hours set up on the Payroll Employee card Gross & Allowances.|
||This field is only used for Auto Pay Employees. To subtract leave hours from ordinary hours|
||The Pay Transaction Type may have this flag setup as a default, if so you may override the flag for this Pay line.|
|Bal. Account Type	|This field displays the General Ledger Balancing account type.  You cannot override the value here.|
|Bal. Account No.	|This field displays the General Ledger Balancing account number.|
|Bank Payment Type	|This field is used to indicate the Pay Payment Type. EFT, Manual Cheque, Computer Cheque, Cash, etc|

Additional information is displayed below the journal lines on the Pay Journal card.  This information relates to the currently selected journal line. 


|Field|	Comments|
|---|---|
|Pay Description|	This field displays the description column for the selected transaction journal line.|
|Employee Name|	This field displays the full name of the employee for the selected journal line.|
|Balance	|This field displays the sum of the amount field from the first transaction to the selected transaction for the selected employee. | 
|Total Balance	|The “Total Balance” is the sum of the amount field for all the displayed pay journal line(s).|


##### Pay Journal – Home ribbon 

The Home ribbon allows for certain processes to be executed.  

|Field	|Comments|
|---|---|
|Manage Section|
|Delete|	This option allows you to delete an un-calculated transactions.|
|Process Section|
|Calculate Pays	|This option uses the manually entered transactions, plus the Allowances and Deductions set up for each Employee in their Payroll Employee card and generates the Journal Pay Transactions|
|Post|	This option posts the Pay Journal to the General Ledger.  Once you have Posted the Payroll to the General Ledger the amounts cannot be deleted, and errors must be corrected by reversing entries.|
||If posting is attempted while an error in the data exists the system will not post any of the data.|
|Post and Print	|This option performs the post process and also prints a copy of the test report.|
|Entry Validation Report	|This option is used to check the validity of the transactions in the pay journal.  It must be run and printed before the system allows you to create payments and post the payroll to the General Ledger |
||When error messages occurs on the “Entry Validation Report”, posting to the General Ledger is not possible until the errors have been corrected.|
||When warning messages occur you can post the payroll to the General Ledger correcting the warnings is optional|
|Create Bank Transfer File|	This option is used to create the file of payments for EFT paid employees to be interfaced to your selected bank for each net pay dissection. | 
||The dissections have previously been set up on the Payroll Employee card Employee button, Pay Dissections.|
|Calculate An Employee’s Pay	|This option performs the same function as Calculate Pays for a specific employee or range of employees.|
|Cancel Bank Transfer	|This option is used to cancel the Bank Transfer file|
|Page section|
|Refresh	|The Refresh function will refresh data on the Pay Journal page.|
|Find	|The Find function is used to Find information contained in the Pay Journal.|

#### Pay Journal – Actions ribbon 

The Actions ribbon allows for certain processes to be executed.  

|Field	|Comments|
|---|---|
|Functions section|
|Add Default Roster|	This option is used to copy the selected employee’s default roster into the pay journal. | 
||You do not need to perform this function to calculate an employees pay.  The “Calculate Pays” function automatically generates and pays the Employee’s roster.||
|Add Permanent Details|	This option is used to create transactions for each permanent deduction and allowance set up for the selected employee.|
||You do not need to perform this function to calculate an employees pay.  The “Calculate Pays” function automatically generates and pays the Employee’s Standard Pay, Allowances, Deductions, etc|
|Transfer Time Sheets	|This option is used to transfer timesheet entries into the Pay Journal|
|Calculate Pays	|This option uses the manually entered transactions, plus the Allowances and Deductions set up for each Employee in their Payroll Employee card and generates the Journal Pay Transactions|
|Calculate An Employee’s Pay	|This option performs the same function as Calculate Pays for a specific employee or range of employees.
Cancel Calculated Pays	This option reverses the Calculations of Pays.|
||All Pay Journal lines created by the Pay Generation function are reversed. | 
||All manually entered Pay Journal lines are flagged as “unprocessed” and may be maintained.|
||You can cancel the Calculated Pays for individual employees or all the employees.|
||When cheques or EFT Payments have been processed the pay calculation cannot be reversed.  You must void the cheques and cancel the bank transfer to cancel the calculated pays.||
||A Calculated Pay cannot be cancelled after you have posted the pay to the General Ledger.  You must process reversing entries in the next pay run to correct the mistakes|
|Posting section|
|Reconcile|	This report is only used if you have flagged the “Control Total By Units” option in “Payroll Setup”. | 
||This option is used to check all manually entered Pay Journal Lines against entered Control Totals for this batch.|  
||If the Control Totals do not balance you will not be able to post the payroll transactions.|
|Test Report	|This option creates a batch listing of the Pay Journal, highlighting any errors that will prevent posting, or warnings.|
|Post	|This option posts the Pay Journal to the General Ledger.  Once you have Posted the Payroll to the General Ledger the amounts cannot be deleted, and errors must be corrected by reversing entries.|
||If posting is attempted while an error in the data exists the system will not post any of the data.|
|Post and Print	|This option performs the post process and also prints a copy of the test report.|

#### Pay Journal – Navigate ribbon 

The Navigate ribbon allows for certain processes to be executed.  

|Field|	Comments|
|---|---|
|Employee section|
|Card	|This option is used to display the Payroll Employee card.|
|Ledger Entries	|This option is used to display all Employee ledger entries.|
|G/L Cost Allocations	|This option is used to display the cost allocations for the selected Pay Journal Line.|
|Job Cost Allocations	|This option displays the job cost allocations for the selected Pay Journal Line.|
|Associated Transactions	|This option displays the transactions associated with the current Pay Journal Line.|
||You can use this window to make additions, deletions, and modifications to the associated transaction|
|Pay Details Enquiry	|This option defaults to the selected employee, but you can select another employee.|
||The report displays an employee’s pay details without calculating the pay.  Details for current pay, YTD accumulations, and leave accruals are displayed or printed.|
|Pay Preview	|The selected employee’s pay details, without calculating the pay is displayed. |
|Line section|
|Pay Header	|This option is used to maintain the “No. Tax Weeks”, “No. Leave Periods”, “No. Deduction Periods”, “No. Allowance Periods” and “Payment Method” in the Pay Header details for the selected Employee.|
||**Note:** Once the pay advice has been calculated you can only change the “No. Leave Periods” and “Payment Method” fields.|
|Leave Accruals	|This option displays the period and to-date totals for all Leave accruals accumulated for the selected employee.|
|Dimensions	|You have the ability to override the employees Global Dimensions 1 and 2 on the Pay Journal line.  If your organisation uses other Dimensions they can be maintained on this card.|
|Reports section|
|Entry Validation Report	|This option is used to check the validity of the transactions in the pay journal.  It must be run and printed before the system allows you to create payments and post the payroll to the General Ledger |
||When error messages occurs on the “Entry Validation Report”, posting to the General Ledger is not possible until the errors have been corrected.|
||When warning messages occur you can post the payroll to the General Ledger correcting the warnings is optional|
|Details Generated Report	|This option prints a detailed list of each employee pay.|
|Payroll Details Report	|This option prints a detailed breakdown of the pay run.|
|Payroll Summary Report	|This option prints a breakdown of the payroll by transaction type.|
|Payroll Payment Details	|This option prints a breakdown of the pay run by payment type.|
|Employee Not Paid	|This option prints a report identifying employees not paid in this run.|
|Batch Print Reports	|This option is used to print the above reports in a batch process. Each report can be individually selected or de-selected from the batch print process.|
||If the “Entry Validation Report” reports any errors in the pay run then the batch print process will not allow you to print the reports.|
|Payment section|
|Payment Details	|This option displays all payments made in this pay for the selected employee.|
|Preview Cheque	|When an Employee is paid by cheque this option displays the details for the cheque printed for the currently selected Employee's Net Pay.|
|Print Cheque| This option prints the Cheques for the Payroll prior to posting the pay Run. You must enter the Bank Account The payment is made from|
||Cheque Ledger Entry records for the Bank Account will be updated with the cheques produced.|
||After the cheques are printed you cannot Cancel the Employee's Pays or delete the journal lines unless the cheques are voided first.|
|Void Cheque	|This option is used to void the currently selected cheque|
|Void All Cheques	|This option is used to void all cheques in the current Pay run.|
|Create Bank Transfer |File	This option is used to create the file of payments for EFT paid employees to be interfaced to your selected bank for each net pay dissection.  |
||The dissections have previously been set up on the Payroll Employee card Employee button, Pay Dissections.|
|Cancel Bank Transfer	|This option is used to cancel the Bank Transfer file|
|Pay Cash\Manual Cheques	|This option produces a coinage analysis report for employees with a Payment Type of “Cash” and flags the Pay Advice as paid|
Cancel Cash\Manual Cheques	|This option cancels the Pay Cash or Manual Cheque function.|

 
