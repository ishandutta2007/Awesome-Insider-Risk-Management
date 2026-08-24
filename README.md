# Awesome-Insider-Risk-Management

## Top Insider Risk Management Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Insider Threat Detection, User & Entity Behavior Analytics (UEBA), Data Exfiltration Monitoring, Privileged User Oversight & Behavioral Risk Scoring*

**Last updated: August 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Insider Risk Management**. These systems detect and help mitigate risks from employees, contractors, and privileged users — including data exfiltration, policy violations, account misuse, and anomalous behavior — through behavioral analytics, activity monitoring, and risk scoring.



**Examples** include Microsoft Purview Insider Risk, Code42 Incydr, Proofpoint Insider Threat, DTEX Systems, Teramind, Varonis, ObserveIT (Proofpoint), Cyberhaven, Forcepoint Insider Threat, and Securonix (the category leaders).



**Open-source emphasis**: Fully featured commercial-grade insider risk platforms are rare in pure open source. Most activity is in UEBA prototypes, user-activity analytics, endpoint telemetry tools, and research systems. This section is expanded with the strongest available open projects and building blocks.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Microsoft Purview Insider Risk Management](https://www.microsoft.com/en-us/security/business/microsoft-purview)**  

  Native Microsoft 365 / Azure insider risk solution that correlates signals across email, files, Teams, and endpoints to identify risky user behavior within the Microsoft ecosystem.



- **[Code42 Incydr](https://www.code42.com/)**  

  Data-exfiltration focused platform that tracks file movement across endpoints, cloud, and email vectors and scores risk without heavy upfront policy configuration.



- **[Proofpoint Insider Threat Management](https://www.proofpoint.com/)**  

  Insider threat solution (including former ObserveIT capabilities) combining session recording, behavioral risk scoring, and integration with email and DLP controls.



- **[DTEX Systems (InTERCEPT)](https://www.dtexsystems.com/)**  

  Enterprise insider risk platform emphasizing metadata-based behavioral analytics and privacy-preserving risk scoring across large user populations.



- **[Teramind](https://www.teramind.co/)**  

  Employee monitoring and insider threat platform with session recording, activity tracking, and policy enforcement capabilities.



- **[Varonis](https://www.varonis.com/)**  

  Data-centric security platform strong in access governance, permissions analysis, and behavioral detection of anomalous data access that can indicate insider risk.



- **[ObserveIT (Proofpoint)](https://www.proofpoint.com/)**  

  Session-recording and user-activity monitoring technology now part of Proofpoint’s insider threat portfolio.



- **[Cyberhaven](https://www.cyberhaven.com/)**  

  Data-detection and response platform focused on tracking sensitive data movement and preventing insider-driven exfiltration.



- **[Forcepoint Insider Threat](https://www.forcepoint.com/)**  

  Insider threat capabilities integrated with Forcepoint’s DLP and human-centric security portfolio.



- **[Securonix](https://www.securonix.com/)**  

  SIEM and UEBA platform with strong behavioral analytics used for insider threat detection and broader security operations.



## Open-Source GitHub Projects

- **[Open UEBA and insider-threat detection prototypes](https://github.com/)**  

  Research and community projects that apply machine learning (Isolation Forest, One-Class SVM, etc.) to user activity logs for anomaly and insider-risk scoring.



- **[INSEC and privacy-respectful insider-threat platforms](https://github.com/)**  

  Emerging open efforts aiming at enterprise-grade insider-threat detection with endpoint telemetry, UEBA, policy controls, and privacy-by-design features.



- **[Sysmon + UEBA scoring agents](https://github.com/)**  

  Prototypes that consume Windows Sysmon (or equivalent) events, build rolling behavioral features, and produce per-event or per-user risk scores.



- **[User Behavior Analytics (UBA) toolkits](https://github.com/)**  

  Open AI/ML pipelines that ingest activity logs, extract behavioral indicators, detect anomalies, and generate alerts and visualizations.



- **[ActivityWatch](https://github.com/ActivityWatch/activitywatch)**  

  Privacy-focused, open-source automated activity tracker that can serve as a local telemetry source for experimental behavioral analytics.



- **[Endpoint and process-monitoring open tools](https://github.com/)**  

  User-mode and educational EDR-style projects that log suspicious process, file, and persistence activity useful for insider-risk research.



- **[Open data-access and file-activity collectors](https://github.com/)**  

  Scripts and agents that capture file open/copy/upload events and feed them into custom risk models.



- **[SIEM + open UEBA rule sets](https://github.com/)**  

  Detection content and correlation rules for Elastic, Wazuh, or similar platforms aimed at insider and privileged-user use cases.



- **[Privacy-preserving monitoring frameworks](https://github.com/)**  

  Designs and prototypes that emphasize pseudonymization, minimal content inspection, and threshold-based identity reveal.



- **[SOC dashboard and risk-scoring notebooks](https://github.com/)**  

  Open visualization and scoring examples that turn raw activity data into analyst-friendly risk views.



### Additional Strong Open-Source Options

- Combining Wazuh / Elastic Security with custom behavioral rules and ML jobs for insider-oriented detection.

- Open DLP and content-inspection components used cautiously for high-risk data channels.

- Audit-log pipelines from identity providers, cloud apps, and endpoints into a central analytics store.

- Research datasets and benchmarks for evaluating insider-threat detection algorithms.

- Policy-as-code and response-playbook examples for containment actions after high-risk scores.



**Frameworks for building custom systems**: Collect endpoint, identity, and data-access telemetry (Sysmon, cloud audit logs, file events), store it in an open analytics platform (Elastic, ClickHouse, etc.), apply open UEBA/anomaly models, and surface risk scores in a SOC dashboard. Enforce privacy controls (pseudonymization, limited retention, content avoidance) from the start. This approach can provide useful visibility for smaller environments or research, but production insider-risk programs at scale still typically rely on commercial platforms for coverage, tuning, legal defensibility, and support.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Insider risk monitoring involves sensitive employee data and significant legal, privacy, and workplace implications. Open-source tools provide transparency but still require careful policy design, legal review, employee notice, and data-minimization practices. Misuse can create serious compliance and trust issues.

- Always align monitoring programs with applicable labor, privacy, and employment laws, and involve HR, legal, and privacy stakeholders.



---

**Made for security, insider-risk, and privacy teams seeking practical approaches to behavioral risk detection.**

Let's make insider risk management more transparent, privacy-aware, and evidence-based.
