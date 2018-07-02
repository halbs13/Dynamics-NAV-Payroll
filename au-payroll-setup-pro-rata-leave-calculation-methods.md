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

 
