# Payroll Employee Card Superannuation

The “Employee Superannuation” window is used to maintain the Superannuation contributions for each employee. You select the Superannuation Product (s), date joined, percentages and amounts to calculate for both employer and employee superannuation.   

You can use either Standard Super (posts the costs at the End of Month) or the Oncost method to calculate the SGC % you cannot use both methods for the same employee.  

Use Oncost if you wish to Expense the cost when you post the Pay Journal.  If you use Oncost you cannot use a Base Salary to base the super % calculation.

Super contributions by both the Employee and the Employer are set up as a percentage or an amount each pay period.  The Employer can also contribute an additional factor of the Employee's Superannuation contribution. 

The Navigate ribbon contains the following options:

* Company - Displays the Superannuation card for the Employee Superannuation.
* Comments - Used to enter comments for the employee superannuation company.
* Ledger Entries - Displays a list of the Employee Superannuation Ledger Entries for this Superannuation Company.

When you initially select the **Superannuation** icon from the Payroll Employee Card you will be presented with the "Edit Employee Superannuation List" where you can complete the following fields;

#### Employee Superannuation – List

The Employee Superannuation List displays the Superannuation Products the employee has been enrolled into.  .  

Before you can add a new Superannuation record to an employee, the [Superannuation Fund](au-payroll-setup-superannuation-funds.md) and the [Superannuation Product](au-payroll-setup-superannuation-products.md) must be setup in [Payroll Setup](au-payroll-setup-payroll-setup.md).


|Field|	Comments|
|---|---|
|**Superannuation Code**|	Use this field to enter or select the Superannuation Product.
|**Membership No.**|	Enter the employee Membership No.
|**Date Joined**|	Enter the date the employee joined the fund or the Employee start date.
|**Starting Date**| 	This date is used as the date contributions starts to be contributed for this fund.
|**Ending Date**|	This date is used as the date contributions stop to be contributed for this fund.
|**Employer SGC Amount**|	The standard amount the employer will contribute.
|**Employer SGC %**|	This field is used to determine the percentage the employer contributes calculated on the Employees Earnings or the amount Entered in the Base Salary field if not zero.  
|**Employer Factor**|	The employer contributes a percentage of any employee contribution entered in the fields.  For example, if the Employer Factor is set to 0.50 then the Employer will contribute in addition half the contribution amount/percentage the employee contributes.
|**Employer Non-SGC Amt**|	This field is used when the Employer contributes an amount in addition to the Super Guarantee.
|**Employer Non-SGC %**|	This field is used when the Employer contributes a percentage in addition to the Super Guarantee.
|**Employee Salary Sacrifice Amt**|	This field is used to enter the Pre Tax Employee Contribution amount.
|**Employee Salary Sacrifice %**|	This field is used to enter the Pre Tax Employee Contribution percentage.
|**Employee Net Pay Contr. Amt.**|	This field is used to enter the Post Tax Employee Contribution amount.
|**Employee Net Pay Contr. %.**|	This field is used to enter the Post Tax Employee Contribution percentage used to calculate against Earnings.
|**Per Day Worked Amount**|	Enter the amount of the contribution to be made for each day the employee works.
|**Minimum Salary Check**|	If ticked the system checks the minimum salary earned for the month by the employee before contributions are made by the employee.
|**Base Salary**|	This field is used to calculate the Employee SGC % on the value entered instead of on the Pay Transaction Types ticked "Apply to Super".  The amount is entered as the annual salary of the employee. If the "Base Salary" field is zero then the employee’s actual earnings are used to calculate the Amount.


To access the Employee Superannuation Card, select the **Edit** icon on the *Home* ribbon.


## Employee Superannuation card – General FastTab

|Field|	Comments|
|---|---|
|**Superannuation Code**|	This field is used to select the Superannuation Product Code.
|**Membership No.**|	Enter the employee superannuation fund "Membership No." 
|**Base Salary**|	To use this field you must have the Standard Salary check box flagged on the [Superannuation Products](au-payroll-setup-superannuation-products.md) Options FastTab.  This field is then used to calculate the Employee SGC % on this value instead of using the [Pay Transaction Types](au-payroll-setup-pay-transaction-types.md) flagged "App to Super".  This amount is entered as an annual salary for the employee. If this field is zero then the employees actual earnings (Pay Transaction types flagged "App to Super".) are used to calculate the SGC super.
|**Date Joined Fund**|	This field is used to enter the date the employee joined the fund.
|**Last Period Updated**|	This field displays the end date of the last pay period that superannuation was calculated for this employee.
|**Last Date Modified**|	This field displays the last date this Employee Superannuation record was changed.
|**Ordinary Pay PTD**|	This field displays the accumulated ordinary earnings of the employee applicable to superannuation for the current pay period.
|**Ordinary Pay Life To Date**|	This field displays the accumulated ordinary earnings of the employee applicable to superannuation to date.
|**Navigate ribbon**
|**Company**|	This menu option displays the Superannuation Products card.
|Comments|	This menu option displays existing comments for this employee, and allows you to enter or modify comments.
|**Ledger Entries**|	This menu option lists superannuation ledger entries for the employees that have been posted to the Payroll Superannuation Sub-Ledger.

 [GoToTop](#payroll-employee-card-superannuation)
 
## Employee Superannuation card – Employer (Concessional) FastTab

 
|Field	|Comments|
|---|---|
|**Minimum Salary Check**|	For Employee contributions this field indicates the employee is subject to the minimum salary check before this transaction is deducted from the employee’s salary.  When the "Minimum Salary Check" field is ticked the employee must earn at least the amount entered in the "Minimum Salary" field on the Payroll Employee Pay Details card. 
|**Employer Factor**|	The employer contributes a percentage of any employee contribution entered. For example, if the Employer Factor is set to 0.50 then the Employer will contribute in addition half the contribution amount/percentage the employee contributes.
|**SGC Amount**|	The standard amount the employer will contribute each pay period.
|**SGC %**|	This field is used to enter the percentage the employer contributes calculated on the Employees Earnings or the amount entered in the Base Salary field.
|**Per Day Worked Amount**|	The amount contributed for each day the employee works.
|**Always Pay Contribution**|	This field indicates the employee must always receive the employer superannuation contribution regardless of the employee earnings.  This option can only be used with SGC Amount or Base Salary fields.
|**Non SGC Standard Amount**|	This field is used when the Employer contributes an amount in addition to the Super Guarantee
|**Non SGC Standard %**|	This field is used when the Employer contributes a percentage in addition to the Super Guarantee
|**Employer Period to Date Amt.**|	This field displays Period to Date contributions paid by the employer.
|**Employer Life to Date Amt.**|	This field displays Life to Date contributions paid by the employer. You can drill down to view the ledger entries.

## Employee Superannuation card - Employee FastTab

 
|Field|	Comments|
|---|---|
|**Period to Date Amt.**|	This field displays the Period to Date contributions paid by the employee.  You can drill down to view the ledger entries.
|**Life to Date Amt.**|	This field displays the Life to Date contributions paid by the employee.  You can drill down to view the ledger entries.
|**Non Concessional Section**
|**Net Pay Contr. Amt:**	|This field is used to enter the Post Tax Employee Contribution amount.
|**Net Pay Contr. %**|This field is used to enter the Post Tax Employee Contribution percentage.
|**Concessional Section**
|**Salary Sacrifice Std. Amt**|	This field is used to enter the Pre Tax Employee Contribution amount.
|**Salary Sacrifice Std. %**| This field is used to enter the Pre Tax Employee Contribution percentage.
 
 [GoToTop](#payroll-employee-card-superannuation)
 
## Employee Superannuation card - Contributions FastTab

 
|Field	|Comments|
|---|---|
|**Employer Annual Contribution**|	This field is used to calculate the "Employer Standard Amt.".  Enter the employer's annual contribution and the system calculates the "Employer Standard Amt" based on the pay period frequency.
|**Employer SGC Amt.**|	The "Employer SGC Amount" is the amount of the employer contribution each period.
|**Employee Annual Contribution**|	The "Employee Annual Contribution" field is used to calculate the "Employee Standard Amt.".  Enter the employee's annual contribution and the system calculates the "Employee Standard Amt" based on the pay cycle frequency.
|**Employee Net Pay Contr. Amt.**|	The "Employee Net Pay Contr. Amount" field is used to display the amount of the employee contribution.|


 
 [GoToTop](#payroll-employee-card-superannuation)
