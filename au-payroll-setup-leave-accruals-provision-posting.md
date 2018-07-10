# Leave Accrual Posting

Posting Leave Accrual Provisions is a process located in the End of Month menu option.  

To Calculate and Post Provisions, go to the following menu: *Payroll/EOM Processing/ Leave Processing/Calculate & Post Provision*.

You must select the **Payroll** you wish to use to Post Leave accruals to the General Ledger.

Once you have selected the Payroll the Calculate Leave Provisions card is displayed.

Depending on the filters selected the report will print:

|Field|Description|  
|:---------------------------------|:---------------------------------------|  
|**Sorted by Leave Type / Leave Code**|
|**Employee**|
|**Previously Posted Amount**| If this process was ran in period sequence (Jan. Feb, March etc each month after all Pay Journals were posted and the period finalised) the amount will equal the amount of the Provision Amount on the previous Calculation of Leave Provision report.  
|**Provision Amount**| Remaining Amount + Leave Loading Value + OnCost Value.
|**Amount to Post to GL**| Remaining Amount + OnCost value.
|**Value of Leave**| Remaining Amount.
|**Leave Loading Value**| Value of Leave Loading.
|**Value of On-Costs**| The Remaining amount x On Cost %.

The report totals the above columns for each Leave Type and produces a summary page for posting:

|Field| 
|:---------------------------------|
|Account No
|Document Date
|Department Code (Global Dimension 1)
|Project Code (Global Dimension 2)
|Previously Posted Amount
|Provision Amount
|Amount to Post to GL

The report totals the last 3 columns by GL Account and prints the Totals Debits and Total Credits
 




