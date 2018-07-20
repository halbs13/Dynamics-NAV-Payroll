# PROCESSING BACK PAY CALCLUATIONS

When award rates have changed and are backdated prior to the current period, this function is used to generate the pay variance for the periods affected by the new pay rate.  The Back pay adjustments are created in the current pay period for the selected Payroll.  

Before you can generate Back Pays you must first change the Award Classification and or Employee Over award Rate using a past period date for the change to become effective. 
The generated pays are inserted into the Pay Journal for the current pay period. 

The default Pay Transaction Types used for the ‘back pay’ gross amount and ‘back tax’ amount, are specified on the General FastTab of the “Payroll Setup” card.  

You can make adjustments to the transaction lines generated in the Pay Journal if you require before you generate the pays.

This function is used to calculate Back Pay for selected Payroll(s), Employees, and Period(s).  
You can choose to produce a report with no update.  The amounts calculated will adjust the Job Cost for the jobs worked during the previously processed period if applicable.

To open the Back Pay Calculation window,

Departments/Payroll/Payroll Processing/Back Pay Calculation
 

4.9.1.1	Back Pay Calculation – Options FastTab

|Field|	Comments|
|---|---|
|The first 4 fields specify the period of time to apply the back pay calculation.|
|Tax Year From|	Select the From Tax Year and Period for the back pay calculation by selecting the “ArrowDown" |
||Selecting a record populates the “Tax Year” and the “Period” in the “From” fields.|
|Period From|	Select the From Tax Year and Period for the back pay calculation by selecting the “ArrowDown" |
||Selecting a record populates the “Tax Year” and the “Period” in the “From” fields.|
|Tax Year To|	Select the To Tax Year and Period for the back pay calculation by selecting the “ArrowDown"| 
||Selecting a record populates the “Tax Year” and the “Period” in the “From” fields.|
|Period To	|Select the To Tax Year and Period for the back pay calculation by selecting the “ArrowDown" |
||Selecting a record populates the “Tax Year” and the “Period” in the “From” fields.|
|No. of Back Pay Weeks|	This field is used to display the number of weeks included in the back pay.  | 
|Document Date|	The Document Date can be a date within the Pay Period and will typically be the first date of the Pay Period.|
|Posting Date|	The Posting Date defaults to today’s date.  You may select an alternate posting date |
|Show All Employees	|Select this box to display all selected employees on the report regardless.  Leave this field blank to only display employees that receive a back pay.|
|Report Only|	This field is used to produce a report used to check back pay calculations before you commit them for Payment.| 
||Leave this field blank to generate the pay transactions in the Pay Journal.|  
|Pay Advice No.|	Use this field to enter the Pay Advice No. you want the transactions paid in.|  
||If left zero the system will place the back pay transactions into the current pay advice.|
|Batch Name|	You may enter the "Batch Name" of the Pay Journal Batch into which the generated back-pay journal lines are to be placed.|
||This field defaults to the last Pay Journal Batch used.|
||Select a Batch Name by selecting the “ArrowDown".|
|The following fields are default values that cannot be altered.  They are used to confirm the Payroll, Tax Year and pay Period the back pay transactions generated in.|
|Current Pay:||	
| Payroll No.	|The selected Payroll number.|
| Tax Year|	The current Tax Year.|
| Period No.|	The current Pay Period number.|
| Pay Period Start Date|	The Starting dates of the current Pay Period.|
|Pay Period End Date	|The Ending dates of the current Pay Period.|

4.9.1.2	Back Pay Calculation – Payroll Employee FastTab

|Field	|Filter|
|---|---|
|Only the standard fields are covered here.  A full list of fields available as filters can be used, by selecting the first blank line, and selecting the “ArrowDown".|  
|Employee No.|	Select the Employee(s) No. by selecting the “ArrowDown".|
||Leave blank to include all employee in this payroll|


