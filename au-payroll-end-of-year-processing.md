# END OF YEAR PROCESSING
A number of Payroll activities must be performed annually or on request. Transactions entered into the Payroll granule during the Tax Year are used to create the:
* Payment Summaries and Australian Taxation Office (ATO) Electronic Payment Summary (EPS) file. 
* Employer Termination Payment (ETPs) Summaries - generated using data entered against employees when they are terminated.
The Payment Summaries and Employment Termination Payment summaries are printed on plain paper with a laser printer using the Australian Tax Office (ATO) approved layout.   The Payment Summary details are generated into a data file.

**Note:** Income tax legislation states when plain paper is used to print employee Payment Summaries the Payment Summary details must be lodged with the ATO using Electronic media. The Payment Summaries meet the requirements of the ATO Self Printing PAYG Payment Summaries Specification Version 5.1. The Individual Non-Business Payment Summary prints 1 copy in either Full Page or Z-Folded format. The Electronic Reporting File Structure has been updated to Specification Version 12.0.

After the Payment Summary is generated the employer and employee pay transactions are flagged; ”Payment Summary Raised” in the Payroll Employee card until the first pay run for the new fiscal year. 

The values printed on the Payment Summaries are taken from the YTD Accumulators. If the YTD accumulators on Pay Transaction Types were not setup correctly or changed during the fiscal year you must:
*	Correct the Pay Transaction Type 
*	Update the YTD Accumulators values prior to printing the Payment Summaries. 

The EOFY Payment Summaries menu option is used to:
*	Print the Payment Summary Proof List 
*	Print the Payment Summaries 
*	Print Employment Termination Payment Summaries
*	Produce the ATO EPS file.  
 
 
## Payment Summary Processing Steps
1.	Enter Employment Termination Payments (ETPs) for your Terminated employees. 

Departments/Payroll/Employee Maintenance/Payroll Employee card/Navigate ribbon/ Employment Termination Pay card

2.	Enter Fringe Benefits (FBT) Gross amounts for your Employees. 

Departments/Payroll/Employee Maintenance/Payroll Employee card/Tax tab/Fringe Benefit Amount field.

3.	Run the “Payment Summary Proof List” without producing the Payment Summaries or ATO file and then reconcile the employees YTD values against the Posted Payment Summary report

4.	Once you have reconciled the Payroll you must produce the Payment Summaries together with any Employment Termination Payment Summaries and the ATO EPS file.  
  
Payment Summaries may be re-printed at any time and will indicate that they are amended on the top of the page.  

 
## YTD Accumulator Code Update 
The Pay Transaction Types paid to employees are accumulated to Payment Summary YTD Accumulation codes. The codes are used to accumulate YTD amounts reported on the employee’s payment summary.  
 
Only Pay Transaction Type codes that have an YTD Accumulation code assigned on the General tab are printed on the Payment Summaries.

When the Payment Summary YTD Accumulation code has not been correctly applied to the Pay Transaction Type you must correct the PS YTD Accumulation code assigned to the Pay Transaction and then run the YTD Accumulation Code Update to update the values in the Employee Ledger table.  

You must select the Tax year and then click “OK” 

When you have finished you can continue End of Year Processing

Departments/Payroll/EOFY Processing/End of Tax Year/YTD Accumulation Code Update
 
Run this report to update any changes made in the YTD Accumulation for Payment Summaries of any Pay Transaction Types. Running the report updates YTD figures according to new settings made.
  
 
## Payment Summary Proof List Overview
The same menu option is used to:

*	Print the Payment Summary Proof List
*	Print the Payment Summaries
*	Print the ETP Summaries
*	Create the Electronic ATO file.  

The Proof List can be printed without printing the Payment Summaries by leaving the “Print Payment Summaries” field un-ticked on the option tab.  

The Proof list can be run unlimited times until you are satisfied with the amounts to print on the employee payment summaries and in the corresponding ATO EPS file.

The “Payment Summary Proof List” is designed to assist you in balancing your Payroll for the Taxation year.  You can select parameters (filters) to assist you in the balancing and checking of the Payment Summaries.  The Proof List prints errors and warnings that must be corrected before the Payment Summaries and ATO EPS files are produced. 

Note: Depending on the type of error produced the process will not continue.  For example, if Payroll Company information is missing the process will stop; if employee information is missing the process continues.

Payment Summaries are not produced for employee with an” Incorporated Company” type select in the Payroll Employee card - Employee Type Code.  These employees are still printed on the “Payment Summary Proof List” to assist with the End of Year (EOY) reconciliation process.
Note:  If an employee has been employed under several different employment types during the same tax year a payment summary is produced for each type unless the employee has also had Salary Sacrifice deductions.  In this case the Payment Summaries must be produced manually.  The values of the payments will be shown on the “Payment Summary Proof List” with a warning message to this effect.

A “Payment Summary Proof List” is always printed, by default, when selecting the “Print Payment Summaries” option. This is used to provide proof of the values printed on the Payment Summaries supplied to the ATO.


## Payment Summary Proof List 
 To open the “Payment Summary Proof List” window,

Departments/Payroll/EOM Processing/Reconciliation Reports/Payment Summary Proof List

Once you have selected the report, a request form will appear with the following options:

*	Normal Processing – this will print the Payment Summary Proof List Report only
*	End of Tax Year processing – this will print the Payment Summary Proof List Report and options to print PAYG Payment Summaries.

Select “Normal processing”
 

#### Payment Summary Proof List – Options FastTab
| Field	|Comments|
|---|---|
|Tax Year|	Select the Tax Year you wish to reconcile and report

#### Payment Summary Proof List – Payroll FastTab
|Field	|Filter|
|---|---|
|Only the standard fields are covered.  A full list of fields available as filters can be used by selecting the first blank line and selecting the “ArrowDown”.|
|No.	|Select a Payroll(s) to use as a filter to limit the employee’s printed.
||If left blank all Payroll(s) will print|

#### Payment Summary Proof List – Payroll Employee FastTab
|Field|	Filter|
|---|---|
|Only the standard fields are covered.  A full list of fields available as filters can be used by selecting the first blank line and selecting the “ArrowDown”.|
|Employee No.|	Select an Employee No(s) to use as a filter to limit the employee’s| 
||If left blank all Employee Payment Summaries details for the selected Payroll(s) will print.|
|Employee Type Code|	Select an Employee Type Code(s) to use as a filter to limit the Payment Summaries details to print| 
||If left blank all Employee Types for the selected Payroll(s) will print.|

Reconcile this report to the Posted Payroll Summary Report and General Ledger until you are satisfied.


## Overview Payment Summary and the PAYG EPS ATO File 
The same menu option is used to print the Payment Summary Proof List, Payment Summaries, and the ETP’s and to create the Electronic ATO file.  

There are five types of Payment Summaries that can be produced.
  
1.       Individual Non-Business.
2.       Labour Hire 
3.       Personal Services 
4.       Voluntary Agreement 
5.       Employment Termination Payment. 

The EOTY Payment Summaries menu option automatically prints the correct Payment Summary Type for each employee when the process is run.  Employees receive the type of Summary based on their “Employee Type Code” on the Payroll Employee card - General tab. The Employee Type code is assigned an “Employment Basis” which determined the type of Payment Summary
Payment Summaries are not produced for employee with an” Incorporated Company” type.  

The payment Summaries cannot be previewed; you must print the Payment Summaries. 

The Payment Summaries are printed to your MS Windows default printer.  If the Payment Summaries must be printed to a different printer other than your default printer then set the other printer as your default windows printer before printing the payment summaries.

**Note:**  If an employee has been employed under several different employment types during the same tax year a payment summary is produced for each type unless the employee has also had Salary Sacrifice deductions.  In this case the Payment Summaries must be produced **manually**.  The values of the payments will be shown on the “Payment Summary Proof List” with a warning message to this effect.

A “Payment Summary Proof List” is always printed, by default. This is used to provide proof of the values printed on the Payment Summaries and supplied to the ATO.
The name of the ATO EPS file is automatically populated as a default.  You must indicate the path where the file is to be placed by entering the path location or navigating to the required directory.  If no Path is present then the file will be written to the NAV client directory on your PC.

**Note:**  Employment Termination Payment (ETP) summaries are produced automatically during the Payment Summary process if you have entered the employees ETP details on the Payroll Employee card/Navigate ribbon/Employment Termination Pay card. 


### Print Payment Summary, ETP and Create the PAYG ATO File 
Use this option to produce your Payment Summaries, ETP Summaries and the ATO EPS file:

Departments/Payroll/EOFY Processing/End of Tax Year/EOTY Payment Summaries
Once you have selected the report, a request form will appear with the following options:

* Normal Processing – this will print the Payment Summary Proof List Report only
*	End of Tax Year processing – this will print the Payment Summary Proof List Report and options to print PAYG Payment Summaries.

 

Click “End of Tax Year Processing”


#### Payment Summary Proof List – Options FastTab
|Field	|Comments|
|---|---|
|Tax Year|	Select the Tax Year you wish to create Payment Summaries, and  ETP’s and the ATO EPS file| 
|Print Payment Summaries|	Select this field to print the Payment Summaries, ETP’s and produce the ATO EPS file.|                    ||The Employee and their transactions are flagged as “Payment Summaries printed”| 
|E-Mail Payment Summaries|	Select this field to e-mail out payment summaries to an employees.|  
||As a prerequisite, the e-mail address must be completed on the Employee Card.|
|Date|	This date prints as the signatory date on the Payment Summary.  This date has no effect on the production or selection of the payment summaries.| 
|Authorised Person|	Use this field to enter the Authorised Person’s name registered with the ATO.  This field is printed on each Payment Summary.|  
||If left blank the Individual Payment Summary must be manually signed by the Authorised signatory from your organisation.|
|Include Printed|	Select this field to print previously printed Payment Summaries.|  
||This option is used to reprint Payment Summaries already printed for terminated employees or when an employee has misplaced the original. The payment summary will indicate that it is an amended copy.|
|INB or BPS PAYG Payment Summary Format|	Select one of the following options;
||•	Full Page – this is the full page format| which can be used to issue with standard window-faced envelopes
||•	Z-Fold – this is the z-fold format which can be used to issue with security sealed stationery.
|Do not Create Electronics File|	It is recommended that this field is blank when printing Payment Summaries to ensure your ATO EPS file always reflects the amounts printed on the Payment Summaries. | 
||**Note** This flag has been included for situations where you do not require an ATO EPS file.|
|File Name|	This field is used to enter the file path and name.  The default value in this field is the file name format required by the ATO. | 
||You must specify the file path where the file is to be created ; select the “EditAssist” button to specify the directory.|
||The default file name is “Empdupe.A01”.|  
||The “01” can be incremented manually when there is more than one Payment Summary print cycle.|
||When running the process for more than one payroll the process will automatically produce one file for each Payroll.|  
||The file extension (A01) will be automatically increment for each payroll file produced.|
|Run Type|	Select “Production” if you wish to produce a file to be sent to the ATO.|  
||Select “Test” only to send a test file to the ATO for clarification before creating the production file 
||Dialog has received confirmation for the layout from the ATO.
|Supplier File Reference|	This field is used by the ATO to further identify the file for enquiries from the ATO to you.|

#### Print Payment Summaries – Payroll FastTab
|Field|	Filter|
|---|---|
|Only the standard fields are covered.  A full list of fields available as filters can be used by selecting the first blank line and selecting the “ArrowDown”.|
|No.	|Select a Payroll(s) to use as a filter to limit the process to a specific payroll. |

||If left blank all Payroll(s) will print|

#### Payment Summary Proof List – Payroll Employee FastTab
|Field	|Filter|
|---|---|
|Only the standard fields are covered.  A full list of fields available as filters can be used by selecting the first blank line and selecting the “ArrowDown”|
|Employee No.	|Select an Employee No(s) to limit the process to 1 or more employee’s for the selected payroll(s)|
||If left blank all Employee Payment Summaries details for the selected Payroll(s) will print.|
|Employee Type Code|	Select an Employee Type Code(s) to use as a filter to limit the process to only a specific Employee Type |
|If left blank all Employee Types for the selected Payroll(s) will print.|

