# Hands-on-SIEM-Platforms-Detection-Engineering-Threat-Hunting-CTF-Labs-SecByte-Index
A practical collection of cybersecurity CTF labs covering Enterprise SIEMs (Microsoft Sentinel, Elastic SIEM, Wazuh, QRadar), Detection Engineering 101, Threat Hunting (IOCs, IOAs), MITRE ATT&amp;CK Mapping, and Cyber Kill Chain Analysis.
# Enterprise SIEM Platforms, Detection Engineering & Threat Hunting CTF Labs

Welcome to the **Enterprise SIEM Platforms, Detection Engineering & Threat Hunting CTF Lab Collection**. This repository serves as an organized, searchable catalog of practical cybersecurity labs hosted on Learn SecByte.

This collection focuses on centralizing telemetry and proactive defense—including **Enterprise SIEM Platforms (Microsoft Sentinel, Elastic Security, Wazuh, IBM QRadar)**, **Detection Engineering & Rule Authoring**, **Proactive Threat Hunting**, and **Threat Framework Mapping (MITRE ATT&CK, Cyber Kill Chain)**.

---

## Lab Collection Index

### 1. Enterprise SIEM Platforms
* **Microsoft Sentinel Basics**  
  *Lab Link:* [https://learn.secbyte.org/ctf/microsoft-sentinel-basics](https://learn.secbyte.org/ctf/microsoft-sentinel-basics)  
  *Focus:* Ingesting security logs via Data Connectors, writing basic KQL queries, configuring analytics rules, and managing incident workbooks.

* **Elastic SIEM: Zero to Detection Engineer**  
  *Lab Link:* [https://learn.secbyte.org/ctf/elastic-siem-zero-detection-engineer](https://learn.secbyte.org/ctf/elastic-siem-zero-detection-engineer)  
  *Focus:* Setting up Elastic Agent/Filebeat telemetry pipelines, authoring EQL and ES|QL detection rules, tuning threshold triggers, and building security dashboards.

<Image src="image_agent_tag_8435658717119001519" alt="Elastic SIEM rule monitoring dashboard displaying detection execution metrics" caption="Elastic SIEM Detection Rule Monitoring Overview" />

---

* **Wazuh Fundamentals**  
  *Lab Link:* [https://learn.secbyte.org/ctf/wazuh-fundamentals](https://learn.secbyte.org/ctf/wazuh-fundamentals)  
  *Focus:* Deploying open-source Wazuh agents, configuring XML decoders and custom rules, auditing file integrity monitoring (FIM), and vulnerability assessment.

* **QRadar Essentials**  
  *Lab Link:* [https://learn.secbyte.org/ctf/qradar-essentials](https://learn.secbyte.org/ctf/qradar-essentials)  
  *Focus:* Navigating IBM QRadar DSM log sources, writing AQL (Ariel Query Language) searches, building Custom Rules Engine (CRE) logic, and offense management.

### 2. Detection Engineering & Rule Creation
* **Detection Engineering 101**  
  *Lab Link:* [https://learn.secbyte.org/ctf/detection-engineering-101](https://learn.secbyte.org/ctf/detection-engineering-101)  
  *Focus:* The detection engineering lifecycle, telemetry validation, log source evaluation, eliminating false positives, and baseline rule testing.

* **Detection Rule Creation**  
  *Lab Link:* [https://learn.secbyte.org/ctf/detection-rule-creation](https://learn.secbyte.org/ctf/detection-rule-creation)  
  *Focus:* Constructing robust correlation logic, implementing behavioral thresholds, setting severity scoring, and authoring cross-platform rule triggers.

### 3. Proactive Threat Hunting & Threat Intelligence
* **Threat Hunting Basics**  
  *Lab Link:* [https://learn.secbyte.org/ctf/threat-hunting-basics](https://learn.secbyte.org/ctf/threat-hunting-basics)  
  *Focus:* Formulating hunting hypotheses, querying raw log repositories, establishing activity baselines, and searching for anomalous host/network behavior.

* **Advanced Threat Hunting: Hunting the Adversary**  
  *Lab Link:* [https://learn.secbyte.org/ctf/advanced-threat-hunting-hunting-the-adversary](https://learn.secbyte.org/ctf/advanced-threat-hunting-hunting-the-adversary)  
  *Focus:* Executing iterative threat hunts against persistent adversaries, unearthing living-off-the-land (LotL) techniques, and converting findings into SIEM rules.

* **Indicators of Compromise: Theory & Hunt**  
  *Lab Link:* [https://learn.secbyte.org/ctf/indicators-of-compromise-theory-hunt](https://learn.secbyte.org/ctf/indicators-of-compromise-theory-hunt)  
  *Focus:* Hunting for atomic/computed IOCs (file hashes, IP addresses, domains), analyzing indicator decay, and integrating threat feeds into SIEM platforms.

* **Indicators of Attack (IOA)**  
  *Lab Link:* [https://learn.secbyte.org/ctf/indicators-of-attack-ioa](https://learn.secbyte.org/ctf/indicators-of-attack-ioa)  
  *Focus:* Detecting behavioral Indicators of Attack (IOAs) focused on adversary intent, TTP execution, and real-time execution anomalies rather than static file hashes.

### 4. Threat Framework Analysis & Mapping
* **MITRE ATT&CK Mapping Mastery**  
  *Lab Link:* [https://learn.secbyte.org/ctf/mitre-attack-mapping-mastery](https://learn.secbyte.org/ctf/mitre-attack-mapping-mastery)  
  *Focus:* Systematically mapping security alerts, threat hunter findings, and SIEM rules to MITRE ATT&CK tactics, techniques, and sub-techniques.

* **Cyber Kill Chain Analysis**  
  *Lab Link:* [https://learn.secbyte.org/ctf/cyber-kill-chain-analysis](https://learn.secbyte.org/ctf/cyber-kill-chain-analysis)  
  *Focus:* Analyzing multi-stage intrusion campaigns, mapping event timelines across kill chain phases, and strategically interrupting attack paths.

---

## Learning Path

### Path A: SIEM Engineer & Operations Specialist
1. **Platform Foundations:** Start with [Microsoft Sentinel Basics](https://learn.secbyte.org/ctf/microsoft-sentinel-basics), [Elastic SIEM: Zero to Detection Engineer](https://learn.secbyte.org/ctf/elastic-siem-zero-detection-engineer), [Wazuh Fundamentals](https://learn.secbyte.org/ctf/wazuh-fundamentals), and [QRadar Essentials](https://learn.secbyte.org/ctf/qradar-essentials).
2. **Rule Engineering:** Master detection logic authoring in [Detection Engineering 101](https://learn.secbyte.org/ctf/detection-engineering-101) and [Detection Rule Creation](https://learn.secbyte.org/ctf/detection-rule-creation).

### Path B: Threat Hunter & Detection Analyst
1. **Hunting Fundamentals:** Begin with [Threat Hunting Basics](https://learn.secbyte.org/ctf/threat-hunting-basics), [Indicators of Compromise: Theory & Hunt](https://learn.secbyte.org/ctf/indicators-of-compromise-theory-hunt), and [Indicators of Attack (IOA)](https://learn.secbyte.org/ctf/indicators-of-attack-ioa).
2. **Advanced Hunting & Frameworks:** Deep dive into advanced hunting and mapping via [Advanced Threat Hunting](https://learn.secbyte.org/ctf/advanced-threat-hunting-hunting-the-adversary), [MITRE ATT&CK Mapping Mastery](https://learn.secbyte.org/ctf/mitre-attack-mapping-mastery), and [Cyber Kill Chain Analysis](https://learn.secbyte.org/ctf/cyber-kill-chain-analysis).

---

## How to Use the Labs

1. Select a practice scenario from the **Lab Collection Index**.
2. Click the corresponding link to open the exercise directly on Learn SecByte.
3. Review scenario directives, log datasets, and platform consoles.
4. Write KQL/EQL/AQL queries, build SIEM detection rules, execute threat hunting hypotheses, or map TTPs to capture flags.

---

## Target Audience

* **SIEM Engineers & Administrators:** Deploy, configure, and maintain enterprise SIEM platforms (Microsoft Sentinel, Elastic, Wazuh, QRadar).
* **Detection Engineers & SOC Analysts:** Author high-fidelity detection rules, reduce false positives, and map alerts to MITRE ATT&CK.
* **Threat Hunters:** Conduct hypothesis-driven threat hunting across host and network telemetry using IOCs and IOAs.
* **Cybersecurity Students:** Gain hands-on experience using industry-standard SIEM tools and threat hunting methodologies.

---

## Disclaimer

All lab links in this repository direct to official training environments hosted on Learn SecByte. All materials and exercises are provided strictly for educational purposes, defensive skill building, and authorized security research.
