# Payroll Journal Process
The following steps must be completed in sequence to successfully produce the payroll:

1.    Open the Pay Journal

2.    Select the Payroll you wish to process.

3.    Enter time sheet information for time sheet employees and / or exceptions for automatically paid employees.  An example of this will be leave adjustments, etc.

4.    Select the **“Calculate Pays”** icon.
      - Select to Calculate Pays for all employees on the payroll or Calculate An Employee’s Pay to select an employee (You can cancel calculated Pays for all employees or selected employees)

5.    Select the **“Entry Validation Report”** icon from the Process section of the Home ribbon.
      - Select the Entry Validation Report.  To continue processing the payroll, it is not enough that you preview this report. You must **print** this report in order to proceed or alternatively generate and save it as a pdf file.  
      - Correct any errors indicated in the report.  
    - You do not need to cancel every calculated pay to correct any error; you can simply filter for the pays that needed corrections via **“Cancel Calculated Pays”** icon on the Actions ribbon.  
      - Select any of the other reports you wish to run.  
 
6.    Select the **“Create Bank Transfer File”** icon from the Process section on the Home ribbon.
      - Select Cheque, EFT or Cash as the method of payment you wish to pay the employees.  These options create the actual payments.
      - Remit the generated bank file to the bank and on successful upload then you are ready to post the pays to update the various ledgers.  
7.    Select the Post icon.
      - When you are ready to post the transactions to the General Ledger select the **“Posting”** icon.
      - Prior to posting the payroll journal you can reconcile or produce a Test Report.  
      - To post the transactions select the **“Post”** or **“Post and Print”** icon.  You will also be given the option of printing/emailing the pay advices from this function or you can choose to print/email them in bulk after the journal has been posted.  
      - After these processes have completed you can select to close the Pay Period.  
      - If more employees need to be paid or pay corrections are required then you must not close the Pay Period.  You can close the Pay Period later if you wish by selecting the **“Close Pay Period”** icon before you process your next Payroll.

At this point you have completed the payroll for the Pay Period. 

## 4.7	Payroll Journal Calculations
The following outline explains how the system processes employee pays.

1.    **The pay calculation function** uses the manually entered Pay Journal lines together with the parameters, allowances, and deductions set up for each employee and Payroll parameters to generate the Pay Journal lines that make up an employee’s pay.

2.    **Explode Gang** - For each Pay Journal Line for a Gang, the system creates the Pay Journal lines for each Employee in the Gang.  The Gang Employee table is used to locate the Employees who belong in the Gang for the nominated payroll during the period included in the document date.

3.    **Check Employee Eligible for Pay:** For each Employee on the Payroll the following steps are performed:
      - The Employee is checked to verify if they were terminated prior to this Pay Period.  If terminated, the Employee is not processed.
      - The Employee is checked to verify if they have already been paid up to the end of this period.  If already paid they are not processed.
   
4.    **Calculate Employee Rate** (Function of Calculate Pays): Using the Employee Classification Rate and the Classification Rate tables, calculate the Employee's current weekly rate.  The Classification Rate is date dependent and is calculated for each Pay Journal line for the Employee entered using the time entry process.

5.    **Add Allowances and Deductions** for the Employees in the Payroll:

6.    The Employee's Pay Advice header is checked 
      - To verify if the Pay Advice is the first advice for this Pay Period.  If it is not, then ordinary Pay Journal lines are not automatically generated.  
      - The Employee's Pay Advice header is checked for exclusion of permanent details.  
      - When permanent details are excluded, Allowance and Deduction are not processed.  
      - The Employee's Pay Advice header is then checked for the Number of times to add the Allowances and Deductions set up.  The units or the fixed value of the Allowance is multiplied by this amount. 
   
7.    **The Date** of the generated Pay Journal line is set to the end of period date.  

8.    **The Classification** of the generated Pay Journal line is copied from the Employee card.  

9.    **The Job No.,** Branch, Division, Department, and Project are copied from the Employee card.  

10.   **The transaction type** on the Pay Journal line is copied from the Employee Allowance or Deduction.

11.   **The units/hours** of the Pay Journal line are copied from the Employee Allowance or alternatively the fixed value of the Allowance is copied. 

12.   **If the Allowance or Deduction** is not for a fixed value, and then the rate of the Pay Journal line is calculated.  The Transaction Type is checked to determine if there is a fixed rate which is used instead.  If the transaction type is not for a fixed rate then the Employee's Classification Weekly Rate is calculated for the date of the Pay Journal line.  The transaction type is checked to determine if any Over Award Rate exists.  The hourly rate is then determined using the hour's basis of the Pay transaction type.

13.   **The conversion factor** is then applied to the Pay Journal line.  The conversion factor is taken from the Pay transaction type.  The hourly rate is multiplied by the conversion factor in order to obtain the Pay rate for the Pay Journal line.  The journal line amount is calculated by multiplying the derived pay rate by the units entered in the pay journal line 

14.   If the Pay Journal Line has **Associated Transactions**, then these are created. 

15.   **If the Award** the employee is paid under has Award Associated Transaction, and then these are created.

16.	Superannuation Calculation: 
        - Each employee is examined to determine if superannuation contributions are calculated.  If the employer superannuation contribution is subject to a minimum salary check, this is performed.  An employer contribution is only calculated when the employee has earned enough to satisfy this requirement.
       - Employees that have nominated personal contributions to superannuation are processed.
       - All fixed value contributions are multiplied by the number of deduction periods set up on the pay advice header. 
    
17.	Tax Instalment Deduction Calculation:
      - The tax calculations conform to the requirements of the "Statement of Formulae for calculating Income Tax Instalments" from the Australian Taxation Office.
      - The manually entered and system created Pay Journal Lines are checked to determine the gross taxable income applicable for this pay advice.  The gross taxable income on any previously posted pay advices are also taken into account and the tax instalment for the pay advice is calculated.
