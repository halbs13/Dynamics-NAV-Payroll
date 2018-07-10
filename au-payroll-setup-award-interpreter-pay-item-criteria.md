# Award Interpreter Pay Item Criteria 

When reviewing the Pay Item Criteria, there are 2 methods of viewing this information;

1. Pay Item Criteria List

2. Pay Item Criteria Worksheet

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
