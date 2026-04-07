# AML Risk Scoring & Alert Triage System (Python)

## Overview
This project simulates an end-to-end Anti-Money Laundering (AML) alert triage system using a rules-based risk scoring model.

It demonstrates how financial institutions prioritise high-risk customers and transactions by assigning risk scores based on key indicators such as transaction behaviour, customer profile, and regulatory risk factors.

---

## Objective
To design a system that:
- Assigns risk scores to customers  
- Classifies alerts into High, Medium, and Low risk  
- Prioritises alerts for investigation  
- Simulates real-world transaction monitoring workflows  

---

## Key Features
- Rules-based AML risk scoring model  
- Alert classification (High / Medium / Low)  
- Prioritised alert queue for investigation  
- Alert workflow simulation (Immediate Review / Review Soon / Queue)  
- Risk distribution analysis with visualisation  
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

| Risk Level | Priority           |
|------------|-------------------|
| High       | Immediate Review  |
| Medium     | Review Soon       |
| Low        | Queue             |

This reflects how AML investigation teams prioritise cases in real-world operations.

---

## Key Insights
- High-risk customers are clearly identifiable based on multiple risk indicators  
- Risk scoring improves prioritisation of alerts  
- Enables better allocation of investigation resources  
- Provides visibility into customer risk distribution  

---

## Business Impact
This system demonstrates how data-driven approaches can:
- Reduce false positives in transaction monitoring  
- Improve investigator productivity  
- Enhance risk visibility across portfolios  
- Support compliance with AML/CFT regulatory expectations  

---

## Operational Considerations
Rules-based systems may generate false positives.

In practice, thresholds and scoring weights would be calibrated using historical data to balance detection accuracy and operational efficiency.

---

## Future Enhancements
- Machine learning models (classification, anomaly detection)  
- Integration with real-time transaction data  
- Automated alert decisioning using AI  
- Dashboard for monitoring alerts and KPIs  

---

## Author
**Farzean Hassim**  
Financial Crime Risk & Data Analytics
