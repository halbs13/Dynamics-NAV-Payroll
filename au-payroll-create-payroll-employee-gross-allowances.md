# Payroll Employee card – Navigate ribbon - Gross & Allowances

This area is used to setup permanent Gross Pay Transaction Type and Allowances for employees.   This means that whatever transactions are setup here will either automatically generate based on the Start or End Dates.  An example of when you might set transactions up is where an employee is an “Auto paid” employee.  

Allowances can also be setup as an “Associated Transaction” and will be paid to the employee if a specific Pay Transaction Type is used to trigger the transaction.  
  
E.g. If a “Meal Allowance” transaction is associated with an Overtime Pay Transaction it can be setup in the Associated Transactions area.  When the overtime transaction is entered on the Pay Journal the employee automatically receives the meal allowance.


|Field|Comments|
|---|---|
|Transaction Type Code|This field is used to select the Ordinary Pay Transaction Type for the employee’s standard hours (auto pay) You must tick the “Use Full Week Hours” flag|
|||
||Setup any permanent Allowance Transaction Types with a fixed value or units and their “Associated” Pay Transaction Types. |
|||
||E.g. Add a Pay Transaction Type, for Overtime, and leave the fixed value and units’ fields blank.  Add an associate Pay Transaction Type, for Meal Allowance, to the Overtime Pay Transaction Type.  (Whenever an Overtime transaction type is used in the Pay Journal for this employee they will receive the Meal Allowance pay transaction automatically.|
|||
||The “Transaction Type Code” is selected using the “ArrowDown” in the field.|
|Shift Code|If the employee works a “Shift” enter the shift code (for shifts where an allowance is paid)
|||
||E.g. When the employees work the midnights to dawn shift they will receive the Pay Transaction Type allowance for sleep deprivation automatically.  If the employee does not work this shift then they will not receive this allowance.||Start Date|This field is used to enter the date from which this Pay Transaction Type applies.|
|End Date|This field is used to enter the date this Pay Transaction Type ceases.  This field is left blank if the Pay Transaction Type is to apply for an indefinite period.|
|Description|This field displays the Pay Transaction Type description.|
|Use Full Week Hours|Tick this flag if the employee is to be paid the standard number of hours each pay period against this Pay Transaction Type.  This type of payment is usually setup for Automatically paid (Auto-pay) employees.|
|Units|This field is used to enter the number of units to pay the employee each pay period on a permanent basis.|
||Generally, units are hours, but units can also be kilometres, etc.|
||If the Pay Transaction Type is not a unit’s type leave this field zero.|
|Fixed Value|Use this field to enter the fixed amount the employee is paid each pay period.|
||This field is left zero if a fixed amount is not to be paid.|
|Classification|If the Pay Transaction Type is paid at a different Classification Pay Rate to the employee’s normal Classification Pay Rate enter the Classification for the different pay rate in this field.|
|Hourly Rate|This field is used to display the “Hourly Rate” from either the employee Pay Rate or the Classification card for this Pay Transaction Type (for Pay Transaction Types that have the “Rate Calculation Method” field set to “Employee Pay Rate”). | 
||The “Use Full Week Hours” flag must also be ticked.  The value in this field cannot be changed. |
|Pay Value|This field is calculated using the Employee’s Hours in Full Week, Hourly Rate, Number of Days per week and their Pay Frequency.  The value in this field cannot be changed. |
|Apportion Cost|This field indicates if the Allowance paid is apportioned to Jobs by the same ratio of hours worked on a job by the employee.|
||An Allowance in this case is referring to a Pay Transactions Type with the Accumulation Type of "Allowance".|
|Associated Transactions|This field indicates if this Pay Transaction Type has associated transactions linked to it.|
|Not Used|If this field is ticked the Pay Transaction Type is not applied to the “current” pay period only.  The flag will be reset for the next pay period.|
|Navigate ribbon||
|Associated Transactions|This option is used to setup Pay Transaction Type associated with the Pay Transaction Type on the Gross & Allowances card.|
|Pay Details Enquiry|This option allows you to preview the employee’s standard pay for the current pay period.|

 

 






























 


#### Payroll Employee card – Navigate ribbon – Associated Transactions

The “Allowance Associated Trans” window is used to maintain the links between Pay Transaction Types and their “Associated” Pay Transaction Types.  

  

For example, a Living Away from Home allowance is associated with the Ordinary Pay Transaction Type for this employee.  Each time the employee is paid Ordinary time the employee also receives the allowance for LAFH.

 
 
