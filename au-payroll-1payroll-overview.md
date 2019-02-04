# PAYROLL OVERVIEW

The Payroll granule is used to process an Australian payroll and calculate PAYG tax.

Payroll integrates with the General Ledger and Human Resource granules.  You can elect to not post Payroll to the General Ledger, but the separation of these granules is required for security.  

Employees must first be setup in Human Resources before you can set them up as Payroll Employees. 

The Payroll module integrates with other D365 Business Central modules such as Purchases and Payables, Sales and Receivables, Job Costing, and General Ledger.

Payroll has numerous parameters that can be customised to suit your own business process to provide maximum flexibility.  Defaults for most of these parameters are created when the Payroll is first installed.  Payroll processing cannot commence until setup is completed in the correct sequence.

An essential step of the setup is creating the [Pay Transaction Types](au-payroll-setup-pay-transaction-types.md) which are used by the system for recording and calculating pays.  Examples of these transactions are Ordinary Time, Overtime, Deductions, Superannuation, Tax, and Net Pay.

The system allows flexibility as to how these transactions affect other areas of the system, such as whether to include for leave accrual, whether to apply before or after tax, etc.

Defined Pay Transactions are used in many parts of system setup, including; superannuation defaults, leave entitlements, award classifications, and time in lieu. 

Other setup information in the Payroll granule includes [Coinage Denominations](au-payroll-setup-denominations.md), Payment Summary, [Bank Accounts](au-payroll-setup-pay-bank-state-branches.md), [General Ledger Postings](au-payroll-setup-posting-group-setup.md), [Work Care Contributions](au-payroll-end-of-month-processing-work-cover.md), [Employee Types](au-payroll-setup-employee-types.md), [Pay Locations](au-payroll-setup-payroll-codes.md), [Shifts](au-payroll-setup-shift-roster.md), [Employee Positions](au-payroll-setup-payroll-codes.md), [Branches, Divisions](au-payroll-setup-branches.md), [Tax Scales](au-payroll-setup-tax-scales.md), etc.

Information must be setup in the other NAV granules with which the Payroll is integrated to. An employee’s pay is processed when the payroll that employee is assigned to, is posted.

Many parameters are set up to determine frequency of pay, Pay Period Dates, and Coinage denominations available for paying cash employees and information that will optionally appear on reports and pay slips for that payroll.  

Employees are entered into the system and associated with their Award Classifications, Leave Allowances, Tax Scales, Payroll, Pay Location, Employee Type, Permanent Allowances, Permanent Deductions, Pay Method, etc.

The following is a non-exhaustive list of additional functions of this Payroll granule.

•	[Timesheet Entry](au-payroll-processing-pay-time-sheet-processing.md)

•	[Payroll Generation](au-payroll-processing-payroll-processing.md), & [Back Pay Processing](au-payroll-periodic-activities-back-pay-calculations.md)

•	[Pay Advice](au-payroll-report-print-email-pay-advices.md), & [Payment Summary Printing](au-payroll-end-of-year-processing.md)

•	Electronic File Production for Bank Transfer & ATO Employment Declarations

•	[Superannuation](au-payroll-end-of-month-processing-superannuation.md) & [State Payroll Tax reporting](au-payroll-end-of-month-processing-payroll-tax.md)
