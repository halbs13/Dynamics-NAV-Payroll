# Award Overview

An Award is set up by:

- Defining the Award 
- Creating one or more Award Classifications 
- Creating Classification Rates for each Award Classification (Optional) 

At least one Award and Classification must be setup for each company to process the payrolls.  

The default Award is automatically created by the Initialisation Codeunit when payroll is implemented and is called “GENERAL” for both the Award and Classification: 

 * All employees Pay Rates are associated with the default Award until you create your own Awards and assign them to Employees. 
 * Setting up additional Awards and Classifications is optional. 
 * Awards are broken down into Classifications (Grades) that may apply for a specific period of service until they increment to a higher classification.
 * Classifications may have Pay Rates that apply from a specified date. 
 * Each Classification can have the “Number of Months of Service” for which the Classification is applicable, and a “Next Classification” that applies on completion of the Number of Months.  When the specified “Number of Months of Service” is complete, an Employee is automatically incremented to the “Next Classification”.
 * Each Classification can have an effective date specified for each Pay Rate that you can set to increment and apply to the Employee’s in the Classification. 
 * Awards have a Weekly Rate and may have an Over Award Rate applied to Payroll Employees.
 * A second Over Award Rate added in addition to the Over Award Rate may be applied to individual Employees. 
 * Classifications may have additional Allowances generated for each Employee in a Classification.  These allowances are granted each Pay-run for those Employees.

Each Employee must be allocated to a Classification in order to obtain a rate of Pay.  The date of Employment is used to determine the date from which to calculate the Employee length of service.

When the Payroll is processed and the rate is not set up in the Pay Transaction Type the following applies: 

* The Classification of the Employee or the Classification entered against the Employee Hours in the pay journal is used to determine the Pay rate to assign to the Pay transaction.

Awards may have Associated Transactions. When a pay is run the Associated Transactions are generated for each Employee covered by the
Award.  These affect each Pay-run for Employees that falls within the date range of the Award Associated Transactions.  When the date fields are left blank no date limitation apply.

When an award has standard allowances (e.g. for uniforms) applicable to all persons on the payroll that are under that award, these can
be set up by creating Gross / Allowances for that Award.

On the Payroll Employee Card a second Over Award Rate can be added in addition to the Over Award Rate.


## To setup Award Classifications

The Award and Classifications menu options are only displayed after you flag the **Allow Award Pay Rates** check box on the **Options** FastTab, of the [Payroll Setup](au-payroll-setup-payroll-setup.md) card.

The Awards card is used to maintain Awards and to link the Award to Gross, Allowances, Associated Transactions, and Classifications. (For example shift allowances that apply to hours worked on a specific shift or to associate Leave Loading with Annual Leave.

1.  To access the Award setup, go to the following menu: *Departments/Payroll/Setup/Payroll Setup/Award/Awards &
Associated Transactions*

2.  To create a new record, click on the **New** button.

|Field|Description|  
|:---------------------------------|:---------------------------------------|  
|**Code**|This field is used to uniquely identify this Award.
|**Description**|This field is used to name this Award.
|**Gross/Allowances**|This field is automatically populated with a checkmark after transaction has been set up for this award.  The value cannot be changed here. To view the transactions set up for the award, select the **ArrowDown**.
|**Associated Transactions**|This field is automatically ticked after an Associated Transaction is set up for this award.  The value cannot be changed here. To view the transactions set up for the award, select the **ArrowDown**.
|**Position Code**|This field is optional and is used to indicate the Award is only used for a specific Position.  The position is attached to either a Payroll Employee.
|**Position Description**|This field is the description of the Position Code selected.
|**Customer No.**|The Customer No. field is used to identify that this Award pertains to a particular customer.
|**Public Holiday Calendar**|This field is optional and is used to assign a calendar to determine Public Holidays for this Award for the purposes of Award Interpretation.  Alternatively the Calendar can be attached to the Employee’s Branch and the Employee assigned to the Branch.
|**Certification Date**|This field is Mandatory and is used to enter  the date the Award is certified for use.   If this date is left blank you cannot setup the Award Interpretation Criteria Items for this Award as this date is verified when setting up Items.
|**Blocked**|This field is used to block the Award and any of its Classifications for use.
|**Comments**|This field is optional and is used to indicate a comment is recorded against this Award. To add or maintain comments click the “Navigation Menu” and then select the Comments icon.

3. Click on the **OK** button to close this window.
  
 
[GoToTop](#award-overview)


## Navigate Ribbon - Award

**Gross Allowances** - opens the Gross Allowances window.  You can link this Award Code to a specific Pay Transaction Type(s) to create Award Gross/Allowance records.

**Associated Transactions** - opens the Award Associated Transactions window.  You can associate this Award Code to Specific Pay Transaction Type(s) to create Award Associated Transaction records

**Award Leave Setup** - opens the Award Leave Transaction Setup window. The area allows you to setup Award Leave rules for each of the leave types associated to an award.

**Pay Item Criteria** - opens the Pay Item Criteria window. The Pay Item Criteria area allows you to configure pay items against an Award for the purposes of Award Interpretation. 

**Allow Item Criteria** - opens the Allow Item Criteria window. The Allowance Item Criteria area allows you to configure allowance items against an Award for the purposes of Award Interpretation.

**Classifications** - opens the Award Classification List window. The Award Code has a one to many classification links to create Award Classifications records.

**Comments** - opens the Comments window. The Comments area allows you to maintain and record comments pertaining to an Award which you might enter into NAV.


## Awards - Gross Allowances
The Award Code is linked to a Pay Transaction Type to create an Award Gross / Allowance record.

Where an award has allowances (e.g. uniform allowance) applicable to all employees under this award you can set up the Allowance under the Award so that it generates automatically each pay run.

|Field|Description|  
|:---------------------------------|:---------------------------------------|  
|**Transaction Type Code**|This field is used to select the Pay Transaction Type Code for the Gross and Allowance record. Select a “Transaction Type Code” from the **ArrowDown**. You can only select Transaction Types with an “Accumulation Summary Type” of Gross.
|**Shift Code**|	This field is used to filter the allowance to a specific shift worked by the employees under this award. Select a “Shift Code” from the **ArrowDown**. You can setup several Allowance line for each shift your employees use.
|**Start Date**|	This field determines the effective date from which this transaction is used.  An “End Date” must be entered when a “Start Date” is entered.
|**End Date**|	This field determines the date this transaction is no longer used.  An “End Date” must be entered when a “Start Date” is entered.
|**Description**| 	This field is used to display the description of the selected “Transaction Type”.
|**Use Full Week Hours**|	Tick this field to use the employees default hours from the Employee Pay card Rate tab.
|**Units**|	This field indicates the number of units paid by this transaction.
|**Fixed Value**|	This field determines the dollar value paid by this transaction.
|**Classification**|	This field is used to select the classification.
|**Apportion Cost**|	Tick this field to apportion the allowance to jobs entered into the pay journal for the employee.
|**Not Used**|	Tick this box to temporarily stop this transaction line from generating for the current pay period only.  To effectively end transactions you should use the Start and End date fields.

 
## Awards & Associated Transactions 

The Award Code is associated to Pay Transaction Types to create “Award Associated Transaction” records.

Awards may have Associated Transactions created to generate Pay Transactions for each Employee covered by that Award.  These will affect each Pay-run that falls within the date range specified.  If the date fields are blank no date limitations apply.

|Field|Description|  
|:---------------------------------|:---------------------------------------|  
|**Originating Tran. Type Code**| This field is used to select the originating Transaction Type Code the Associated Transaction Type applies its conversion factor against. Only Transactions Types with an Accumulation Type other than Deduction, Advance, Tax and Net may be used.
|**Transaction Type Code**|	This field is used to select the Pay Transaction Type Code generated when the Originating Transaction Type Code is used.  Valid Transaction Types are those with an Accumulation Type not equal to “Net”.
|**Shift Code**|	This field is used to filter the generation of Associated Transactions to a specific Shift. Select a Shift Code from the **ArrowDown**.
|**Start Date**|	This field determines the date from which this transaction is effective.  An “End Date” must be entered when a “Start Date” is entered.
|**End Date**|	This field determines the date after this transaction is not used.  An “End Date” must be entered when a “Start Date” has been entered.
|**Transaction Type Description**|	This displays the description of the selected Transaction Type.
|**Fixed Units**|	This field is used to enter Fixed Units. When a value is entered here it overrides the value entered on a transaction it is associated with.
|**Fixed Value**|	The field id used to enter the Value.  When a value is entered here it overrides the value entered on a transaction with which it is associated with.
|**Conversion Factor**|	This field is used for conversions of Pay.  Up to three decimal places may be entered.  The conversion factor is applied to the Pay Journal line.  The conversion factor is taken from the Pay Transaction Type.  The hourly rate is multiplied by the conversion factor to obtain the Pay Rate for the Pay Journal line.  The units in the Pay Journal line multiply the Pay Rate. **Example the transaction type equals ‘no value’. (E.g. sick with no entitlement available) then the conversion factor must be zero.**|
|**Number of Units before Used**|	This field is used to enter the total number of units the originating transaction must total before this associated transaction is generated.
|**Once Only Per Pay Run**|	Tick this box if the associated transaction is only generated once per employee in the pay run regardless of the number of times the originating transaction is used.
|**Not Used**|	This field is ticked when this transaction is not used for this pay period only.  To effectively end transactions, you must use the Start and End date fields.  

## Award Leave Setup 

The Award Leave Setup is used to defined the rules for Leave specific to each of the Awards.  An award has the potential to dictate what rules are to be incorporated when leave is applied for through the Dynamics AX HRPayFocus portal.

An example of a requirement is where Compassionate Leave in some awards allows up to 2 days per incidence whereas others may allow for 3 days.

|Field|Description|  
|:---------------------------------|:---------------------------------------|  
|**Award Code**| This field is used to identify the Award Code the Award Leave Setup is being configured.
|**Award Description**|	This field is used to identify the name of the Award.
|**Transaction Type Code**|	This field is used to identify the Transaction Type of the Leave that is being configured in the Award Leave Setup.  Select a Transaction Type code from the **ArrowDown**.
|**Transaction Type Description**|	This field displays the description of the Transaction Type code.
|**Blocked**|	This field can be used to block this particular transaction from the Award Leave Setup so that it may longer be in use.
|**Minimum Service (Months)**|	This field is used to define the minimum service in months for this particular transaction.  An example of where this might be used is where Parental Leave requires at least 12 months of service before it can be applied for.
|**Maximum Days Per Year**|	This field is used to define the maximum days allowed per year.   An example of where this might be used is where Parental Leave has a maximum of 12 months of leave per incident. 
|**Maximum Days Per Occurrence**|	This field is used to define the maximum days allowed per occurrence/application.

 
## Award Classification List

Classifications are linked to an Award Code to create an “Award Classification” record. 

In the Award Classifications window Classifications assigned to the selected Award are displayed.  New classification can be created from this card and from the menu option.  Classification can only exist in one Award

Each Employee is allocated a Classification Code.  The Description of the Classification is printed on various reports.
Once a Classification Rate has been used in a pay-run, it cannot be updated or deleted.  To make changes to the rate or conditions you must create a new Classification Rate dated before the next pay run.

The Classification Rates entered automatically update the employee classification rates 

1.  To access the Award Classifications, go to the following menu: *Departments/Payroll/Setup/Payroll Setup/Award/Classifications*

2.  To create a new record, click on the **New** button.

|Field|Description|  
|:---------------------------------|:---------------------------------------|  
|**Code**|This field is used to uniquely identify this Award Classification.
|**Description**|	This field is used to name this classification code.
|**Award Code**|	This field is used to select records defined in Awards & Associated Transactions.  Select an Award Code from the **ArrowDown**.
|**Description**|	This field is used to name this Award Code.  
|**No. Months Service**|	This field defines the number of months that must be completed by an employee before automatically incremented to the next classification.
|**Next Classification Code**|	This field is used to define the Next Classification the employee will automatically increment to after completion of the number of months of service.  The Next Classification must belong to the same Award as the current Classification.  Select a Classification Code from the **ArrowDown**.
|**Shift Code**|	This field is used to select a permanent shift for this Award classification if required
|**Work Cover Code**|	Enter the Work Cover Code applicable to this Classification
|**Position Code**|	This field is used to attach a specific position to the Award Classification.
|**Sub Band**|	This field is used to define the Sub Band code which will be setup within HRPayFocus.


 
## Award Classifications & Rates

This form is used to define the Classification Rates of Pay.

1.  To access the Classifications & Rates, go to the following menu: *Departments/Payroll/Setup/Payroll Setup/Award/Classifications & Rates*

2.  Select **Edit** once you have launched the window.  

3.  On the **General** FastTab, fill the following fields;

|Field|Description|  
|:---------------------------------|:---------------------------------------|  
|**Code**| Used to identify the Award Classification.
|**Description**|	Used to name this classification code.
|**Award Code**|	Select the Award Code from the **ArrowDown**.
|**Next Classification Code**|	This field is used to define the Classification an employee will automatically increment to on completion of the number of months of service.  The Next Classification must belong to the same Award as the current Classification.
|**No. Months Service**|	This field defines the number of month’s service that must be completed by an employee before incrementing to the next classification.
|**Position Code**|	This field is used to attach a specific position to the Award Classification.

4.  On the **Workers Comp** FastTab, fill the following fields;

|Field|Description|  
|:---------------------------------|:---------------------------------------|  
|**Work Cover Code**| This field is used to assign the Workers Compensation Rate to this Classification.  Select the Work Cover Code from the **ArrowDown**.

5.  In the **Award Classification Subform** FastTab, fill the following fields; 

|Field|Description|  
|:---------------------------------|:---------------------------------------|  
|**Starting Date**| The Starting Date is used to define the date this rate is effective for this Award Classification.
|**Shift Code**|	This field indicates the shift this Award classification is applicable against Award Rate.	The pay rate for this Award Classification line.
|**Over Award Rate**|	This field is the over award pay rate for this Award Classification.  The Award plus the Over Award rate is the total weekly rate for this Award Classification.
|**Charge Rate**|	This field is used to enter the charge rate for Jobs.
