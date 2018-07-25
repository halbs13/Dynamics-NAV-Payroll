# Single Touch Payroll Processing


- STP Message Structure
- STP Processing
- Pay Event
  - Updage Event
  - Pay Event EOTY Submission
- Viewing STP Sumbissions
- Resending STP Submissions
- STP Zero Submission


## STP Message Structure

This area holds the information about the setup of the STP files uploaded to the ATO. This next step must be completed prior to creating Pay Events.

Two text files were sent with these instructions PAYEVNT.0003 Import File.csv and PAYEVNTEMP.0003 Import File.csv and these should be saved into a folder on your PC or network prior to the next step.

Go to:

*Payroll/Setup/Payroll Setup/Single Touch/STP Message Structure*

Select OK.
 

Browse to the location on your PC or server where you saved the two files previously mentioned above.

Select PAYEVNT.0003 Import File.csv and select Open



Browse to the location on your PC or server where you saved the two files previously mentioned above.
Select PAYEVNTEMP.0003 Import File.csv and select Open

 
## STP Processing

The processing of the pay runs hasn’t changed. You just need to perform another step as part of your pay run process.

Once you have completed your pay run, you will then need to create a Pay Event.

Prior to running a Pay Event we strongly recommend you run the STP Payment Proof List and refer to the last page of the report which lists any errors that may cause the Pay Event to be rejected by the ATO. These errors are similar to those that you may have seen in prior years at EOTY e.g. invalid address, post code, etc.

If there are any errors they can be corrected prior to creating the Pay Event.

### Pay Event

Go to:

*Payroll/Single Touch Processing/Submit STP Pay Event*

For a new pay run you have just completed select New and OK.

This process will also create a Pay Event for any other outstanding pay runs that a Pay Event has not been already created.

 

Select Yes

 
Select Yes

Payfocus will now generate the file.

 

Once the file has been generated you will be prompted to Open, Save or Cancel.

  

Select Save. Make sure you save the file in a secure area of your network as the file contains sensitive information about your organisation and employees.

Upload the saved file to your portal of choice. Follow the provided “How To” instructions based on your SSP’s requirements.

If there are no pay runs ready for upload to the ATO or you have created all the relevant pay events you will receive the following message. Select OK.

 

### Update Event

Go to:

*Payroll/Single Touch Processing/Submit STP Event*

The update event allows you to provide corrections and revisions of YTD values for your employees. This event can include employees who are no longer being paid but whose YTD values need updating. It also allows you to declare that your employee’s EOTY data is complete.

To perform an update, select Update, enter the Update Date and select OK.

EOTY Submission should not be ticked at this stage, it is used to finalise your Tax Year (similar to creating your EMPDUPE file).

  

### Pay Event - EOTY Submission

If you have just completed your last pay run of the financial year and you have completed any relevant reconciliations you can advise the ATO through a Pay Event.

Go to:

*Payroll/Single Touch Processing/Submit STP Pay Event*

Select New and tick the EOTY Submission box and select OK
 
Select Yes



## Viewing STP Submissions

To see past submissions go to:

*Payroll/Single Touch Processing/STP Submissions.*

This page shows you all STP Submissions created.

You can review your submissions two ways:

1)	Choose the Submission Details option in the ribbon.
2)	Choose the Submission Employees option in the ribbon. If you want to view specific employee information you will need to select the relevant employee and select the Submission Employee Details option in the ribbon.

 

## Resending STP Submissions

If you need to replace the previously submitted Pay Event, go to:

*Payroll/Single Touch Processing/STP Submissions*

Select the Resend Last Pay Event option in the ribbon.

You may need to replace the pay event if it contained errors or significant corrupt data.

Tick Create File and select OK. 

Select Yes

Once the file has been created you will need to Save the file. Make sure you save the file in a secure area of your network as the file contains sensitive information about your organisation and employees.

Enter any relevant filter options as required, e.g. Payroll No. and select OK.

Select Yes

Select Yes

Payfocus will now generate the file as shown below.

Once the file has been generated you will be prompted to Open, Save or Cancel.

Select Save. Make sure you save the file in a secure area of your network as the file contains sensitive information about your organisation and employees.

Upload the saved file to your Portal of choice. Follow the provided “How To” instructions based on your SSP’s requirements.


## STP Zero Submission

If you have changed Payroll systems within the financial year and need to clear out the values previously sent to the ATO through Pay Events, you will need to create an Update Event. You only need to perform this step if your new Payroll system will take on current YTD values previously created in Payfocus.

Go to:

*Payroll/Periodic Activities/Periodic Maintenance/STP Zero Submission*

Select the relevant Tax Year and Update Date and any relevant filters and select OK.

Save the file in a secure area of your network as the file contains sensitive information about your organisation and employees.

 

