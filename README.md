# Awesome-Security-Awareness-Training

## Top Security Awareness Training Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Phishing Simulation, Human Risk Management, Microlearning, Behavioral Change & Compliance Training*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Security Awareness Training**. These systems educate employees, run simulated phishing campaigns, measure click/report rates, and drive lasting behavior change to reduce human risk.



**Examples** include KnowBe4, Hoxhunt, Living Security, Usecure, Cofense PhishMe, Proofpoint Security Awareness, Infosec IQ, Hook Security, Ninjio, and MetaCompliance (the category leaders).



**Open-source emphasis**: Full commercial-grade awareness platforms (content libraries, adaptive training, compliance reporting) are largely proprietary. Strong open-source options exist for **phishing simulation and campaign tooling** — especially **Gophish** and related frameworks. This section lists those tools and is realistic about the remaining gap.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[KnowBe4](https://www.knowbe4.com/)**  

  Largest and most widely deployed security awareness platform — extensive content library, simulated phishing, human risk management, and compliance reporting.



- **[Hoxhunt](https://www.hoxhunt.com/)**  

  Behavior-change focused platform with AI-personalized phishing simulations, high engagement, gamification, and strong reporting-rate metrics.



- **[Living Security](https://www.livingsecurity.com/)**  

  Human risk management and awareness platform emphasizing measurable behavior change and continuous training.



- **[Usecure](https://www.usecure.io/)**  

  Security awareness and phishing simulation platform aimed at practical, ongoing employee education.



- **[Cofense PhishMe](https://cofense.com/)**  

  Phishing simulation and reporting platform tightly linked to Cofense’s phishing detection and response capabilities.



- **[Proofpoint Security Awareness (ZenGuide)](https://www.proofpoint.com/)**  

  Awareness and training offerings integrated with Proofpoint’s email security and threat intelligence ecosystem.



- **[Infosec IQ](https://www.infosecinstitute.com/iq/)**  

  Security awareness training platform with a large content library, assessments, and phishing simulation features.



- **[Hook Security](https://www.hooksecurity.co/)**  

  Phishing simulation and awareness training focused on realistic campaigns and measurable results.



- **[Ninjio](https://ninjio.com/)**  

  Engaging, story-driven security awareness video training designed for high completion and retention.



- **[MetaCompliance](https://www.metacompliance.com/)**  

  Compliance and security awareness platform popular for policy management, training, and regulatory attestation.



## Open-Source GitHub Projects

- **[Gophish](https://github.com/gophish/gophish)**  

  The leading open-source phishing toolkit — create and run phishing campaigns, track opens/clicks/submissions, and support security awareness programs. Self-hosted and widely used.



- **[King Phisher](https://github.com/securestate/king-phisher)**  

  Open-source phishing campaign toolkit with a server/client architecture for more advanced simulation scenarios.



- **[G-SIM and Gophish automation helpers](https://github.com/5urg3on/G-SIM)**  

  Tools that simplify provisioning and running authorized Gophish simulations (e.g., cloud deployment automation).



- **[Social-Engineer Toolkit (SET)](https://github.com/trustedsec/social-engineer-toolkit)**  

  Open-source framework for social-engineering attacks and demonstrations, useful in controlled awareness and red-team exercises.



- **[Evilginx2 and advanced phishing proxies](https://github.com/kgretzky/evilginx2)**  

  Open tools for more sophisticated phishing simulations (including session/token scenarios) — use only in authorized testing.



- **[Custom phishing landing-page and analytics stacks](https://github.com/)**  

  Community projects that combine Gophish with Flask/dashboards for credential-harvest simulation and anonymized reporting.



- **[Open training content and quiz frameworks](https://github.com/)**  

  Free or open educational materials, LMS plugins, and quiz tools that can supplement phishing simulations with formal training modules.



- **[Email security testing and spoofing-check tools](https://github.com/)**  

  Open utilities for testing SPF/DKIM/DMARC and related controls that support awareness of email-based threats.



- **[Reporting-button and browser-extension prototypes](https://github.com/)**  

  Experimental open components for “report phishing” workflows that integrate with internal security teams.



- **[Campaign analytics and visualization scripts](https://github.com/)**  

  Open scripts and dashboards that turn simulation results into actionable awareness metrics.



### Additional Strong Open-Source Options

- Running **Gophish** (or King Phisher) for controlled, authorized phishing simulations and baseline click-rate measurement.

- Pairing open simulation tools with internal LMS or open content for the actual training follow-up.

- Using advanced open frameworks only in tightly scoped, authorized red-team or awareness exercises.

- Building simple internal dashboards on top of Gophish results for leadership reporting.

- Accepting that large content libraries, adaptive AI personalization, gamification at scale, and compliance-ready reporting still favor commercial platforms.

- Starting with open simulation to quantify risk, then evaluating commercial awareness suites when you need continuous training and behavior-change programs.



**Frameworks for building custom systems**: Deploy **Gophish** for simulations → analyze results → deliver targeted training via internal LMS or open content → repeat. This covers the core “measure then educate” loop. Commercial platforms (KnowBe4, Hoxhunt, Proofpoint, Infosec IQ, etc.) remain the practical choice for enterprise content libraries, adaptive campaigns, user experience, and audit-ready compliance reporting.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Phishing simulations must be authorized by the organization. Unauthorized phishing is illegal and unethical. Always obtain proper approval, use clear internal guidelines, and avoid collecting real credentials in production simulations. Open-source tools require secure hosting, access control, and careful template design. Training content should be accurate and kept up to date. This list is not legal or security-compliance advice.



---

**Made for security awareness leads, CISOs, and teams who know the human layer is part of the defense.**

Let's keep training continuous, measurable, and focused on real behavior change.
