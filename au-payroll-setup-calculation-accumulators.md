# On Costing Overview (Calculation Accumulators)

An On Cost type transaction is a calculation of some type of overhead or Employer Liability transaction such as Payroll Tax, Workers Comp Levy, Insurance, Superannuation, etc. for example.

While some of these calculations may be possible using other methods, these are not all pay period type calculations and therefore no data is available for reporting purposes until end of month when the other calculation is performed.  By using On costing, the Employer is able to report on Wages plus on costs to get a true cost of labour as opposed to just having the wage component available.

As On Cost amounts are posted through to GL expense and provision accounts per pay period, the General Ledger is always up to date.

The functionalities of On Costing are;

- Allows a transaction type to be calculated as a percentage % of another transaction or accumulated value
- Allows double sided account entries – expense and provision account set up
- Allows the setup of a transaction type that does not affect the contractor’s pay – Employer Liability
- Allows on cost transactions to be automatically generated for a group of contractors under relevant conditions.

On Cost Setup encompasses the following activities:

- On Cost Accumulators – In order to be able to calculate on costs, there will need to be a base from which to calculate.  For example, if calculating on costs for the provision of annual leave, then you will need to base the calculation on the value of those types of incomes that accrue annual leave.  

To enable this, new Accumulators and Transaction Accumulators need to be setup and assigned to the appropriate transactions.

Transaction Accumulators – Are accessed via the Pay Transaction Type Card.  This option will allow the selection of as
many accumulators as required, to be attached to the selected pay transaction type code.

## On Cost Accumulators

1.  To access the On Cost Accumulators, go to the following menu: *Departments/Payroll/Setup/Payroll Setup/ General/Calculation
Accumulators* 

2. To create a new record, click on the **New** button.

3.  Fill the fields as described in the following table.

|Field|Description|  
|:---------------------------------|:---------------------------------------|  
|**Accumulator Code**|The “Accumulator Code” is used to uniquely identify the Accumulator.|
|**Accumulator Description**|The “Accumulator Description” field is used to record a description for the Accumulator.|

4.  Click on the **OK** button to close this window.
  

## Transaction Accumulators

1.  To access the Transaction Accumulators, go to the following menu: *Departments/Payroll/Setup/Payroll Setup/ General/Pay
Transaction Types*

2.  Select a Transaction Type and click on the **Accumulators** icon.

3.  To create a new record, cick on the **New** button.

|Field|Description|  
|:---------------------------------|:---------------------------------------|  
|**Accumulator Code**|Select the Accumulator Code from the **ArrowDown**.|
|**Accumulator Description**|The Description field will be updated with the description from the Accumulator code selected.|
|**Negative Accumulator**|Tick this field if you expect the calculation base to be a negative value.|

4.  Click on the **OK** button to close this window.

## Posting Setup

During the Post Journal Lines process, General Ledger Accounts are resolved for each transaction where amounts will be consolidated
according to:

- GL Account
- Global Dimensions and Shortcut Dimensions

With On Cost transactions they are calculated and post both sides of the journal entry.  Where an amount of $20 is calculated, a debit entry is generated and posted to the nominated expense account and an equal credit entry is generated and posted to the nominated provision account.

Transaction Posting groups must be setup and specified to ensure that the provision and expense go the correct General Ledger account.

## On Cost Generation 
On Costs are generated automatically as there is a flag used to identify any transaction types that should be generated automatically if the code in question is found in the rateset applicable to the resource allocation.

### Calculate Pays
When the Calculate Pays function is run, the following process happens:

- Check Rateset for any transactions that are flagged as Auto Generate.
- Generate Transactions and calculate values based on rateset rate.  If there is no rateset rate found then the rate found on the Pay Transaction Type will be used. 

### Branch/Division/Global Dimensions/Shortcut Dimension

When the On Cost transactions are generated, Branch, Division, Global Dimension codes can be assigned automatically to the transactions.


To learn more about setting up [Pay Transaction Types](au-payroll-setup-pay-transaction-types.md)

To learn more about setting up [Payroll Posting Groups](au-payroll-setup-posting-group-setup.md)
