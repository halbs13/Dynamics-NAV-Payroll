4.9.3	Pay Transaction Bulk Generation 
Pay Transaction processing is used to generate bulk pay transactions such as public holidays etc.

•	Bulk Generation

4.9.3.1	Pay Transaction - Bulk Generation 
Bulk Generation is used to generate bulk Pay Journal lines for a Pay Transaction Type for a selected Payroll for the current pay period.

This option can be used to create Public Holiday or Annual Leave pay transactions for all employees with the option of excluding non-permanent employees. It can be used for other Pay Transaction types if required such as a Bonus payment.

Bulk Pay Transactions will not generate for employees who have already be paid for the current pay period.

To open the Bulk Generation window, 

Departments/Payroll/Periodic Activities/Pay Transactions/Bulk Generation
 

4.9.3.2	Generate Pay Transactions – Options FastTab
Field	Comments
Date of Transaction	Use this field to enter or select a date within the Current Pay Period for the bulk transactions. 
Transaction Type	This field defaults to Ordinary Pay Transaction Type defined on the “Payroll Setup” card.  You can override the Transaction by selecting a Pay Transaction Type (E.g. Public Holiday, Annual Leave)
Amount 	This field is used to enter a value for this transaction.  If entered the Day and Unit fields must be left as zero.
Days	This field is used to enter the number of days to use for this transaction.  If entered then the Amount and Units fields are to be left as zero.
Units	The “Units” is the number of units to use for this transaction.  Units may be hours/decimals, occurrences, etc. If entered then the Amount and Days fields must be left as zero.
Subtract from Permanent	This field is ticked if the number of units is to be subtracted from the ordinary hours during the Calculate Pays process.
The flag defaults from the Pay Transaction Type.  You may override this flag here.
Pay Advice No.	Enter the “Pay Advice No.” you want this Pay Transaction paid in.
Exclude Non-Permanent Employees	Select this option to exclude employees who are not Full Time 
The following fields are default values that cannot be altered here.  They are used to confirm the transactions you are generating are for the correct Payroll and Pay Period.
Payroll No.	The “Payroll No.” the Pay Transaction is to be generated for.
Tax Year	The “Tax Year” of the Pay Period that the Pay Transaction is to be generated for.
Period No.	The “Period No.” of the Pay Period you are generating the Pay Transaction for.
Pay Period Starting Date	The Pay Period Start Date for the Pay Period that the Pay Transaction is to be generated.
Pay Period Ending Date	The Pay Period End Date for the Pay Period that the Pay Transaction is to be generated.



4.9.3.3	Generate Pay Transactions – Payroll Employee FastTab
Field	Filter
Only the standard fields are discussed.  A full list of fields available for filters can be selected by selecting the “ArrowDown".  
Employee No.	This field is use as a filter to limit the employee’s that you wish to generate the bulk transactions.
Leave this field blank to generate transactions for all employees in the selected Payroll 
You may enter the Employee No(s) or select an Employee No(s) by clicking in the field and selecting the “ArrowDown”.

