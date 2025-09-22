# IT Security Audit – Botium Toys (Case Study)

> **EN:** Internal IT audit case study for Botium Toys, a fictional U.S. toy company expanding to the EU.  

📄 **Full Audit Report (PDF):**  
[docs/Botium-Toys_Audit.pdf](docs/Botium-Toys_Audit.pdf)

---

## 📌 Scope & Objectives
- Assess IT controls (technical/administrative/physical) and compliance maturity  
- Evaluate PCI DSS, GDPR, SOC criteria exposure  
- Provide prioritized recommendations (0–90 days)  

## ✅ Highlights (Executive)
- **Controls:** Firewall ✅ · DRP ❌ · IDS ❌ · Encryption ❌ · AV ✅  
- **PCI DSS:** Missing encryption & access controls for cardholder data ❌  
- **GDPR:** Data inventory/classification missing ❌ · Breach notification plan ✅  
- **SOC (TSC):** Integrity/Availability ✅ · Access control/Confidentiality ❌  

## 📊 Audit Flow (Mermaid)
```mermaid
graph TD
  A[Define Scope & Goals] --> B[Risk Assessment]
  B --> C[Controls & Compliance Checklist]
  C --> D[Findings & Recommendations]
  D --> E[Report & Next Steps]
