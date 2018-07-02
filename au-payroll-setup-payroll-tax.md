# To setup Payroll Tax

A Payroll Tax Card must be setup for each State that you process payrolls for employees.  The Payroll Tax Calculation report will
provide you with the ability to calculate your payroll tax liability based on the Branch and Division assigned to your employees/contractors.

To setup Payroll Tax:

- Setup the [Payroll Code Setup](au-payroll-setup-payroll-codes.md) - Payroll Tax and Payroll Tax Group: 
- Defines the state Set up [Branch](au-payroll-setup-branches.md) - Attaches the Payroll Tax State to the Branch
- Assign the Branch to the [Payroll Employee](au-payroll-create-payroll-employee.md) - Attaches the Branch associated to the Payroll Tax State to the employee
- Setup Payroll Tax Rates - Defines the Rates and Thresholds for each state and effective dates
- Flag [Payroll Transaction Types](au-payroll-setup-pay-transaction-types.md) on the Parameter tab - Defines the transactions attracting Payroll Tax

1.  To access the Payroll Tax setup, go to the following menu: *Departments/Payroll/Setup/Payroll Setup/ Tax/Payroll Tax*

2.  To create a new record, click on the **New** button.
  
|Field|Description|  
|:---------------------------------|:---------------------------------------|  
|**Date Applicable**|This is the date which the Payroll Tax rate is effective.|
|**Code**|The “Code” is used to uniquely identify the Payroll Tax.  The codes were previously defined in the section “Payroll Tax”.|
|**Description**|The “Description” is used to name the Payroll Tax.|

3.  Click on the “Actions/Edit” if you wish to edit this Payroll Tax card OR Click on the “OK” button to close this window.

4.  On the **General** FastTab, fill the fields as described in the following table.

|Field|Description|  
|:---------------------------------|:---------------------------------------|    
|**Date Applicable**|This is the date which the Payroll Tax rate is effective.|
|**Code**|The “Code” is used to uniquely identify the Payroll Tax.  The codes were previously defined in the section “Payroll Tax”.|
|**Description**|The “Description” is used to name the Payroll Tax.|  
|**Monthly FBT Estimation**|Enter the amount of the monthly FBT estimation.  This field can be left blank if your organisation is not required to estimate their FBT obligations.  This field is used in the calculation of Payroll Tax.|

5.  On the **Payroll Tax Subform** FastTab, fill the fields as described in the following table.

|Field|Description|  
|:---------------------------------|:---------------------------------------|   
|**Yearly Threshold**|The “Yearly Threshold” is used for reconciling payroll tax paid.|
|**Monthly Threshold**|The “Monthly Threshold” is used for calculating the monthly payroll tax to pay.|
|**Rate**|The “Rate” is the tax rate at which to calculate the levy.|
|**Rate – Maximum**|The “Rate - Maximum” is the maximum tax rate at which to calculate the levy.|
|**Exceeds Threshold Divisor**|The Divisor should be set to 3.|

6.  On the **VIC Information** FastTab, fill the fields as described in the following table.

|Field|Description|  
|:---------------------------------|:---------------------------------------|    
|**State Annual Estimate**|Enter the Victorian State Annual Estimate if applicable.|
|**Australia Wide Annual Estimate**|Enter the Australia Wide Annual Estimate.|
|**Part Year Start**|Enter the date that the Part Year Start began.|
|**Part Year Start**|Enter in the date that the Part Year End will cease.|

7.  On the **ACT Information** FastTab, fill the fields as described in the following table.

|Field|Description|  
|:---------------------------------|:---------------------------------------|   
|**ACT Calculation Method**|Select the Calculation Method Option 1. Not Claiming the ACT Threshold: The system calculates ACT payroll tax at a flat rate of 6.85% of the total ACT wages. Option 2. Claiming the ACT Threshold: The System calculates the portion of the tax free threshold.|

8.  On the **Adjustments** FastTab, fill the fields as described in the following table.

|Field|Description|  
|:---------------------------------|:---------------------------------------|   
|**Estimated Tax Rate**|If an “Estimated Tax Rate” is required, enter the amount in this field.  This field may be left zero.|
|**Estimated Deduction**|Enter an “Estimated Deduction” amount if a deduction is incorporated into the calculation of Payroll Tax. This field may be left zero.|
|**Monthly Adjustment**|Enter a “Monthly Adjustment” amount if this is incorporated into the calculation of Payroll Tax.  This field may be left zero.|

9.  Click on the **CLOSE** button to close this window.
  
 
[GoToTop](#to-setup-payroll-tax)
