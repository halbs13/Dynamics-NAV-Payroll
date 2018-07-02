# Supplementary Information on Pay Transaction Types

This section will provide examples of how some of the new pay transactions can be setup within the Dynamics NAV Payroll module.  It will specifically discuss;

 * Bonus/Commission Payment Transactions – where Method A is used as the tax calculation method.
 * Termination Transactions used in the Termination Wizard
 * Government Paid Parental Leave (GPPL)

## Bonus/Commission Payment Transactions

Bonus/Commission payment transactions will need to be setup in a particular way to ensure that the correct method of tax (Method A) is calculated on the value of this pay transaction type.

The guidelines are as follows:	

1. On the **General** FastTab, ensure that you have the **Accumulation Type** set to *Lump Sum*,
2. On the **Calculations** FastTab, ensure that you have the **Lump Sum Tax Method** set to *Bonus/Commission* and the **Apply to Lump Sum Tax Method** is selected.


## Termination Transactions Using the Wizard

The treatment of tax is calculated within the Wizard based on the transactions that are setup within the Termination FastTab on the [Payroll Setup](au-payroll-setup-payroll-setup.md) card.

The guidelines are as follows:

### Long Service Leave taxed as Gross Salary & Wages (Marginal Tax)

1.  On the **General** FastTab, the **Accumulation Type** is set to *Long Service Leave* and the **P.S. YTD Accumulation Code** is *Gross*,
2.  On the **Calculations** FastTab, the **Lump Sum Tax Method** is set to *None (Termination)*,
3.  On the **Leave Application** FastTab, the **Apply to Leave Taken** is selected,  


 



 


 

 




10.16.2.2	Long Service Leave taxed as a Lump Sum A (35%)


 

 

 




 


10.16.2.3	Long Service Leave taxed as Lump Sum B 

 

 

 

 



10.16.2.4	Annual Leave taxed as Gross Salary & Wages (Marginal Tax)

 

 




 

 

If your organisation accrues and pays leave loading then this will be setup similar to the Annual Leave transaction, however the Rate Conversion Factor on the Calculations FastTab will be set to 0.175 to refelct the 17.5% percentage pay rate.



10.16.2.5	Annual Leave taxed as a Lump Sum A (35%)

 

 

 

 



If your organisation accrues and pays leave loading then this will be setup similar to the Annual Leave transaction, however the Rate Conversion Factor on the Calculations FastTab will be set to 0.175 to refelct the 17.5% percentage pay rate.

10.16.2.6	In Lieu of Notice

 

 

 

 



10.16.3	Government Paid Parental Leave


 

 

 

 
