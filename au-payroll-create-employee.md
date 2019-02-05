# Create Employee

You must setup an Employee card prior to creating a [Payroll Employee](au-payroll-create-payroll-employee.md) record.  

**Note:** There are a few fields contained on the Employee card which are mandatory (you must enter information to continue) whilst other fields are optional which can be filled in at a later stage or be left blank.

The following list is used to indicate the **Field Type** on each tab:

* **M**= Mandatory
* **O** = Optional
* **S** = System Defined

1.  To create an Employee record, go to the following menu:  *Employees*

2.  Select the **New** link.  On the **General** FastTab, fill the following fields;

|Field	|Field Type	|Comments|
| :--- | :---: | :--- |
|**No.**|	M	|This field identifies the Employee throughout the Payroll and Human Resource Granules.
|**First Name**|	M	|The “First Name” is displayed.  The field is populated from the Employee card.  You can edit this field.  If you change the Employee Name in this field the Payroll Employee card is also updated with the change.
|**Middle Name**|	O	|Enter the Middle name.
|**Last Name**|	M	|The “Last Name” is displayed. The field is populated from the Employee card.  You can edit this field.  If you change the Employee Name in this field the Payroll Employee card is also updated with the change.
|**Job Title** |	O	|Select a Job Title if required.  This field is used only for reporting.
|**Title**|O|Enter in the Employee's Title
|**Initials**	|O	|Enter the Employees initials.
|**Other Names**| O | This field is used to record if the employee has an Alias Name or Name otherwise known as.
|**Search Name**|M	|This field is used to search for the Employee throughout the Payroll 
|||The contents of the Alpha Search field do not need to be the same as those of the Employee First and Last Name fields. 
|**Gender**|O |Select from one of the options the gender of the employee.
|**Marital Status**|O | Select from one of the options to describe the marital status of the employee.
|**Company Phone No**|O | Enter in the employee's company phone no.
|**Company Email**|O| Enter in the employee's company email address.
|**Last Date Modified**|S |This field is populated with the date that last time the record was modified.
|**Privacy Blocked**|O |Select this field if you wish for the record to be blocked.

3. Complete the following fields on the **Address & Contact** FastTab;

|Field	|Field Type	|Comments|
| :--- | :---: | :--- |
|**Address**	|O	|Enter in the address for the employee.
|**Address 2**|	O	|Thsif field is used to enter in additional address information.
|**City/Post Code**	|M	|The “City/Post Code” is 2 fields used to record the post code and city. Enter or select the post code from the table.  If the post code exists in the Post Code table the City field automatically populates to the city associated with the post code.  This information is mandatory for STP reporting purposes.
|**Country/Region Code**|M |The "Country/Region Code" is used to record the Country or Region associated with the post code.
|**Private Phone No.**	|O	|Enter in the employee's home or private phone no.
|**Pager**|O |Enter in the employee's pager number if applicable.
|**Extension**|O |Enter in the employee's work extension number.
|**Direct Phone No.**|O |Enter in the employee's direct phone number.
|**Work Phone No.**|O |Enter in the employee's work phone number.
|**Private Email**|O |Enter int he employee's private email address.  This email address will be used to send the pay advices to when emailed.
|**Alt. Address Code**|O |From the ArrowDown, select the Alternative Address code.
|**Alt. Address Start Date**|O |Enter in the start date of when the alternative address is in use.
|**Alt. Address End Date**|O |Enter in the end odate of when the alternative address is to cease.

4.  Complete the following fields on the **Administration** FastTab;

|Field	|Field Type	|Comments|
| :--- | :---: | :--- |
|**Employment Date**|M |Enter in the employee's commencement date with your company.
|**Status**|M |This field will default to "Active".  The other options available are "Inactive" and "Terminated".
|**Inactive Date**|O |This field is used to identify the date the employee became inactive.
|**Cause of Inactivity Code**|O |This field is used to identify the reason the employee became inactive.
|**Termination Date**|O |This field is used to identify the date the employee terminated with your organisation.
|**Ground for Term. Code**|O |This field is used to identify the reason the employee terminated with your organisation.
|**Emplymt. Contract Code**|O |This field is used for reporting purposes and to identify the employment contract code your employee is assigned to.
|**Statistics Group Code**|O |This field is used for reporting purposes and to identify the statistics group your employee is assigned to.
|**Resource No.**|O |This field is used to link the employee's Resource Card to the employee card.
|**Salespers./Purch. Code**|O |This field is used to link the employee's Salesperson/Purchaser code to the employee card.

5.  Complete the following fields on the **Personal** FastTab;

|Field	|Field Type	|Comments|
| :--- | :---: | :--- |
|**Birth Date**|M |Enter in the employee's birth date.
|**Tax File No.**|S |This field will be encrypted with the employee's Tax File Number as this information is entered and maintained on the Payroll Employee card.
|**Union Code**|O |This field is used for reporting purposes and to identify the union code your employee is associated with.
|**Union Membership No.**|O |This field is used for reporting purposes and to identify the union membership no.
|**Previous Surname**|O |This field is used to record an employee's previous surname.
|**Previous First Name**|O |This field is used to record an employee's previous first name.
|**Previous Middle Name**|O |This field is used to record an employee's previous middle name.
|**Date Name Changed**|O |This field is used to record the date the name changed.

6.  The **Payments** FastTab is used to record employee payment information only where an employee is paid reimbursements via the Purchase & Payables granule as a Vendor.  It is not required to be completed.



[GoToTop](#create-employee)
