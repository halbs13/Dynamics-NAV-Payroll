# INSTALLATION AND IMPLEMENTATION

The following instructions outline the procedures for installing and implementing the Payroll granule.  

**Note: Not all steps are required for every implementation.**

1.	Import the payroll objects to the database.

2.	In the object designer: 

  * To set up default Pay Transaction Types, Leave, Awards, Posting Groups, etc. Run the following Codeunit: ID **16000400  Payroll-        Initialise** 
  
  * To set up the default MS Dynamics NAV security payroll permission groups.  Run the Codeunit: ID **16000401 Payroll-Initialise Permissions**  
      
  * **PAY-READONLY** to give users read only permission,
  * **PAY-STANDARD** to give general read write permission, 
  * **PAY-SUPER** to give all payroll permissions.
      
3.	Set up Payroll Users and Permissions

  * You must grant at least one user the **PAY-SUPER** permission.
  * Assign the user either the **Payroll Officer** or **Payroll Supervisor Role Centre**.
  
4.	Import the current Tax Scale text file.

5.	[Import the Employee BSB numbers.](au-payroll-import-bsb-numbers.md)

6.	Set up the Payroll General Codes

      •	Pay Transaction Types - determine allowances and deductions required by your company by reviewing your current payroll.
      •	Leave Accruals - Review the defaults set up as part of the Payroll-Initialise and modify if required
      •	Payroll Setup card - Set up the required Payroll Cards, Tax Years and Hours.
      •	YTD Accumulations. 
      •	Awards, Award Classifications and Rates, - if Award Rates is ticked in the Payroll Setup.  You will need to determine the awards required for your company.
      •	Payroll Posting Setup. - You must determine the General Ledger accounts required
      •	Superannuation Funds & Superannuation Companies.
      •	Set up the Workers Compensation Rates and Workers Compensation Locations.
      •	Set up the Employees in the Human Resources granule.

7.	Set up the Employees in the Payroll granule:
      •	Add the Pay Dissections for the employee.
      •	Add the Pay Rate for the employee.
      •	Add any permanent Allowances and Associated Transactions for the employee.
      •	Add any permanent Deductions for the employee.
      •	Add the Superannuation configurations for the employee including employee and employer contributions.
      •	Create any Oncost and Cost Allocations for the employee.
      •	Add the Leave types to the employee.

8.	Set up employee work Gangs.

9.	**CONDUCT PAYROLL TESTING.**
