# End of Month Processing Leave

*Departments/Payroll/EOM Processing/Leave Processing*

* [Mass Adjust Leave Balance](#end-of-month-processing-mass-adjust-leave-balance) - The Mass Adjust Leave Balance function is used to adjust leave entitlements or pro rata balances in the employee leave ledger to correct leave balances.  It is also used to enter entitlements when implementing a new Payroll System. You can choose to post the Leave to the General Ledger or only update the Payroll Employee Leave Ledger Entries.
* [Calculate and Post Provision](#end-of-month-processing-calculate-and-post-provision) - The Calculate and Post Provision function is used to calculate the leave entitlement and post the expense and provision for Leave to the General Ledger depending on your configuration.  It is usually run at the end of each month after you have finished processing all Payrolls for the calendar month
* [Employee Leave Entitlement Report](#employee-leave-entitlement) - The Employee Leave Entitlement Report contains Employee Leave accrual information and can be used to reconcile leave provision postings to the General Ledger.
* [Employee Time In Lieu Adm List](#employee-time-in-lieu-adm-list) - The Employee Time In Lieu Adm List report contains Employee Time In Lieu accrual information.  


### End of Month Processing Mass Adjust Leave Balance

The Mass Adjust Leave Balance function is used to adjust employee leave entitlements or pro rata balances in the employee ledger to correct balances.  It is also used to enter entitlements when implementing a new Payroll System.

To open the Mass Adjust Leave Accruals window, 

*Departments/Payroll/EOM Processing/Leave Processing/Mass Adjust Leave Balances*
 

#### Mass Adjust Leave Accruals

|Field|	Comments|
|---|---|
|Employee No.	|Enter or select the Employee No. by selecting the “ArrowDown”.
|Leave Type|	Select the Leave Type by selecting the “ArrowDown”.
|Leave Code|	Select a Leave Code by selecting the “ArrowDown”.
|Document Type|	Select the Document Type by selecting the “ArrowDown” (Entitlement, Pro Rata, Pro Rata Value, or Value Only).
|Leave Period Posting Date|	Enter the Leave Period Posting Date of the leave adjustment.  The Leave Period Posting Date identifies the Leave Anniversary period the transaction will appear in.
|Posting Date|	Enter the Posting Date of the leave adjustment.
|Document No.|	Enter the Document No of the leave adjustment.
|No. of Hours (Adj.)|	Enter the number of hours you wish to adjust the leave.  E.g. -40, 25.5, etc. 
||This field is only applicable if accruing leave in hours.
|No. of Days (Adj.)|	Enter the number of days you wish to adjust the leave.  E.g. -10, 25, etc.
||This field is only applicable if accruing leave in days.
|Value|	The value field displays the value of the leave adjustment.
|On-Cost Amount|	Enter the value of the On-Cost Amount if applicable.
|Adjustment Description|	Enter a “Description” of the leave adjustment.
|Tick Data Take-On Column|	Select this option to only affect the Payroll Leave Ledger and not to post the adjustment to the General Ledger.  
||This option is used to enter leave balances for a payroll implementation.
||Leave this option blank to post the provision to the General Ledger


[GoToTop](#end-of-month-processing-leave)

#### Mass Adjust Leave Accruals – Home ribbon

 |Field	|Comments|
 |---|---|
|Manage section
 |Delete|	Select this option if you wish to delete the transaction line.
|Process section
|Post	|This option Posts the Leave adjustment to the Employee Leave Sub-Ledger and General Ledger Leave Provision accounts. 
|Page section
|Refresh|	The Refresh function will refresh data on the Journal page.
|Find|	The Find function is used to Find information contained in the Journal.
 
 
#### Mass Adjust Leave Accruals – Actions ribbon

|Field	|Comments|
|---|---|
|Functions section
|Tick Data Take-On Column|	Select this option to only affect the Payroll Employee leave balances and not to post the adjustment to the General Ledger.  This option is used to enter leave balances for a payroll implementation
|Un-tick Data Take-On Column|	Select this option to post the provision to the General Ledger
|General section
|Post| 	This option Posts the Leave adjustment to the Employee Leave Sub-Ledger and General Ledger Leave Provision accounts 


### End of Month Processing Calculate and Post Provision

The Calculate Leave Provision calculates the Leave Accrual and Entitlements and posts them to the General Ledger Granule of NAV Financials.

This Report uses the current Leave Days accrued and entitled for each Employee and multiplies these by the current Employee pay rate to calculate the provision value for each Employee.


### Leave Accrual Posting

To open the Calculation Leave Provision window,

*Departments/Payroll/EOM Processing/Leave Processing/Calculate and Post Provision*

You must select the Payroll you wish to post Leave accruals for.

Once you have selected the Payroll the Calculate Leave Provisions form is displayed.

This form has three tabs; Leave Type, Payroll Employee and Options:

 [GoToTop](#end-of-month-processing-leave)
 
#### Calculate Leave Provision – Options FastTab

|Field	|Filter|
|---|---|
|Date of Calculation|	This field is Mandatory.  Enter the date you wish the transactions to Post to the General Ledger.
|Document No.|	This field is Mandatory.  Enter a meaningful document name or number to help you identify where the transactions have come from when you review the transactions in the General Ledger.
|Post to G/L	|This field is Optional.  Select this option when you wish to post the Leave Expense and Provision to the General Ledger.  
||If you leave this option blank you will be previewing the report in “Report Only” mode which generates how the transactions will appear when posted to the General Ledger.


#### Calculate Leave Provision – Leave Type FastTab

|Field	|Filter|
|---|---|
|Only the standard fields are covered.  A full list of fields available as filters can be used by selecting the first blank line and selecting the “ArrowDown”.
|Code	|Select the Leave Type you wish to process.  
||If left blank then all leave types are processed.


#### Calculate Leave Provision – Payroll Employee FastTab

|Field	|Filter|
|---|---|
|Only the standard fields are covered.  A full list of fields available as filters can be used by selecting the first blank line and selecting the “ArrowDown”.
|Employee No.|	Enter or Select the Employee No. by selecting the “ArrowDown”. 
||If left blank all employees are processed.
 
 
### Leave Reporting
There are 2 leave reports available from within the Leave Processing menu and throughout the Dynamics NAV Payroll module:

1.	Employee Leave Entitlement
2.	Employee Time In Lieu Adm List


### Employee Leave Entitlement
The Employee Leave Entitlement Report contains Employee Leave accrual information and can be used to reconcile leave provision postings to the General Ledger.
To generate the Employee Leave Entitlement Report, 

*Departments/Payroll/EOM Processing/Leave Processing/Employee Leave Entitlement*
 
 [GoToTop](#end-of-month-processing-leave)

#### Employee Leave Entitlement Report – Options FastTab

|Field	|Filter|
|---|---|
|As At Date|	Enter in the date you wish the leave entitlements to be calculated to.
||Please note that this function only works on leave accrual ledger transactions which have been posted to the Leave Accrual Ledger Entry table.  This date will not forecast accruals in the future.
|Exclude Zero Accruals|	Select this option if you wish to exclude zero accruals.
|Group by Global Dimension 1|	Select this option if you wish to group the entitlements by Global Dimension 1.
|Print Leave As|	There are 3 options available for selection;
||1.	Decimal Hours – this calculates and reports the accruals in decimal hours
||2.	Hours & Minutes – this calculates and reports the accruals in hours and minutes
||3.	Days – this calculates and reports the accruals in days. 
|Exclude LSL not Provisioned|	Select this option if you wish to exclude Long Service Leave calculations from the report that have not been provisioned or where the employee has not yet reached an entitlement to the Long Service Leave.


#### Employee Leave Entitlement Report – Leave Type FastTab

|Field|	Filter|
|---|---|
|Only the standard fields are covered.  A full list of fields available as filters can be used by selecting the first blank line and selecting the “ArrowDown”.
|Code|	Select the Leave Type you wish to process.  
||If left blank then all leave types are processed.

#### Employee Leave Entitlement Report – Payroll Employee FastTab

|Field|	Filter|
|---|---|
|Only the standard fields are covered.  A full list of fields available as filters can be used by selecting the first blank line and selecting the “ArrowDown”.
|Payroll No.|	Enter or Select the Payroll No. by selecting the “ArrowDown”.
||If left blank all employees are processed.
|Employee No.|	Enter or Select the Employee No. by selecting the “ArrowDown”. 
||If left blank all employees are processed.
|Branch Code|	Enter or Select the Branch Code by selecting the “ArrowDown”.
||If left blank all employees are processed.
|Division Code|	Enter or Select the Division Code by selecting the “ArrowDown”.
||If left blank all employees are processed.

 [GoToTop](#end-of-month-processing-leave)
 
#### Employee Leave Entitlement Report Preview 
 

|Field|	Filter|
|---|---|
|The Header Section of the report contains information such as the Report Name, Date, Page No., User and the filters applied to produce the report.  
|Other information contained in the Detailed Section of the report;
|•	Emp No.
|•	Employee Name
|•	Status
|•	Starting Date
|•	Leave Code
|•	YTD Taken – Year To Date Taken value
|•	LTD Taken – Life To Date Taken value
|•	Entitled – This field represents the value of leave up until the employee’s last anniversary date.
|•	Curr-Pro Rata – This field represents the value of the current pro-rata value from the employee’s last anniversary date to the report date.
|•	Accrued – This field represents the sum of “Entitled” and “Curr-Pro Rata” for the employee.
|•	Leave Value
|•	Loading Value – This field represents the value of Leave Loading.
|•	On-Cost Value – This field represents the value of the On Costs if this has been setup against the Leave Accrual Card.
|•	Total Leave Value – This field represents the value represents the sum of “Leave Value”, “Loading Value”, “On-Costs Value”.


### Employee Time In Lieu Adm List

The Employee Time In Lieu Adm List report contains Employee Time In Lieu accrual information.  
To generate the Employee Time In Lieu List, 

*Departments/Payroll/EOM Processing/Leave Processing/Employee Time In Lieu Adm List* 
 

#### Employee Time In Lieu Adm List – Options FastTab

|Field|	Filter|
|---|---|
|Show Employees with Zero Accrued|	Select this option if you wish to show employees with zero accruals.

[GoToTop](#end-of-month-processing-leave)

#### Employee Leave Entitlement Report – Payroll Employee FastTab

|Field|	Filter|
|---|---|
|Only the standard fields are covered.  A full list of fields available as filters can be used by selecting the first blank line and selecting the “ArrowDown”.
|Payroll No.	|Enter or Select the Payroll No. by selecting the “ArrowDown”.
||If left blank all employees are processed.
|Branch Code|	Enter or Select the Branch Code by selecting the “ArrowDown”.
||If left blank all employees are processed.
|Division Code|	Enter or Select the Division Code by selecting the “ArrowDown”.
||If left blank all employees are processed.

 
#### Employee Time In Lieu Adm List Preview 

|Field	|Filter|
|---|----|
|The Header Section of the report contains information such as the Report Name, Date, Page No., User and the filters applied to produce the report.  
|Other information contained in the Detailed Section of the report;
|•	Emp No.
|•	Employee Name
|•	Accrued – This field represents the value accrued in hours.
|•	Taken – This field represents the leave taken value in hours.
|•	Entitled – This field represents the value of entitlement in hours.
|•	Value as Accrued – This field represents the $ value of the accrual.
|•	Value at Current Rate – This field represents the $ value of the accrual at the employee’s current rate.
|•	Adjustment Required – This field represents if there is an adjustment required to record into the General Ledger.
|•	Accrued – This field represents the value accrued if the accrual is recorded as a value.
|•	Taken – This field represents the value taken if the accrual is recorded as a value.
|•	Entitled – This field represents the entitled value if the accrual is recorded as a value.

[GoToTop](#end-of-month-processing-leave)
