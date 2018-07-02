10.8.2	Leave Accruals
Leave Accruals cannot be set up for Time in Lieu Leave Types.

To open the Leave Accruals window,

Departments/Payroll/Setup/Payroll Setup/Leave/Accruals
  

10.8.2.1	Leave – General FastTab 
Field	Comments
Leave Type	This field is used to select the Leave Type you wish to assign to the Accrual 
Code	This field identifies the Accrual within this Leave Type. Enter a unique code for the Type
Description	Enter a description to identify the Leave Type / Accrual Code combination.
Value Conversion Factor	The factor ordinary earnings are multiplied by to obtain the current Leave value.
Percentage Method Factor	The percentage of the entitlement that accrues for the employee.  Set to 1 unless the Calculation Method is Percentage
Over Award Applicable	This field indicates when an Over Award rate is allowed for this accrual.
Over Award is calculated by the sum of the Standard Rate plus Over Award Rate.  If the Over Award field is blank the Over Award is ignored.
Max Days	This field is the maximum number of days that is accrued for this Leave Accrual at any one time.  If this field is set to 20 days then the employee entitlement will never exceed 20 days 
Use a Flat Accrual Calculation	Primarily used when the leave is setup to accrue in Days.

If this field is selected then the employee’s leave accrual is averaged over the Leave Accrual period (Usually 12 months) to give a standard accrual amount for each pay period.  
If the field is not selected then the leave accrual will be apportioned on the number of days in the current month.  This field is only used for Pro Rata Calculation method
Leave Type Based in Hours	This field is used to identify this leave accrual is based in hours.  This field defaults from the Leave Type. If the Leave Type is based in hours you must use Pro Rata Days Worked as the Calculation Method.
Max Hours	This field is used to identify the Maximum No. of Hours to be accrued for in the entire Anniversary Period. 

10.8.2.2	Leave – Long Service Leave FastTab
This tab is used only for Long Service Leave Type accruals.
  
The fields are used to delay pro-rata accruing for the LSL liability.  

If the “L.S.L. Threshold (Years) of 10.00 is entered then after the 10th anniversary of the employee is reached the first ten-years liability is posted to the General Ledger.  From this time on the liability will accrue and post each pay period according to the rules defined in the Award Detail Lines.


 

Field	Comments
L.S.L. Threshold (Years)	The Number of years before Long Service Leave is accrued as a liability in the General Ledger.
Action Prior To Threshold	This field determines how the L.S.L accrual is handled during the L.S.L. threshold.
The options available are: Accrue Only or Accrue & Post and can be selected from the “ArrowDown”. 

10.8.2.3	Leave – Posting FastTab
The Leave Posting tab is used to set up posting groups that determine General Ledger accounts for posting the End of Month Leave journals.

 

Field	Comments
No G/L Posting	Leave this field blank if you wish to post leave accruals to the General Ledger.
Select this field if you do not wish  to post accruals to the General Ledger
Accrual Cost Tran. Posting Group	The Calculate & Post Leave Provision process uses this field to Debit the Leave Expense account in the General Ledger. This group must be a P&L account
Provision Tran. Posting Group	The Calculate & Post Leave Provision process uses this field to Credit the Leave Provision account in the General Ledger. This group must be a Balance Sheet account
Taken Cost Adj. Tran. Posting Group	1. This field is not used when the "Post Leave Accruals Only" flag is selected in the Payroll Setup - Options tab.  

The Calculate & Post Leave Provision process uses this field to Credit this Posting Group with the value of the Leave Taken

2. When the Leave Taken Pay Transaction Type Posting group is the Leave Provision Group this field must be the same Provision Posting Group to have a nil net effect on the Provision.
 
3. When the Leave Taken Pay Transaction Type Posting Group is a P&L Expense account. This group must be a P&L Expense account. The Pay Transaction Type must be a different Group to the group entered here to avoid a nil expense in the General Ledger

10.8.2.4	Leave – Reporting FastTab
The Reporting tab is used to set up information for leave loading calculations.

 

Field	Comments
Max Salary	This field is used to set the maximum Salary Amount an employee is paid Leave Loading. 
Loading Percentage	This field is for reporting purposes.

10.8.2.5	Leave – On-Costs FastTab
The On-Costs tab is used to add on costs that apply to this Accrual.  The on cost rates are added to the Leave Provision posted to the General ledger on the Calculate & Post Provision for leave End of Month Processing.

 

Field	Comments
Superannuation On-Costs	Select this field is you wish to apply “Superannuation On-Cost” to this leave accrual.
Work Cover On-Costs	Select this field is you wish to apply “Work Cover On-Costs” to this leave accrual.
Additional On-Costs %	Enter a % to apply “Additional On-Costs” to this leave type.

10.8.2.6	Leave – Leave Accrual Subform FastTab 

Set up Award detail lines for each Leave Type / Accrual combination to define the Leave Periods and Calculation Methods for the entitlement and nominated periods of time.

 


Field	Comments
Award Period No.	The “Award Period No.” is automatically incremented by the system when a new line is entered.
Calculation Method

	Select the “Calculation Method for this period;

•	Pro-Rata Calculated - Calculate the Number of days since the end of the previous period of service and allocate the proportion of the days applicable to the total Number of days in the period.
•	Anniversary - Apply the Number of days on anniversary of the Number of months applicable.
•	Percentage - Apply a percentage of ordinary earnings for the period.
•	Return to Period - Loop Back to a previous Awards Period No.
•	Pro-Rata Time Worked - Same as for Pro-Rata but only increase Leave depending on the Number of days worked in the period. You must use this method for Leave in Hours
•	Pro-Rata No Carry - Same as Pro-Rata but does not carry forward previous period's entitlement.
•	Anniversary No Carry - Same as Anniversary but does not carry forward previous period's entitlement.
•	Percentage No Carry - Same as Percentage but does not carry forward the previous period's entitlement.
No. Hours Entitlement	This field indicates the number of days / hours entitlement in a Leave period.
Hours Basis (Weekly)	This field is used to identify the number of hours the accrual is based on.  E.g. 160 hours entitlement with an hour basis of 40 grants 20 days leave to an employee on a 40 hour week
No. Months	This field indicates the length of the Leave period in months.
Return to Period	Used to loop back to a previous period.  Enter the “Award Period number that you wish to loop back to.

 
