# To setup Pay Transaction Types

Default Pay Transactions are automatically created when the Codeunit 16000400 Payroll-Initialise is run when the system is installed.  

Pay Transaction Types are used to calculate pays, superannuation, leave accruals, payroll tax and to determine the output for Payment Summaries, identify taxable and non-taxable transactions, identify vendors and to determine General Ledger posting etc.  Additional Pay Transaction types must be set up to cater for each Superannuation Company and individual company requirements

Examples of Pay Transaction Types are Normal Time, Overtime, Net Pay, Superannuation, Allowances, Deductions, and Leave Payments.

1. To access the Pay Transaction Types, go to the following menu: *General Setup/Pay Transaction Types*.

2. On the **General** FastTab, fill the fields in the following table.

|Field|Description|  
| :--- | :--- |  
|**Code**|This field is used to identify the Pay Transaction Type and is used in Journal lines.|  
|**Brief Description**|This field is used to provide a short description for the **Pay Transaction Type**.|  
|**Description**|This field is used to provide a detailed description for the “Pay Transaction Type”.|
|**Accumulation Type**|This field is mandatory and is used to group like transactions together for processing by the system and reporting.  The Accumulation Types are: Ordinary,Overtime, Annual Leave, Leave Loading, Long Service Leave, Sick Leave, Other Leave, Time in Lieu, Lump Sum, Allowance, Deduction, Advance, Tax, Net, On Cost. Select an option from the **ArrowDown**.|
|**Accumulation Summary Type**|This field is used to group Accumulation Types together for processing by the system and for reporting.  This field is populated automatically depending on the Accumulation type selected in the previous field.  You cannot change this field.|
|**Deduction Type**| This field is used only when the Accumulation Type = Deduction. The options are Deduction or Superannuation.  If the deduction is for Superannuation you must select Superannuation to include the deduction in all Superannuation reporting. Select an option from the **ArrowDown**.|
|**P.S. YTD Accumulation Code**|This field is used for Pay Transaction Types that must accumulate and print on the Employee’s Payment Summary.  The accumulation code selected determines where the amount is printed on the Payment Summaries. If no Code is selected, the amount does not print on the Payment Summary. The ATO determines the Pay Transactions that must print on the Payment Summary.  See the “Year To Date Accumulations” section  for further information.|
|**Non-P.S. Accum. Code**|This field is similar to the PS. YTD Accumulation Code, except it is used to accumulate values that do not print on the Payment Summary. These accumulation codes can be used for reporting. See the “Year To Date Accumulations” section for further information.|
|**Report Group**|This field is user defined and is used to group Pay Transaction Types for reporting purposes.|
|**Blocked**|A checkmark in this field indicates that the Pay Transaction type can no longer be used.|

3.  On the **Calcluations** FastTab, fill the fields in the following table.

|Field|Description|  
| :--- | :--- | 
|**Rate Amount**|This field is used to apply a fixed rate to a Pay Transaction Type.  When a Rate is entered it is used as the default value. The value can be overridden at the Employee Level.  If this field is left blank the rate must be entered at the Employee Level or at the time of entering the Pay Journal.  The format used to enter this value is determined by the option selected in the “Rate Calculation Method” field.|
|**Rate Conversion Factor**|This field determines the factor applied to the Rate Amount. 3 decimal places may be entered E.g. Transaction Type for Overtime at time and a half - the Rate Conversion Factor is 1.5. If the Pay Transaction Type is Leave Without Pay then the Rate Conversion factor is 0 (zero).|
|**Rate Calculation Method**|This field is used to select the type of rate used for the calculation (Percentage, Unit or Employee Pay Rate). E.g. Employee Pay Rate - the Pay Transaction Type uses the Employee’s Pay Rate setup on the Employee’s Payroll Employee card.  Units – Amount entered in the Payroll Employee card for Superannuation or a Deduction Percentage – SGC  9% = 0.09.|
|**Calculation Base**|This field is used only for On Cost Pay Transaction Types.  Select the corresponding on cost accumulation code from the **ArrowDown**.|
|**Deduction Basis**|The “Deduction Basis” field defines the calculation of a Deduction when setup as a % value.  The options are; Net Pay – this option will calculate the deduction based on the Net Pay.   Gross Income – this option will calculate the deduction based on the Gross Income. Taxable Gross Income – this option will calculate the deduction value based on the Taxable Income.|
|**Apply Lump Sum Tax Method**|The “Apply Lump Sum Tax Method” when selected will apply the Lump Sum Tax Method ruling to the value of the transaction when calculating tax.This field will only work on when the Lump Sum Tax Method is Bonus/Commission.|
|**Lump Sum Tax Method**|This field is used to define the calculation of Tax on(Termination) Lump Sum Payments, Bonus/Commissions or ETP calculations. The options available are; A, B, C, D, ETP Life Excluded, ETP Life Non-Excluded, ETP Death Non-Dependant, ETP Death – Dependant, ETP Death – Trustee, Bonus/Commission. Select the Lump Sum Tax Method from the **ArrowDown**.|
|**Vendor No.**|This field is used for deduction Transactions Types. The Vendor must first be setup in the Payables Granule. When a Vendor is selected unpaid invoice are created against the vendor when a transaction is generated from Payroll.  You can select the Vendor from the **ArrowDown**.  (See the Vendors option on the Payroll - Tran Type button. You can specify a Vendor for a specific Payroll for this Pay Transaction Type.  When set, the Payroll specific vendor will override the Vendor on the Calculations FastTab.)|
|**Charge Rate Conversion Factor**|This field is used in a similar way to the Rate Conversion Factor except it is applied to the “Charge Rate”.|

4.  On the **Leave Application** FastTab, fill the fields in the following table. 
  
|Field|Description|  
| :--- | :--- |  
|**Apply to Leave Taken**|This checkbox only applies to Annual, Long Service, Sick, and Time In Lieu Pay Transaction Types.  Select this box to indicate the transaction is applied as leave taken.   It is used to determine if the entered hours are taken off the leave entitlement balances.|
|**Leave Type**|This field is used to define the leave entitlement type the hours are taken from. Select the Leave Type from the **ArrowDown**.|
|**Cause of Absence Code**|This field is used to indicate the cause of absence and is linked to Human Resources Absence Register.  Select the Cause of Absence from the **ArrowDown**.|
|**Accum. For Leave Calculations**|This indicator is used to flag the transactions applicable to leave entitlement accumulation. This field is used when leave entitlement is based on ordinary hours worked. The following options are available; Accumulate – this setting identifies that the value of the transactions (whether that be Hours or $ value) will be used as the basis of the accrual calculation.   No Accumulation – this setting identifies that there is no accrual on the Hours or $ value of this transaction.  Value Only – this setting identifies that the $ value of this transaction will be used as the basis of the accrual calculation.  Units Only – this setting identifies that the Units (Hours) of this transaction will be used as the basis of the accrual calculation.|

5.  On the **Parameters** FastTab, fill the fields in the following table. 

|Field|Description|  
| :--- | :--- |  
|**Apply to Taxable Income**|This field is used to determine if the value calculated for this Pay Transaction Type is taxable.  Select this field to apply PAYG tax or leave this field blank for exempt transactions.  Note: Pre tax deductions for Salary Sacrifice must have this flag ticked to reduce the tax liability.  Leave this field blank for Post tax deductions.|
|**Apply to Superannuation**|Select this field to indicate the PayTransaction Type is used in the calculation of percentage based Superannuation amounts.This field determines if the value of this Pay Transaction Type is to be included in the calculation and have SGC calculated.|
|**Apply to Min. Salary Check**|Tick this field to include this Pay Transaction Type as part of the employee’s “ordinary time earnings”. The “ordinary time earnings” is used with the “Monthly Min. Earnings” field on “Payroll Setup - Superannuation” tab to determine if the employee has earned the minimum monthly pay to be eligible for Superannuation Guarantee Contributions.|
|**Apply to Time In Lieu**|Tick this field to indicate if this Pay Transaction Type is used in the calculation of Time in Lieu.|
|**Apply to Work Cover**|Tick this field to indicate if this transaction is to be part of Workers Compensation gross pay.  The gross value is used for the calculation of the Workers Compensation Rate contribution.|
|**Apply to Hours Worked**|This field is used to determine if this Pay Transaction Type is applied to hours worked for the calculation of Leave accruals and Superannuation.|
|**GST Applicable**|A checkmark in this field indicates that GST is applicable to the transaction type.  This field is used to invoke a GST transaction for employees who trade as Incorporated Companies.|
|**Gen. Prod. Posting Group**|This field is used for posting the GST component to the General Ledger.  This field should be completed if GST is applicable for the transaction’s value to be included in the BAS.|
|**GST Prod. Posting Group**|This field is used for posting the GST component to the General Ledger.  This field should be completed if GST is applicable for the transaction’s value to be included in the BAS.|
|**Subtract From Permanent Hours**|Tick this field to automatically reduce the Ordinary Hours by the hours entered for this Transaction Type on the pay journal line.  This field is only applicable for Leave type Transactions when the employee is auto-paid.|
|**Payroll Report Category**|The “Payroll Report Category” field is used to defined where each of the transactions will appear in the Payroll Report.|

6.  On the **Posting** FastTab, fill the fields in the following table. 

|Field|Description|  
| :--- | :--- |  
|**Transaction Posting Group**|This field is used to determine the Debit posting group for this “Pay Transaction Type”. The Pay Journal uses this group to determine the GL Account to post against. **Note: This field Increases the Expense Accounts and Decreases the Balance Sheet Accounts**|
|**On Cost Prov. Posting Group**|This field is only used for On Cost Accumulation Type transactions. It is used to Credit the Provision Accounts.  **Note: This field Increases the Balance Sheet**.|
|**Do Not Post Dimensions**|Tick this field to stop Dimensions posting for this Pay Transaction Type to the General Ledger Accounts.  This flag might be ticked for Deduction Pay Transaction Types.|
|**Is Hold Pay Transaction Type**|A checkmark in this field indicates that the transaction type is a “Hold Pay” transaction. These types of transactions are used to hold contractor’s gross or net pay.|
|**Exclude from Integration**|A checkmark in this field indicates that this transaction type will not be transferred across to AXiOM.  An example of where you might use this is if the Pay Transaction Type is used for internal purposes only, e.g. Annual Leave.|
|**Timesheet Submission Tracking**|A checkmark in this field indicates that this transaction type is applicable to timesheet tracking used in identifying missing timesheets for a contractor.  An example of where you might use this is tracking missing timesheets on Ordinary time.|
|**Automatic Timesheet Generation**|A checkmark in this field indicates that a timesheet will be generated for this transaction type.|

7. Click on the **Arrow** button after you have completed your record.  

You can learn more about setting up [Transaction Groups and Posting Setup](au-payroll-setup-posting-group-setup.md)
  
## Pay Transaction Types – Vendors

This function is used to allocate specific Vendor to the current Pay Transaction Type for a specific Payroll.  The “Vendor No.” field is only applicable to deduction transactions that money is drawn from the employees pay and then paid directly to a vendor, e.g. Tax, Private Health Insurance, etc.  An unpaid invoice is created for the vendor the amount deducted from the employees pay. 

1.  To create a new record, click on the **New** icon.

|Field|Description|  
| :--- | :--- |  
|**Payroll No.**|This field is used to define a vendor by payroll no. if this is transaction is to have a different vendor by payroll. Select the Payroll No. from the **ArrowDown**.|
|**Vendor No.**|This field is used to define a vendor no. for this transaction type.  Select the Vendor No. from the**ArrowDown**.|
|**Name**|This field is used for informational purposes only.|

2.  Click on the **Arrow** button after you have completed your record.

## Pay Transaction Types – Payroll Tax

This function determines the “Payroll Tax Code(s)” applicable to this Pay Transaction Type. This field works in association with the payroll tax code and the branch the employee is assigned to flag the Transaction at the time of Posting as Payroll Taxable.  

1.  To create a new record, click on the **New** button.
  
|Field|Description|  
| :--- | :--- |  
|**Payroll Tax Code**|This field is used to add the Payroll Tax code applicable for this transaction.  Select the Payroll Tax code from the **ArrowDown**.|
|**Description**|This field is used for informational purposes only.|

2.  Click on the **Arrow** button after you have completed your selection

You can learn more about setting up [Payroll Tax Rates & Thresholds](au-payroll-setup-payroll-tax.md)
  
## Pay Transaction Types – Accumulators

This function is used to allocate on cost accumulators to this Pay Transaction Type.  The accumulator codes are used to accumulate values for On-Cost calculations.  Transactions that have an accumulator matching the “On-Cost Calculation Base” field of an On-Cost type transaction form the basis for the calculation of its value.

1.  To create a new record, click on the **New** button.
  
|Field|Description|  
| :--- | :--- |   
|**Accumulator Code**|This field is used to add the Accumulator code applicable for this transaction. Select the Accumulator Code from the **ArrowDown**.|
|**Description**|The Accumulator Description will default through from the code that is selected.|
|**Negative Accumulator**|A checkmark in this field indicates that you expect the calculation base to be a negative value.|

2.  Click on the **Arrow** button after you have completed your selection.

You can learn more about setting up [Accumulation Calculations](au-payroll-setup-calculation-accumulators.md)

[GoToTop](#to-setup-pay-transaction-types)

