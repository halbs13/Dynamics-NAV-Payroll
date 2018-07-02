## Update Payroll Employee card – General FastTab

The General FastTab is use to edit the employee name and address details used for Payment Summary production. You must assign the employee to a Payroll which determines the frequency of payment.  You can define the employee’s location, position and payment method. You must select the Employee Type code to determine the type of Payment Summary issued.




Field	Field Type	Comments
General FastTab
Employee No.	M	This field identifies the Employee throughout the Payroll and Human Resource Granules.
 
The Employee must exist as an Employee in Human Resources before you can setup a Payroll Employee card.
 
To setup a Payroll Employee card press the "New" icon on the Home Ribbon and place the cursor in the Employee No field.  

Click the “ArrowDown” button and select the “Employee No.” from the Employee List table. The Payroll Employee has the same Employee No as the Human Resource Employee.

You cannot complete any fields in the Payroll Employee card until you have selected an Employee Number.
Job Title	O	Select a Job Title if required.  This field is used only for reporting.
Employee First Name	M	The “Employee First Name” is displayed.  The field is populated from the Employee card.  You can edit this field.  If you change the Employee Name in this field the Employee card is also updated with the change.
Employee Last Name	M	The “Employee's Last Name” is displayed. The field is populated from the Employee card.  You can edit this field.  If you change the Employee Name in this field the Employee card is also updated with the change
Middle Name	O	Enter the Middle name
Initials	O	Enter the Employees initials
Address	O	The field is populated from the Employee card.  You can edit this field.  If you change this field the Employee card is also updated with the change.  

This field is used when producing the Payment Summaries.
Address 2	O	The field is populated from the Employee card.  You can edit this field.  If you change this field the Employee card is also updated with the change.  This field is used when producing the Payment Summaries.
Post Code/City	M	The “Post Code/City” is 2 fields used to record the post code and city. 

Enter or select the post code from the table.

If the post code exists in the Post Code table the City field automatically populates to the city associated with that post code.
Phone No.	O	The field is populated from the Employee card.  You can edit this field.  If you change this field the Employee card is also updated with the change.
Mobile Phone No.	O	The field is populated from the Employee card.  You can edit this field.  If you change this field the Employee card is also updated with the change.
Alpha Search	M	This field is used to search for the Employee throughout the Payroll 
The contents of the Alpha Search field do not need to be the same as those of the Employee First and Last Name fields. 
Payroll No.	M	Use this field to assign the employee to a specific Payroll (To learn more about Payrolls, read General – Payroll section below)
Pay Cycle Frequency	S	This field is only used to display the pay frequency for the selected Payroll.
The frequency defines the number of tax weeks calculated per Pay Run.
Position Code	O	This field indicates the position title of the employee.  These codes are common to all payrolls in this database.
Shift Code	O	This field is used to assign a default shift to this employee. The shift is used in the Pay Journal and may be overridden.
Pay Location	O	This field is used to indicate the location of the employee to distribute their Pay Advice.
Pay Advices can be printed in Pay Location order for each Payroll 
Employee Type Code	M	This field determines the type of Payment Summary issued to the employee.  

The employee type code must be updated prior to calculating the pay journal.
Payment Method	M	This field specifies the employee default Payment Method.  
Cash, Cheque, or EFT.
E-Mail Pay Advice	O	When this field is ticked, the employee will receive Pay Advice via email. This field can only be ticked if the E-Mail field in the Employee card is populated with a valid email address.
E-Mail Payment Summary	O	When this field is ticked, the employee will receive the Payment Summary via email. This field can only be ticked if the E-Mail field in the Employee card is populated with a valid email address.
