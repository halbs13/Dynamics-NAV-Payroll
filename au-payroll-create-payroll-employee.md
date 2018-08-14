# Create Payroll Employee

Prior to setting up a Payroll Employee card, you must first set up a [Human Resources Employee](au-payroll-create-employee.md) card. 

1.  To create an Employee, go to the following menu: *Departments/Payroll/Employee Maintenance/Employees* 

2.  After you have setup the Employee card, then create the Payroll Employee card from the following menu: *Departments/Payroll/Employee Maintenance/Payroll Employees*

**Note:** Several fields in the Payroll Employee card are mandatory (you must enter information to continue) whilst other fields are optional which can be filled in at a later stage or be left blank.

The following list is used to indicate the field type on each tab:

* **M**= Mandatory
* **O** = Optional
* **S** = System Defined

## Payroll Employee card

When setting up a new Payroll Employee, you will complete the following areas for each employee;

* [General](#payroll-employee-card-general-fasttab)
* [Posting](#payroll-employee-card-posting-fasttab)
* [Rate](#payroll-employee-card-rate-fasttab)
* [Tax](#payroll-employee-card-tax-fasttab)
* [Declaration](#payroll-employee-card-declaration-fasttab)
* [Pay Details](#payroll-employee-card-pay-details-fasttab)
* [Work Cover](#payroll-employee-card-work-cover-fasttab)
* [Pay Dissections](au-payroll-create-payroll-employee-pay-dissections.md)
* [Pay Rates](au-payroll-create-payroll-employee-pay-rates.md)
* [Gross & Allowances](au-payroll-create-payroll-employee-gross-allowances.md)
* [Deductions](au-payroll-create-payroll-employee-deductions.md)
* [Superannuation](au-payroll-create-payroll-employee-superannuation.md)
* [Cost Allocations](au-payroll-create-payroll-employee-cost-allocations.md)
* [Accumulations Calculations/Employer On Costs](au-payroll-create-payroll-employee-accumulation-calculations.md)
* [Work Schedules](au-payroll-create-payroll-employee-work-schedule.md)


1.  Select the **New** icon on the Home ribbon to create a new Payroll Employee.

2.  Complete the following information on the **General** FastTab;

### Payroll Employee card General FastTab

The General FastTab is use to edit the employee name and address details used for Payment Summary production/ATO reporting. You must assign the employee to a [Payroll](au-payroll-setup-payrolls.md) which determines the frequency of payment.  You can define the employee’s [location](au-payroll-setup-payroll-codes.md), position and payment method. You must select the [Employee Type](au-payroll-setup-employee-types.md) code to determine the type of Payment Summary issued.

 
|Field	|Mandatory/Optional	|Comments|
|---|:---:|---|
|**Employee No.**|	M	|This field identifies the Employee throughout the Payroll and Human Resource Granules.  The Employee must exist as an Employee in Human Resources before you can setup a Payroll Employee card.  Click the **ArrowDown** button and select the “Employee No.” from the Employee List table. The Payroll Employee has the same Employee No as the Human Resource Employee.
|**Job Title** |	O	|Select a Job Title if required.  This field is used only for reporting.
|**Employee First Name**|	M	|The “Employee First Name” is displayed.  The field is populated from the Employee card.  You can edit this field.  If you change the Employee Name in this field the Employee card is also updated with the change.
|**Employee Last Name**|	M	|The “Employee's Last Name” is displayed. The field is populated from the Employee card.  You can edit this field.  If you change the Employee Name in this field the Employee card is also updated with the change
|**Middle Name**|	O	|Enter the Middle name
|**Initials**|O	|Enter the Employees initials
|**Address**|O	|The field is populated from the Employee card.  You can edit this field.  If you change this field the Employee card is also updated with the change.  This field is used when producing the Payment Summaries.
|**Address 2**|	O	|The field is populated from the Employee card.  You can edit this field.  If you change this field the Employee card is also updated with the change.  This field is used when producing the Payment Summaries.
|**Post Code/City**	|M	|The “Post Code/City” is 2 fields used to record the post code and city. Enter or select the post code from the table.  If the post code exists in the Post Code table the City field automatically populates to the city associated with that post code.
|**Phone No.**|O	|The field is populated from the Employee card.  You can edit this field.  If you change this field the Employee card is also updated with the change.
|**Mobile Phone No.**|	O	|The field is populated from the Employee card.  You can edit this field.  If you change this field the Employee card is also updated with the change.
|**Alpha Search**	|M	|This field is used to search for the Employee throughout the Payroll.  The contents of the Alpha Search field do not need to be the same as those of the Employee First and Last Name fields. 
|**Payroll No.**|	M|	Use this field to assign the employee to a specific Payroll. 
|**Pay Cycle Frequency**|	S	|This field is only used to display the pay frequency for the selected Payroll.  The frequency defines the number of tax weeks calculated per Pay Run.
|**Position Code**|O	|This field indicates the position title of the employee.  These codes are common to all payrolls in this database.
|**Shift Code**|	O	|This field is used to assign a default shift to this employee. The shift is used in the Pay Journal and may be overwritten.
|**Pay Location**|O	|This field is used to indicate the location of the employee to distribute their Pay Advice.  Pay Advices can be printed in Pay Location order for each Payroll. 
|**Employee Type Code**|M	|This field determines the type of Payment Summary issued to the employee.   The employee type code must be updated prior to calculating the pay journal.
|**Payment Method**|	M	|This field specifies the employee default Payment Method.  The options are; Cash, Cheque, or EFT.
|**E-Mail Pay Advice**|O|	When this field is ticked, the employee will receive Pay Advice via email. This field can only be ticked if the E-Mail field in the Employee card is populated with a valid email address.
|**E-Mail Payment Summary**|	O	|When this field is ticked, the employee will receive the Payment Summary via email. This field can only be ticked if the E-Mail field in the Employee card is populated with a valid email address.

[GoToTop](#create-payroll-employee)

3.  Complete the following fields on the **Posting** FastTab;

### Payroll Employee card Posting FastTab

The Posting FastTab is used to assign the employee to a Branch, Division and the Global Dimensions.  You can also assign a default Job and Task for the employee.

The [Branch Code](au-payroll-setup-branches.md) is attached to a state which determines the state when calculating payroll tax.  Branch and Division Codes can be used to determine the GL accounts to post transactions against which is defined in the [Payroll Posting Setup](au-payroll-setup-posting-group-setup.md).

Global Dimensions are used in conjunction with GL Accounts in the General Ledger.

 
|Field	|Mandatory/Optional	|Comments|
|---|:---:|---|
|**Branch**|	O	|This field is used to select the Branch.  The branch is used for Payroll Posting Groups and is associated with a State for Payroll Tax calculations.
|**Division Code**|	O	|This field is used to select the Division.  The division is used for Payroll Posting Groups.
|**Global Dimension 1 Code**|	O	|This field is used to assign Global Dimension 1 to the employee. 
|**Global Dimension 2 Code**|	O	|This field is used to assign Global Dimension 2 to the employee. 
|**Job No**|	O	|Selected from the Job numbers in the Job window.
|**Job Task No**|	O	|Mandatory when a Job No is used.  If not entered the Pay Journal will not post.  
|**Gen Bus. Posting Group**|	O	|Selected from the Posting Group window, this information is primarily used if posting GST transactions from Payroll to the General Ledger.
|**GST Bus. Posting Group**|	O	|Selected from the Posting Group window, this information is primarily used if posting GST transactions from Payroll to the General Ledger.
|**Currency Code**|	O	|Used if multiple currency is being used.  Only 1 currency type can exist for a payroll.

[GoToTop](#create-payroll-employee)


4.  Complete the following fields on the **Rate** FastTab;

### Payroll Employee card Rate FastTab

This tab is used to determine the standard hours worked and can be used to calculate Ordinary Time and Leave Accruals.

|Field	|Mandatory/Optional	|Comments|
|---|:---:|---|
|||
|The following three fields are used to calculate the hourly rate for each Employee and Accrue Time In Lieu hours.
|||
|**Hours in a Full Week**|	M	|This field is used to determine the standard hours worked for Ordinary pay and for Accruals.
|||Hours can be defaulted from the following areas;
|||•	Payroll Card – the hours can be set on the Defaults FastTab and when an employee record is initially attached to a Payroll, this field will be populated with the setup contained on the Payroll Card,
|||•	Award Setup – the hours can be set on the Awards & Associated Transactions table and when an employee record is initially attached to an Award, this field will be populated with the setup contained on the Award Card.
|||A log  of hours can be maintained in the “Employee Worked Hours” table to record historical and future-dated Worked Hours.   
|||Select the **ArrowDown** to access the “Employee Worked Hours”.
|**Hours Worked for TIL**|	M	|This field is used to calculate the value accrued to Time in Lieu.  The Hours worked in excess of this value are accrued to the employee’s TIL entitlement.  
|||Hours can be defaulted from the following areas;
|||•	Payroll Card – the hours can be set on the Defaults FastTab and when an employee record is initially attached to a Payroll, this field will be populated with the setup contained on the Payroll Card,
|||•	Award Setup – the hours can be set on the Awards & Associated Transactions table and when an employee record is initially attached to an Award, this field will be populated with the setup contained on the Award Card.
|||A log  of hours can be maintained in the “Employee Worked Hours” table to record historical and future-dated Worked Hours.   
|||Select the **ArrowDown** to access the “Employee Worked Hours”.
|**Days Per Week**|M|	Enter the standard number of days in a week the employee works.  This field is used for the calculation and processing of leave.
|||Default Days Per Week can be defaulted from the following areas;
|||•	Payroll Card – the no. of days can be set on the Defaults FastTab and when an employee record is initially attached to a Payroll, this field will be populated with the setup contained on the Payroll Card,
|||•	Award Setup – the hours can be set on the Awards & Associated Transactions table and when an employee record is initially attached to an Award, this field will be populated with the setup contained on the Award Card.
|||A log  of hours can be maintained in the “Employee Worked Hours” table to record historical and future-dated Worked Hours.   
|||Select the **ArrowDown** to access the “Employee Worked Hours”.
|**Over Award Applicable**|O	|Tick this field if the employee is entitled to receive Over Award Rates of Pay. Only applicable if using awards.
|**Flexitime Applicable**|	O	|Tick this field if you wish to calculate an Employee's entitlement based on hours worked.  If an Employee is not entitled to flexi-time, the “Flexitime Applicable” field should be left blank.
|**Work Schedule Code**|O	|The Work Schedule Code is used to define the work pattern worked by an employee.  Select the **ArrowDown** to access and update the “Employee Worked Hours” table which is used to record historical and future-dated Worked Hours and where the Work Schedule Code can be entered.
|||
|The following fields are for display purpose only.  The fields are set up by clicking the Payroll button and then select Pay Rates from the menu.  The Pay Rate displayed is the Current Payroll Period as of the starting date for the Classification Rate.  See the section on Awards in this manual for more details. The following fields are blank if the Employee Start Date is in a future Pay Period in the Pay Rate card.
|||
|**Classification Code**|	S|	This field displays the “Classification Code” within the award for this employee.
|**Award Code**|	S	|This field displays the “Award Code” for the employee.
|**Rate Start Date**|	S	|This field displays the date the employee started on this Pay Rate.
|**Employee Rate**|	S	|The Employee Rate is the “Employee Rate” entered for this employee in the [Employee Pay Rate Card](au-payroll-create-payroll-employee-pay-rate.md).
|**Award Rate**|	S	|The Award Rate is the rate that applies to this award classification.
|**Over Award Rate**|	S	|The over award pay rate for this award classification.
|**Actual Rate**|S	|The Actual Rate will be the sum of the “Award Rate” plus the “Over Award Rate” plus the “Employee Weekly Rate”.  This sum is the total actual rate for this employee.
|**Pay Rate**|	S	|This is the employee’s actual pay rate multiplied by the Hours in a Full Week.
|**Pay Period Rate**|	S|	This value reflected in this section is the employee’s pay per pay period.  
|**Annual Rate**|	S|	The value reflected in this section is the employee annual rate of pay.

[GoToTop](#create-payroll-employee)

5.  Complete the following fields in the **Employee Worked Hours** section;

### Payroll Employee card Employee Worked Hours

In the “Hours In A Full Week” field, select the **ArrowDown** to access the Employee Worked Hours table.  

This table is designed to record historical and future dated transactions of the hours an employee has/will work.
 
|Field	|Mandatory/Optional	|Comments|
|---|:---:|---|
|**Employee No.**|	M	|This field will contain the Employee’s No. It will default to the number of the employee’s record you are working on.
|**Starting Date**|	M	|This field is used to identify when the Worked Hours are effective.
|Hours in a Full Week|	M|	This field is used to determine the standard hours worked for Ordinary pay and for Accruals.  The value in this field will be updated on the Payroll Employee card, where the “Start Date” falls within the current pay period.  If the effective date of this transaction is future-dated, the value in this field will be updated on the Payroll Employee card, where the “Start Date” falls within the current pay period.
|**Hours Worked for TIL Calc.**|	M|	This field is used to calculate the value accrued to Time in Lieu.  The Hours worked in excess of this value are accrued to the employee’s TIL entitlement.  The value in this field will be updated on the Payroll Employee card, where the “Start Date” falls within the current pay period.  
|**Days Per Week**|M	|Enter the standard number of days in a week the employee works.  This field is used for the calculation and processing of leave.  The values in this field will be displayed on the Payroll Employee card, if the “Start Date” falls within the current pay period.  
|**Work Schedule Code**|	O	|The Work Schedule Code is used to define the work pattern worked by an employee.  The updates in this field will be displayed on the Payroll Employee card, if the “Start Date” falls within the current pay period.
|**Defunct**|O	|Tick this field if you wish to inactivate the transactional record.  


6.  Complete the following fields on the **Tax** FastTab;

### Payroll Employee card Tax FastTab

The information entered on this tab is obtained from the Employees Tax File Number Declaration form.  The information entered is used with the Declaration tab to calculate PAYG tax withholding amounts for the employee each pay run.

The FBT field is used to add the Employee's Fringe Benefit Tax each year.  This entry prints on the Payment Summaries

 
|Field	|Mandatory/Optional	|Comments|
|---|:---:|---|
|**Tax Scale No.**|	M	|This code defines the Tax Scale for this employee.  Tax Scales are provided by the ATO to calculate PAYG withholding tax for Employees.  To select the Tax Scale No, select the **ArrowDown**. 
|**HELP Debt**|	O	|This field Indicates the employee has a Higher Education Loan Program.   If ticked the employee will pay extra tax.
|**Student Loan (SFSS)**|	O|	This field Indicates the employee has a student loan.   If ticked the employee will pay extra tax.
|**Fixed Tax Rate Applicable**|	O|	Tick this field if the employee has applied for and has been granted a variance to their normal tax rate.  A separate letter from the Australian Taxation Office must be provided to the employer before this variation can occur.
|**Fixed tax rate Valid Until Date**|	O|	Enter the date the Fixed Tax rate expires.  Once this date has been reached standard taxation according to the Tax Scale outlined above will occur.
|**Fixed Tax Rate**|	O	|Enter the percentage value of the fixed tax rate.  The value is entered as a percentage e.g. 25%
|**Medicare Reduction Applicable**|	O|	Tick this field if the employee has been granted a reduction for their Medicare surcharge.  The system automatically calculates the amount of reduction the employee is entitled.
|**Number of Dependants**|	O	|This field is used to enter the Number of Dependants if you also ticked the Medicare Reduction Applicable checkbox.  The value entered is used to calculate the Medicare surcharge reduction.
|**Payroll Tax Exempt**|	O|	Tick this box if this employee’s earnings are deemed exempt from Payroll Tax (E.g. Apprentice, Registered Trainees).
|**G.S.T. Exempt**|	O|	This field is reserved for future development.
|**Payment Summary Raised**|S	|This field is used to indicate the Payment Summary has been issued to the employee.  This field is automatically ticked by the system after Payment Summaries have been printed for this employee and is reset when the first pay is run for the new taxation year.
|**Fringe Benefit Amount**|	O	|This field is used to access the Employee FBT Amount List.   Enter the total taxable amount of fringe benefit received by the employee for the corresponding tax year.  The value in these fields print on the Employee’s Payment Summary for the corresponding year.

[GoToTop](#create-payroll-employee)

7.  Complete the following fields on the **Declaration** FastTab;

### Payroll Employee card Declaration FastTab

The information entered on this card is obtained from the employees Tax File Number Declaration form.  The information entered is used to work out how much PAYG tax to withhold from payments made to the employee and are used when producing the electronic lodgement file for employment declarations to the ATO.

|Field	|Mandatory/Optional	|Comments|
|---|---|---|
|Resident	|O|	Tick this field if the employee has indicated they have residential status.
|Tax Status		
|Tax Free Threshold Claimed|	O	|Tick this field if the employee has is claiming the Tax Free Threshold.
|Claim FTB	|O|	Tick this field if the employee is claiming the Family Tax Benefit.
|Claim Zone Allowance|	O	|Tick this field and select the zone region the employee has indicated.
|Zone|	O|	Select the Zone that applies from the “ArrowDown”.
|HELP Debt|	O	|Tick this field if the employee has indicated they have a HELP debt. 
|Student Loan (SFSS)	|O|	Tick this field if the employee has indicated they have a SFSS loan.
|Claim Pension Rebate|	O	|Tick this field if the employee has indicated they are claiming a Pension Rebate.
|Use TFN for Super	|O|	Tick this field if the employee has indicated they agree to supply their TFN to their Superannuation Company.
|Senior Australians tax offset claimed|	O	|Tick this field if the employee has indicated they wish to claim the Senior Australians tax offset.
|Rebates Amt. Claimed	|O	|Enter the value of rebates the employee has claimed.  The employee’s annual tax will be reduced by this amount.
|A.B.N.	|O	|This field is used to record the Employee’s ABN number if supplied.
|Tax File No.|	O	|Enter the employee’s Tax File Number.  If you do not have Payroll Supervisor privileges the TFN will not be shown.
|Birth Date|	O|	Enter the employee’s birth date 
|Date Declaration Signed|	O	|Enter the date the employee signed the declaration.
|Payee Signature|	O	|Tick this field if the employee has signed their declaration.
|Declaration Lodged|	S|	The system populates this field when you produce the electronic declaration lodgement file.

### Payroll Employee card Pay Details FastTab

This tab is used to display pay details for the employees.  Some fields on this tab are calculated and cannot be maintained on this tab.


|Field|	Field |Type	Comments|
|---|---|---|
|Pay Details FastTab
|Minimum Net Salary|	O	|This field is used to record the minimum net salary an employee should receive.  An example of where you might store information in this field, is if your employee has a Child Support arrangement and the Child Support Office advises you of the minimum net salary the employee should receive.  Entering an amount in this field ensures the employee will receive this minimum net amount.  
|||If you have previously entered the amount in the Payroll setup the amount will default from there and you can override the amount 
|Forward Paid Periods|	S	|This field indicates the number of pay periods that the Employee has been paid in advance.
|Date Paid Up Until	|S|	This field displays the date to which an Employee has been paid.
|Last Period Paid	|S	|This field is used to display the last period in which an Employee was paid.
|Gross Pay	|S	|The “Gross Pay” is the sum of the amounts from Payroll Ledger Entries for gross pay  The default value is year to date, but can be changed using flow filters.
|Net Pay|	S	|The “Net Pay” is the sum of the amounts from Payroll Ledger Entries for net pay.  The default value is year to date, but can be changed using flow filters.
|Employment Date|	S	|This field is populated from the Employee card - Employment Date field.  The date cannot be changed 
|Status	|O|	The default “Status” is Active.  You can Inactivate or Terminate an employee by selecting the value from the look up.
|Inactive Date	|O	|Enter the date the employee was made “Inactive”.
|Termination Date|	S|The “Termination Date” can only be entered on the Employee card 



 
### Payroll Employee card Work Cover FastTab

The fields on this tab are used to assign Work Cover details to this employee for the purposes of calculating Work Cover liabilities for your employees.


|Field	|Field |Type	Comments
|---|---|---|
|Work Cover FastTab
|Work Cover Code	|O	|Select the “Work Cover Code” for the Employee.
|||Work Cover is set up as a percentage of Gross Wages calculated as the Work Cover Levy.  
|Work Cover Location	|O|	Select the “Work Cover Levy” Location.


[GoToTop](#create-payroll-employee)
