# Award Interpreter

The Award Interpreter Module is used to interpret employee timesheet hours into pay and allowance transactions. 

The Employee Timesheet entries can be manually entered or imported into the Employee Timesheet Worksheet, at the same time the timesheets are simultaneously loaded into the Interpretation Worksheet. After the timesheets are loaded or entered the user can interpret the lines and once satisfied you can submit the lines. After the lines are submitted you can transfer them into the Pay Journal for validation and payment.
 
 
## Setup Award Interpreter

After the Payroll has been setup and your [Award and Classification](au-payroll-setup-award.md) Structure defined in the base payroll you must setup the following items in sequence for the Award Interpreter:

## [Public Holiday Calendars](au-payroll-setup-public-holiday-calendars.md)

•	Base- Australian Wide – the Country Calendar is assigned to the Payroll Setup.
•	State - State Wide – the State Calendar is setup against the Branch Code
•	Branch – Local – the Branch Calendar is setup against the Branch Code

## [Payroll Setup](au-payroll-setup-payroll-controls-payroll-setup.md)

•	Payroll
•	Award
•	Classification
•	Item Criteria Worksheet
•	Assign Award to Employee

## Award Interpretation Process 

Once the Award Interpreter has been setup the following steps must be performed in sequence to interpret timesheets:

1.	Timesheet Entry
2.	Timesheet Interface Exception - only used with Timekeeper
3.	Employee Timesheet Worksheet 
4.	Interpret Timesheets
5.	Interpretation Worksheet
6.	Automatic Interpretation - only used Timekeeper
7.	Pay Timesheet Journal
8.	Pay Journal
 
### Award Interpreter Public Holiday Calendars

You can create and maintain all Public Holiday Calendars for the Award Interpreter within the Dynamics NAV Payroll granule.

### Award Interpreter Payroll Setup

Go to the [Payroll Setup](au-payroll-setup-payroll-controls-payroll-setup.md) card to update the following fields on the **Time Sheet Entry** FastTab: *Departments/Payroll/Setup/Payroll Setup/Payroll Controls/Payroll Setup*
 
#### Payroll Setup – Timesheet Entry FastTab 

|Field|Description|  
|:---------------------------------|:---------------------------------------|  
|**Public Holiday Calendar Code**|This field is used to specify the Country Wide calendar used to determine Public Holidays for this Payroll Company.
|**Auto-Interpret (Timekeeper Only)**| This field is only used for Timekeeper imported Timesheet lines. When this field is ticked the imported timekeeper lines are automatically interpreted.
|**Summarise Interp. by weeks**| When this field is ticked the Interpretation Worksheet lines are summarised into a week. When this field is blank the fields are summarised into a day. You cannot have a mixture of week and day summarisation.

#### Payroll – Options FastTab 
 
Go to the [Payroll](au-payroll-setup-payroll.md) card to update the following fields on the **Options** FastTab:  *Departments/Payroll/Setup/Payroll Setup/General/Payrolls*
 
|Field|Description|  
|:---------------------------------|:---------------------------------------|  
|**Timesheet Week Ending Day**|This field is used to specify the day of the week to use as the week ending date and determines the Payroll Period for payment.

 
 
## Award Interpreter Review Award

This card is used to maintain your Awards for use with the Award Interpreter. 

1. In the **Search** box, enter **Award & Associated Transactions**, and then choose the related link, or go to the following menu: *Departments/Payroll/Setup/Payroll Setup/Award/Award & Associated Transactions*.

To set up an Award please refer to the following link Award 

To maintain an Award for use with the Award Interpreter you must complete the following fields:

### Award

|Field|Description|  
|:---------------------------------|:---------------------------------------| 
|**Position Code**| This field is optional and is used to indicate the Award is only used for a specific Position. The position is attached to a Payroll Employee.
|**Public Holiday Calendar Code**|	This field is optional and is used to assign a calendar to determine Public Holidays for this Award. Alternately the Calendar can be attached to the Employee's Branch and the Employee assigned to the Branch. 
Certification Date.  This field is **Mandatory** and is used to enter the date the Award is Certified for use. If this date is left blank you cannot setup Award Interpretation Criteria Items for this Award as this date is verified when setting up Items.
|**Comment**| This field is optional and is used to indicate a comment is recorded against this Award. To add or maintain comments click the Award Button and then select the Comment menu option.
|**Blocked**|	This field is used to block the Award and any of its Classifications from use.

 
### Award Interpreter Pay Item Criteria List

The fields on this form are for display purposes only. The Pay Item Criteria records that have been setup to interpret the hours into Pay Transaction Types for the Award or the Award Classification are listed.

They are maintained in the Item Criteria Worksheet. 

1. On the **General** FastTab, fill the fields in the following table.

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


    
 
10.13.9	Award Interpreter Allowance Item Criteria List
The fields on this form are for display purposes only. The Allowance Item Criteria records that have been setup to interpret the hours into Pay Transaction Types for the Award or the Award Classification are listed.

They are maintained in the Item Criteria Worksheet. 

 
10.13.9.1	Allowance Item Criteria Card – General FastTab

Field	Comments
Classification Code	This field is displays the Award Classification Code
Award Code	This field displays the Award
Pay Transaction Type	This field displays the Pay Transaction Type code that is generated from this Allowance Item criterion. The pay Transaction type must have an Accumulation Type of Allowance
Pay Tran. type Description	This field displays the Pay Transaction Type description
Starting Date	This field displays the date the criteria becomes effective. This date must be on or after the Certification date of the Award Classification
Sequence No	This field displays the sequence and must be greater then 0. The sequence defines the order that Time and Attendance Allowance Items are applied when the maximum threshold has been reached.
Line No	This field is used internally by the system.
Ending Date	This field displays the date the criteria is no longer used. This date must be after the Starting Date.
Day of the Week	This field indicates the day this criteria is used.
Application Type	This field is used to define when the allowance is generated:
Always - This allowance is always generated
After Hours - This allowance is paid after X (Quantity entered in the next field) amount of hours have been worked. 
After Time - This allowance is paid after a certain time of the day has past.
Before Time - This allowance is paid until a certain time of the day has been reached.
After Hours	This field is used with the Application Type After Hours and must be between 0 - 24. After the quantity of hours entered in this field have been worked this Allowance kicks in. 
After Time	This field is used with the Application type After Time. The times worked are checked and if there are hours after the time entered in this field the allowance is paid.
Note A transaction filter is not used with this criteria as there are no start and end times
Before Time	This field is used with the Application type Before Time. The times worked are checked and if times are entered prior to this time the allowance is paid.
Note A transaction filter is not used with this criteria as there are no start and end times.
Quantity Type	The Quantity Type is multiplied by the payment Quantity for the Pay Transaction Type:
Fixed - The Allowance paid is multiplied by the Quantity entered in the Quantity field.
Per Hour - The Allowance paid is multiplied by the number of hours applicable to these transactions.
Per Day - The Allowance is generated only once each day when applicable..
Applies to All Hours
	Only applicable when Quantity Type = Per Hours and Allowance Type = After Time. it is used to apply the Allowance to all hours in the day.
Leave this field blank to only apply to the after time hours. 
Quantity	This is the quantity used with the Quantity type field. 
This field may be zero for allowances that you wish to manually maintain in the interpreted times.  This is used for allowances where the quantity cannot be generated.
Max. Qty. Per day
	When the Quantity generated on any day is greater than this field then this value is used instead.
Max. Qty. Per tax Week	When the Quantity generated in a week is greater then this field then this value is used instead
Applies to Tran. Type	This field is used to only generate the allowance on the Pay Transaction type (s). 
Exclude Leave	This field is used to prevent the Allowance generating for Leave Pay Transaction types
Rounding Method	This field displays the rounding method:
No Rounding
Nearest
Up
Down
This field works with the rounding precision
Rounding Precision	This field displays the rounding precision for the rounding method:
Minute
5 Minutes
6 Minutes
15 Minutes
30 Minutes
Hour
Deleted	This field indicates the line is no longer used to generate transactions.



 
10.13.10	Award Interpreter - Classification
This card is used to maintain your Classifications for use with the Award Interpreter. 

To open the Award Classification List form, 

Departments/Payroll/Setup/Payroll Setup/Award/Award & Associated Transactions

To set up a Classification please refer to the following link Award - Award Classification List

To maintain Classification for use with the Award Interpreter you must complete the following fields:

In the Award and Associated Transaction form select the Award you wish to work with.
Click the Award button and then select the Classification menu option

Field	Comments
Position Code	This field is optional and is used to indicate the Award Classification is only used for this Position. The position is attached to a Payroll Employee.


To review the Pay and Allowance Criteria specific to this Award Classification

In the Award Classification List select the classification that you wish to review the Pay Items or Allowance Items

Click the Class button and select from the following options
•	Pay Item Criteria
•	Allowance Item Criteria

    
 
10.13.11	Award Interpreter Item Criteria Worksheet
The Item Criteria Worksheet is used to setup and maintain the Pay and Allowance Criteria Items used to interpret the timesheet lines.

To open the Item Criteria Worksheet form, 

Departments/Payroll/Setup/Award Interpreter/ Interp. Setup Worksheet


10.13.11.1	Item Criteria Worksheet Header

 


Field	Comments
Starting Date
	This field is used to enter the start date the criteria becomes effective. This date must be on or after the Award Classification Certification date.
Ending Date	This field is used to enter the date the criteria are no longer used. This date must be after the Starting Date.
Award Code	This field is used to select the Award
Award Description	This field is used to display the description
Classification Code	This field is used to select the Award Classification Code
Classification Description	This field is used to display the description
Position Code	This field is used to specify a Position


Depending on the Criteria Type you wish to setup select from the following tabs:

•	Pay Item Criteria Worksheet Card
•	Allowance Criteria Worksheet Card

10.13.12	Pay Item Criteria Worksheet Card
The Pay Item records are used to interpret the hours into Pay Transaction Types. You setup the criteria for example; Ordinary Time, Overtime, Public Holidays, Leave etc.

 

10.13.12.1	Pay Item Criteria Card – General FastTab

Field	Comments
Starting Date	This field is used to enter the date this criteria becomes effective and is used to interpret timesheets. This date must be equal to or greater than the Classification Certification date
Ending Date	This field is used to enter the date the criteria is no longer effective.
Award	This field is used to apply the criteria to a specific Award. If the Classification is not specified all employees attached to the Award work under the criteria setup for this Award
Award Description	This field is used to display the Description
Classification Code	This field is used to select a specific Classification Code to limit the criteria to only apply to the specified Classification
Classification Description	This field displays the Award Classification Description.
Position Code	When the Award Classification is setup specifically for only 1 position this field displays the position
Criteria Type	This field displays Pay for Pay Item Criteria
Day of the Week	This field is used to select the day of the week the criteria applies.
Sequence No	This field is used to enter the sequence and must be greater then 0. The sequence defines the order that Time and Attendance Pay Items are applied when the maximum threshold has been reached for a Pay Item. 
For example: When Ordinary time reaches the threshold of 38 hours in a week move to sequence 2 to pay overtime.
Pay Transaction Type	This field is used to select the Pay Transaction Type code that generates from this Pay Item criteria.
Pay Tran. type Description	This field displays the above Pay Transaction Type description
Start Time	This field is used to enter the earliest start time and must be between 00:00 - 23:59. When a timesheet is processed with hours that lie within the Start and End times the Pay Item is generated
For example Ordinary time is paid between the hours of 6am and 6pm. If the employee starts work at 5am a different criteria line applies to the hour worked before 6am.
End Time	This field is used to enter the latest end time and must be between 00:00 - 23:59
Max. hours	This field is used to enter the maximum hours worked in a day that is allowed for this Pay item and must lie within the range of: 0 - 24. 
For example once Ordinary time of 7.6 hours has been worked the next sequence used to pay the remaining hours as Overtime.
Min. Hours	This field is used to enter the minimum hours worked allowed for this Pay Item and must lie within the range of: 0 - 24. 
When the minimum hours have not been worked then the minimum hours of work is still paid to the employee.
Unpaid Break	This field is used to enter the employee time for unpaid meal breaks. The field is entered as a decimal and will reduce the hours worked for the specified day by the value entered in this field. Alternately the employee can manually enter their meal breaks in the timesheet.
Max Hours Per Week	This field is used to enter the maximum hours per week generated for this pay item. 
Use this field with the "Include All Perm. Hours in Maximum". To include transaction types for Leave to make up the Maximum.
Include All Perm. Hours in Maximum	This field is used to flag the lines that will contribute to the Max Hours Per Week. 
Usually you would tick all the Ordinary, Unpaid and Leave Transactions.
Applies to Cause of Absence	This field is used to set up criteria for Leave and other absence codes.
Rounding method	This field is used to select the rounding method:
•	No Rounding
•	Nearest
•	Up
•	Down
This field works with the rounding precision
Apply to Following Day	This field is used to apply this Pay Criteria to the next day's week ending date.


 
10.13.13	Allowance Criteria Worksheet Card 
The Allowance Item records are used to interpret the hours into Allowance Pay Transaction Types.

 

10.13.13.1	Allowance Item Criteria Card – General FastTab

Field	Comments
Starting Date	This field is used to enter the date this criteria becomes effective and is used to interpret timesheets. This date must be equal to or greater than the Classification Certification date
Ending Date	This field is used to enter the date the criteria is no longer effective.
Award Code	This field is used to apply the criteria to a specific Award. If the Classification is not specified all employees attached to the Award work under the criteria setup for this Award
Award Description	This field is used to display the Description
Classification Code	This field is used to select the Award Classification Code
Classification Description	This field displays the Award Classification Description
Position Code	When the Award Classification is specified for 1 position this field displays the position
Criteria Type	This field displays Allowance for Allowance Item Criteria
Day of the Week	This field is used to select the day of the week the criteria applies.
Sequence No	This field is used to enter the sequence and must be greater then 0. The sequence defines the order that Time and Attendance Allowance Items are applied when the threshold has been reached.
Pay Transaction Type	This field is used to enter the Pay Transaction Type code to generate from this Allowance Item criteria. The Pay Transaction Type must have an accumulation type of Allowance
Pay Tran. type Description	This field displays the Pay Transaction Type description
Application Type	This field is used to define when the allowance is generated:
•	Always Applied - This allowance is always generated
•	After Hours - This allowance is paid when the timesheet exceeds the entered hour(s)
•	After Time - This allowance is paid when the timesheet exceeds the time
•	Before Time - This allowance is paid when the time on the timesheet are before the time.
Before Time	This field must be between 0 - 24. Applies to time worked before the time entered in this field
After Time	This field must be between 0 - 24. Applies to time worked after the time entered in this field
After Hours	This field must be between 0 - 24. Applies to time worked after working the number of hours entered in this field
Quantity Type	The Quantity Type is multiplied by the Payment Quantity for the Pay Transaction Type:
•	Fixed - Once per timesheet
•	Per Hour - Once per applicable hours
•	Per Day - Once per applicable day.
Quantity	The quantity for this allowance. This field equal 0 for allowances that are manually entered in the Timesheet. When a timesheet with 0 in the Quantity is interpreted the allowance will display with 0 quantity
Max. Quantity Per Day	When the allowance Quantity generated is greater then the amount entered in this field then the Max. Qty. Per Day is used instead of the Quantity
Applies to All Hours	Only applicable when Quantity Type = Per Hours and Allowance Type = After Time to apply the Allowance to all hours in the day.
Leave this field blank to only apply to the after time hours. 
Exclude Leave	This field is selected to prevent the Allowance generating for Leave Pay Transaction types
Applies to Tran. Type	This field is used to only generate this allowance on this Pay Transaction type and is only used when the Quantity Type is Per Hour and the Application Type is Always or After Hours
Rounding Method	This field is used to enter the rounding method:
•	No Rounding
•	Nearest
•	Up
•	Down
This field works with the rounding precision
Rounding Precision	This field is used to select the rounding precision for the above rounding method:
•	Minute
•	5 Minutes
•	6 Minutes
•	15 Minutes
•	30 Minutes
•	Hour
10.13.14	Award Interpreter Employee Timesheets Worksheet
The Employee Timesheet Worksheet is used to enter the employee times into the Award Interpreter when you are not using Timekeeper.

To open the Employee Timesheets Worksheet form, 

Departments/Payroll/Award Interpretation Processing

 

10.13.14.1	Employee Timesheets Worksheet 

Field	Comments
Employee No Filter
	This field is used to select or enter the Payroll Employee code that you wish to enter Timesheet lines against
View By	This field allows you to select how you wish to view the times within the Employee Timesheets Worksheet.

The options available are “Day” or “Weekly”.
Total Hours	This field displays the total number of hours entered for the employee within the specified date range
Employee no.	This field displays the employee number entered in the Employee No Filter by default. 
You may enter a different Employee No. and rename the record if you wish to enter a line for someone else without changing the Employee Filter. . The different employee will not display in the grid unless you change the Employee No. filter to include the employee.
Job No.	This field is used to assign the hours worked to a specific Job. 
Classification Code	This field is used to change the employees default classification rate for the hours worked. You might change this field to pay the employee at a higher rate of pay for the hours entered on this line.
Work Date	This field is used to enter the date the hours were performed and determines if the date is a public holiday according to the employees Public Holiday calendar.
Day Worked	This date will automatically populate with the correct day of the week for the work date. This day is used by the Interpreter.
Week Ending Date	This field is defined in the Payroll > Options Card > Week Ending Day field. You can select any day of the week from Monday to Sunday for timesheet entry. It is used to determine which Payroll Period the times are paid from in the pay Journal 
Start Time	This field is used to enter the time the employee started work and is used by the Interpreter to assign the correct Pay Transactions to the hours worked between the Start and Finish Time. It is also used to generate any Allowances.
End Time	This field is used to enter the time the employee stopped work and is used by the Interpreter to assign the correct Pay Transactions to the hours worked between the Start and Finish Time. It is also used to generate any Allowances.
Quantity	This field is for display only. It will show the difference between the start and end time.
Meal Break Start Time	This field is used to enter the start time the unpaid meal breaks began for the line. You must also enter a Meal break End time. The interpreter will minus the difference off the hours paid for this line.
Meal Break End Time	This field is used to enter the End time the unpaid meal break stopped for the line. You must also enter a Meal break Start time. The interpreter will minus the difference off the hours paid for this line.
Meal Break Quantity 	This field is used to enter a total of time the employee took for unpaid meal breaks for the line. The interpreter will minus this time off the hours paid for this line.
Shift Code	This field is used to enter the shift these hours were worked. The shift can be setup as an associated transaction for an Award and a shift allowance attached if required. The allowance will be generated in the Pay Journal.
Cause of Absence Code	This field is used to capture hours taken off work for a list of reasons. The code is used to generate a Pay Transaction Type for leave as opposed to Ordinary. The hours can be counted towards the ordinary hours (38) worked in a week. 
Work Type Code	This field is used in the Jobs Module to cost the values
Unit of Measure Code	This field is used in the Job Module
Description 	This field is used to display the employee’s name. 
Time Sheet Ref.No	This field is used to capture the Timesheet Ref. No.
Branch Code	This field is used to override the employees default branch
Division Code	This field is used to override the employees default division
Global Dimension 1	This field is used to override the employees default Dimension Value
Global Dimension 2	This field is used to override the employees default Dimension Value
Shortcut Dimension 3-8	This field is used to override the employees default Dimension Value
Source Code	A source code indicates where an entry was created and is used internally by the system.


 
10.13.15	Award Interpreter Interpretation Worksheet
In the top section of this form the Un-Interpreted timesheet lines are displayed for the Employee and Date filter criteria.  The Un-Interpreted lines are copied directly from the Employee Timesheets Worksheet. 

 

10.13.15.1	Interpretation Worksheet Top Section

Field	Comments
Employee no.	This field displays the employee number entered in the Employee No Filter by default. 
You may enter a different Employee No. and rename the record if you wish to enter a line for someone else without changing the Employee Filter. The different employee will not display in the grid unless you change the Employee No. filter to include the employee.
Job No.	This field is used to assign the hours worked to a specific Job. 
Modified Since Interpretation 	This field will be ticked when this line has previously been interpreted and then this line edited. You should interpret the lines again.
Classification Code	This field is used to change the employees default classification rate for the hours worked. You might change this field to pay the employee at a higher rate of pay for the hours entered on this line.
Work Date	This field is used to enter the date the hours were performed and determines if the date is a public holiday according to the employees Public Holiday calendar.
Day Worked	This date will automatically populate with the correct day of the week for the work date. This day is used by the Interpreter.
Week Ending Date	This field is defined in the Payroll > Options Card > Week Ending Day field. You can select any day of the week from Monday to Sunday for timesheet entry. It is used to determine which Payroll Period the times are paid from in the pay Journal 
Start Time	This field is used to enter the time the employee started work and is used by the Interpreter to assign the correct Pay Transactions to the hours worked between the Start and Finish Time. It is also used to generate any Allowances.
End Time	This field is used to enter the time the employee stopped work and is used by the Interpreter to assign the correct Pay Transactions to the hours worked between the Start and Finish Time. It is also used to generate any Allowances.
Quantity	This field is for display only. It will show the difference between the start and end time.
Meal Break Quantity	This field is used to enter a total of time the employee took for unpaid meal breaks for the line. The interpreter will minus this time off the hours paid for this line.
Meal Break Start Time	This field is used to enter the start time the unpaid meal breaks began for the line. You must also enter a Meal break End time. The interpreter will minus the difference off the hours paid for this line.
Meal Break End Time	This field is used to enter the End time the unpaid meal break stopped for the line. You must also enter a Meal break Start time. The interpreter will minus the difference off the hours paid for this line.
Shift Code	This field is used to enter the shift these hours were worked. The shift can be setup as an associated transaction for an Award and a shift allowance attached if required. The allowance will be generated in the Pay Journal.
Cause of Absence Code	This field is used to capture hours taken off work for a list of reasons. The code is used to generate a Pay Transaction Type for leave as opposed to Ordinary. The hours can be counted towards the ordinary hours (38) worked in a week. 
Work Type Code	This field is used in the Jobs Module to cost the values
Unit of Measure Code	This field is used in the Job Module
Description 	This field is used to display the employee’s name. 
Branch Code	This field is used to override the employees default branch
Division Code	This field is used to override the employees default division
Global Dimension 1	This field is used to override the employees default Dimension Value
Global Dimension 2	This field is used to override the employees default Dimension Value
Shortcut Dimension 3-8	This field is used to override the employees default Dimension Value
Source Code	A source code indicates where an entry was created and is used internally by the system.


In the bottom section of this form the Interpreted Times for the employee within the date filter are displayed and correspond to the top section entries. The lines are summarised in days unless flagged to summarise in weeks in the Payroll Setup Timesheet tab.
 
10.13.15.2	Interpretation Worksheet - Bottom Section

 

Field	Comments
Employee no.	This field displays the employee number entered in the Employee No Filter. 
Job No.	This field is used to display the Job No. the hours worked will post against. 
Job Task No	This field is used to display the Job Task No. the hours worked will post against.
Classification Code	This field is used to display the classification the employee will be paid under for the hours worked for this line.
Pay Transaction Type Code	This field displayed the Pay Transaction Type (PTT) the Interpreter has generated.
Description	This field displays the PTT description
Work Date	This field is only populated when the Interpreted lines are summarised by day. It is used to display the date the work for this line was performed.
Week Ending Date	This field is defined in the Payroll > Options Card > Week Ending Day field.  It is used to determine which Payroll Period the times are paid from in the pay Journal 
Work Type Code	This field is used in the Jobs Module to cost the values
Shift Code	This field is used to display the shift these hours were worked. The shift can be setup as an associated transaction for an Award and a shift allowance attached if required. The allowance will be generated in the Pay Journal.
Cause of Absence Code	This field is used to capture hours taken off work for a list of reasons. The code is used to generate a Pay Transaction Type for leave as opposed to Ordinary. The hours can be counted towards the ordinary hours (38) worked in a week. 
Branch Code	This field is used to display the branch assigned to this line.
Division Code	This field is used to display the division assigned to this line.
Global Dimension 1	This field is used to display the Dimension Value
Global Dimension 2	This field is used to display the Dimension Value
Units	This field displays the total value of units generated for this line by the AI.
Pay Rate	This field displays the rate the units will be paid.
Pay Amount	This field displays the Value of the sum (Units x Pay rate)
Charge Units	This field displays the total value of units generated for this line by the AI
Charge Rate	This field displays the rate the units will be charged
Charge Amount	This field displays the Value of the sum (Units x Charge rate)
Sunday - Saturday Units	This field summarises the units for each line by the day of the week
Charge Monday - Sunday Units	This field summarises the units for each line by the day of the week
Monday - Sunday Public Holiday	This field indicates if the day of the week was a Public holiday.


The Interpret Button is used to interpret the Un-Interpreted Timesheet Line displayed in the top section of the form. Once Interpreted the lines will also display in the bottom section.

The Print Button is used to run the Interpreted Times Report.

The Submit Button is used to pass the Interpreted Lines in the bottom section to the Pay Timesheet Journal. You can open the Pay Time Sheet Journal if you wish and edit the lines. Alternately you can open the Pay Journal and Transfer the lines into the corresponding Pay Period.

10.13.16	Award Interpreter Interpret button
The Interpret Button is used to interpret the Un-Interpreted Timesheet Lines displayed in the top section of the form. Once Interpreted the lines will also display in the bottom section.

Interpret function:

1.	All Interpreted Lines that have not been submitted are deleted for the selected employee within the date filter criteria.
 
2.	The lines to be Interpreted are summarise by day or week depending on the option selected in the Payroll Setup Timesheet Tab. 
 
3.	The times entered are verified that not more than 24 hours in 1 day have been entered. If more than 24 hours in 1 day have been entered the timesheet is not interpreted.
 
4.	The Interpreter reads the lines and processes the lines one at a time:
 
5.	The Classification is retrieved from the Payroll Employee. When no classification exists the times are not interpreted. 
 
6.	When a classification exists the program processes in sequence each pay item criteria that applies to the Award or the Classification. 
 
Public Holiday Calendar: The time is checked against the public holiday calendars in the following sequence:

1.	Employees Default Branch
2.	The Award
3.	The Employee's Payroll State
4.	Employee's Payroll Country
5.	Payroll Setup Public Holiday Calendar Code 
 
Day Type: The time entry is checked to see how much of the time falls between the start time and the end time of the criteria. The portion of time that lies within the start and end time is interpreted. If none does then the whole line is passed on to the next criteria in sequence. When the hours are interpreted the hours remaining that lie outside the start and end time is un-interpreted for the next item in sequence. 
 
Min Hours: Mon - Sun and Public Holidays are checked and when the hours are less than the Minimum Hours the hours are increased to the Minimum Hours. 
 
Max Hours: Mon - Sun and Public Holidays are checked and when the hours are more than the Maximum Hours the hours in excess of the maximum are passed to the next Item criteria sequence.
 
Apply to the following Day flag: The week ending date is based on the day after the time worked when the start/end time goes past midnight. It checks items whose start stop times go to the next day e.g. night shift. When a portion of the hours that fall in the same day that time period will be interpreted. The remaining time outside the time period will be passed onto the next criteria.
 
Rounding: Rounding of Up Down or nearest is performed to the Precision defined in the Rounding Precision field of the Item Criteria.
 
Allowance Item Criteria: After all the Pay Items are interpreted the Allowance items are processed.
 
Application Type
•	Always Applied: The hours are not checked and when the employee has worked the Pay Transaction Type defined in the filter the Allowance is Paid
•	After Hours: The number of hours worked for the Pay Transaction Type (excludes Min Hours Increase) is checked and if the hours meet the criteria the Allowance is Paid
•	After Time: When the time worked is after the After Time the Allowance is paid.
•	Before Time: When the time worked is before the Before Time the Allowance is paid.
•	Quantity
•	Fixed: When the criteria is met the allowance is applied once per week 
•	Per Hour: When the criteria is met the allowance is applied once per hour worked
•	Per Day: When the criteria are met the allowance is applied once per day worked.
 
Exclude Leave: The allowance is not applied for Public Holidays and Pay Transaction Types with the Apply to Leave Taken flag = true
 
Applies to All Hours: When ticked and the Quantity Type = Hours all the hours for the day are used to calculate the Allowance Quantity when the Allowance criteria are met.
 
Maximum Allowance Quantity per tax Week: When the weeks calculated quantity for the allowance is greater than the Maximum Quantity the Maximum Quantity is used instead.
 
Applies to Pay Transaction Type Filter: The allowance is only calculated on the Pay Transaction in this filter. When the filter is blank the allowance is calculated on un-interpreted times.
 
Rounding: Rounding of Up Down or Nearest is performed to the Precision defined in the Rounding Precision field of the Item Criteria. 
10.13.17	Award Interpreter Submit button
This option transfers interpreted lines to the Posted Interpreted Times table. The lines are transferred as adjustments if an existing posted interpreted time exists. The new / adjustments lines populate the Pay Time Sheet Journal as locked lines where they can be edited if required. 

You can also Transfer the Interpreted Lines directly into the Pay Journal.

