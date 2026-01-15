# Ethics and GDPR Considerations

## 📌 Overview
Several projects within this repository involved handling applicant data and automated communication. Ethical considerations and data protection principles were embedded into the solution design to ensure responsible and compliant outcomes.

---

## 📧 Ethical Considerations: Automated Communication

### Risk: Email Spamming
Automated reminders could overwhelm applicants or send inaccurate messages.

**Mitigation:**
- Used controlled, trigger-based communication
- Avoided blanket automation
- Ensured staff intention before sending emails
- Limited frequency of reminders

---

## 🔐 Data Protection & Privacy

### GDPR Principles Considered
- Data minimisation
- Purpose limitation
- Accuracy
- Accountability

---

### Risks Identified
- Mishandling personal data
- Retaining unnecessary or unused data
- Lack of transparency in automated decisions

---

### Mitigation Strategies
- Reviewed and removed unused Salesforce fields
- Backed up data before deletion
- Checked dependencies before system changes
- Ensured personal data was accessed only by authorised users

---

## 🛡️ Data Security
- Considered system access controls
- Avoided exposing sensitive data in reports
- Ensured solutions aligned with existing Salesforce security settings

---

## ✅ Outcome
Ethical and GDPR-aware design:
- Protected applicant privacy
- Reduced reputational and compliance risk
- Built trust with stakeholders
- Supported sustainable, responsible system improvement

