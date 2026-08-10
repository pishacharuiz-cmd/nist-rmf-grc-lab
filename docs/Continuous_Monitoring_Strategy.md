# Continuous Monitoring (ConMon) Strategy

## 1. Objective
To maintain an ongoing awareness of security posture, vulnerability status, and control effectiveness for Project-Alpha-Portal following the issuance of an Authority to Operate (ATO).

## 2. Monitoring Cadence & Controls
* **Vulnerability Scanning:** Automated infrastructure and web container vulnerability scans executed on a monthly basis.
* **Log Review & SIEM Integration:** Centralized log-shipping via `rsyslog` to a SIEM instance with continuous alert monitoring for anomalous behaviors (e.g., failed authentication spikes, log service termination).
* **Configuration Management:** File Integrity Monitoring (FIM) deployed to track unexpected baseline drift on production servers.
* **Control Re-assessment:** Annual review of the System Security Plan (SSP) and random spot-checks of high-risk operational controls.
