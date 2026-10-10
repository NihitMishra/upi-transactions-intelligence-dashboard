# UPI Transactions Intelligence Dashboard — Power BI

## Project Overview
An interactive Power BI dashboard designed to analyze UPI transaction performance, customer usage patterns, transaction failures, and fraud indicators. The project explores transaction value, payment success rates, customer demographics, merchant categories, time-based trends, geographic distribution, and risk patterns.

## Tools & Technologies
- Microsoft Power BI
- Power Query (if used)
- DAX (if used)
- Excel / CSV (data source, as applicable)

## Dashboard Objectives
- Monitor transaction volume and total transaction value.
- Evaluate payment success and failure rates.
- Understand customer, device, network, and merchant-category patterns.
- Analyze transaction trends by hour, weekday/weekend, and state.
- Explore fraud indicators across devices, networks, merchant categories, and receiver banks.

## Executive Overview — Key Insights

- **Transaction success rate:** 95.05%, with a reported failure rate of 4.95%.
- **Total transaction value:** Approximately ₹328 million.
- **Average transaction value:** Approximately ₹1.31K.
- **Transaction volume:** Approximately 250K transactions.
- **Monthly trend:** Transaction volume and transaction value broadly follow similar patterns, with a visible dip around February and higher points around May, July, and October.
- **Payment type:** P2P represents the largest displayed segment, while P2M also contributes substantially.

## Customer and Transaction Behaviour

- **Age group:** Customers aged 26–35 account for the highest displayed transaction volume, at approximately 87K.
- **Weekday vs. weekend:** Weekdays account for approximately 179K transactions, compared with 71K on weekends.
- **Time of day:** Transaction activity peaks around 19:00–20:00 in the displayed analysis.
- **Merchant category:** Grocery leads transaction volume, followed by Food and Shopping.
- **Geography:** Maharashtra records the highest displayed state-level volume, followed by Uttar Pradesh and Karnataka.
- **Device and network:** Android has the highest displayed device volume, while 4G is a major contributor in the network breakdown.

## Fraud and Risk Analysis

- **Fraud cases:** 480 displayed cases, with a reported fraud value of approximately ₹720K.
- **Failed transactions:** Approximately 12K.
- **Device pattern:** Approximately 364 flagged fraud cases appear on Android in the current dashboard.
- **Network pattern:** 4G has the highest displayed fraud count.
- **Merchant category:** Grocery has the highest displayed failed-transaction count.
- **Receiver bank:** SBI has the highest displayed fraud count in the bank-level chart.
- **Time pattern:** Fraud counts peak around 19:00–20:00 in the displayed hourly analysis.

These are observed counts, not necessarily fraud rates. Higher transaction volumes can produce higher fraud counts, so comparisons should account for total transactions within each group.

## Business Recommendations

1. Investigate payment failures by merchant category and failure reason.
2. Monitor payment-system performance during peak evening hours.
3. Compare fraud rates across devices, networks, banks, and merchant categories rather than relying on raw counts.
4. Review geographic and demographic segments to identify customer-service and growth opportunities.
5. Validate fraud-related KPIs and reconcile them with the underlying transaction records.

## Data Validation Notes

- Confirm that the total transaction count, transaction value, and average transaction value reconcile with the underlying data.
- Validate the reported fraud count, fraud value, and fraud-rate KPI, as a discrepancy has been noted.
- Confirm whether failed transactions overlap with fraud cases; these are different measures.
- Verify that monthly trends and category comparisons use consistent date ranges and filters.

## Conclusion
The dashboard provides a consolidated view of UPI transaction performance, customer behaviour, and potential risk patterns. It demonstrates how interactive business intelligence reporting can help identify areas for payment-performance improvement and further fraud investigation.

## Project Files
- Power BI dashboard (`.pbix`)
- Dashboard screenshot (`.png`), if included

## Author
Nihit Mishra
