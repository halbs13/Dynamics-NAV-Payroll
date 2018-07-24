# End of Month Processing - Superannuation

*Departments/Payroll/EOM Processing/Superannuation Processing*

 Superannuation processing includes the following activities:
* Bulk Adjustment
* Calculate Monthly Superannuation  
* Calculate & Post Superannuation
* Super. Payment Export & Notification
* Super. Payment Export Reversal
* New Member Registration Export
* Super. Payment History 
* Superannuation Reports

 
### Calculate Monthly Superannuation

This option is only used when the On Cost method for calculating employer SGC contributions is used and where the “Calc. Superannuation Monthly” flag is selected on the “Payroll” card to create monthly superannuation transactions to post to the General Ledger.  This process moves the superannuation transactions from the Employee Ledger Entries to the Employee Superannuation Ledger entries and it must be run before the Calculate and Post Superannuation process.

This process updates the Employee Superannuation Ledger Entry with on-cost superannuation transaction details for Posting to the General Ledger when the “Calculate & Post Superannuation” process is run.  You must print this report for the process to move the on-cost transactions to the Employee Superannuation Ledger Entries table.  You can run this process as often as required.  It is recommended that this process is also run after all Payrolls have been finalised for the calendar month to ensure all the On Cost transactions are moved to the Superannuation Ledger.

To open the Calculate Monthly Superannuation window,

*Departments/Payroll/EOM Processing/Superannuation Processing/Calculate Monthly Superannuation*

#### Calc. Monthly Superannuation – Options FastTab

|Field|	Comments|
|---|---|
|Calculation Date|	Enter the date you want the Monthly Superannuation transactions calculated and moved to the Employee Superannuation Ledger.  
||The last date of the month must be entered to ensure all transactions for the month are picked up for the calculations.
|Month to Calculate|	This field displays the month used for the after you enter the Calculation Date.
|Month Start Date|	This field displays the 1st date of the above month after the date has been entered.
|Month End Date|	This field displays the last date of the above month after the date has been entered
|Report Only|	Tick this flag to produce a report without updating the Employee Superannuation Ledger records 
||Leave this field blank to update the Employee Superannuation Ledger records.
 
### Calculate & Post Superannuation 

This process must be run for each payroll on a monthly basis to post and make any required superannuation adjustments.  

If using the Oncost method to calculate SGC superannuation this process must only be run after the “Calculate Monthly Superannuation” process.  

You should ensure all Payrolls for the calendar month have been posted to the General Ledger because this process may validate all Employees are entitled to the Employer SGC contributions for the calendar month.  

If the employee fails to meet the criteria the SGC components are not contributed and prior posting is reversed from the General Ledger provision & expense if flagged in the Payroll setup card.

This process is used to calculate and post superannuation transactions to the General Ledger and create the Vendor invoices. 

To open the Calculate & Post Superannuation window,

*Departments/Payroll/EOM Processing/Superannuation Processing/Calculate & Post Superannuation*
 

#### Calculate & Post Super. Exp. – Options FastTab

|Field	|Comments|
|---|---|
|Payroll No.|	This field displays the selected payroll number. 
|Posting Date|	This field is used to enter the date you want the Superannuation transactions posted to in the GL.  
|Month Start Date|	This field displays the 1st date of the Posting date month. 
|Month End Date|	This field displays the last date of the above Month start date.
|Document No.|	Enter a meaningful document number to identify the transactions in the General Ledger. (E.g.SUPERAUG2007)
|Post To G/L|	Select this flag to post to the General Ledger.  
||If left un-selected the report is produced without updating the General Ledger.
|Create Vendor Invoices|	Select this option to create Vendor Invoices for the Superannuation Companies with their corresponding Vendor ||Number set up in the Options tab. 
|Consolidate Vendor Invoices|	Select this option to create one invoice per Vendor 
||If left un-selected a separate vendor invoice is created for each Employee Superannuation record.
|Skip SGC Employees|	If you run this process more than once per month (i.e. after each payroll for weekly pay frequencies) then you must select this option.  
||The flag must be left blank for the last Calculate & Post Superannuation process for the month.

#### SGC Posting with Vendor Integration

The Pay Journal and the Calculate and Post Superannuation will post according to the setup in the Superannuation Company and the Pay Transaction Types.

Debit Super Provision                   +1116.00

Credits Vendors                         -1116.00 

