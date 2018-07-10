# Award Interpreter Setup

This section discussed the following setup;

* [Public Holiday Calendars](#award-interpreter-public-holiday-calendars)
* [Payroll Setup](#award-interpreter-payroll-setup)
* [Payrolls Setup](#payroll-options-fasttab)
* [Award](#award-interpreter-award)
* [Classification](#award-interpreter-classification)
* [Pay Item Criteria](au-payroll-setup-award-interpreter-pay-item-criteria.md)
* [Allowance Item Criteria](au-payroll-setup-award-interpreter-allowance-item-criteria.md)


## Award Interpreter Public Holiday Calendars

You can create and maintain all [Public Holiday Calendars](au-payroll-setup-public-holiday-calendar.md) for the Award Interpreter within the Dynamics NAV Payroll granule.

### Award Interpreter Payroll Setup

Go to the [Payroll Setup](au-payroll-setup-payroll-controls-payroll-setup.md) card to update the following fields on the **Time Sheet Entry** FastTab: *Departments/Payroll/Setup/Payroll Setup/Payroll Controls/Payroll Setup*
 
#### Payroll Setup Timesheet Entry FastTab 

|Field|Description|  
|:---------------------------------|:---------------------------------------|  
|**Public Holiday Calendar Code**|This field is used to specify the Country Wide calendar used to determine Public Holidays for this Payroll Company.
|**Auto-Interpret (Timekeeper Only)**| This field is only used for Timekeeper imported Timesheet lines. When this field is ticked the imported timekeeper lines are automatically interpreted.
|**Summarise Interp. by weeks**| When this field is ticked the Interpretation Worksheet lines are summarised into a week. When this field is blank the fields are summarised into a day. You cannot have a mixture of week and day summarisation.

#### Payroll Options FastTab 
 
Go to the [Payroll](au-payroll-setup-payroll.md) card to update the following fields on the **Options** FastTab:  *Departments/Payroll/Setup/Payroll Setup/General/Payrolls*
 
|Field|Description|  
|:---------------------------------|:---------------------------------------|  
|**Timesheet Week Ending Day**|This field is used to specify the day of the week to use as the week ending date and determines the Payroll Period for payment.

  
## Award Interpreter Award

This card is used to maintain your Awards for use with the Award Interpreter. 

1. In the **Search** box, enter **Award & Associated Transactions**, and then choose the related link, or go to the following menu: *Departments/Payroll/Setup/Payroll Setup/Award/Award & Associated Transactions*.

To set up an Award please refer to the following link Award 

To maintain an Award for use with the Award Interpreter you must complete the following fields:

|Field|Description|  
|:---------------------------------|:---------------------------------------| 
|**Position Code**| This field is optional and is used to indicate the Award is only used for a specific Position. The position is attached to a Payroll Employee.
|**Public Holiday Calendar Code**|	This field is optional and is used to assign a calendar to determine Public Holidays for this Award. Alternately the Calendar can be attached to the Employee's Branch and the Employee assigned to the Branch. 
|**Certification Date**| This field is **Mandatory** and is used to enter the date the Award is Certified for use. If this date is left blank you cannot setup Award Interpretation Criteria Items for this Award as this date is verified when setting up Items.
|**Comment**| This field is optional and is used to indicate a comment is recorded against this Award. To add or maintain comments click the Award Button and then select the Comment menu option.
|**Blocked**|	This field is used to block the Award and any of its Classifications from use.


## Award Interpreter Classification

This card is used to maintain your Classifications for use with the Award Interpreter. 

1. To open the Award Classification List form, *Departments/Payroll/Setup/Payroll Setup/Award/Award & Associated Transactions*

2. To set up a Classification please refer to the following link Award - Award Classification List

3. To maintain Classification for use with the Award Interpreter you must complete the following fields:

4. In the Award and Associated Transaction form select the Award you wish to work with.

5. Click the **Award** button and then select the **Classification** icon

6. Fill the following fields

|Field|Description|  
|:---------------------------------|:---------------------------------------| 
|**Position Code**| This field is optional and is used to indicate the Award Classification is only used for this Position. The position is attached to a Payroll Employee.

To review the Pay and Allowance Criteria specific to this Award Classification, in the Award Classification List, select the classification that you wish to review the Pay Items or Allowance Items.

Select the **Class** icon, and select from the following options;

•	[Pay Item Criteria](au-payroll-setup-award-interpreter-pay-item-criteria.md)

•	[Allowance Item Criteria](au-payroll-setup-award-interpreter-allowance-item-criteria.md)

    
 



 

