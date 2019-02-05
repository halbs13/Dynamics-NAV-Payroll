# To setup Tax Scales

The Tax Scales card displays the coefficients used to calculate employee PAYG tax determined by the Australian Taxation Office (ATO).  The full details can be obtained from the ATO.

The current Tax Scale coefficients are provided when the Payroll granule is installed and are supplied as a text file when the rates change.    The Rates are date effective and may be imported when received.

**Note: This service is only available to clients who pay their Annual Software Subscription for the Payroll Granule.**

1. In the **Search** box, enter **Tax Scales**, and then choose the related link, or go to the following menu: *Tax Setup/Tax Scales*

2.  To view an existing record, double click one of the records.   
  
|Field|Description|  
| :--- | :--- |
|**Date Effective**|This is the date which this scale comes into effect.|
|**No.**|This value is the tax scale number assigned by the ATO for the calculation of PAYG.|
|**Name**|This is the Tax scale name assigned by the ATO.|

3.  On the **General** FastTab of the **Tax Scale** window, review the fields as described in the following table.
  
|Field|Description|  
| :--- | :--- |
|**Type**|This field determines the type of tax applied.  The options available are: Standard, HELP, SFSS, HELP & SFSS.  When a value is selected the relevant coefficients are displayed.|
|**Date Effective**|This is the date which the tax scales comes into effect.|
|**No.**|This value is the tax scale number assigned by the ATO for the calculation of PAYG.|
|**Name**|This is the Tax scale name assigned by the ATO.|
|**Rounding Method**|This field displays the rounding method:  Pre-2000, Up, Down, Nearest.|
  
4.  On the **Tax Scale Subform** FastTab, reivew the fields as described in the following table.

|Field|Description|  
| :--- | :--- |  
|**Minimum Weekly Rate**|If an employee’s weekly earnings are less than this value the associated coefficients are applied.|
|**Co-efficient A**|Multiplication coefficient supplied by the ATO.|
|**Co-efficient B**|Subtraction coefficient supplied by the ATO.|

5.  On the **Medicare Levy Adjustment** FastTab, reivew the fields as described in the following table.

|Field|Description|  
| :--- | :--- |
|**MLA**|Each Tax scale requires fields for the MLA calculation for low-income earners. The entries are used to calculate the amount of MLA.  The MLA is applicable to low-income earners and employees with declared dependents who are paid on tax scale 2 or 6.  The calculated MLA amount is used to reduce the tax instalment. To receive a reduction in tax instalments the employee must complete a Medicare Levy Variation Declaration form obtained from the ATO (Ref: NAT 929-5.97)|
|**Earnings Threshold**|This field is used to determine if an employee is eligible to receive the MLA.|
|**Earnings Shade-In Threshold**|This field (ESIT) is used to determine if an employee is eligible to receive a MLA.|
|**Medicare Levy Family Threshold**|This field is used to calculate the Weekly Family Threshold (WFT).  The WFT is used to determine if an employee is eligible to receive a MLA.|
|**WFT Divisor**|This field is used in calculating the WFT.|
|**SOP Divisor**|The “SOP Divisor” (Shade Out Point Divisor) is used in calculating the SOP.|
|**WLA Factor**|The “WLA Factor” is used in calculating the MLA.|
|**Medicare Levy**|This field is used in calculating the MLA.|

To learn more about [Importing Tax Scales](au-payroll-setup-import-tax-scales.md)

[GoToTop](#to-setup-tax-scales)
