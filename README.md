# Advertising Operations Budget Reconciliation

A data auditing and financial reconciliation project in Excel. Reconciles a $70,600 regional media budget against vendor invoices to identify billing discrepancies using XLOOKUP and SUMIF.

## 📝 Project Overview
This project demonstrates end-to-end invoice management and budget reconciliation for advertising operations. Using raw CSV exports of scheduled media orders and data extracted from PDF vendor invoices, I cleaned the data and built a dynamic tracking system to verify expenditures across multiple regional markets (Chicago, Dallas, Miami) for two different brands. 

By leveraging advanced Excel functions, the audit successfully flagged duplicate billings, unmatched records, date mismatches, and budget overages, ensuring accurate final payment processing.

## 🛠️ Key Skills Demonstrated
* **Data Cleaning & Formatting:** Standardizing raw CSV text strings, correcting spelling errors, and standardizing date formats.
* **Financial Reconciliation:** Matching planned budgets against gross invoice amounts.
* **Advanced Excel Functions:** Utilizing `XLOOKUP` for relational data mapping and `SUMIF` for conditional budget aggregation.Built complex nested formulas (e.g., combining SUM and XLOOKUP) for dynamic data retrieval
* **Variance & Error Tracking:** Quarantining duplicate records, calculating budget overages, and identifying missing invoices.

## 📊 Discrepancy Report & Findings
As part of the audit, I prepared the following discrepancy report summarizing the final financial status and action items:

**Financial Summary:**
* **Total Planned Budget:** $70,600
* **Gross Invoiced Amount:** $62,750
* **Approved for Payment:** $54,700
* **Remaining / Unbilled Balance:** $15,900

**Discrepancies Flagged for Review:**
* **Overage:** MP-1002 (KLOOP-FM) billed $4,850 against an approved budget of $4,500 ($350 overage).
* **Date Mismatch:** MP-1006 (KDAL-FM) invoice lists billing dates for August, but the scheduled flight dates were for September. 
* **Duplicate Invoice:** Received two copies of the invoice for MP-1004. Quarantined `INV-3110-B` as a duplicate to prevent double payment.
* **Unmatched Record:** Invoice `INV-999` references order MP-1015, which does not exist in the media order export. 
* **Missing Invoices:** Still waiting on final bills for MP-1008 (SunCoast Digital) and MP-1010 (Tropics Radio).
