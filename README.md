# 🔍 AML Risk Scoring & Alert Triage System

## 📌 Overview
This simulates a Level 1 transaction monitoring triage system used in financial institutions to prioritise alerts before escalation to investigation teams.

This project simulates a rule-based AML transaction monitoring system that assigns risk scores to customers based on predefined risk indicators.

It reflects how traditional financial institutions prioritise alerts for investigation.

---

## 📂 Access Notebook
👉 [View Notebook on GitHub](https://github.com/FarzeanHassim/aml-risk-triage-system/blob/main/aml_risk_triage.ipynb)

---

## 🎯 Objective
- Assign risk scores based on key AML risk factors  
- Classify alerts into High, Medium, and Low risk  
- Improve prioritisation of investigation workload  

---

## ⚙️ Methodology
1. Define risk indicators:
   - Transaction amount  
   - Transaction frequency  
   - PEP status  
   - Sanctions hits  
   - Country risk  
   - Account age  

2. Assign weighted scores to each risk factor  

3. Calculate total risk score per customer  

4. Classify alerts:
   - High Risk  
   - Medium Risk  
   - Low Risk  

---

## 📊 Key Output
- Risk scoring model for customer profiling  
- Alert classification based on thresholds  
- Prioritised investigation queue  

---

## 🧠 Key Insight
Rule-based systems are simple and explainable but may generate large volumes of alerts and lack adaptability.

This creates opportunities for optimisation using machine learning (see Project 2).

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

## 👤 Author
Farzean Hassim
