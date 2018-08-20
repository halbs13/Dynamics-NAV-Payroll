# Supplementary Information on Pay Transaction Types

This section will provide examples of how some of the new pay transactions can be setup within the Dynamics NAV Payroll module.  It will specifically discuss;

 * [Bonus/Commission Payment Transactions](#bonus-commission-payment-transactions) – where Method A is used as the tax calculation method.
 * [Termination Transactions](#termination-transactions-using-the-wizard) used in the Termination Wizard
 * [Government Paid Parental Leave (GPPL)](#government-paid-parental-leave)

## Bonus Commission Payment Transactions

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
3.  On the **Leave Application** FastTab, the following fields need to be selected;
  a. **Apply to Leave Taken** is selected,
  b. **Leave Type** is set to Long Service Leave,
  c. **Cause of Absence Code**,
  d. **Accum. For Leave Calculations** is set to No Accumulation.
4.  On the **Parameters** FastTab, the **Apply to Work Cover** is selected.

### Long Service Leave taxed as a Lump Sum A (35%)

1.  On the **General** FastTab, the **Accumulation Type** is set to *Long Service Leave* and the **P.S. YTD Accumulation Code** is *LUMPA*,
2.  On the **Calculations** FastTab, the **Lump Sum Tax Method** is set to *None (Termination)*,
3.  On the **Leave Application** FastTab, the following fields need to be selected;
  a. **Apply to Leave Taken** is selected,
  b. **Leave Type** is set to Long Service Leave,
  c. **Cause of Absence Code**,
  d. **Accum. For Leave Calculations** is set to No Accumulation.
4.  On the **Parameters** FastTab, the **Apply to Work Cover** is selected. 

[GoToTop](#supplementary-information-on-pay-transaction-types)

 ### Long Service Leave taxed as a Lump Sum B 

1.  On the **General** FastTab, the **Accumulation Type** is set to *Long Service Leave* and the **P.S. YTD Accumulation Code** is *LUMPB*,
2.  On the **Calculations** FastTab, the **Lump Sum Tax Method** is set to *None (Termination)*,
3.  On the **Leave Application** FastTab, the following fields need to be selected;
  a. **Apply to Leave Taken** is selected,
  b. **Leave Type** is set to Long Service Leave,
  c. **Cause of Absence Code**,
  d. **Accum. For Leave Calculations** is set to No Accumulation.
4.  On the **Parameters** FastTab, the **Apply to Work Cover** is selected. 


### Annual Leave taxed as Gross Salary & Wages (Marginal Tax)

1.  On the **General** FastTab, the **Accumulation Type** is set to *Annual Leave* and the **P.S. YTD Accumulation Code** is *Gross*,
2.  On the **Calculations** FastTab, the **Lump Sum Tax Method** is set to *None (Termination)*,
3.  On the **Leave Application** FastTab, the following fields need to be selected;
  a. **Apply to Leave Taken** is selected,
  b. **Leave Type** is set to Annual Leave,
  c. **Cause of Absence Code**,
  d. **Accum. For Leave Calculations** is set to No Accumulation.
4.  On the **Parameters** FastTab, the **Apply to Work Cover** is selected.

### Leave Loading Transactions

If your organisation accrues and pays leave loading then this will be setup similar to the Annual Leave transaction, however the **Rate Conversion Factor** on the **Calculations** FastTab will be set to 0.175 to refelct the 17.5% percentage pay rate.

 
### Annual Leave taxed as a Lump Sum A (35%)

1.  On the **General** FastTab, the **Accumulation Type** is set to *Annual Leave* and the **P.S. YTD Accumulation Code** is *LUMPA*,
2.  On the **Calculations** FastTab, the **Lump Sum Tax Method** is set to *None (Termination)*,
3.  On the **Leave Application** FastTab, the following fields need to be selected;
  a. **Apply to Leave Taken** is selected,
  b. **Leave Type** is set to Annual Leave,
  c. **Cause of Absence Code**,
  d. **Accum. For Leave Calculations** is set to No Accumulation.
4.  On the **Parameters** FastTab, the **Apply to Work Cover** is selected.
 
[GoToTop](#supplementary-information-on-pay-transaction-types)


### In Lieu of Notice

1.  On the **General** FastTab, the **Accumulation Type** is set to *Lump Sum*, the **P.S. YTD Accumulation Code** is *BLANK* and the **Non-P.S. YTD Accumulation Code** is *ETP*,
2.  On the **Calculations** FastTab, the **Apply Lump Sum Tax Method** is selected and the **Lump Sum Tax Method** is set to *None (Termination)*,
3.  On the **Leave Application** FastTab, the following fields need to be selected;
  a. **Accum. For Leave Calculations** is set to No Accumulation.
4.  On the **Parameters** FastTab, the following fields need to be selected;
  a. **Apply to Work Cover** is selected,
  b. **Apply to Superannuation** is selected,
  c. **Apply to Min. Salary Check (Super)**  is selected.



## Government Paid Parental Leave

1.  On the **General** FastTab, the **Accumulation Type** is set to *Allowance*, the **P.S. YTD Accumulation Code** is *GROSS*,
2.  On the **Calculations** FastTab, the **Rate Amount** is entered as the Unit Rate and the **Rate Calculation Method** is set to *Units*,
3.  On the **Leave Application** FastTab, the following fields need to be selected;
  a. **Accum. For Leave Calculations** is set to No Accumulation.
4.  On the **Parameters** FastTab, the following fields need to be selected;
  a. **Apply to Taxable Income** is selected,
   

 
[GoToTop](#supplementary-information-on-pay-transaction-types)
 

 
