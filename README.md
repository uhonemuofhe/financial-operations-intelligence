# Financial Operations Intelligence: Transaction Reconciliation & Data Quality Monitoring

## Project Overview

This project uses a simulated financial transaction dataset to demonstrate data quality monitoring, operational reporting, and KPI analysis using Google Sheets.

The analysis focuses on transaction statuses, missing values, repeated reference IDs, and summary metrics that can help identify records requiring further investigation.

## Business Objectives

- Summarise transaction statuses and completion rates.
- Identify missing transaction amounts.
- Flag repeated reference IDs for investigation.
- Present key findings through a summary report and chart.
- Recommend follow-up actions based on identified exceptions.

## Tools Used

- Google Sheets
- Spreadsheet formulas: `COUNTIF`, `COUNTBLANK`, `COUNTA`, `SUM`, and `AVERAGE`
- KPI calculations and chart visualisation

## Key Findings

- 15 simulated transactions were analysed.
- 10 were marked Completed, 3 Pending, and 2 Failed.
- The completion rate was 66.67%.
- One transaction had a missing amount.
- Two records shared the reference ID `PAY-509` and were flagged for investigation.
- Total recorded transaction value: R19,230.00.
- Average recorded amount: R1,373.57 across 14 recorded amounts.

## Recommendations

- Investigate the repeated reference against source records before determining whether a duplicate exists.
- Obtain and validate the missing amount.
- Review pending and failed transactions to establish their causes.
- Resolve data quality issues before relying on affected records for further reporting.

## Data Limitations

The dataset is simulated and contains 15 transactions. A repeated reference is a reason to investigate, not proof of a duplicate payment. The analysis does not establish why transactions are pending or failed.

## Project Status

The initial spreadsheet analysis, KPI summary, status chart, exception report, and project documentation have been completed. Future development could include Python-based validation, SQL analysis, and additional reporting.

