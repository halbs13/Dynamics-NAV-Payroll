# PAYROLL INSTALLATION AND IMPLEMENTATION

The following instructions outline the procedures for installing and implementing the Payroll granule.  

**Note: Not all steps are required for every implementation and will be dependant upon your organisation's payroll requirements.**

1.	Create users within Business Central and assign permissions; 
       
      * **PAY-READONLY** to give users read only permission,
      * **PAY-STANDARD** to give general read write permission, 
      * **PAY-SUPER** to give all payroll permissions.
      
2.	Set up Payroll Users and Permissions

      * You must grant at least one user the **PAY-SUPER** permission.
      * Assign the user either the **Payroll Officer** or **Payroll Supervisor Role Centre**.
  
3.	[Import the current Tax Scale text file](au-payroll-setup-import-tax-scales.md)

4.	[Import the Employee BSB numbers](au-payroll-setup-import-bank-state-branch-numbers.md)

5.	Review or set up the following areas;

      * [Leave Accruals](au-payroll-setup-leave.md) - Review the defaults set up as part of the Payroll-Initialise function and modify if required.
      * [Payrolls](au-payroll-setup-payrolls.md) - Set up the required Payrolls which determine the frequency in which the employee is paid, the Tax Years and Payroll defaults.  
      * [YTD Accumulators](au-payroll-setup-ytd-accumulators.md)
      * [Awards, Award Classifications and Rates](au-payroll-setup-awards.md) - if Award Rates is ticked in the Payroll Setup.  You will need to determine the awards required for your company.
      * [Payroll Posting Setup](au-payroll-setup-posting-group-setup.md) - Assign General Ledger accounts to the transaction posting groups.
      * [Pay Transaction Types](au-payroll-setup-pay-transaction-types.md) - determine allowances and deductions required by your company by reviewing your existing payroll requirements for your organisation.
      * [Superannuation Funds](au-payroll-setup-superannuation-funds.md) & [Superannuation Products](au-payroll-setup-superannuation-products.md)
      * [Work Cover Rates & Locations](au-payroll-setup-work-cover.md) 
      

6.	Create Employees in the [Human Resources](au-payroll-create-employee.md) & [Payroll](au-payroll-create-payroll-employee.md) granules:
      * Add the [Pay Dissections](au-payroll-create-payroll-employee-pay-dissections.md),
      * Add the [Employee Pay Rates](au-payroll-create-payroll-employee-pay-rates.md),
      * Add any permanent [Allowances and Associated Transactions](au-payroll-create-payroll-employee-gross-allowances.md),
      * Add any permanent [Deductions](au-payroll-create-payroll-employee-deductions.md), 
      * Add the [Superannuation Product](au-payroll-create-payroll-employee-superannuation.md) and any additional contributions,  
      * Add any [Oncost Calculations](au-payroll-create-payroll-employee-accumulation-calculations.md) and [Cost Allocations](au-payroll-create-payroll-employee-cost-allocations.md),
      * Add the [Leave types](au-payroll-create-payroll-employee-leave-accruals.md),
      * Add the [Work Schedule](au-payroll-create-payroll-employee-work-schedule.md), if applicable.

7.	**CONDUCT PAYROLL TESTING.**
