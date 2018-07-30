# Classification Rates

The Classification Rate Change Report is used to change Payroll Award Classification Rates of Pay.

The rates held in these records are used to update the Employee Classification rate table for employees in the Classification.  These Classification Codes can also be assigned on the fly within the time sheet entry and pay journal for an employee. 

Back Pay calculations are based upon rates changes which update the Employee Classification rate table.

The next Classification and length of service can be maintained to allow for automatic updating of Employee Classifications within an Award from one classification to another.  
The End of Period Close process checks the Date that the Classification Last Changed for the employee, to determine when this occurs.  If the Classification is due to be changed within the next Pay Period, then it is updated when you close the period.

To open the Classification Rate Change window, 

*Departments/Payroll/Periodic Activities/Change Rates/Classification Rates*
 


#### Classification Rate Change – Options FastTab

|Field	|Comments|
|---|---|
|Classification Start Date|	Enter the date the new classification pay rate becomes effective.|
||**Note** the pay rate change is effective from the first day of the pay period that this date falls within. The system will not spilt the employees pay rate automatically in the same pay period for the old rate and the new rate.| 
|Award Rate|	Select one of the following options;|
||*	Adjust By Amount - Select this option to adjust the current award rate by the value entered in the "Adjustment" field.|
||*	Adjust By % - Select this option to adjust current award rate by the percentage entered in the "Adjustment" field and Rounding Precision field.|
||*	Set New Rate - Select this option to set the new award rate to the value entered in the "Adjustment" field.|
|Adjustment|	Enter the value to adjust the award classification rate.|
|Rounding Precision|	This field is only available when adjusting the award rate by a percentage.|
||Enter the "Rounding Precision" for the "Adjust By %" calculation.|  
|Apply to Employees|	By selecting this option any changes to the classification rates will apply to the employee’s Pay Rate.|
|Over Award Rate|	Select one of the following options;|
||*	Adjust By Amount - Select this option to adjust the current over award rate by the value entered in the "Adjustment" field.|
||*	Adjust By % - Select this option to adjust the current over award rate by the percentage entered in the "Adjustment" field.|
||*	Set New Rate - Select this option to set the New Over Award Rate to the value entered in the "Adjustment" field.|
|Adjustment|	Enter the value that will adjust the over award classification rate.|
|Rounding Precision	|This field is only available when adjusting the over award rate by a percentage |
||Enter the "Rounding Precision" for the "Adjust By %" calculation. |

 [GoToTop](#classification-rates)

#### Classification Rate Change – Classification FastTab

|Field	|Filter|
|---|---|
|Only the standard fields are covered.  A full list of fields available as filters can be used by selecting the first blank line and selecting the “ArrowDown”.|
|Award Code|	Select the “Award Code” the classification is under that you wish to change.  If left blank all awards are used.|
|Code|	Select the Award Classification “Code” you wish to change.  If left blank all Award Classifications are processed. You can use this for an across the board pay rise for all employees|


#### Apply Classification Rate to Employees

The Apply Classification Rate to Employee Report is used to apply the above Classification Rate Change to Payroll Employees.

When a new Classification is selected for the Employee the date to commence paying the Classification rate is entered.
The Classification is selected, the Classification rates that apply after that date, and before today are copied into the Employee rates table.  The first rate is given the date that was entered, and any subsequent rates are given the date from which that Classification rate started applying.

To open the Apply Class Rate to Employees 

*Departments/Payroll/Periodic Activities/Change Rates/Apply Classification Rate to Employees*
 

#### Apply Class. Rate to Employees – Options FastTab

|Field|	Comments|
|---|---|
|Apply Award|	Select the Award to apply the rate change.  If left blank then all Awards are processed.|
|Apply Classification	|Select the Award Classification to apply the rate change.  If left blank then all Award Classifications are processed.|
|Apply Most Recent Rate|	Select this field to apply the most recent award classification rate to the employee. | 
||Un-select this field to use the award classification rate with the "Classification Rate Start" date entered below.|
|Classification Rate Start|	Enter the "Classification Rate Start" date of the classification rate to be applied to the employee.|
||This option is only available if "Apply Most Recent" above is not selected.|
|Include Employees|	The options available for selection are;|
||*	Only In The Classification - If selected only employees that currently belong or have belonged to the classification will have the new rate applied to them.|
||*	Not In The Classification - If selected only employees that do not belong and never have belonged to the classification will have the new rate applied to them.|
||*	Not In Any Classification - If selected only employees that do not yet belong to any classification will have the new rate applied to them.|
|Employee Start Date|	Enter the date the employee is to begin on the new classification rate.|

#### Apply Class. Rate to Employees – Apply To Payroll FastTab

|Field|	Filter|
|---|---|
|Only the standard fields are covered.  A full list of fields available as filters can be used by selecting the first blank line and selecting the “ArrowDown”.|
|No.|	Enter a payroll to filter which employees receive the award rate change. | 

 
 [GoToTop](#classification-rates)
 
