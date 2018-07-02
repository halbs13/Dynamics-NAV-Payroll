# LEAVE OVERVIEW

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

Additional Information:

[Leave Types](#au-payroll-setup-leave-types.md)
[Leave Accruals}(#au-payroll-setup-leave-accruals.md)
[Pro Rata Leave Calculation Methods](#au-payroll-setup-pro-rata-leave-calculation-methods.md)
[Leave Accruals Provision Posting](#au-payroll-setup-leave-accruals-provision-posting.md)
[Post Leave Accruals Only Flag](#au-payroll-setup-post-leave-accruals-only-flag.md)

[GoToTop](#leave-overview)
