# Payroll Setup - Leave

You can set up unlimited Leave Types and Accruals.  Each employee can have more than one Leave Type and Accrual assigned to them. To setup the parameters for Leave you must setup:

* Types
* Accruals

After you setup the Types and Accrual rules you can assign them to your employees.  

Default Leave Codes and Types can be setup to default for each [Payroll](au-payroll-setup-payrolls.md) for Annual Leave, Leave Loading, Personal Leave, and Long Service Leave.  The defaults are used for each Payroll Employee assigned to the Payroll. You can change and delete the defaults for the individual employees prior to their first pay from the [Leave Accruals](au-payroll-create-payroll-employee-leave-accruals.md) on the [Payroll Employee card](au-payroll-create-payroll-employee.md).  

Leave Accruals can be one of the following types:

* Annual Leave
* Leave Loading
* Long Service Leave
* Personal Leave
* Other Leave
* Time in Lieu

Each Type can have a different method of entitlement calculated dependant on the length of service.

### Example 1: 
Annual Leave is setup to give the employee an Entitlement of four weeks on the first anniversary of employment.  

After the first year of service the calculation method automatically moves to Pro-rata and entitlement is granted according to the percentage of the leave period (Usually 12 months) that has passed. 

### Example 2: 
Annual Leave is accrued as a percent of the rate of the employee’s pay for the first year of employment, and then accrued as days after that time.  You can use this method to prevent an employee from being paid leave in the first year of employment, upon termination of employment; they are paid the value of their leave entitlement.

A period is the duration of the leave period for the leave accrual. Leave Accrual periods are setup in the system using Calculation Methods for entitlement.  

* [Pro-Rata](#pro-rata)
* [Pro-Rata Time Worked](#pro-rata-time-worked)
* [Pro-Rata No Carry](#pro-rata-no-carry)
* [Anniversary](#anniversary)
* [Anniversary No Carry](#anniversary-no-carry)
* [Percentage](#percentage)
* [Percentage No Carry](#percentage-no-carry)
* [Return to Period](#return-to-period)

## Pro-Rata

This Calculation Method calculates the number of days since the end of the previous period of service (N) and the total number of days in the current period (D).

It uses the ratio of these two numbers (N/D) to calculate the proportion of leave entitlement for the period to accrue.

No. Days Accrued = No. Days Accrued Prior Periods + (No. Days to Date in Period / Total No. Days in Period) * No. Days leave entitlement for the period.)

Leave Rate = Ordinary Earnings Rate * Conversion Factor

## Pro-Rata Time Worked

This Calculation Method must be used for Leave based in hours and is the same as Pro-Rata except that the first number (N) is the number of hours worked in the period.

No. Days Accrued = No. Days Accrued Prior Periods + (No. Days worked in Period / Total Days in Period) * No. Days leave entitlement for the period.)

Leave Rate = Ordinary Earnings Rate * Conversion Factor.
 
## Pro-Rata No Carry

This Calculation Method is the same as Pro-Rata except that it does not carry forward the previous period’s entitlement.

No. Days Accrued = (No. Days to day in Period / Total No. Days in Period) * No. Days leave entitlement for the period.)

Leave Rate = Ordinary Earnings Rate * Conversion factor.
 
## Anniversary

This Calculation Method uses the number of days in the entitlement on anniversary of the number of months for accrual.

When anniversary is reached then: 

No. Days Accrued = No Days Accrued Prior Period + No Days Entitlement for the period.
Leave Rate = Ordinary Earnings Rate * Conversion Factor

## Anniversary No Carry

This Calculation Method is the same as the Anniversary Calculation Method, except that it does not carry forward the previous period’s entitlement.

When anniversary is reached then: No. Days Accrued = No. Days Entitlement.
 
## Percentage

This Calculation Method accrues an amount that is a percentage of ordinary earnings for the period.

Leave Value = Leave Percentage * Ordinary Earnings
 
## Percentage No Carry

This Calculation Method is the same as Percentage Calculation Method, except that it does not carry forward the previous period’s entitlement.
 
## Return to Period 

Loop back to a previous period.

The end of the previous period is determined using the starting Award Period No. on the Employee Leave Accrual Table.

Where the method **Percentage or Percentage No Carry** is used, the percentage to divide the ordinary earnings must be set up.  These earnings can be made to exclude over award amounts.

Where days are to be **accrued at half pay**, a conversion factor can be set-up against the leave type.  This conversion factor will affect the value of the entitlement.

In order to track leave taken for leave accruals, pay transaction types must be set up to **apply to leave taken** against the leave accrual codes.

**Annual Leave** can be accrued according to any of the above Calculation Methods.  A maximum number of days to accrue can also be entered.

**Leave Loading** may be setup as a separate leave type, or as part of “Another leave” type.  When leave loading is setup, a transaction type to use for generated leave loading must be entered with a percentage-loading factor.  A maximum salary to calculate loading percentage against can be setup. 

**Long Service Leave** may be accrued according to any of the above Calculation Methods.  LSL may be set-up to appear on reports after a set number of years.  A specific LSL percentage to report for the first number of years of service may be set up.

**Personal Leave** can use any of the Calculation Methods for entitlement calculation.  A maximum number of days to accrue can be set-up against sick leave accruals.

**Time in Lieu** entitlement is calculated using the employee’s average hours and worked hours.

Time in Lieu Hours Accrued formula = (Hours Worked – Average Hours) / Hours Worked.

In order to calculate the hours accrued for a pay period, the result of this formula is multiplied by the hours worked in the pay period (determined by the [pay transactions](au-payroll-setup-pay-transaction-types.md) that are flagged as **Apply to Time in Lieu**). 
 
An accrual transaction is generated for the employee with a value of the calculated number of hours multiplied by the employee’s pay rate.  The resulting value is used to reduce the employee’s pay for the period.

The transaction type to generate for accruals is entered on the Time in Lieu Setup table.

To enable tracking Time in Lieu taken, one or more pay transaction types must be set up as affecting the Time in Lieu Award.

The transaction used to take Time in Lieu can be set up to “Apply to Time in Lieu”.  This means that the user could enter 8 hours as the time taken, but only reduce the Entitlement by the formula result hours.

Additional Information
Pro Rata Leave Calculation Methods
Leave Accruals Provision Posting
Post Leave Accruals Only Flag
10.8.1	Leave Types
Leave Types must be created before defining any Leave Accruals.

You can set up unlimited Leave Types  

Leave Types can be one of the following types:

•	Annual Leave
•	Leave Loading
•	Long Service Leave
•	Personal Leave
•	Other Leave
•	Time in Lieu.

To open the Leave Types window 

Departments/Payroll/Setup/Payroll Setup/Leave/Types
 
Field	Comments
Code	This field is used to identify the Leave Type in the system.
Description	This field is user defined.  Enter a name for this Leave Type.
Accumulation Type	You must select an accumulation type (leave type) from the “ArrowDown” on the right of the field.
Accumulation Types allow the accumulation of values. 
Leave Type Based in Hours	Select this field if you wish to use Hours instead of Days for this Leave Type.
If left blank the leave type is based in Days. 



 
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

 
