# Single Touch Payroll Upgrade

## Upgrade Checklist

Use the checklist below in conjunction with the notes to ensure all required steps have been completed.

|Step No.|	Task Description	Done|
|---|---|
|1.		|Superannuation Transaction Type Code
||Confirm the Pay Transaction Type Code for Superannuation
||*Payroll/Setup/Payroll Setup/Payroll Controls/Payroll Setup* 	
|2.|		Update YTD Accumulation for Superannuation (SGC)
||Update the P.S. YTD Accumulation Code to GROSS
||*Payroll/Setup/Payroll Setup/General/Pay Transaction Types*
|3.|		Single Touch Upgrade
Upgrade Payfocus and enter the date you will start using STP
Payroll/Periodic Activities/Periodic Maintenance/Single Touch Upgrade 	
|4.|		Update Payroll Setup
||Specify your STP Sending Service Provider
||*Payroll/Setup/Payroll Setup/Payroll Controls/Payroll Setup*
|5.|		Payroll User Setup
||Update the Payroll Users so they can create Pay Events/Update Events
||*Payroll/Setup/Payroll Setup/Payroll Controls/Payroll User Setup*	
|6.|		YTD Accumulations
||Update the STP Allowance Type Codes
||*Payroll/Setup/Payroll Setup/General/YTD Accumulations*	
|7.|		STP Message Structure
||Import the STP Message Structure required by the ATO
||*Payroll/Setup/Payroll Setup/Single Touch/STP Message Structure*
|8.|		Employee Types
||Update the Basis of Payment field on Employee Types
||*Payroll/Setup/Payroll Setup/General/Employee Types*


## Superannuation Type Code
You need to confirm which transaction type code is used for Superannuation.
Go to:

 *Payroll/Setup/Payroll Setup/Payroll Controls/Payroll Setup* 

 

## Update YTD Accumulation for Superannuation (SGC)

You now need to update the YTD Accumulation for the code located in the previous step e.g. 6000 so that the SGC values are correctly reported in a STP Pay Event/Update Event.
Go to:

*Payroll/Setup/Payroll Setup/General/Pay Transaction Types*

Select the transaction type code you located in the previous step.
Go to the P.S. YTD Accumulation Code field and select GROSS from the drop down option list and then select OK.

 

## Single Touch Upgrade

You only need to run the upgrade process once, it tells Dynamics NAV (Payfocus) when you are going to start using STP.

Go to:

*Payroll/Periodic Activities/Periodic Maintenance/Single Touch Upgrade*

Enter the date you will go live with STP and select OK. It may take a few moments for this process to run. If you do not enter in a date the system will default to 1st July 2018.

Please note this process may take a few minutes to complete.

 

Once this has been performed you need to specify which Sending Service Provider (SSP) your organisation will use to submit your STP Pay Events and Update Events, this will be added to the declaration you make when creating a Pay Event or Update Event.

Go to:

*Payroll/Setup/Payroll Setup/Payroll Controls/Payroll Setup*

On the Single Touch Payroll tab enter in your STP Sending Service Provider Name and select OK.

 
 
## Payroll User Setup

The ATO requires you to be identified when submitting Pay Events and Pay Updates so you must setup the unique identifiers in Payroll User Setup.

Go to:

*Payroll/Setup/Payroll Setup/Payroll Controls/Payroll User Setup*
 

In the ABR Credential ID/Payer Declarer Identifier field you must enter a unique identifier for each Payroll User that will be required to create a Pay Event and/or Update Event e.g. Full Name or Email Address.

If this is not populated the Payroll User will not be able to create Pay Events or Update Events.


## YTD Accumulations

You now need to populate the STP Allowance Type Codes so the allowance information is passed on to the ATO correctly.

You will need to specify all Allowances with a STP Allowance Type Code, the options are:

- Car (Car expense allowance)
- Transport (Award transport payments up to reasonable amounts)
- Laundry (Laundry allowances)
- Meals (Award overtime meal allowance)
- Travel (Domestic or overseas travel allowance above the reasonable limit and all overseas accommodation allowances)
- Other (All other allowances for expected deductible expenses)

Go to:

*Payroll/Setup/Payroll Setup/General/YTD Accumulations*

Review all the YTD Accumulations that have Allowances set under Payment Summary Box and select the relevant STP Allowance Type Code.


## Employee Types

With the introduction of Working Holiday Makers in 2017 modifications were made within Payfocus to cater for changes that need to be reported differently on the Payment Summaries and now with a Pay Event within STP. Go to:

*Payroll/Setup/Payroll Setup/General/Employee Types*

Ensure that your Employment Basis and Basis of Payment fields match i.e. Employment Basis Full Time should be Basis of Payment Full Time as shown below.

 
## STP Message Structure

This area holds the information about the setup of the STP files uploaded to the ATO. This next step must be completed prior to creating Pay Events.

Two text files were sent with the release notes for HotFix 33, PAYEVNT.0003 Import File.csv and PAYEVNTEMP.0003 Import File.csv and these should be saved into a folder on your PC or network prior to the next step.

Go to:

*Payroll/Setup/Payroll Setup/Single Touch/STP Message Structure*

Select OK.
 

Browse to the location on your PC or server where you saved the two files previously mentioned above.

Select PAYEVNT.0003 Import File.csv and select Open



Browse to the location on your PC or server where you saved the two files previously mentioned above.
Select PAYEVNTEMP.0003 Import File.csv and select Open

[GoToTop](#single-touch-payroll-upgrade)

