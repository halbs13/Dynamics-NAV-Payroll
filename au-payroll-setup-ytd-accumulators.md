# To setup YTD Accumulators

YTD accumulators, accumulate YTD values for Gross, Tax, Lump Sums, Allowances and Deductions.  The values accumulated are
then used to print Payment Summaries, Pay Advices, and reports.  The YTD Accumulator codes are assigned to Pay Transaction Types.  A Pay Transaction Type can have only one YTD accumulator at any one time. 

The YTD accumulations also determine the layout for the Payment Summaries for Taxation.

1.  To access the YTD Accumulations, go to the following menu: *General Setup/YTD Accumulations*

2.  To create a new record, click on the **New** button.
  
|Field|Description|  
| :--- | :--- |
|**Code**|This field is used to identify the YTD accumulation code and used to assign to a Pay Transaction Type code.|
|**Short Description**|This field provides an abbreviated description.|
|**Description**|This field provides for a fuller description.|
|**Payment Summary Box**|This field is used to determine where the value is to be printed on the Payment Summary. It is important that the setup is correct before Payment Summaries are printed, otherwise the values will be printed in the wrong positions. If nothing is set, the value will not print on the Payment Summary.|
|**Payment Summary Line**|This field is used to determine the line in the Payment Summary box the value is printed on. The line number is always set to zero if no box number is set. For items to be printed, the line number should always be set to 1, except for the box “Lump Sums”. For “Lump Sum” allowances the line number should be set to 1, 2, 3, 4 or 5 corresponding to the lump sum allowances A, B, C, D, or E. Note:  Lump Sum C will create an Employee Termination Payment Summary (ETP).|
|**Accumulation Summary Type**|This field must either be Gross, Deduction, Advance, Tax or Net.|
|**Not Printed On Pay Advice**|A checkmark in this field prevents this accumulation from printing on the pay advice.|
|**PS. Net Change**|This field is an accumulation of all pay transaction types excluding superannuation that has been assigned to this YTD Accumulator. This field shows the total of this YTD Accumulation code that will print on the Payment Summaries.|
|**PS. Net Superannuation**|This field is an accumulation of all pay transactions for superannuation that have been assigned to this YTD Accumulation code. This field shows the total of this YTD Accumulation code that will print on the Payment Summary if required.|
|**Non PS. Net Change**|This field is an accumulation of all pay transaction types, excluding superannuation that is assigned to this YTD Accumulation code.  This field shows the total of this YTD Accumulation code that will not print on the Payment Summary.|
|**Non PS Net Superannuation**|This field is an accumulation of all pay transaction types that are for superannuation that are assigned to this YTD Accumulation code.  This field shows the total of this YTD Accumulation code that will not print on the Payment Summary.|

3.  Click on the **OK** button after you have completed your selection.

