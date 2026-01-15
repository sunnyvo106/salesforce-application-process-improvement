# Project 3: Salesforce Data Management & Field Optimisation

## 📌 Project Overview
This project addressed Salesforce system limitations caused by reaching the maximum number of custom fields on the Application object.

---

## ❗ Problem Statement
- Salesforce had reached custom field capacity
- New business requirements could not be accommodated
- Many fields were suspected to be unused or redundant

---

## 🎯 Objectives
- Identify unused or low-value custom fields
- Reduce technical debt
- Free system capacity safely without data loss

---

## 🔍 Analysis Approach
1. Reviewed field usage using:
   - Field Trip
   - Apsona
2. Analysed:
   - Populated record counts
   - Data types
   - Field creation dates
3. Checked dependencies:
   - Validation rules
   - Flows
   - Formula fields
   - Reports and layouts

---

## 🛠️ Solution
- Filtered fields with minimal or zero population
- Excluded:
  - Recently created fields
  - Formula and lookup fields
  - Fields used by automation
- Produced a validated deletion shortlist
- Backed up data prior to deletion recommendation

---

## ✅ Outcome & Value
- Identified fields unused since 2020
- Enabled safe cleanup pending sponsor approval
- Reduced system complexity
- Improved long-term scalability

---

## 🔧 Tools Used
- Salesforce
- Apsona
- Field Trip
- Excel

---

## 🧠 Key Learnings
- Field-level analysis is more reliable than record-level dates
- Data deletion requires strong governance
- Technical debt has real business impact

