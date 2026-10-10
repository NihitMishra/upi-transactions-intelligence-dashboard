# UPI Transactions Intelligence Dashboard | Power BI

## Project Overview

An interactive Power BI dashboard designed to analyze UPI transaction performance, customer behaviour, payment failures, and fraud indicators. The project explores transaction volume and value, customer demographics, merchant categories, time-based trends, geographic distribution, and risk patterns to derive actionable business insights.

## Tools & Technologies

- Microsoft Power BI
- Data Analysis
- Data Visualization
- Business Intelligence
- UPI Transaction Data

## Project Objectives

- Monitor transaction volume, total transaction value, and average transaction value.
- Evaluate payment success and failure rates.
- Analyze customer behaviour by age group, device, network, and time of day.
- Compare transaction activity across merchant categories and states.
- Explore fraud indicators by device, network, receiver bank, and transaction hour.
- Translate dashboard findings into practical business recommendations.

## Dashboard Previews

### Dashboard 1 — Executive Overview

![UPI Dashboard - Executive Overview](./Screenshot%202026-10-10%20174335.png)

### Dashboard 2 — Transaction Intelligence

![UPI Dashboard - Transaction Intelligence](./Screenshot%202026-10-10%20174931.png)

### Dashboard 3 — Fraud and Risk Analysis

![UPI Dashboard - Fraud and Risk Analysis](./Screenshot%202026-10-10%20174948.png)

## 1. Executive Overview — Key Insights

| Metric | Dashboard Result |
|---|---:|
| Total Transactions | Approximately 250K |
| Total Transaction Value | Approximately ₹328M |
| Transaction Success Rate | 95.05% |
| Reported Failure Rate | 4.95% |
| Average Transaction Value | Approximately ₹1.31K |
| Flagged Fraud Transactions | 480 |
| Reported Fraud Value | Approximately ₹720K |
| Failed Transactions | Approximately 12K |

### Key Findings

- **Transaction performance:** The dashboard reports a 95.05% success rate and a 4.95% failure rate, highlighting an opportunity to investigate failed payments.
- **Monthly trends:** Transaction volume and value broadly follow similar patterns, with a visible dip around February and higher points around May, July, and October.
- **Payment type:** P2P is the largest displayed payment-type segment, while P2M also contributes substantially.
- **Merchant categories:** Grocery leads transaction volume, followed by Food and Shopping.

## 2. Customer and Transaction Behaviour

### Customer Demographics

- The 26–35 age group leads with approximately 87K transactions.
- The 36–45 age group contributes approximately 63K transactions.
- The 18–25 age group contributes approximately 62K transactions.

### Weekday vs. Weekend

- Weekdays account for approximately 179K transactions.
- Weekends account for approximately 71K transactions.
- Weekday transaction volume is approximately 2.5 times weekend volume.

### Time of Day

Transaction activity peaks around 19:00–20:00 in the displayed analysis.

**Business implication:** Peak-hour patterns can help guide payment-system monitoring and customer-support planning.

### Device and Network

- Android has the highest displayed transaction volume among Android, iOS, and Web.
- The network breakdown shows 4G as a major contributor to transaction volume.

These are transaction counts, not device or network reliability rates.

### Geographic and Merchant Insights

- Maharashtra leads with approximately 37K transactions.
- Uttar Pradesh and Karnataka follow with approximately 30K transactions each.
- Grocery, Food, and Shopping account for the largest displayed merchant-category volumes.

**Business implication:** These segments provide useful starting points for regional performance analysis and merchant-focused improvements.

## 3. Fraud and Risk Analysis

### Device-Level Fraud

The dashboard shows approximately 364 flagged fraud transactions on Android, representing about 75.8% of the 480 displayed fraud cases.

**Recommendation:** Investigate flagged transactions and compare fraud rates against total transaction volumes by device before concluding that Android has a higher fraud risk.

### Network-Level Fraud

4G has the highest displayed fraud count among the network categories.

**Recommendation:** Compare fraud rates within each network type. Higher raw counts may reflect greater network usage rather than greater risk.

### Merchant Category and Failed Transactions

Grocery has the highest displayed failed-transaction count at approximately 2,500, followed by Food at around 1,900 and Shopping at around 1,500.

**Recommendation:** Investigate payment failure reasons by merchant category. Failed transactions should not be treated as fraudulent transactions unless separately identified as fraud.

### Receiver Bank

SBI has the highest displayed fraud count by receiver bank, followed by HDFC and ICICI.

**Recommendation:** Compare bank-level fraud rates using total transaction volumes for each bank before drawing risk conclusions.

### Fraud by Time of Day

The displayed hourly fraud count peaks around 19:00–20:00.

**Recommendation:** Compare hourly fraud rates against overall transaction volume by hour to determine whether this peak represents higher fraud risk or simply higher payment activity.

## 4. Business Recommendations

1. **Improve payment reliability:** Investigate failed transactions by merchant category, time, and available failure reason.
2. **Monitor peak-hour performance:** Review payment success rates and system performance during evening peaks.
3. **Strengthen fraud analysis:** Compare fraud rates by device, network, bank, and merchant category rather than relying only on raw counts.
4. **Explore customer segments:** Use demographic and weekday/weekend patterns to understand transaction behaviour.
5. **Investigate regional performance:** Study transaction value, success rates, and fraud rates across high-volume states.
6. **Validate key metrics:** Reconcile fraud-related KPIs with underlying transaction records before making operational decisions.

## 5. Data Validation and Limitations

- Verify the exact underlying transaction count behind the approximately 250K figure.
- Validate total transaction value and average transaction value against the source data.
- Reconcile the reported fraud count, fraud value, and fraud-rate KPI, as a discrepancy has been noted.
- Confirm whether failed transactions overlap with fraud cases.
- Compare fraud counts with total transaction volumes within each segment.
- Treat displayed figures as approximate where exact underlying values have not been independently verified.

## Conclusion

The UPI Transactions Intelligence Dashboard provides a consolidated view of payment performance, customer usage patterns, geographic distribution, merchant activity, and potential fraud indicators. It demonstrates how interactive dashboards can support performance monitoring, customer segmentation, and risk investigation while highlighting the importance of validating metrics before making business decisions.

## Project Files

- `UPI_Dashboard_final.pbix` — Interactive Power BI dashboard.
- Dashboard screenshots — Visual previews of all three report pages.

## Author

**Nihit Mishra**

[GitHub Profile](https://github.com/NihitMishra)
