Tax Scales
The Tax Scales card displays the coefficients used to calculate employee PAYG tax determined by the Australian Taxation Office (ATO).  The full details can be obtained from the ATO.

The current Tax Scale coefficients are provided when the Payroll granule is installed and are supplied as a text file when the rates change.    The Rates are date effective and may be imported when received.

Note This service is only available to clients who pay their Annual Software Subscription for the Payroll Granule.

To open the Tax Scales window

Departments/Payroll/Setup/Payroll Setup/Tax/Tax Scales
 

Field	Comments
Date Effective	This is the date which this scale comes into effect.
No.	This value is the tax scale number assigned by the ATO for the calculation of PAYG.
Name	This is the Tax scale name assigned by the ATO.



 


10.4.1.1	Tax Scales – General FastTab
This tab is used to identify the Tax Scale and the date the levy comes into effect.  

Field	Comments
Type	This field determines the type of tax applied:
•	Standard
•	HELP
•	SFSS
•	HELP & SFSS.
  
When a value is selected the relevant coefficients are displayed.
Date Effective	The date which this scale comes into effect.
No.	This value is the tax scale number assigned by the ATO for the calculation of PAYG.
Name	Tax scale name assigned by the ATO.
Rounding Method	This field displays the rounding method: Pre-2000, Up, Down, Nearest.

 

10.4.1.2	Tax Scales – Tax Scale Subform FastTab

Field	Comments
Minimum Weekly Rate	If an employee’s weekly earnings are less than this value the associated coefficients are applied.
Co-efficient A	Multiplication coefficient supplied by the ATO
Co-efficient B	Subtraction coefficient supplied by the ATO

All tax calculations are performed on a weekly basis and then extended to the normal pay period, i.e. fortnightly, monthly, etc.

 

10.4.1.3	Tax Scales – Medicare Levy Adjustment FastTab
The records in the Medicare Adjustment tab are used to calculate the amount of Medicare Levy Adjustment (MLA)

Each Tax Scale requires fields for the MLA calculation for low-income earners.

The entries are used to calculate the amount of MLA.  The MLA is applicable to low-income earners and employees with declared dependants who are paid on tax scale 2, 6, or 7.  The calculated MLA amount is used to reduce the tax instalment.

To receive a reduction in tax instalments the employee must complete a Medicare Levy Variation Declaration form obtained from the ATO (Reference: NAT 929-5.97).

Field	Comments
Earnings Threshold	This field is used to determine if an employee is eligible to receive the MLA.
Earnings Shade-In Threshold	This field (ESIT) is used to determine if an employee is eligible to receive a MLA.
Medicare Levy Family Threshold	This field is used to calculate the Weekly Family Threshold (WFT).  The WFT is used to determine if an employee is eligible to receive a MLA.
WFT Divisor	This field is used in conjunction with the Medicare Levy Family Threshold.  
Additional Child	This field is used in calculating the WFT.  
SOP Multiplier	The “SOP Multiplier” (Shade Out Point Multiplier) is used in calculating the SOP.  
SOP Divisor	The “SOP Divisor” (Shade Out Point Divisor) is used in calculating the SOP.  
WLA Factor	The “WLA Factor” is used in calculating the MLA.  
Medicare Levy	This field is used in calculating the MLA.  


