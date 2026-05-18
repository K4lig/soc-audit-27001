# 📋 ISO/IEC 27001:2022 Internal Audit: Security Monitoring & Log Management

![ISO 27001:2022](https://img.shields.io/badge/Framework-ISO_27001:2022-0284c7?style=flat-square)
![IT Audit](https://img.shields.io/badge/Domain-Internal_Audit-0f172a?style=flat-square)
![Blue Team Alignment](https://img.shields.io/badge/Alignment-SOC_%26_Blue_Team-166534?style=flat-square)

> A formal Internal Audit Report evaluating the effectiveness of security monitoring controls, log aggregation, and SIEM integration within a virtualized enterprise data center.

## 1. Project Overview
This project simulates an internal IT audit acting under the purview of an Information Security Management System (ISMS). The objective is to verify compliance with ISO/IEC 27001:2022 logging and monitoring controls, identify operational blind spots, and issue actionable non-conformities (findings) to IT and SOC management.

## 2. Business Scenario
The audit focuses on an organization utilizing a virtualized infrastructure cluster (VMware) hosting critical internal applications. The security architecture relies on a centralized SIEM (Wazuh) for threat detection and incident response. 

**The Audit Focus:** Assessing whether all critical servers are properly generating, protecting, and forwarding authentication and system logs to the centralized SIEM, ensuring the SOC has full visibility over the environment.

## 3. Key ISO 27001:2022 Controls Audited
The assessment evaluates compliance against the following Annex A controls:
* **A.8.15** Logging (Event, fault, and security logging)
* **A.8.16** Monitoring activities (Continuous system and network monitoring)
* **A.8.17** Clock synchronization (NTP configuration for accurate log correlation)

## 4. Skills Demonstrated
### Governance & IT Audit
* **Audit Execution:** Planning, scoping, and executing an IT security audit.
* **Finding Drafting:** Writing clear, professional non-conformities (Condition, Criteria, Cause, Risk, Recommendation).
* **Corrective Action Planning (CAPA):** Evaluating management responses for remediation.

### Technical Security Alignment
* **Log Management & SIEM:** Understanding the mechanics of log ingestion, agent deployment (Wazuh), and event correlation.
* **Infrastructure Visibility:** Identifying security gaps in virtualized environments.
