# To setup Leave Accruals

There are 2 methods in which to setup Leave accruals;

* Accrued in Days
* Accrued in Hours

Leave Accruals cannot be set up for Time in Lieu Leave Types.  

1.  To access the Leave Accruals setup, go to the following menu: *Leave Setup/Leave/Accruals*

2.  To create a new record, click on the **New** button.

3.  On the **General** FastTab, fill the fields as described in the following table.

|Field|Description|  
| :--- | :--- |  
|**Leave Type**|This field is used to select the Leave Type you wish to assign to the Accrual.|
|**Code**|This field identifies the Accrual within this Leave Type. Enter a unique code for the Type.|
|**Description**|Enter a description to identify the Leave Type.|
|**Value Conversion Factor**|The factor ordinary earnings are multiplied by to obtain the current Leave value.|
|**Percentage Method Factor**|The percentage of the entitlement that accrues for the employee.  Set to 1 unless the Calculation Method is Percentage.|
|**Over Award Applicable**|This field indicates when an Over Award rate is allowed for this accrual. Over Award is calculated by the sum of the Standard Rate plus Over Award Rate.  If the Over Award field is blank the Over Award is ignored.|
|**Max Days**|This field is the maximum number of days that is accrued for this Leave Accrual at any one time.  If this field is set to 20 days then the employee entitlement will never exceed 20 days.
|**Use a Flat Accrual Calculation**|If this field is ticked then the employee’s leave accrual is averaged over the Leave Accrual period (Usually 12 months) to give a standard accrual amount for each pay period.   If the field is not ticked then the leave accrual will be apportioned on the number of days in the current month.  This field is only used for Pro Rata Calculation method.|
|**Leave Type Based in Hours**|This field is used to identify this leave accrual is based in hours.  This field defaults from the Leave Type. If the Leave Type is based in hours you must use Pro Rata Days Worked as the Calculation Method.|
|**Max Hours**|If leave is accrued in hours, this field is the maximum number of hours that is accrued for this Leave Accrual at any one  time.  If this field is set to 160 hours (based on a 40 hours) then the employee entitlement will never exceed 160 hours.|

4.  On the **Leave Accrual Subform** FastTab, fill the fields as described in the following table.

|Field|Description|  
| :--- | :--- |
|**Award Period No.**|The “Award Period No.” is automatically incremented by the system when a new line is entered.|
|**Calculation Method**|Select the “Calculation Method for this period.|
|**No. Days Entitlement**|This field indicates the number of days / hours entitlement in a Leave period.|
|**No. Months**|This field indicates the length of the Leave period in months.|
|**Return To Period**|Used to loop back to a previous period.  Enter the “Award Period number that you wish to loop back to.|
  
5.  On the **Long Service Leave** FastTab, fill the fields as described in the following table.

|Field|Description|  
| :--- | :--- | 
|**L.S.L Threshold (Years)**|The Number of years before Long Service Leave is accrued as a liability in the General Ledger.|
|**Action Prior To Threshold**|This field determines how the L.S.L accrual is handled during the L.S.L. threshold. The options available are: Accrue Only or Accrue & Post and can be selected from the **ArrowDown**.|

6.  On the **Posting** FastTab, fill the fields as described in the following table.

|Field|Description|  
| :--- | :--- | 
|**No G/L Posting**|Leave this field blank if you wish to post leave accruals to the General Ledger. Tick this field if you don’t wish  to post accruals to the General Ledger.|
|**Accrual Cost Tran. Posting Group**|The Calculate & Post Leave Provision process uses this field to Debit the Leave Expense account in the General Ledger. This group must be a P&L account.|
|**Provision Tran. Posting Group**|The Calculate & Post Leave Provision process uses this field to Credit the Leave Provision account in the General Ledger. This group must be a Balance Sheet account.|
|**Taken Cost Adj. Tran. Posting Group**|This field is not used when the "Post Leave Accruals Only" flag is ticked in the Payroll Setup - Options tab. The Calculate & Post Leave Provision process uses this field to Credit this Posting Group with the value of the Leave Taken.  2. When the Leave Taken Pay Transaction Type Posting group is the Leave Provision Group this field must be the same Provision Posting Group to have a nil net effect on the Provision.  3. When the Leave Taken Pay Transaction Type Posting Group is a P&L Expense account. This group must be a P&L Expense account. The Pay Transaction Type must be a different Group to the group entered here to avoid a nil expense in the General Ledger.|

7.  On the **Reporting** FastTab, fill the fields as described in the following table.

|Field|Description|  
| :--- | :--- |
|**Max Salary**|This field is used to set the maximum Salary Amount an employee is paid Leave Loading.|
|**Loading Percentage**|This field is for reporting purposes.|

8.  On the **On-Costs** FastTab, fill the fields as described in the following table.

|Field|Description|  
| :--- | :--- |  
|**Superannuation On-Costs**|Tick to apply “Superannuation On-Cost” to this leave accrual.|
|**Work Cover On-Costs**|Tick to apply “Work Cover On-Costs” to this leave accrual.|
|**Additional On-Cost %**|Enter a % to apply “Additional On-Costs” to this leave type.|

9.  Click on the **OK** button to close this window.
  
   
## Leave Accrual Card (Leave Accrued in Hours)

1.  Double click the record, to edit/update the existing record.

2.  On the **General** FastTab, fill the fields as described in the following table.
 
|Field|Description|  
| :--- | :--- | 
|**Leave Type**|This field is used to select the Leave Type you wish to assign to the Accrual.|
|**Code**|This field identifies the Accrual within this Leave Type. Enter a unique code for the Type.|
|**Description**|Enter a description to identify the Leave Type.|
|**Value Conversion Factor**|The factor ordinary earnings are multiplied by to obtain the current Leave value.|
|**Percentage Method Factor**|The percentage of the entitlement that accrues for the employee.  Set to 1 unless the Calculation Method is Percentage.|
|**Over Award Applicable**|This field indicates when an Over Award rate is allowed for this accrual. Over Award is calculated by the sum of the Standard Rate plus Over Award Rate.  If the Over Award field is blank the Over Award is ignored.|
|**Max Days**|This field is the maximum number of days that is accrued for this Leave Accrual at any one time.  If this field is set to 20 days then the employee entitlement will never exceed 20 days.|
|**Use a Flat Accrual Calculation**|If this field is ticked then the employee’s leave accrual is averaged over the Leave Accrual period (Usually 12 months) to give a standard accrual amount for each pay period.   If the field is not ticked then the leave accrual will be apportioned on the number of days in the current month.  This field is only used for Pro Rata Calculation method.
|**Leave Type Based in Hours**|This field is used to identify this leave accrual is based in hours.  This field defaults from the Leave Type. If the Leave Type is based in hours you must use Pro Rata Days Worked as the Calculation Method.|
|**Max Hours**|  If leave is accrued in hours, this field is the maximum number of hours that is accrued for this Leave Accrual at any one time.  If this field is set to 160 hours (based on a 40 hours) then the employee entitlement will never exceed 160 hours.|
|**Use Emp Std Hrs For Day Value**|If ticked both the hour and day balances are displayed on the Employee Leave Accrual card. The value of a day is determined by the “Hours in Full Week” and “Days per Week” fields on the Payroll Employee card.  If blank only the hours balance will display on the Employee Leave Accrual card (Only used for Accruals in Hours).|
  
3.  On the **Leave Accrual Subform** FastTab, fill the fields as described in the following table.

|Field|Description|  
| :--- | :--- | 
|**Award Period No.**|The “Award Period No.” is automatically incremented by the system when a new line is entered.|
|**Calculation Method**|Select the “Calculation Method for this period.|
|**No. Days Entitlement**|This field indicates the number of days / hours entitlement in a Leave period.|
|**Hours Basis (Weekly)**|This field is used to identify the number of hours the accrual is based on.  E.g. 160 hours entitlement with an hour basis of 40 grants 20 days leave to an employee on a 40 hour week.|
|**No. Months**|This field indicates the length of the Leave period in months.|
|**Return To Period**|Used to loop back to a previous period.  Enter the “Award Period number that you wish to loop back to.|

4.  On the **Long Service Leave** FastTab, fill the fields as described in the following table.

|Field|Description|  
| :--- | :--- |
|**L.S.L Threshold (Years)**|The Number of years before Long Service Leave is accrued as a liability in the General Ledger.|
|**Action Prior To Threshold**|This field determines how the L.S.L accrual is handled during the L.S.L. threshold. The options available are: Accrue Only or Accrue & Post and can be selected from the **ArrowDown**.|

5.  On the **Posting** FastTab, fill the fields as described in the following table.

|Field|Description|  
| :--- | :--- |
|**No G/L Posting**|Leave this field blank if you wish to post leave accruals to the General Ledger. Tick this field if you don’t wish  to post accruals to the General Ledger.|
|**Accrual Cost Tran. Posting Group**|The Calculate & Post Leave Provision process uses this field to Debit the Leave Expense account in the General Ledger. This group must be a P&L account.|
|**Provision Tran. Posting Group**|The Calculate & Post Leave Provision process uses this field to Credit the Leave Provision account in the General Ledger. This group must be a Balance Sheet account.|
|**Taken Cost Adj. Tran. Posting Group**|This field is not used when the "Post Leave Accruals Only" flag is ticked in the Payroll Setup - Options tab. The Calculate & Post Leave Provision process uses this field to Credit this Posting Group with the value of the Leave Taken.  2. When the Leave Taken Pay Transaction Type Posting group is the Leave Provision Group this field must be the same Provision Posting Group to have a nil net effect on the Provision.  3. When the Leave Taken Pay Transaction Type Posting Group is a P&L Expense account. This group must be a P&L Expense account. The Pay Transaction Type must be a different Group to the group entered here to avoid a nil expense in the General Ledger.|

6.  On the **Reporting** FastTab, fill the fields as described in the following table.

|Field|Description|  
| :--- | :--- | 
|**Max Salary**|This field is used to set the maximum Salary Amount an employee is paid Leave Loading.|
|**Loading Percentage**|This field is for reporting purposes.|

7.  On the **On-Costs** FastTab, fill the fields as described in the following table.

|Field|Description|  
| :--- | :--- |
|**Superannuation On-Costs**|Tick to apply “Superannuation On-Cost” to this leave accrual.|
|**Work Cover On-Costs**|Tick to apply “Work Cover On-Costs” to this leave accrual.|
|**Additional On-Cost %**|Enter a % to apply “Additional On-Costs” to this leave type.|

8.  Click on the **Arrow** button to close this window.  
