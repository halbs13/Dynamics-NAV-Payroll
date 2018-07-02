10.10	Post Leave Accruals Only Flag
This field is in the Payroll Setup  option card and is used to determine the method for posting leave accruals to the General Ledger.

To access this option click:

Departments/Setup/Payroll Setup/ Payroll Controls/Payroll Setup/Options tab 
•	Option 1 The employee’s taken leave is posted directly to the leave provision General Ledger account during payroll processing.  The employee leave accruals is posted to the leave provision and leave expense General Ledger accounts during the “Calculate Leave Accruals” process. 

•	Option 2 The” net” value of taken and accrued leave is posted to the leave provision and leave expense accounts during the “Post Leave Accruals” process

10.10.1	Option 1 “Post Leave Accruals Only” is “SELECTED” 
Leave taken is posted directly to the “Leave Provision” account during payroll processing.  The employee leave accruals are posted to the leave provision and leave expense accounts during the “Post Leave Accruals” process

Note: The General Ledger transaction Posting Group on the Leave Taken Pay transaction type must be the “Leave Provision” General Ledger account.

Journal Examples:

Employee Details
            Employee Salary net of Super     $54600.00
            Hourly Rate                               $      26.25
            Monthly Salary                           $ 4550.00

            Monthly Leave Accrual Hours      13.33

Payroll Processing Journal
Activity / Transaction	DR	CR	GL Account
Ordinary Hours	4130.00		Gross Salary 8724
2 days Annual Leave	  420.00		Leave Provision 5844
Tax		1550.00	Tax 5810
Net pay		3000.00	Wages Clearing 5845

Post Leave Accruals at month end    (Based on 13.33 hrs * $26.25 = $349.91)      
Activity / Transaction	DR	CR	GL Account
Leave Expense	349.01		Leave Expense 8744
Leave Accrual		349.91	Leave Provision 5844
10.10.2	Option 2 “Post Leave Accruals Only” is “BLANK” 
The net value of the employees taken and accrued leave is posted to the leave provision and leave expense General Ledger accounts during the “Post Leave Accruals” process. 

Note: The General Ledger account on the Annual Leave taken pay transaction type must be the “Gross Salary” General Ledger account

Journal Examples:
Employee Details
            Employee Salary net of Super     $54600.00
            Hourly Rate                               $      26.25
            Monthly Salary                          $   4550.00
          
  Monthly Leave Accrual Hours      13.33

Payroll Processing Journal
Activity / Transaction	DR	CR	GL Account
Ordinary Hours	4130.00		Gross Salary 8724
2 days Annual Leave	  420.00		Gross Salary 8724
Tax		1550.00	Tax 5810
Net pay		3000.00	Wages Clearing 5845

Post Leave Accruals at month end    (Based on 13.33 hours - 2.67 * $26.25 = $70.09)      

Activity / Transaction	DR	CR	GL Account
Leave Expense	70.09		Leave Expense 8744
Leave Accrual		70.09	Leave Provision 5844
