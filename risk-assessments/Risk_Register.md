# Risk Register – MediHealth Solutions

| ID | Asset | Threat | Vulnerability | Likelihood (1–5) | Impact (1–5) | Risk Score | Proposed Mitigation |
|----|-------|--------|---------------|------------------|--------------|------------|---------------------|
| R-01 | EMR Database | Ransomware Attack | Lack of daily backups | 4 | 5 | 20 | Implement automated encrypted daily backups; train staff on phishing |
| R-02 | Patient Portal | Credential Stuffing | Weak password policy | 4 | 4 | 16 | Enforce MFA and strong password requirements |
| R-03 | HR System | Insider Threat | Excessive access permissions | 3 | 4 | 12 | Apply least privilege principles; perform quarterly access reviews |
| R-04 | AWS Cloud Storage | Data Breach | Misconfigured S3 bucket | 2 | 5 | 10 | Enable bucket encryption and access logging; audit configurations monthly |
| R-05 | Employee Laptops | Malware Infection | No endpoint protection | 3 | 3 | 9 | Deploy EDR software; block unauthorized software installation |
| R-06 | Internal Network | Phishing Email | No security awareness training | 4 | 3 | 12 | Launch quarterly phishing simulations and awareness campaigns |

---

## Risk Scoring Key

- **Likelihood (1–5):** Probability of occurrence (1 = rare, 5 = very likely)  
- **Impact (1–5):** Business impact (1 = minimal, 5 = catastrophic)  
- **Risk Score:** Likelihood × Impact  
- **Mitigation:** Preventive or detective control to reduce risk
