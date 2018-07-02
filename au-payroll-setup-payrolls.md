# To setup Payroll 

The Payroll Card is used to maintain the Payrolls used to pay the employees.  Each employee is assigned to a specific Payroll in the Payroll Employee card.

The parameters set up in Payrolls are the defaults applied to all employees assigned to that payroll.  The Pay Frequency and integration to the General Ledger and other Dynamics NAV granules is defined and activated.

When a new Payroll is created some fields are automatically populated from the Payroll Setup card and from Company Information in the General Ledger.  These fields may be overwritten.

When you setup a new Payroll you are prompted to create the new Payroll Tax Year.  To create the Payroll Tax Year you must enter
the following information Pay frequency (weekly, fortnightly, 4 weekly, monthly or quarterly) The first pay period start date.  

**Note: The pay period start date, is not necessarily the 1st June.  The Payroll Tax Year can be setup at any time prior to running the first payroll.**

1.  To access the Payroll Card, go to the following menu: *Departments/Payroll/Setup/Payroll Setup/ General/Payroll*

2.  The **Payroll List** window contains the following fields as described in the following table.
  
|Field|Description|  
|---------------------------------|---------------------------------------|  
|**No.**|This field is used to identify this Payroll throughout the Payroll Granule. You can type the name of the Payroll that you wish to use or select a number from the Payroll Number Series by selecting the **ArrowDown**.|
|**Group Account No.**|The Group Account No. field will display the information as entered into the Payroll card.|
|**Company Name**|The Company Name field will display the Company Name of the Payroll you are viewing.|
|**Ship-To Contact**|The Ship-To Contact will display the contact of the Payroll you are viewing.|
|**Company Phone No.**|The Company Phone No. will display the information as entered on the Payroll card.|

3.  Click on the *Actions/Edit* if you wish to edit this Payroll, Click on the **Periods** Button if you wish to view/edit the Pay Periods associated to this Payroll, OR Click on the **CLOSE** button to close this window.

4.  To create a new record, click on the **New** button.

5.  On the **General** FastTab, fill the fields as described in the following table.

|Field|Description|  
|---------------------------------|---------------------------------------| 
|**No.**|This field is used to identify this Payroll throughout the Payroll Granule. You can type the name of the Payroll that you wish to use or select a number from the Payroll Number Series by selecting the **ArrowDown**.|
|**Company Name**|The contents of the Name and Address fields are printed on documents including Payment Summaries and must be entered.  This field populates from the Company setup in the General ledger.  You can over type the Company Name if you wish.|
|**Company Name 2**|The “Company Name 2” is used to extend the “Company Name” when a longer name is required.|
|**Company Address 1**|The “Company Address” holds line one of the company addresses.|
|**Company Address 2**|The “Company Address 2” holds line two of the company address.|
|**Company Post Code**|The “Company Post Code/City” is used to store the postcode and city.  You may enter the postcode or select it from the **ArrowDown**. If the postcode exists in the Post Code table the City field is populated to the city associated with the postcode. If no value appears in the City field the postcode does not exist in the table and you must add the postcode and its City to the Post Code table.|
|**Company City**|The “Company Post Code/City” is used to store the postcode and city.  You may enter the postcode or select it from the “ArrowDown”.  If the postcode exists in the Post Code table the City field is populated to the city associated with the postcode.  If no value appears in the City field the postcode does not exist in the table and you must add the postcode and its City to the Post Code table.|
|**Company Country Code**|The “Company Country Code” must be selected from the **ArrowDown**.|
|**Group Account No.:**|The “Group Account No.” is the current active PAYG Group Number allocated to the Employer by the Australian Taxation Office (ATO).|
|**Company A.B.N.:**|The “Company A.B.N.” is the Australian Business Number.|
|**Registered Name**|The “Registered Name” is the registered name for this company.|
|**Registered Name 2**|The “Registered Name 2” is used to extend the “Registered Name” when a longer name is required.|
|**Company Division Part No.**|This field is used to enter in the Company Division Part No. of this company forms part of a Group.|
  
6.  On the **Communications** FastTab, fill the fields as described in the following table.

|Field|Description|  
|---------------------------------|---------------------------------------| 
|**Company Phone No.**|The “Company Phone No.” is the Company’s telephone number.  Use a standard format for the telephone number so that it will look uniform on printouts.|
|**Company Fax No.**|The “Company Fax No.” is the Company's fax number.  Use a standard format to enter the fax Number so that it will look uniform on printouts.|
|**Company Email**|The “Company E-Mail” is the Company's E-Mail address. When your program is integrated with an E-Mail system, you can click the button located next to the field to create and send messages.  If you have entered an address in the E-Mail field, the program automatically fills in this address in the ‘To’. Field.|
|**Contact Person**|Enter the name of the person to contact in relation to this payroll.|
|**Contact Phone No.**|Enter the telephone number of the Contact Person.|

7.  On the **Shipping** FastTab, fill the fields as described in the following table.

|Field|Description|  
|---------------------------------|---------------------------------------| 
|**Ship-To Contact**|Enter the name of the person to send mail to for this payroll.|
|**Ship-to Address**|Enter the address items are sent for this payroll.|
|**Ship-To Address 2**|Line two of the “Ship To Address”.|
|**Ship-To Post Code**|The “Ship to Post Code” is used to store the postcode.  You may enter the postcode or select it from the **ArrowDown**. If the postcode exists in the Post Code table the City field is populated to the city associated with the postcode.  If no value appears in the City field the postcode does not exist in the table and you must add the postcode and its City to the Post Code table.|
|**Ship-To Country/Region Code**|You must select a Country from the list using the **ArrowDown**.|

8.  On the **Integration** FastTab, fill the fields as described in the following table.

|Field|Description|  
|---------------------------------|---------------------------------------| 
|**G/L Integration**|A checkmark in this field indicates that integration to the General Ledger granule. An example of where you might use this is when you want to post entries into the General Ledger.|
|**Job Cost Integration**|A checkmark in this field indicates integration into the Jobs granule. An example of where you might use this is when you want to post entries into the Jobs where job information is entered into the Pay Journal.|
|**Customer Integration**|A checkmark in this field indicates integration into the Sales & Receivables granule. An example of where you might use this is when you want to post entries to Customers if your employee is setup as a customer.|
|**Vendor Integration**|A checkmark in this field indicates integration into the Purchase & Payables granule.  An example of where you might use this is when you want to post deduction entries to a Vendor when posting the pay journal.|
|**Create Vendor Invs. For Super**|A checkmark in this field indicates to post unpaid invoices to the Purchase & Payables granule.  This field is available only when Vendor Integration has been ticked. An example of this is Superannuation deductions, Health and Union deductions.|
|**Payroll Posting Group**|Enter or select the posting group for this payroll by selecting the **ArrowDown**. Payroll Posting Groups are used to help define the General Ledger Account Number to post payroll transactions against. See [Payroll Posting Setup](au-payroll-setup-posting-group-setup.md).|
|**Journal Template Name**|This field defines the journal template used to process Employee Pays.  This field must be selected from previously defined templates.  Select the “ArrowDown” in the field to select the Journal Template Name.|
|**Journal Batch Name**|This field defines the journal batch used to process Employee Pays.  This field must be selected from previously defined batches.  Select the **ArrowDown** in the field to select the Journal Batch Name.|
|**Time Journal Template Name**|This field defines the journal batch used to process Time.  This field must be selected from previously defined batches.  Select the **ArrowDown** in the field to select the Journal Template Name.|
|**Time Journal Batch Name**|This field defines the journal batch used to process Time.  This field must be selected from previously defined batches.  Select the **ArrowDown** in the field to select the Journal Batch Name.|
|**Gen. Bus. Posting Group**|This field is used to define the General Business Posting Group for posting GST amounts.  This field may be left blank if your organisation is not calculating GST components in Payroll.|
|**GST Bus. Posting Group**|This field is used to define the GST Business Posting Group for posting the GST component.  This field may be left blank if your organisation is not calculating GST components in Payroll.|
|**Currency Code**|This field is used to identify the currency for this payroll for reporting purposes only. This field may be left blank if your organisation does not use multiple currencies.|

9.  On the **Pay Periods** FastTab, review the fields as described in the following table.

|Field|Description|  
|---------------------------------|---------------------------------------| 
|**Pay Period Frequency**|This field defines the frequency for this  Payroll.  Select from the following options: Weekly, Fortnightly, 4 Weekly, Monthly, and  Quarterly.|
|**No. Pays Per Year**|This field is used to define the number of Pay Periods in the Payroll Tax Year for this Payroll.|
|**No. Tax Weeks per Pay Run**|This field defaults based upon the “No. Pays Per Year” (E.g. 52 weekly = 1 tax week, 12 monthly = 4.3333 tax weeks, 13 4-weekly = 4 tax weeks).|
|**Tax Year**|This field indicates the current tax year.|
|**Period No.**|This field is updated by the system each time you close a Pay Period. It indicates the current Pay Period and is automatically reset to 1 after the last Pay Period is closed for the Payroll Tax Year.|
|**Period End Date**|This field is displayed on Reports and is used to validate the dates entered are within the current period.|
|**Previous Period End Date**|This field is transferred from the current “Period End Date” when End Of Period Processing is run.  These two dates determine the number of days in the period for Leave Entitlement.|

10.  On the **Options** FastTab, fill the fields as described in the following table.

|Field|Description|  
|---------------------------------|---------------------------------------| 
|**Printer Name**|This field is used to select a default Printer when a different printer is required to print payroll documents from your default windows printer.  When a different printer is required  you must select a Printer previously set up in the Windows Printer table.  Select the Printer from the **ArrowDown**.|
|**Max. Overtime Before Warning**|This field is used to set the maximum allowed before a warning is triggered on the Payroll “Entry Validation” report.|
|**Max. Worked Before Warning**|This field is used to set the maximum allowed before a warning is triggered on the Payroll “Entry Validation” report.|
|**Max. Pay Value Before Warning**|This field is used to set the maximum allowed before a warning is triggered on the Payroll “Entry Validation” report.|
|**Max. Leave Days Before Warning**|This field is used to set the maximum allowed before a warning is triggered on the Payroll “Entry Validation” report.|
|**Net Pays by Cash Denomination**|When using Cash to pay your employees tick this field to round Net Pay amounts that cannot be made up of the lowest denomination to be applied to tax.  This is the default when the employee is paid in cash.|
|**Round Net If Tax Applicable**|This field is ticked only when the Net Pay is rounded, using “Net Pays by Cash Denomination”, if the employee pays tax.|
|**Employer Super. Rounding**|This field is used to nominate the rounding amount.  The default is 1 cent.|
|**Employee Super. Rounding**|This field is used to nominate the rounding amount.  The default is 1 cent.|
|**Show Leave as Hours**|Ticked this field to show the employees leave balances in hours on the employee’s pay advice. By default the system calculates employee leave accruals and entitlements in days.|
|**Validation Not Required**|Leave this field blank to force the User to run the Entry Validation report prior to posting the Payroll Batch.  (This option is Recommended).  Errors reported must be corrected before the batch will post. Tick this field to allow posting without running the “Entry Validation Report”.|
|**ATO Supplier Number**|This field is populated from the Payroll Setup card You can override the field if required. This field is used to display the registered number from the ATO and is required when submitting electronic data to the ATO.  This is either your ABN or withholding payer number (WPN). If you are reporting via the internet using ECI, only a valid ABN will be accepted in the supplier number field and it must match the ABN provided on the digital certificate. If reporting via magnetic media, either an ABN or WPN will be accepted.|
|**Minimum Net Salary**|This field defines the minimum net salary an employee on this payroll must be paid before deductions are deducted from their pay.  If the deductions bring the value of their net pay below the Minimum Net Salary the deduction is not deducted.|
|**Payroll Tax Code**|This field defines the code used to calculate Payroll Tax for this payroll.  This field can be left blank.  Payroll Tax can be defined at the employee level by indicating the Branch associated with the Payroll Tax code.|
|**Dissections for Pay Advice >1**|You can produce more than 1 pay advice for an employee in the current pay period to pay terminations payments, bonus’s, adjustments etc.  The employee’s bank account dissections are only applicable to Pay Advice 1 (Standard Pay).  When a pay is calculated on subsequent pay advices in a pay period only the main bank account dissection is used to pay the employee.  Tick this field to use all the employee bank account dissections for subsequent pay advices.|
|**On Cost Dims From Employee**|Tick this field to post on-cost pay transaction types with employee dimensions through to the General Ledger. Leave this field blank to post the on cost transaction types without the employee dimensions to the General Ledger.|
|**Calc. Superannuation Monthly**|Tick this field to calculate employer superannuation contributions monthly using the Calculate Monthly Superannuation menu reporting option. Leave this field blank to calculate employer superannuation contributions each pay period.|
|**Time Sheet Week Ending Day**|This field identifies which day of the week that the Time Sheet Week Ending Day.|

11.  On the **Pay Advice** FastTab, fill the fields as described in the following table.

|Field|Description|  
|---------------------------------|---------------------------------------| 
|**Pay Advice Report ID**|This field is used to select the Pay Advice Report Id.  The report Id is used to define the format of the Pay Advice.  The Standard Pay Advice Report Id is 16000473 for internal employees or 16003876 for Labour Hire which includes an Incorporated Company RCTI.  To use a custom pay advice we recommend a new Report ID is used.|
|**Pay Advice Report Name**|This field is populated with the name of the Pay Advice selected and cannot be changed.|
|**Pay Advice Message**|Use this field to enter a message to print on all Pay Advices.  The message can be overridden when printing pay advices during the pay process.|
|**Weekly Rate on Pay Advice**|Tick this field to print the employee’s weekly rate of pay on the pay advice.  This is only applicable for internal employees.|
|**Annual Rate on Pay Advice**|Tick this field to print the employee’s annual rate on the pay advice.  This is only applicable for internal employees.|
|**YTD Value on Pay Advice**|Tick this field to print the Year to Date values on the pay advice.|
|**Employer Super. On Pay Advice**|Tick this field to print the Employer Superannuation Contribution on the pay advice.|
|**Accrued TIL on Pay Advice**|Tick this field to print the balance of Time in Lieu on the pay advice.|
|**Annual Leave on Pay Advice**|Tick this field to print the Annual Leave on the pay advice.|
|**Sick Leave on Pay Advice**|Tick this field to print the Sick Leave on the pay advice.|
|**L.S.L. on Pay Advice**|Tick this field to print the Long Service Leave on the pay advice.|
|**Leave Ent. ONLY on Pay Advice**|Tick this field to only print the employees leave entitlement excluding pro-rata on the pay advice.|
|**Pay Advice Logo:**|The Pay Advice Logo can be imported into the Payroll Card where you can have a different logo for each payroll if you wish. Right click over the logo section and select one of the following options: Select Picture, Save Picture As, Preview Picture, Copy, Delete.|

12.  On the **Defaults** FastTab, fill the fields as described in the following table.

|Field|Description|  
|---------------------------------|---------------------------------------| 
|**Default Superannuation Company**|This field defines the Employer‘s standard Superannuation Company used for SGC payments. **Note: You must setup the Superannuation Company before making your selection. Select a Superannuation Companies from the ArrowDown.**|
|**Default Annual Leave Type**|This field defines the default Annual Leave Type used for employees attached to this payroll.   The Leave Type(s) must be setup before making your selection.  To display the Leave Types assigned an Accumulation Type of “Annual Leave” select the **ArrowDown**.|
|**Default Annual Leave Code**|This field defines the default Annual Leave Code used for employees attached to this payroll.  The Leave code defines the accrual rules for the leave.  The Leave Code must be setup before making the selection. To display Leave Codes with a Leave Type of Annual Leave select the **ArrowDown**.|
|**Default Leave Loading Type**|This field defines the default Leave Loading Type used for employees attached to this payroll.  The Leave Type(s) must be setup before making your selection.  To display the Leave Types assigned an Accumulation Type of “Leave Loading” select the **ArrowDown**.|
|**Default Leave Loading Code**|This field defines the default Leave Loading Code used for employees attached to this payroll.  The Leave code defines the accrual rules for the leave. The Leave Code must be setup before making the selection. To display Leave Codes with a Leave Type of Leave Loading select the **ArrowDown**.|
|**Default Sick Leave Type**|This field defines the default Sick Leave Type used for employees attached to this payroll.   The Leave Type(s) must be setup before making your selection.  To display the Leave Types assigned an Accumulation Type of “Sick Leave” select the **ArrowDown**.|
|**Default Sick Leave Code**|This field defines the default Sick Leave Code used for employees attached to this payroll.  The Leave code defines the accrual rules for the leave. The Leave Code must be setup before making the selection. To display Leave Codes with a Leave Type of Sick Leave select the **ArrowDown**.|
|**Default L.S.L. Leave Type**|This field defines the default Long Serve Leave Type used for employees attached to this payroll.   The Leave Type(s) must be setup before making your selection.  To display the Leave Types assigned an Accumulation Type of “Long Serve Leave” select the **ArrowDown**.|
|**Default L.S.L. Leave Code**|This field defines the default Long Service Leave Code used for employees attached to this payroll.  The Leave code defines the accrual rules for the leave. The Leave Code must be setup before making the selection. To display Leave Codes with a Leave Type of Long Service Leave select the **ArrowDown**.|
|**Default Work Cover Code**|This field defines the default Workers Compensation Rate used for employees attached to this payroll. The Workers Compensation Rates must be setup before making the selection. To display the available Workers Compensation Rate codes select the **ArrowDown**.|
|**Default Work Cover Loc. Code**|This field defines the default Workers Compensation Location used for employees attached to this payroll The Workers Compensation Locations must be setup before making the selection.  To display the available Workers Compensation Location codes select the **ArrowDown**.|
|**Default Days Per Week**|This field defines the number of days per week the majority of employees attached to this payroll work.  This field can be overridden at the employee level.|
|**Default Hours Per Week**|This field defines the number of hours per week the majority of employees attached to this payroll work.  This field can be overridden at the employee level.|
|**Default Hours Per Period**|This field defines the number of hours per pay period the majority of employees attached to this payroll work.  This field can be overridden at the employee level.|
|**Default Payment Method**|This field defines the Payment method for the majority of employees attached to this payroll.  This field can be overridden at the employee level.  Select from Cash, Cheque, or EFT.|
|**Default Tax Scale No.**|This field defines the PAYG Tax Scale used by the majority of employees attached to this payroll.  This field can be overridden at the employee level.|


13.  Click on the “Periods" Button if you wish to view/edit the Pay Periods associated to this Payroll, OR Click on the “OK” button to close this window.
  

[GoToTop](#how-to-setup-payroll)

 

# To setup Pay Periods

The Pay Period card is used to maintain the Pay Periods for this Payroll.  The card is nested within the Payroll Card so fields maintained on this card only update this specific Payroll Card.

1.  You can access the Pay Periods window, by clicking on the “Periods” Button on the Home ribbon.

|Field|Description|  
|---------------------------------|---------------------------------------| 
|**Tax Year**|This field indicates the Tax Year.|
|**No.**|This field indicates the Period Number within the tax year.  This field starts at 1 for each new Payroll Tax Year.|
|**Starting Date**|This field defines the first date (inclusive) of the Corresponding Period No.|
|**Ending Date**|This field defines the last date (inclusive) of the Corresponding Period No.|
|**Closed**|A checkmark in this field indicates that the pay period is closed. You can either manually place a checkmark in this field, or run a process to close the pay period correctly.|
|**Date Locked**|A checkmark in this field indicates that Pays have been generated within the Pay Period and the dates can’t be changed.  You can manually place a checkmark in this field, or run a process to lock the dates for the pay period correctly.|

2.  Click on the “Edit” icon if you wish to

- Create a New Tax Year,
- Delete a Tax Year,
- Modify Pay Periods or 
- Close a Current or Selected Pay Periods
- OR Click on the “CLOSE" button to close this window.
  
 
[GoToTop](#how-to-setup-payroll)


### Create a New Tax Year

**Note:  After the first tax year has been created, you cannot change the starting date if payrolls have been processed against any of the pay periods. All subsequent tax years start the date after the previous tax year.**

When you create a Payroll Tax Year, the equivalent to a year’s worth of pay period records are created. After clicking OK on this card, the created periods will display in the Pay Periods card.

1.  On the **Options** FastTab, fill the fields as described in the following table.

|Field|Description|  
|---------------------------------|---------------------------------------| 
|**Payroll No.**|This field identifies the currently selected Payroll.|
|**Starting Date**|This field defines the first date of the first pay period for the year.  The day after the last pay period end date of the previous tax year is the default.|
|**Pay Period Frequency**|This field defaults to” Weekly”.  You must select the correct frequency from the list.|
|**No. of Periods**|The default for this field is calculated from the “Pay Period Frequency” entry.|
|**Weeks Per Pay Period**|This field is calculated from the above entries and cannot be changed.|

2.  Click on the **OK** button after you have entered your selection to close this window.

[GoToTop](#how-to-setup-payroll)

 

### Delete Tax Year

1.  On the **Options** FastTab, fill the fields as described in the following table.

|Field|Description|  
|---------------------------------|---------------------------------------| 
|**Payroll No.**|This field identifies the currently selected Payroll.|
|**Tax Year**|This field identifies the Tax Year you wish to delete for the currently selected Payroll.|
|**Starting Date**|This field defines the first date of the first pay period for the year.|
|**End Date**|This field defines the end date of the last pay period for the year.|

2.  Click on the **OK** button after you have entered your selection to close this window.
  

[GoToTop](#how-to-setup-payroll)



### Modify Pay Periods

1.  On the **Options** FastTab, fill the fields as described in the following table.

|Field|Description|  
|---------------------------------|---------------------------------------| 
|**Payroll No.**|This field identifies the currently selected Payroll.|
|**Starting Date**|This field indicates the pay period start date you wish to modify.|
|**Pay Period Frequency**|This field can be changed by selecting the **ArrowDown** and selecting from list. Once changed; all Pay Periods from the starting date are converted to the new frequency. Example of changing from a weekly to a monthly frequency during a tax year follows. Decide on the first period to be changed to monthly, preferably one with an Ending Date in the same month as the start date  The sequence you apply the following date changes must never allow periods to overlap.   1. In the Pay Periods window change the Ending Date of the last weekly period to the last date of the month 2. Change the Starting Date for the first monthly period to the first date of the month.  3. Select the first monthly period, go to the Modify Pay Periods window and change the frequency to monthly. After you exit this window, all future periods have changed to monthly.|
|**By Calendar Months**|The “By Calendar Month” is used in conjunction with either the Monthly or Quarterly setting in the Pay Period Frequency.  When ticked, modifications are applied according to calendar months. This is only necessary when changing the frequency.|

2.  Click on the **OK** button after you have entered your selection to close this window.
  

[GoToTop](#how-to-setup-payroll)

### Closing Pay Periods

The 2 options available to close a pay period are:

- Close Current – this option will close the current period.
- Close Selected – from the Pay Periods window, you can nominate by highlighting which pay period you wish to close.

[GoToTop](#how-to-setup-payroll)
 
