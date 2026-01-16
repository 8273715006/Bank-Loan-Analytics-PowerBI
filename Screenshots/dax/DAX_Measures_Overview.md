# Key DAX Measures – Retail Lending Analysis

## Base Measures
- Total Loan Applications
- Total Funded Amount
- Total Amount Received
- Average Interest Rate
- Average DTI

These measures form the foundation for all higher-level calculations.

## Time Intelligence
- MTD Loan Applications
- MoM Loan Applications %
- MTD Funded Amount
- MoM Funded Amount %

MTD and MoM metrics are driven by a synced date slicer to ensure consistent time context.

## Risk Measures
- Bad Loan Applications
- Bad Loan Funded Amount
- Bad Loan %
- Good Loan %

These measures are used to assess portfolio risk and default behavior.

## Design Consideration
All calculated measures are built on top of base measures to ensure reusability and filter safety.

