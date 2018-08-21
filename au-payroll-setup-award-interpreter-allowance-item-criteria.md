# Award Interpreter Allowance Item Criteria List

When reviewing the Pay Item Criteria, there are 2 methods of viewing this information;

1. [Allowance Item Criteria List](#allowance-item-criteria-list)

2. [Allowance Item Criteria Worksheet](#allowance-item-criteria-worksheet)

## Allowance Item Criteria List

The fields on this form are for display purposes only. The Allowance Item Criteria records that have been setup to interpret the hours into Pay Transaction Types for the Award or the Award Classification are listed.

They are maintained in the Item Criteria Worksheet. 

1. Fill the fields in the following table.

|Field|Description|  
|:---------------------------------|:---------------------------------------|  
|**Classification Code**| This field is displays the Award Classification Code.
|**Award Code**| This field displays the Award.
|**Pay Transaction Type**| This field displays the Pay Transaction Type code that is generated from this Allowance Item criterion. The pay Transaction type must have an Accumulation Type of Allowance.
|**Pay Tran. type Description**| This field displays the Pay Transaction Type description.
|**Starting Date**| This field displays the date the criteria becomes effective. This date must be on or after the Certification date of the Award Classification.
|**Sequence No**| This field displays the sequence and must be greater then 0. The sequence defines the order that Time and Attendance Allowance Items are applied when the maximum threshold has been reached.
|**Line No**| This field is used internally by the system.||Per Day - The Allowance is generated only once each day when applicable.
|**Ending Date**| This field displays the date the criteria is no longer used. This date must be after the Starting Date.
|**Day of the Week**| This field indicates the day this criteria is used.
|**Application Type**| This field is used to define when the allowance is generated:
||Always - This allowance is always generated.
||After Hours - This allowance is paid after X (Quantity entered in the next field) amount of hours have been worked. 
||After Time - This allowance is paid after a certain time of the day has past.
||Before Time - This allowance is paid until a certain time of the day has been reached.
|**After Hours**| This field is used with the Application Type After Hours and must be between 0 - 24. After the quantity of hours entered in this field have been worked this Allowance kicks in. 
|**After Time**| This field is used with the Application type After Time. The times worked are checked and if there are hours after the time entered in this field the allowance is paid. **Note**: A transaction filter is not used with this criteria as there are no start and end times.
|**Before Time**| This field is used with the Application type Before Time. The times worked are checked and if times are entered prior to this time the allowance is paid.  **Note**: A transaction filter is not used with this criteria as there are no start and end times.
|**Quantity Type**| The Quantity Type is multiplied by the payment Quantity for the Pay Transaction Type:
||Fixed - The Allowance paid is multiplied by the Quantity entered in the Quantity field.
||Per Hour - The Allowance paid is multiplied by the number of hours applicable to these transactions.
||Per Day - The Allowance is generated only. 
|**Applies to Tran. Type**| This field is used to only generate the allowance on the Pay Transaction type (s). 
|**Exclude Leave**| This field is used to prevent the Allowance generating for Leave Pay Transaction types.
|**Rounding Method**| This field displays the rounding method:
||No Rounding
||Nearest
||Up
||Down
||This field works with the rounding precision.
|**Rounding Precision**|This field displays the rounding precision for the rounding method:
||Minute
||5 Minutes
||6 Minutes
||15 Minutes
||30 Minutes
||Hour
|**Deleted**| This field indicates the line is no longer used to generate transactions.

[GoToTop](#award-interpreter-allowance-item-criteria-list)

## Allowance Item Criteria Worksheet

The Allowance Item records are used to interpret the hours into Allowance Pay Transaction Types.

1. To open the Item Criteria Worksheet form, *Departments/Payroll/Setup/Award Interpreter/ Interp. Setup Worksheet*

2. Fill the fields in the following table

|Field|Description|  
|:---------------------------------|:---------------------------------------| 
|**Starting Date**|	This field is used to enter the date this criteria becomes effective and is used to interpret timesheets. This date must be equal to or greater than the Classification Certification date.
|**Ending Date**|	This field is used to enter the date the criteria is no longer effective.
|**Award Code**|	This field is used to apply the criteria to a specific Award. If the Classification is not specified all employees attached to the Award work under the criteria setup for this Award.
|**Award Description**|	This field is used to display the Description.
|**Classification Code**|	This field is used to select the Award Classification Code.
|**Classification Description**|	This field displays the Award Classification Description.
|**Position Code**|	When the Award Classification is specified for 1 position this field displays the position.
|**Criteria Type**|	This field displays Allowance for Allowance Item Criteria.
|**Day of the Week**|	This field is used to select the day of the week the criteria applies.
|**Sequence No**|	This field is used to enter the sequence and must be greater then 0. The sequence defines the order that Time and Attendance Allowance Items are applied when the threshold has been reached.
|**Pay Transaction Type**|	This field is used to enter the Pay Transaction Type code to generate from this Allowance Item criteria. The Pay Transaction Type must have an accumulation type of Allowance.
|**Pay Tran. type Description**|	This field displays the Pay Transaction Type description.
|**Application Type**|	This field is used to define when the allowance is generated:
||•	Always Applied - This allowance is always generated.
||•	After Hours - This allowance is paid when the timesheet exceeds the entered hour(s).
||•	After Time - This allowance is paid when the timesheet exceeds the time.
||•	Before Time - This allowance is paid when the time on the timesheet are before the time.
|**Before Time**|	This field must be between 0 - 24. Applies to time worked before the time entered in this field.
|**After Time**|	This field must be between 0 - 24. Applies to time worked after the time entered in this field.
|**After Hours**|	This field must be between 0 - 24. Applies to time worked after working the number of hours entered in this fiel.d
|**Quantity Type**|	The Quantity Type is multiplied by the Payment Quantity for the Pay Transaction Type:
||•	Fixed - Once per timesheet.
||•	Per Hour - Once per applicable hours.
||•	Per Day - Once per applicable day.
|**Applies to Tran. Type**|	This field is used to only generate this allowance on this Pay Transaction type and is only used when the Quantity Type is Per Hour and the Application Type is Always or After Hours.
|**Rounding Method**|	This field is used to enter the rounding method:
||•	No Rounding
||•	Nearest
||•	Up
||•	Down
||This field works with the rounding precision.
|**Rounding Precision**|	This field is used to select the rounding precision for the above rounding method:
||•	Minute
||•	5 Minutes
||•	6 Minutes
||•	15 Minutes
||•	30 Minutes
||•	 Hour

[GoToTop](#award-interpreter-allowance-item-criteria-list)
