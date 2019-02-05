# To setup Superannuation Products

Superannuation Products defines the default parameters used for Superannuation Processing including the calculations of employee and employer contributions to an unlimited number of Superannuation funds.

Generally, employees aged over the age of 18, who are paid $450 (before tax) or more in a calendar month are covered by the superannuation guarantee legislation, regardless of their type of employment.  

The Superannuation Guarantee Contribution (SGC) is a percentage of specific components of employees’ remuneration, called “Ordinary Time Earnings”. 

Superannuation contributions by either the employee or the employer are set up as a percentage of the employee’s pay (or base salary), or as a standard amount each pay period. The employer may also contribute a factor of the employee’s superannuation contribution.  Superannuation contribution can be set up to meet the minimum salary amount.  

When calculating Superannuation as a percentage of pay, the process uses the [pay transactions types](au-payroll-setup-pay-transaction-types.md) that have the **Apply to Superannuation** field set to **Yes** on the parameters fasttab for the Standard Superannuation method and Employee contributions.

The payments of contributions to the superannuation funds are also recorded.  Payment can be set up to generate at the frequency required by the superannuation fund. Recorded against each Superannuation fund are the contributions made to it by the employee and employer.  

Manual changes can be made to superannuation contribution amounts for the employer or employee.  These changes will be recorded as transactions. On the Pay Journal one-off contributions to superannuation can be entered.

Cheques to the superannuation fund can be automatically printed from the system.  These can be set up to be a standard amount each month or the actual amount that has been contributed since the last payment was made.

1. In the **Search** box, enter **Superannuation Products**, and then choose the related link.

2. On the **General** FastTab, fill the fields in the following table.

|Field|Description|  
| :--- | :--- | 
|**Code**|This field is used to enter a unique Code to identify the Superannuation Company.|  
|**Product Name**|The Product Name field is used to record the name of the product. Enter in a description (up to 30 characters) to identify the name of the product.|  
|**Product Reference No.**|The Product Reference No. is issued by the Superannuation Fund and will be recorded in this field. Enter in the Product Reference No. (up to 20 characters).|
|**Product ID No. (SPIN)**|The Product ID No. (SPIN) is issued by the Superannuation Fund and will be recorded in this field. Enter in the Product ID No. (up to 20 characters).|
|**Unique Identifier (USI)**|The Unique Identifier (USI) is issued by the Superannuation Fund and will be recorded in this field. Enter the Unique Identifier (up to 20 characters).|
|**Fund Code**|Select the Fund Code for the Superannuation Product from the **ArrowDown**.|
|**Fund Name**|The Fund Name field is not editable and will default from the Fund Code nominated.|
|**Remit Period**|The Remit Period field is used to identify the frequency of your Superannuation payments. The options are: **Pay Period, Monthly, Quarterly**.|
|**Last Date Calculated**|The Last Date Calculated field will identify the last date Superannuation was calculated.|
|**Last Date Updated**|The Last Date Updated field will identify when the record was last updated.|
|**Contact Phone No.**|The Contact Phone No. is used to record the contact number for the Superannuation Fund.|
 
3. On the **Options** FastTab, fill the fields in the following table.

|Field|Description|  
| :--- | :--- |
|**Standard Salary**|A checkmark in this field indicates the superannuation calculation can be based on an annual amount (Base Salary) entered on the Employee Superannuation card, instead of the employee’s actual earnings.|  
|**Company SGC Min. Salary**|This field indicates the minimum salary an employee must earn before an employer must contribute.|  
|**Min. Salary Check Frequency**|This field is the period relating to minimum salary, and is checked during each *Calculate Pays* function.|
|**Payroll Tax Exempt**|This field indicates if payroll tax is calculated against the amounts contributed.|
|**Vendor No.**|If you have vendor Integration turned on and you wish to create Vendor Invoices for this Superannuation Company you must select the Superannuation Company's corresponding Vendor Number.|
|**SGC Type Code**|After you have set up the [Pay Transaction Type](au-payroll-setup-pay-transaction-types.md) you should select the corresponding Transaction for this field.  This is the Standard SGC Transaction Type.|
|**Pre-Tax Transaction Type Code**|After you have set up the [Pay Transaction Type](au-payroll-setup-pay-transaction-types.md) you should select the corresponding Transaction for this field.  This is the Salary Sacrifice Transaction Type.|
|**Post-Tax Transaction Type Code**|After you have set up the [Pay Transaction Type](au-payroll-setup-pay-transaction-types.md) you should select the corresponding Transaction for this field.  This is the Employee After Tax  Transaction Type (Non Concessional).|
|**Non-SGC Transaction Type Code**|After you have set up the [Pay Transaction Type](au-payroll-setup-pay-transaction-types.md) you should select the corresponding Transaction for this field.  This is the Employer Non - SGC Transaction Type.|
   
 4. On the **Defaults** FastTab, fill the fields in the following table.

|Field|Description|  
| :--- | :--- |   
|**Employee Post-Tax Std. Amt.**|This field is used if you wish to enter a standard amount of Superannuation paid to the Superannuation Company each Pay-Period by the employee.  This amount can be overridden at the employee level.|  
|**Employee Post-Tax Standard %**|This field is used if you wish to enter a standard percentage of an Employee earning’s to be paid to the Superannuation Company.  The earnings for the period are summed from transactions marked as “Apply to Superannuation”.  The percentage can be overridden at the employee level.|    
|**Employer SGC Amt.**|This field is used to enter a fixed SGC amount which the Employer will pay Superannuation.  The amount can be overridden at the employee level.|
|**Employee SGC %**|This field is used to enter a fixed SGC percentage which the Employer will pay Superannuation.  The percentage can be overridden at the employee level.|
|**Employer Non-SGC Amt**|This field is additional to the SGC Amount.|
|**Employer Non-SGC %**|This field is additional to the SGC %.|
|**Employee Pre-Tax Standard Amt.**|This field is used to enter a standard amount of Superannuation paid to the Superannuation Company each Pay-Period by the employee as a pre-tax (salary sacrifice contribution).  This amount can be overridden at the employee level.|
|**Employee Pre-Tax Standard %**|This field is used to enter a standard percentage of an Employee earning’s to be paid as a pre-tax (salary sacrifice) contribution to the Superannuation Company.  The earnings for the period are summed from transactions marked as “Apply to Superannuation”.  The percentage can be overridden at the employee level.|
   
5. On the **Employer Posting** FastTab, fill the fields in the following table.

|Field|Description|  
| :--- | :--- |
|**Cost Transaction Posting Group**|This field indicates the Transaction Posting Group assigned to Superannuation transactions.  It is used to determine the debit General Ledger account.|  
|**Provision Tran. Posting Group**|This field indicates the Transaction Posting Group assigned to Superannuation transactions.  It is used to determine the credit General Ledger account.|    

[GoToTop](#to-setup-superannuation-products)
