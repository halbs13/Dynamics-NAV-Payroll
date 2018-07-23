#  End of Month Processing - Payroll Tax

This function is used to calculate State and Territory Payroll Tax.

Payroll Tax is calculated as a percentage of the Employee's Pay.  

If you are setting up Payroll Tax for the first time you must ensure that the following areas have been established;

1.	Payroll Tax States – these are established in the Payroll Tax menu item in the Payroll Codes Setup.
2.	Payroll Tax Groups – if your organisation has payroll tax groups for the purposes of payroll tax these are established in the Payroll Tax Groups menu in the Payroll Codes Setup.
3.	Branches – once the Payroll Tax States have been established they are attached to the Branch Codes which are also defined on the Payroll Employee card when an employee is setup.
4.	Payroll Tax on Pay Transaction Types – Payroll Tax codes are established on each of the respective Pay Transaction Type.
5.	Payroll Tax Rates – Payroll Tax rates are established for each of the States and Territories.

Superannuation is also included in the Payroll Tax report and the thresholds are taken into account for each state when calculating the tax.

To ensure that each of the employee pay transactions applicable to Payroll Tax are calculated you must ensure every Employee has a “Branch” assigned on the Payroll Employee card and every Branch has a Payroll Tax code assigned in the Branches window.

*Departments/Payroll/EOM Processing/Payroll Tax Processing*

### Calculate Payroll Tax

To open the Calculate Payroll Tax window,

*Departments/Payroll/EOM Processing/Payroll Tax Processing*
 
#### Calculate Payroll Tax – Options FastTab

|Field|	Comments|
|---|---|
|Payroll No.|	Select the “Payroll No.” you wish to use to calculate Payroll Tax otherwise leave blank for all payrolls.
|Payroll Tax Code|	Select the Payroll Tax Code that you wish to calculate Payroll Tax otherwise leave blank for all Payroll Tax codes.
|Start of Month Date|	Select the first day of the month that you wish to include in your payroll tax calculation.
|Start Month Name|	The value in the field will default depending upon the “Start of Month Date” selected.
|End of Month Date|	The “End of Month Date” defaults once you have entered the “Start of Month Date” field.  The values in this field cannot be changed.
|End Month Name|	The value in the field will default depending upon the “End Month Date” selected.
|Print Branch Summary|	Select this field to print a summarised cost allocation for each Branch.
|Print Department Summary|	Select this field to print a summarised cost allocation for each Department.

 ## Payroll Tax Report

The fields on the Calculate Payroll Tax Report are:

|Report Field|	Field No.	|Obtained from|
|---|---|---|
|State Code|	(1)	|This is the State Code
|State Description	|(2)|	This is the State Description
|Transaction Detail section
|Transaction Code|	(3)|	This is the Pay Transaction Type Code which has been defined as being applicable to Payroll Tax.
|Transaction Description	|(4)|	This is the Description of the Pay Transaction Type Code.
|Amount (LCY)	|(5)|	This is a sum of the Amount of all the Pay Transaction Type codes.
|Superannuation Summary section
|Employer SGC/Non SGC|	(6)	|This is the sum of the Employer SGC and Non SGC amounts for the Payroll Tax state.
|Salary Sacrifice	|(7)|	This is the sum of the Salary Sacrifice or Pre Tax Superannuation Deduction amount for the Payroll Tax state.
|Other Amounts Summary section
|Fringe Benefits Estimate	|(8)|	This is the value of the Fringe Benefits Estimate as setup on the Payroll Tax Rates record.
|Grand Total|	(9)|	This is the sum of values in the “Transaction Detail”, “Superannuation Summary” and “Other Amounts Summary” sections.
|Payroll Tax Calculations section
|Australia Wide Wages	|(10)|	This is the sum of all wages Australia Wide.
|State Wide Wages	|(11)|	This is the sum of all wages applicable for the Payroll Tax within the Payroll Tax State.
|Exemption Threshold		
|Gross Taxable Wages	|(12)	|This is the sum of all Gross Taxable Wages applicable to Payroll Tax.
|Plus Adjustment	|(13)	|This is the value of the Adjustment as setup on the Payroll Tax Rates record.
|Less Deduction	|(14)|	This is the value of the Monthly Deduction as setup on the Payroll Tax Rates record.
|Net Taxable Wages|	(15)|	This is the sum of the “Gross Taxable Wages” and “Plus Adjustment, “Less Deduction”.
||If the value is negligible then zero will be represented in this field.
|Tax Rate	|(16)	|This is the Tax Rate as setup on the Payroll Tax Rates record.
|Payroll Tax Payable	|(17)| 	This is the value of the Payroll Tax Payable for the State.
