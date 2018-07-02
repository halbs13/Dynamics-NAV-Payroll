Leave Accrual Posting
Posting Leave Accrual Provisions is a process located in the End of Month menu option.  

To Calculate and Post Provisions open Payroll/EOM Processing/ Leave Processing/Calculate & Post Provision.

You must select the Payroll you wish to use to Post Leave accruals to the General Ledger.

Once you have selected the Payroll the Calculate Leave Provisions card is displayed.
Depending on the filters selected the report will print:
•	Sorted by Leave Type / Leave Code
•	Employee
•	Previously Posted Amount - If this process was ran in period sequence (Jan. Feb, March etc each month after all Pay Journals were posted and the period finalised) the amount will equal the amount of the Provision Amount on the previous Calculation of Leave Provision report.  
•	Provision Amount = Remaining Amount + Leave Loading Value + OnCost Value
•	Amount to Post to GL = Remaining Amount + OnCost value
•	Value of Leave - Remaining Amount
•	Leave Loading Value = Value of Leave Loading
•	Value of On-Costs = The Remaining amount x On Cost % 

The report totals the above columns for each Leave Type and produces a summary page for posting:
•	Account No
•	Document Date
•	Department Code
•	Project Code
•	Previously Posted Amount
•	Provision Amount
•	Amount to Post to GL
The report totals the last 3 columns by GL Account and prints the Totals Debits and Total Credits
 
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


10.11	Pro Rata Leave Calculation Methods
The system calculates pro-rata leave using 2 different methods:
1.	Pro-Rata Calculation
2.	Pro-Rata Days Worked (pro-rata hours worked). 

10.11.1	Pro-Rata Calculation 
This method is used to calculate an amount based on the employees standard hours every period regardless of the number of hours the employees are paid.  

The system can be flagged to calculate either a flat rate accrual each period or calculate a daily accrual and multiply the daily amount by the number of days in the pay period.

Example:
Annual leave = 20 days per year  
Employee standard work hours are 40 hours each week / 173.33 hours month.

The employee accrues 0.054945 days per 7 days for the pay period regardless of how many hours are actually worked.
1.	You can set up to calculate a daily accrual, and then multiple it by the number of days within the pay period, such as 31 for January, 28 / 29 for February, 31 for March, etc.  
2.	Alternately, you can calculate a flat accrual for each pay period, such as 20 / 12 = 1.666667 days each month every month.
3.	The pro-rata leave can be setup to recalculate each pay period.  Each period leave is re- calculated from the employee's last leave anniversary date, based on the leave accrual start date, to the end of the current pay period.  The system will only keep one open pro-rata leave transaction, which is the total for the current anniversary leave period. 
4.	Alternately you can setup the system to only calculate the portion of the leave for each pay period.  The system has an open leave transaction for each pay period accrued within the current anniversary leave period.
To configure part time employees:
1.	The "Hours in a Full Week" field on the Payroll Employee’s card must equal the number of hours the employee works in a week (E.g. 32).
2.	The "Days per Week" field on the payroll employee card must equal the number of days worked (E.g. 4).
3.	The "Ratio by Days per Week" field on the Employee Leave Accrual card must be ticked to reduce the employees leave accrual by 1/5 (E.g. 1 day).  
Example
Weekly Accrual = (Full Week Accrual (0.384615) * Days per Week (4) / 5) = 0.307692
Hours per Leave Day = (Hours in Full Week / Days per Week) = 8

10.11.2	Pro-Rata Time Worked (Must be used if Leave is based in Hours)
The pro-rata days worked method is based upon the number of hours an employee actually worked within the pay period.

Example:
Annual Leave = 20 days per year  
Employee standard work hours are 40 hours each week / 173.33 hours month.
1.	If the employee works 40 hours then the accrual will be 0.3846 days for the week.
2.	If the employee works 20 hours then the accrual will be 0.1923 days for the week.

You must have all the Pay Transaction Types set-up correctly on the "Leave Application" tab
The "Accum. For Leave Calculations" field must be set to 'Accumulate" for all transactions that accrue leave such as Ordinary time, Annual leave, Sick leave, LSL etc.  

This field must be set to 'No Accumulation' for transaction types that do not accrue leave such as allowances, deductions, LAHA, and overtime.

Note When only one leave accrual is set-up for a Leave Type the "Hours in a Full Week" and "Days per Week" fields on the Payroll Employee card must all have the same values entered for part time and full time employees.  You cannot enter individual employees standard hours and days.  
In the example above every employee will have 40 "Hours in a Full Week" and 5 "Days per Week".  

The system uses these fields to determine the full accrual used for the calculation.  

Alternatively, you must set up a leave accrual for each employee with different hours and days per week combination.

To configure part time employees:

No special procedure is required as the accrual is based on hours worked and the pay transactions flagged to accrue leave.  If the employee is only paid 30 hours per week they will accrue leave based on the 30 hours.  

 
