# Project 4: Workflow Optimisation – Preferred Subject Logic

## 📌 Project Overview
This project focused on eliminating data inconsistency caused by multiple “Preferred Subject” selections within Salesforce.

---

## ❗ Problem Statement
Applicants could have **multiple preferred subjects selected**, causing:
- Data inconsistency
- Reporting inaccuracies
- Manual correction by staff

---

## 🎯 Objectives
- Ensure only one preferred subject per application
- Automate record updates efficiently
- Avoid performance issues in Salesforce flows

---

## 🔍 Analysis & Iteration
- Conducted multiple flow design attempts
- Encountered common Salesforce challenges:
  - Update-in-loop errors
  - Incorrect trigger logic
  - Misinterpreted requirements

---

## 🔄 Requirement Clarification
Final confirmed requirement:
> When a preferred subject is selected, all other related subject eligibility records must be automatically unchecked.

---

## 🛠️ Final Solution
- Record-triggered flow on Subject Eligibility
- Trigger condition: Preferred Subject = TRUE
- Retrieved related records for the same application
- Bulk-updated all other records to FALSE
- Displayed result on Application object

---

## ✅ Outcome & Value
- Enforced data integrity automatically
- Eliminated manual correction
- Improved reporting accuracy
- Performance-safe bulk update logic

---

## 🔧 Tools Used
- Salesforce Record-Triggered Flows

---

## 🧠 Key Learnings
- Requirement clarity prevents wasted effort
- Bulk processing is critical for Salesforce performance
- Persistence and iteration lead to robust solutions

