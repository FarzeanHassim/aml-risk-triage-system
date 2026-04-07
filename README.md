# AML Risk Scoring & Alert Triage System (Python)

## 🔗 Project Demo
[View Notebook](./aml_risk_triage.ipynb)

---

## Overview
This project simulates a real-world Anti-Money Laundering (AML) risk scoring and alert triage system using a rules-based model, enhanced with data visualisation to support risk prioritisation and decision-making.

It demonstrates how financial institutions identify, score, and prioritise high-risk customers based on transaction behaviour, customer profile, and regulatory risk indicators.

---

## Objective
The objective of this project is to:

- Assign risk scores to customers based on AML risk indicators  
- Classify alerts into High, Medium, and Low risk categories  
- Prioritise alerts for investigation  
- Simulate real-world transaction monitoring workflows  
- Provide analytical insights into portfolio risk distribution  

---

## Key Features
- Rules-based AML risk scoring model  
- Alert classification (High / Medium / Low)  
- Prioritised alert queue for investigation  
- Risk level distribution analysis (bar chart)  
- Risk score distribution analysis (histogram)  
- Scenario analysis for high-risk cases  
- Business and operational considerations (false positives, efficiency)  

---

## Technologies Used
- Python  
- Pandas  
- Matplotlib  

---

## Risk Scoring Logic
The model assigns weighted scores based on key AML risk indicators:

- High-risk country: +30  
- Large transaction amount (>20,000): +20  
- High transaction frequency (>10 in 7 days): +20  
- Politically Exposed Person (PEP): +25  
- Sanctions hit: +40  
- New account (<30 days): +15  

This simulates a simplified transaction monitoring system used in financial institutions.

---

## Workflow Simulation

| Risk Level | Priority |
|-----------|---------|
| High      | Immediate Review |
| Medium    | Review Soon |
| Low       | Queue |

This reflects how AML investigation teams prioritise alerts in real-world operations.

---

## Risk Analytics & Visualisation

### Risk Level Distribution
Provides a portfolio-level view of customer segmentation across risk categories, enabling identification of high-risk populations requiring immediate attention.

### Risk Score Distribution
Shows the distribution of risk scores across customers, highlighting clustering of high-risk cases and supporting threshold calibration and prioritisation strategies.

---

## Key Results
- Successfully categorised customers into High, Medium, and Low risk segments  
- Enabled prioritisation of high-risk alerts for immediate investigation  
- Provided portfolio-level visibility of risk distribution through data visualisation  
- Demonstrated how rules-based models can be enhanced with analytics for better decision-making  

---

## Business Impact
This project demonstrates how data-driven approaches can:

- Reduce false positives in transaction monitoring  
- Improve investigator productivity  
- Enhance risk visibility across customer portfolios  
- Support compliance with AML/CFT regulatory expectations  

---

## Operational Considerations
Rules-based systems may generate false positives and lack adaptability.

In real-world applications, thresholds and scoring weights would be calibrated using historical data to balance detection accuracy and operational efficiency.

---

## Future Enhancements
- Integration of machine learning models (e.g. logistic regression)  
- Real-time transaction monitoring capability  
- Automated alert decisioning using AI  
- Interactive dashboard for monitoring alerts and KPIs  

---

## How to Run

1. Clone the repository  
2. Open `aml_risk_triage.ipynb` in Jupyter Notebook  
3. Run all cells to simulate the AML risk scoring and alert triage workflow  

---

## Author
**Farzean Hassim**  
Financial Crime Risk & Data Analytics
