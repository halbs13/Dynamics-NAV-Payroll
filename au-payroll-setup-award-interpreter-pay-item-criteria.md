# Award Interpreter Pay Item Criteria 

When reviewing the Pay Item Criteria, there are 2 methods of viewing this information;

1. [Pay Item Criteria List](#pay-item-criteria-list)

2. [Pay Item Criteria Worksheet](#pay-item-criteria-worksheet)

## Pay Item Criteria List

The fields on this form are for display purposes only. The Pay Item Criteria records that have been setup to interpret the hours into Pay Transaction Types for the Award or the Award Classification are listed.

They are maintained in the Item Criteria Worksheet. 

1. Fill the fields in the following table.

|Field|Description|  
|:---------------------------------|:---------------------------------------|  
|**Classification Code**| This field displays the Award Classification Code.
|**Award Code**|This field displays the Award Code.
|**Pay Transaction Type**|This field displays the Pay Transaction Type code that is generated from this Pay Item criteria.
|**Pay Tran. type Description**| This field displays the Pay Transaction Type description.
|**Starting Date**| This field displays the date the criteria becomes effective.
|**Sequence No**| This field displays the sequence and must be greater than 0. The sequence defines the order that Time and Attendance Pay Items are applied when the maximum threshold has been reached.
|**Line No**| This field is used internally by the system.
|**Ending Date**| This field displays the date the criteria is no longer used.
|**Day of the Week**| This field displays the day of the week.
|**Max, hours**| This field displays the maximum hours worked for this Pay item until the Interpreter moves to the next sequence. It must lie within the range of: 0 - 24.
|**Max Hours Per Week**| This field displays the maximum hours per week for this Pay.
|**Min. Hours**| This field displays the minimum hours worked for this Pay Item and must lie within the range of: 0 - 24. This field determines the minimum hours that must be worked on the day. When the minimum hours have not been met then the minimum hours of work is paid.
|**Start Time**| This field displays the earliest start time and must be between 00:00 - 23:59. When a timesheet is processed with hours that lie within the Start and End times the Pay Item is generated
|**End Time**| This field displays the latest end time and must be between 00:00 - 23:59
|**Apply to Following Day**| This field is used to apply the Pay Criteria to the next day's week ending date.
|**Unpaid Break**| This field is used to enter the quantity allowed for unpaid breaks for lunch and tea.
|**Applies to Cause of Absence**| This field is used to force this transaction to be used instead of Ordinary when the Cause of Absence Code is equal to this field.  This is used to generate Leave etc.
|**Rounding method**| This field displays the rounding method:
||•	No Rounding
||•	Nearest
||•	Up
||•	Down
||This field works with the rounding precision.
|**Rounding Precision**| This field displays the rounding precision for the rounding method:
||•	Minute
||•	5 Minutes
||•	6 Minutes
||•	15 Minutes
||•	30 Minutes
||•	Hour
|**Apply to Following Day**| This field is used to apply these hours breaching 12midnight to the next day period end date.
|**Deleted**| This field indicates the line is no longer used to generate transactions.

## Pay Item Criteria Worksheet

The Item Criteria Worksheet is used to setup and maintain the Pay and Allowance Criteria Items used to interpret the timesheet lines.

1. To open the Item Criteria Worksheet form, *Departments/Payroll/Setup/Award Interpreter/ Interp. Setup Worksheet*

2. Fill the fields in the following table

|Field|Description|  
|:---------------------------------|:---------------------------------------|  
|**Starting Date**|	This field is used to enter the start date the criteria becomes effective. This date must be on or after the Award Classification Certification date.
|**Ending Date**| This field is used to enter the date the criteria are no longer used. This date must be after the Starting Date.
|**Award Code**| This field is used to select the Award.
|**Award Description**| This field is used to display the description.
|**Classification Code**|	This field is used to select the Award Classification Code.
|**Classification Description**|	This field is used to display the description.
|**Position Code**| This field is used to specify a Position.

Depending on the Criteria Type you wish to setup select from the following tabs:

•	Pay Item Criteria Worksheet Card

•	Allowance Criteria Worksheet Card

## Pay Item Criteria Worksheet Card

The Pay Item records are used to interpret the hours into Pay Transaction Types. You setup the criteria for example; Ordinary Time, Overtime, Public Holidays, Leave etc.

1.  Fill the fields in the following table 

|Field|Description|  
|:---------------------------------|:---------------------------------------|  
|**Starting Date**| This field is used to enter the date this criteria becomes effective and is used to interpret timesheets. This date must be equal to or greater than the Classification Certification date
|**Ending Date**|	This field is used to enter the date the criteria is no longer effective.
|**Award**|	This field is used to apply the criteria to a specific Award. If the Classification is not specified all employees attached to the Award work under the criteria setup for this Award
|**Award Description**|	This field is used to display the Description
|**Classification Code**|	This field is used to select a specific Classification Code to limit the criteria to only apply to the specified Classification
|**Classification Description**|	This field displays the Award Classification Description.
|**Position Code**|	When the Award Classification is setup specifically for only 1 position this field displays the position
|**Criteria Type**|	This field displays Pay for Pay Item Criteria
|**Day of the Week**|	This field is used to select the day of the week the criteria applies.
|**Sequence No**|	This field is used to enter the sequence and must be greater then 0. The sequence defines the order that Time and Attendance Pay Items are applied when the maximum threshold has been reached for a Pay Item. 
||For example: When Ordinary time reaches the threshold of 38 hours in a week move to sequence 2 to pay overtime.
|**Pay Transaction Type**|	This field is used to select the Pay Transaction Type code that generates from this Pay Item criteria.
|**Pay Tran. type Description**|	This field displays the above Pay Transaction Type description
|**Start Time**|	This field is used to enter the earliest start time and must be between 00:00 - 23:59. When a timesheet is processed with hours that lie within the Start and End times the Pay Item is generated
||For example Ordinary time is paid between the hours of 6am and 6pm. If the employee starts work at 5am a different criteria line applies to the hour worked before 6am.
|**End Time**|	This field is used to enter the latest end time and must be between 00:00 - 23:59
|**Max. hours**|	This field is used to enter the maximum hours worked in a day that is allowed for this Pay item and must lie within the range of: 0 - 24. 
||For example once Ordinary time of 7.6 hours has been worked the next sequence used to pay the remaining hours as Overtime.
|**Min. Hours**|	This field is used to enter the minimum hours worked allowed for this Pay Item and must lie within the range of: 0 - 24.  When the minimum hours have not been worked then the minimum hours of work is still paid to the employee.
|**Unpaid Break**|	This field is used to enter the employee time for unpaid meal breaks. The field is entered as a decimal and will reduce the hours worked for the specified day by the value entered in this field. Alternately the employee can manually enter their meal breaks in the timesheet.
|**Max Hours Per Week**|	This field is used to enter the maximum hours per week generated for this pay item. Use this field with the "Include All Perm. Hours in Maximum". To include transaction types for Leave to make up the Maximum.
|**Include All Perm. Hours in Maximum**|	This field is used to flag the lines that will contribute to the Max Hours Per Week.  Usually you would tick all the Ordinary, Unpaid and Leave Transactions.
|**Applies to Cause of Absence**|	This field is used to set up criteria for Leave and other absence codes.
|**Rounding method**|	This field is used to select the rounding method:
||•	No Rounding
||•	Nearest
||•	Up
||•	Down
||This field works with the rounding precision
|**Apply to Following Day**|	This field is used to apply this Pay Criteria to the next day's week ending date.



