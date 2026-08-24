<p align="center">
  <img src="assets/banner.svg" alt="Awesome Insider Risk Management Banner" width="100%" />
</p>

# 🛡️ Awesome-Insider-Risk-Management

<div align="center">

<a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
<a href="https://github.com/ishandutta2007/Awesome-Insider-Risk-Management/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Insider-Risk-Management?style=flat-square&logo=github&color=gold" alt="Stars"/></a>
<a href="https://github.com/ishandutta2007/Awesome-Insider-Risk-Management/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Insider-Risk-Management?style=flat-square&logo=github&color=blue" alt="Forks"/></a>
<a href="https://github.com/ishandutta2007/Awesome-Insider-Risk-Management/pulls"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome"/></a>
<a href="https://github.com/ishandutta2007/Awesome-Insider-Risk-Management/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-green.svg?style=flat-square" alt="License"/></a>
<a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>

</div>

<br/>

> 🔍 **A curated index of top commercial SaaS platforms and open-source cybersecurity repositories for Insider Risk Management (IRM), User & Entity Behavior Analytics (UEBA), Data Loss Prevention (DLP), Privileged User Activity Monitoring (UAM), and Behavioral Threat Detection.**

---

## 📑 Table of Contents

- [🌐 SaaS / Hosted Enterprise Platforms](#-saas--hosted-enterprise-platforms)
- [💻 Open-Source GitHub Projects](#-open-source-github-projects)
- [🧩 Frameworks for Custom Insider Threat Detection](#-frameworks-for-building-custom-systems)
- [🤝 How to Contribute](#-how-to-contribute)
- [📈 Star History](#-star-history)
- [⚖️ Disclaimer](#️-disclaimer)

---

## 🌐 SaaS / Hosted Enterprise Platforms

> 📊 **Estimated Market Size & Sector Structure**: The global Insider Risk Management & Insider Threat Detection market was valued at **$4.8 Billion in 2024** and is projected to reach **$11.9 Billion by 2030**, expanding at a **CAGR of ~18.5%**. The sector is **moderately fragmented**: mega-cap enterprise cloud conglomerates (*Microsoft*) and cybersecurity market incumbents (*Proofpoint, Varonis, Forcepoint*) dominate large enterprise suites, while agile, high-growth pure-play vendors (*Cyberhaven, DTEX, Teramind*) capture substantial market share through specialized data lineage tracing and endpoint UEBA telemetry.

| Platform | Company Size (Valuation / Revenue) | Starting Pricing | Free Tier / Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Microsoft Purview Insider Risk Management](https://www.microsoft.com/en-us/security/business/microsoft-purview)** | **~$3.1T Market Cap** / ~$245B Annual Revenue *(Public: MSFT)* | Starting at **$12.00/user/month** *(Purview Suite add-on for M365 E3)* or included in M365 E5 ($57.00/user/month); compute billing at ~$25 per 10,000 logs (1 DSPU). | **90-day free trial** via Microsoft Purview Portal (up to 25 user licenses / 300 evaluations; no free-forever plan). | Native Microsoft 365 / Azure insider risk solution correlating telemetry across email, files, Teams, and endpoints to identify risky employee activities. |
| **[Proofpoint Insider Threat Management](https://www.proofpoint.com/)** | **~$12.3B Valuation** / ~$1.5B Annual Revenue *(Thoma Bravo)* | Starting at **£13.40 to £62.00 (~$17.00–$80.00)/user/year** (~$1.40–$6.70/user/month) on public framework volume tiers. | **30-day Proof of Concept (PoC)** / complimentary threat assessment trial (full session capture on select test endpoints; no free-forever plan). | Enterprise insider threat platform combining session recording, behavioral risk scoring, and deep email/DLP telemetry. |
| **[ObserveIT (Proofpoint)](https://www.proofpoint.com/)** | **~$12.3B Parent Valuation** *(Acquired for $225M)* / ~$1.5B Rev | Starting at **£62.00 (~$80.00)/monitored endpoint/year** (~$6.70/endpoint/month via G-Cloud framework). | **30-day Proof of Concept (PoC)** trial (session recording & keystroke logging for up to 20 test endpoints; no free-forever plan). | Dedicated session-recording, keystroke logging, and user-activity monitoring technology integrated into Proofpoint's security portfolio. |
| **[Code42 Incydr](https://www.code42.com/)** | **~$5.8B Parent Valuation** *(Mimecast / Permira)* / ~$600M Rev | Starting at **$30.00–$45.00/user/year** (~$2.50–$3.75/user/month) for core endpoint monitoring with annual contract minimums. | **30-day Proof of Value (POV)** guided trial (evaluates file movement and data exposure across test machines; no free-forever plan). | Data-exfiltration focused platform tracking file movement across endpoints, cloud storage, and email without heavy upfront policy tuning. |
| **[Varonis Data Security Platform](https://www.varonis.com/)** | **~$5.5B Market Cap** / ~$550M ARR *(Public: VRNS)* | Starting at **$50.00–$95.00/user/year** (~$4.15–$7.90/user/month) for core SaaS Data Security Platform (DSP) modules. | **30-day free trial** / complimentary Data Risk Assessment (DRA) covering automated discovery across enterprise repositories; no free-forever plan. | Data-centric security platform specialized in access governance, permissions analysis, and behavioral detection of abnormal file access. |
| **[Forcepoint Insider Threat](https://www.forcepoint.com/)** | **~$2.4B Valuation** / ~$450M Annual Revenue *(Francisco Partners)* | Starting at **£119.00–£129.20 (~$150.00–$165.00)/endpoint/year** (~$12.50–$13.75/endpoint/month) on public framework schedules. | **30-day guided evaluation trial** (limited to test endpoints with video playback and policy alert capture; no free-forever plan). | Insider threat platform integrated with Forcepoint’s DLP and human-centric behavioral risk analytics. |
| **[Securonix](https://www.securonix.com/)** | **~$1.5B Valuation** / ~$120M ARR *(Vista Equity Partners)* | Starting at **$15.00–$25.00/GB/day** data ingestion (~$3.00–$5.00/user/month equivalent) with entry enterprise tiers starting at $15,000/year. | **30-day guided Proof of Concept (PoC)** trial (limited to 10–25 GB/day log ingestion for UEBA baseline anomaly modeling; no free-forever plan). | Next-gen SIEM and cloud UEBA platform with machine learning behavioral models designed for detecting insider threats and fraud. |
| **[Cyberhaven](https://www.cyberhaven.com/)** | **~$1.0B Valuation** / ~$52M Annual Revenue *(Series D)* | Starting at **$35.00–$48.00/user/year** (~$3.00–$4.00/user/month) with entry enterprise annual commitments starting around $30,000/year. | **14 to 30-day Proof of Value (POV)** structured trial (limited to data lineage tracking across designated test endpoints/cloud apps; no free-forever plan). | Data detection and response (DDR) platform that traces data lineage to detect unauthorized file exfiltration and shadow AI usage. |
| **[DTEX Systems (InTERCEPT)](https://www.dtexsystems.com/)** | **~$350M–$400M Valuation** / ~$35M+ ARR *(CapitalG / Alphabet)* | Starting at **$35.00–$60.00/endpoint/year** (~$3.00–$5.00/user/month) with enterprise annual minimums starting at $25,000/year. | **30-day Proof of Value (POV)** trial (monitors 100–500 test endpoints for metadata-only behavioral baseline; no free-forever plan). | Enterprise insider risk platform emphasizing privacy-preserving metadata analytics and lightweight endpoint behavioral scoring. |
| **[Teramind](https://www.teramind.co/)** | **~$120M–$150M Valuation** / ~$25M ARR *(Bootstrapped / Profitable)* | Starting at **$11.25/user/month** *(Starter tier billed annually, 5-user minimum = $56.25/mo)* or $15.00/user/month monthly; UAM tier starts at $22.50/user/month. | **7-day free trial** for Cloud deployments (or **14-day free trial** for On-Premise) for up to 5 users/endpoints with full features; no free-forever plan. | Employee monitoring and insider threat detection platform with real-time screen recording, keystroke logging, and automated policy rules. |

---

## 💻 Open-Source GitHub Projects

*Open-source tools, telemetry frameworks, SIEM rule packs, and UEBA analytics toolkits sorted by GitHub stars in descending order.*

1. **[osquery](https://github.com/osquery/osquery)** [![osquery Stars](https://img.shields.io/github/stars/osquery/osquery?style=social&color=white)](https://github.com/osquery/osquery/stargazers)  
   ⚡ Operating system instrumentation framework that exposes an entire OS as a high-performance relational SQL database, widely deployed for real-time endpoint telemetry, process anomaly tracking, and insider threat hunting.

2. **[ActivityWatch](https://github.com/ActivityWatch/activitywatch)** [![ActivityWatch Stars](https://img.shields.io/github/stars/ActivityWatch/activitywatch?style=social&color=white)](https://github.com/ActivityWatch/activitywatch/stargazers)  
   🔒 Privacy-first, open-source automated user and employee activity tracker that records application usage, window titles, and active working intervals with local-only data storage.

3. **[Wazuh](https://github.com/wazuh/wazuh)** [![Wazuh Stars](https://img.shields.io/github/stars/wazuh/wazuh?style=social&color=white)](https://github.com/wazuh/wazuh/stargazers)  
   🛡️ Open-source enterprise security platform delivering unified XDR, SIEM, File Integrity Monitoring (FIM), and behavioral anomaly detection for monitoring privileged user activity and unauthorized file modifications.

4. **[Sigma](https://github.com/SigmaHQ/sigma)** [![Sigma Stars](https://img.shields.io/github/stars/SigmaHQ/sigma?style=social&color=white)](https://github.com/SigmaHQ/sigma/stargazers)  
   📝 Generic, open signature format and rule collection for SIEM systems, offering hundreds of community-curated behavioral detection rules for privilege escalation, abnormal data access, and suspicious exfiltration patterns.

5. **[Caldera](https://github.com/mitre/caldera)** [![Caldera Stars](https://img.shields.io/github/stars/mitre/caldera?style=social&color=white)](https://github.com/mitre/caldera/stargazers)  
   🎯 MITRE's automated cyber adversary and insider threat emulation platform, enabling security teams to test detection defenses against simulated insider sabotage and credential misuse.

6. **[Security Onion](https://github.com/Security-Onion-Solutions/securityonion)** [![Security Onion Stars](https://img.shields.io/github/stars/Security-Onion-Solutions/securityonion?style=social&color=white)](https://github.com/Security-Onion-Solutions/securityonion/stargazers)  
   🧅 Free and open platform for threat hunting, enterprise security monitoring, and log management, integrating endpoint data analysis and full packet inspection.

7. **[Logparser](https://github.com/logpai/logparser)** [![Logparser Stars](https://img.shields.io/github/stars/logpai/logparser?style=social&color=white)](https://github.com/logpai/logparser/stargazers)  
   📊 Open-source machine learning benchmark toolkit for automated log parsing, structuring raw activity logs into events for downstream UEBA anomaly detection and user behavioral clustering.

8. **[Loki](https://github.com/Neo23x0/Loki)** [![Loki Stars](https://img.shields.io/github/stars/Neo23x0/Loki?style=social&color=white)](https://github.com/Neo23x0/Loki/stargazers)  
   🔍 Simple, lightweight cross-platform IOC and internal anomaly scanner that audits endpoints for suspicious scripts, file anomalies, and malicious process activity.

9. **[BinaryAlert](https://github.com/airbnb/binaryalert)** [![BinaryAlert Stars](https://img.shields.io/github/stars/airbnb/binaryalert?style=social&color=white)](https://github.com/airbnb/binaryalert/stargazers)  
   🚨 Airbnb's open-source serverless detection engine that analyzes uploaded file telemetry and detects potential malicious or unauthorized binary staging.

10. **[Elastic Detection Rules](https://github.com/elastic/detection-rules)** [![Elastic Detection Rules Stars](https://img.shields.io/github/stars/elastic/detection-rules?style=social&color=white)](https://github.com/elastic/detection-rules/stargazers)  
    ⚙️ Open repository of production detection rules for Elastic Security, containing dedicated rulesets for UEBA, credential dumping, lateral movement, and data exfiltration.

11. **[Sysmon Modular](https://github.com/olafhartong/sysmon-modular)** [![Sysmon Modular Stars](https://img.shields.io/github/stars/olafhartong/sysmon-modular?style=social&color=white)](https://github.com/olafhartong/sysmon-modular/stargazers)  
    🧩 Modular, community-maintained configuration repository for Microsoft Sysmon, tailored for deep endpoint telemetry collection, file modification tracking, and insider threat logging.

12. **[CASER](https://github.com/mitre/caser)** [![CASER Stars](https://img.shields.io/github/stars/mitre/caser?style=social&color=white)](https://github.com/mitre/caser/stargazers)  
    📚 MITRE's open ontology and framework for modeling insider threat cases, incident response workflows, and behavioral risk scoring.

---

## 🧩 Frameworks for Building Custom Systems

To construct an open-source or hybrid insider risk analytics pipeline:
1. **Telemetry Ingestion**: Collect endpoint, identity, and data-access telemetry via [Sysmon](https://github.com/olafhartong/sysmon-modular), [osquery](https://github.com/osquery/osquery), or [Wazuh](https://github.com/wazuh/wazuh).
2. **Data Pipeline & Normalization**: Parse and normalize events with [Logparser](https://github.com/logpai/logparser) into ClickHouse, Elasticsearch, or OpenSearch.
3. **Behavioral Analytics & UEBA**: Apply anomaly detection algorithms (Isolation Forests, Autoencoders, rolling baseline metrics) or rules from [Sigma](https://github.com/SigmaHQ/sigma) and [Elastic Rules](https://github.com/elastic/detection-rules).
4. **Privacy-by-Design**: Implement pseudonymization, data retention policies, and threshold-based identity reveals to safeguard employee privacy and ensure compliance.

---

## 🤝 How to Contribute

Contributions are welcome! To contribute:
1. Fork the repository 🍴
2. Add or update entries in `README.md` (keep descriptions factual, pricing specific, and link official sources)
3. Ensure open-source entries include valid GitHub links and star badges 🌟
4. Submit a Pull Request with a short summary of changes 🚀

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Insider-Risk-Management&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Insider-Risk-Management&type=date&legend=top-left)

---

## ⚖️ Disclaimer

- This is a **community-curated** list for research, evaluation, and security engineering purposes.
- Insider threat monitoring involves sensitive employee data and requires careful policy design, legal review, and strict data-minimization practices.
- Always align monitoring programs with applicable labor laws, privacy regulations (e.g., GDPR, CCPA), and involve HR, legal, and privacy stakeholders.

---

<div align="center">
  <sub>Built with ❤️ for security engineers, threat hunters, and insider risk specialists.</sub>
</div>

