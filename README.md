# 🔍 AML Risk Scoring & Alert Triage System

## 📌 Overview

This project simulates a rules-based AML transaction monitoring decisioning engine used in Level 1 alert triage.

It combines risk scoring, classification, and alert prioritisation to replicate how financial institutions identify and prioritise high-risk cases before escalation to investigation teams.

The system demonstrates how structured risk indicators and decision logic can optimise alert handling and improve operational efficiency in transaction monitoring workflows.

---

## 📂 Access Notebook
👉 [View Notebook on GitHub](https://github.com/FarzeanHassim/aml-risk-triage-system/blob/main/aml_risk_triage.ipynb)

---

## 🎯 Objective
- Assign risk scores based on key AML risk factors  
- Classify alerts into High, Medium, and Low risk  
- Improve prioritisation of investigation workload  

---

## ⚙️ Risk Framework

The system applies a weighted risk scoring model based on key AML risk indicators:

- Customer risk (PEP status, sanctions exposure)
- Transaction behaviour (amount, frequency)
- Geographic risk (high-risk jurisdictions)
- Account characteristics (account age)

Each factor contributes to an overall risk score, reflecting how financial institutions assess and prioritise financial crime risk.

---

## 🧠 System Architecture

This project simulates a simplified AML monitoring pipeline:

1. Data ingestion (transaction & customer data)  
2. Risk scoring engine  
3. Risk classification  
4. Alert generation  
5. Alert prioritisation  
6. Investigator workflow  

This mirrors real-world transaction monitoring systems used in financial institutions.
---

## 📊 Key Output
- Risk scoring model for customer profiling  
- Alert classification based on thresholds  
- Prioritised investigation queue
- Supports prioritised review before escalation to Level 2 investigations.

---

## 🧠 Key Insight

Rules-based systems provide strong explainability and are widely used in AML operations, but they face key limitations:

- Static thresholds may not capture evolving financial crime patterns  
- High alert volumes can lead to investigator fatigue  
- Limited adaptability compared to machine learning approaches  

This highlights the need for hybrid or ML-driven optimisation, which is explored in subsequent projects.

---

## 🏦 Real-World Application
Applicable to:
- AML transaction monitoring systems  
- Customer risk rating frameworks  
- Financial crime alert triage processes  

---

## 🛠️ Tools Used
- Python  
- Pandas  

---

## 🚀 Future Improvements
- Introduce machine learning for dynamic scoring  
- Reduce false positives  
- Improve risk calibration  

---

## ⚠️ Limitations
- Rules-based approach does not adapt to new patterns  
- May generate false positives  
- Requires periodic recalibration of thresholds and weights  

---

## 💼 Business Impact
- Improves prioritisation of high-risk alerts  
- Enables efficient allocation of investigation resources  
- Reduces alert backlog in transaction monitoring systems

---

## ⚙️ Decisioning Logic

The system translates risk scores into actionable alert priorities:

- High Risk → Immediate Review  
- Medium Risk → Review Soon  
- Low Risk → Queue  

This reflects how transaction monitoring systems prioritise alerts to ensure that high-risk cases are investigated promptly while optimising resource allocation.

---

## 👤 Author
Farzean Hassim
