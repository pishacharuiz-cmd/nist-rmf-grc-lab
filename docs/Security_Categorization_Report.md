# Security Categorization Report (FIPS 199 / NIST SP 800-60)

## System Name: Project-Alpha-Portal

### Impact Analysis
Based on the potential impact of a security event affecting the system's CIA triad:

* **Confidentiality: MODERATE**
  * *Rationale:* The system processes and stores user PII and authentication tokens. Unauthorized disclosure could result in operational disruption and privacy violations.
* **Integrity: MODERATE**
  * *Rationale:* Unauthorized modification or deletion of portal configuration or user transaction data could lead to inaccurate processing and financial discrepancies.
* **Availability: LOW**
  * *Rationale:* A disruption in service causes minor operational inconvenience to users, but does not threaten human life or cause catastrophic economic collapse.

### Final Security Categorization
* **Overall System Impact Level:** **MODERATE**
* **Baseline Control Set:** NIST SP 800-53 Rev. 5 Moderate Controls.
