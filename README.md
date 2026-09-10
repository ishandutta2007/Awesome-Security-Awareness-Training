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

- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Platform / Product | Description | Pricing (Starting Tier) | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- |
| **[KnowBe4](https://www.knowbe4.com/)** | Enterprise security awareness platform with simulated phishing, human risk management (HRM), compliance modules, and extensive interactive training. | **$1.80 / user / month** ($21.60/user/yr billed annually for Silver tier, 25–50 seats; min. 25 users) | **Free Phishing Security Test** (up to 100 users, single campaign) + free assessment tools (RanSim, Weak Password Test); **30-day trial** on select modules. |
| **[Hoxhunt](https://www.hoxhunt.com/)** | AI-personalized, gamified behavior-change platform with adaptive phishing simulations, automated rewards, and real-time response telemetry. | **~$32.00 / user / year** (~$2.70/user/mo for mid-market plans; enterprise packages start near $10,000/yr) | **14 to 30-day guided pilot / PoC trial** for qualified enterprise organizations; no permanent free tier. |
| **[Living Security](https://www.livingsecurity.com/)** | Human Risk Management (HRM) platform providing science-backed training, gamified CyberEscape rooms, and cross-tool risk analytics (Unify). | **~$30.00 / user / year** (training tier; full enterprise HRM subscriptions typically start at $25,000/yr) | **Interactive demo environment** (hands-on risk analytics via "Livvy" AI) + free standalone **"Campaign in a Box"** training content; no permanent free tier. |
| **[Usecure](https://www.usecure.io/)** | Modular security awareness platform including auto-enrolling training (uLearn), phishing simulation (uPhish), policy management (uPolicy), and breach monitoring (uBreach). | **£1.50 / user / month** (~$1.95/user/mo or $23.40/user/yr; flexible monthly/annual billing) | **14-day full-access free trial** across all core modules (no credit card required); free NFR license for MSPs. |
| **[Cofense PhishMe](https://cofense.com/)** | Phishing simulation and threat reporting solution integrated with crowdsourced threat intelligence and automated incident response (Cofense Triage). | **~$30.00 / user / year** (PhishMe + Triage bundle; base high-volume tiers start ~$10.00–$12.00/user/yr) | **Custom guided proof-of-concept trial** (approx. 14–30 days via sales consultation) + free public access to Cofense Phishing Threat Database; no permanent free tier. |
| **[Proofpoint Security Awareness (ZenGuide)](https://www.proofpoint.com/)** | Enterprise awareness training and phishing simulation suite integrated with Proofpoint email security telemetry and Targeted Attack Protection (TAP). | **~$1.50 / user / month** (~$18.00/user/yr billed annually for entry tier; volume-tiered) | **30-day proof-of-concept evaluation** via sales consultation + free one-time **People Risk Assessment** diagnostic. |
| **[Infosec IQ](https://www.infosecinstitute.com/iq/)** | Security awareness and anti-phishing platform offering 2,000+ training modules, adaptive learning pathways, and learner assessment dashboards. | **~$3.50 / user / year** (annual entry contracts typically start around $1,500/year minimum) | **Free Phishing Risk Test** (1 simulated phishing campaign for up to 100 learners) + **7-day free trial** for Infosec Skills content library. |
| **[Hook Security](https://www.hooksecurity.co/)** | Non-punitive, "psychological security" awareness training featuring humor-driven microlearning videos and realistic phishing campaigns. | **$2.00 / user / month** ($20.00/user/yr for 50+ users; flat $999/yr for <50 users; starter plans from $39/mo) | **14-day free trial** with access to simulation campaigns and microlearning modules; free product demo. |
| **[Ninjio](https://ninjio.com/)** | Microlearning platform featuring 3–4 minute animated, story-driven episodes based on actual security incidents, paired with simulated phishing tests (NINJIO PHISH). | **~$1.50 / user / month** (~$15.00–$35.00/user/yr depending on volume and add-ons) | **Free 3-episode trial pack** (full access to 3 animated episodes and quiz assessments) + guided product demo; no permanent free tier. |
| **[MetaCompliance](https://www.metacompliance.com/)** | Comprehensive European compliance, cyber security e-learning, automated policy management, and simulated phishing platform. | **~$10.00 / user / year** (~£8.00–£22.49/user/yr based on volume and tier) | **14-day free trial** (limited to 10 users and 1 administrator, full feature testing) + free 30-minute interactive demo. |



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
