# Payroll Controls Payroll User Setup

Payroll Controls are used to define the parameters and rules for the Payroll Granule at a global level.  Parameters defined at the global level are used as defaults when setting up Payrolls and can be overridden to suit your business requirements. Setup the following Payroll Controls:
                                                                                         
* [Payroll Setup](au-payroll-setup-payroll-controls-payroll-setup.md)
* [Payroll User Setup](#payroll-user-setup) 
* [Pay Source Codes](au-payroll-setup-payroll-controls-pay-source-codes.md)
* [Pay Journal Templates](au-payroll-setup-payroll-controls-pay-journal-templates.md)

## Payroll User Setup

Payroll access is granted using the standard Microsoft Dynamics NAV User Security authorising the tables, forms, reports, and functions the user is allowed to access.   The Standard Security Groups for payroll are installed with the Payroll module when the Code Unit 16000401 Payroll Initialise Permissions is run.

Additional security is provided with the Payroll granule for Payroll Users.  After a user has been setup as a Payroll User  the Payroll User determines the Payrolls the user is allowed to access for data entry, processing, enquiry, and reporting.  The Payroll User Id is the same as the User Id used to log on to Microsoft Dynamics NAV.

A user can be authorised to only inquire on employees in a specific branch or division of the payroll to prevent the user accessing sensitive employee details.

Employees can be granted permissions to inquire on their own pay details.  Access is defined by creating a Microsoft Dynamics NAV User Id, an identical Payroll User Id and then entering the Employee User Id in the employee Payroll Employee card.

**Note:**  This security is not replicated in the Human Resources granule.

1. In the **Search** box, enter **Payroll User Setup**, and then choose the related link or go to the following menu: *Departments/Payroll/Setup/Payroll Setup/Payroll Controls/Payroll User Setup*.

2. Fill the fields in the following table.

|Field|Description|  
|:---------------------------------|:---------------------------------------|  
|**User ID**| This field is used to select the user.
|**Supervisor**|	If selected, this field gives the user “Supervisor” privileges to view employee tax file numbers and import tax scale changes.
|**Payroll Filter**|	This field is used to limit access to specific Payrolls.  When a Payroll List is displayed, only Payrolls with values that match this criteria is shown.  If employees are attached to a restricted payroll you will not be able to view their Employee Pay card.  Users can be restricted to single or multiple payrolls. E.g. Payroll1|Payroll2
|**Branch Filter**|	This field is used to limit access to only employees within the matching branch code entered on the “Posting” tab of the “Employee” card.  When an Employee List is displayed only Employees that match the Branch will be shown.  Users can be restricted to single or multiple branches e.g. “ADM|FIN”
|**Division Filter**|	This field is used to limit access to employee data with a matching division code entered on the “Posting” tab of the “Employee” card.  When an Employee List is displayed only Employees that match the Division will be shown.  Users can be restricted to single or multiple divisions.
|**Employee Filter**|	This field is used to limit access to employee data with a matching “Employee No.”.  When an Employee List is displayed only Employees that match the Employee filter are shown.
 
 
## Current Payrolls button

The "Current Payrolls" area is used to allow users to print reports such as the Payment Summary Proof List and Posted Payroll Summary reports.  I will also allow you to see if a user has a Payroll Selection filter selected to filter payroll information.

|Field|Description|  
|:---------------------------------|:---------------------------------------|  
|**Current User Payroll**|	This form displays a list of all Payroll User IDs and their current Payrolls.  The same payroll may be associated with many User IDs.   The associations setup here act as filters.  The Current Payroll for a User ID is the default Payroll for many activities, including Pay Journals, Bulk Generation, etc.  It may be set and altered here or in the Payroll Selection menu option. It can be left blank.


[GoToTop](#payroll-controls-payroll-user-setup)
 
