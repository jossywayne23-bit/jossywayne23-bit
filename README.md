<div align="center">

# Josiah Azimi

### Identity & Access Management (IAM) — Entra ID · Conditional Access · RBAC

![SC-300](https://img.shields.io/badge/SC--300-Identity%20%26%20Access%20Administrator-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![SC-900](https://img.shields.io/badge/SC--900-Security%2C%20Compliance%20%26%20Identity-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![MTCNA](https://img.shields.io/badge/MTCNA-MikroTik%20Certified%20Network%20Associate-293239?style=flat-square)

</div>

---

## About Me

I specialize in Identity and Access Management (IAM), focusing on the exact controls that govern who gets access to what systems and for how long. My core expertise is rooted in Microsoft Entra ID, where I have built and tested Conditional Access policies, RBAC models, and Identity Governance frameworks from scratch in hands-on lab environments. 

I believe in learning by doing, not just cramming for certifications. Currently, I am expanding my reach into Okta federation, CyberArk PAM, and AWS IAM, while using PowerShell and Microsoft Graph to automate workflows and drive toward a deeper specialization in privileged access.

---

## 🎓 Certifications

| Certification | Issuer | What It Validates |
|---|---|---|
| **SC-300** — Identity and Access Administrator Associate | Microsoft | Designing, implementing, and operating identity and access solutions in Entra ID |
| **SC-900** — Security, Compliance, and Identity Fundamentals | Microsoft | Foundational security, compliance, and identity concepts across Microsoft cloud services |
| **MTCNA** — MikroTik Certified Network Associate | MikroTik | Core networking: routing, switching, wireless, and RouterOS administration |

---

## 🧰 Focus Areas & Tools

**In active use**

![Entra ID](https://img.shields.io/badge/Microsoft%20Entra%20ID-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Conditional Access](https://img.shields.io/badge/Conditional%20Access-0078D4?style=flat-square)
![RBAC](https://img.shields.io/badge/RBAC-6E40C9?style=flat-square)
![Identity Governance](https://img.shields.io/badge/Identity%20Governance-0078D4?style=flat-square)
![osTicket](https://img.shields.io/badge/osTicket%20ITSM-2A3F54?style=flat-square)

**Building toward**

![Okta](https://img.shields.io/badge/Okta-007DC1?style=flat-square&logo=okta&logoColor=white)
![CyberArk](https://img.shields.io/badge/CyberArk%20PAM-FF5C35?style=flat-square)
![AWS IAM](https://img.shields.io/badge/AWS%20IAM-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Microsoft Graph](https://img.shields.io/badge/Microsoft%20Graph%20API-0078D4?style=flat-square&logo=microsoft&logoColor=white)

---

## ✅ Completed Projects

### Identity Governance & Access Reviews

**[Microsoft Entra ID — Identity Governance Access Reviews](https://github.com/jossywayne23-bit/Microsoft-Entra-ID-Identity-Governance-Access-Reviews)**
Hands-on lab configuring Entra ID Access Reviews — periodic recertification of group and application access to surface stale or unnecessary permissions before they become an audit finding.
*Skills: Entra ID · Identity Governance · Access Reviews*

### Conditional Access & Risk-Based MFA

**[Conditional Access Configuration — Entra ID](https://github.com/jossywayne23-bit/Conditional-Access-Configuration---Entra-ID)**
Baseline Conditional Access policy build-out in Entra ID — the foundation the two projects below extend.
*Skills: Entra ID · Conditional Access*

**[Location-Based MFA with Conditional Access](https://github.com/jossywayne23-bit/Location-Based-MFA-with-Conditional-Access)**
Conditional Access policies that require MFA based on network location, separating trusted from untrusted sign-in locations.
*Skills: Conditional Access · Named Locations · MFA*

**[Block MFA Registration for Risky Users](https://github.com/jossywayne23-bit/BLOCK-MFA-Registration-for-Risky-Users-Sign-in-risk-policy-to-block-suspicious-logins)**
Sign-in risk policy built on Entra ID Protection that blocks MFA registration and sign-in for risky users, with blocked attempts captured as evidence.
*Skills: Identity Protection · Risk-Based Policy · Conditional Access*

### RBAC & Access Control

**[RBAC Permission Matrix — Microsoft Entra ID](https://github.com/jossywayne23-bit/rbac_permission_matrix)**
Maps **8 job roles to 34 granular Entra ID permissions** across 7 permission categories, implemented with built-in roles and security groups, and validated with **10 boundary tests in a live lab tenant (10/10 pass)** — proof least privilege was enforced at the platform level, not just documented on paper.
*Skills: Entra ID · RBAC · Least Privilege · Boundary Testing*

### ITSM Deployment — osTicket (3-Phase Build)

A ground-up osTicket deployment, staged across three phases — directly relevant to IAM, since access requests and offboarding tickets typically live in exactly this kind of system.

| Phase | Project | Focus |
|---|---|---|
| 1 | [osTicket Prerequisites](https://github.com/jossywayne23-bit/osTicket-prereQs) | Environment and prerequisite setup |
| 2 | [osTicket Post-Installation Config](https://github.com/jossywayne23-bit/osticket-Post-Installation-Config) | System configuration after install |
| 3 | [osTicket Ticket Lifecycle](https://github.com/jossywayne23-bit/osTicket-Ticket-Lifecycle) | Ticket lifecycle and workflow |

---

## 🎯 IAM / PAM

Nine projects, sequenced to build from Entra ID fundamentals up to enterprise PAM and cloud IAM.

| # | Focus Area | Status | Stack | What I'll Build | Risk It Addresses |
|---|---|---|---|---|---|
| 01 | MFA & Conditional Access | ✅ Completed | Microsoft Entra ID · Conditional Access · Identity Protection | CA policies enforcing phishing-resistant MFA, with blocked sign-in attempts captured as evidence | Weak authentication controls leading to credential compromise |
| 02 | RBAC Design & Implementation | ✅ Completed | Microsoft Entra ID · AWS IAM | Permission matrix extended from Entra ID into a second cloud platform, with least-privilege boundaries validated | Over-privileged accounts and access sprawl creating audit failures |
| 03 | User Lifecycle — JML | 🔄 In Progress | Microsoft Entra ID · Okta (sandbox) | Joiner-Mover-Leaver process built simultaneously across two identity platforms | Orphaned accounts and stale access after employee offboarding |
| 04 | SSO & Federation — Okta ↔ Entra ID | 🔄 In Progress | Okta · Microsoft Entra ID · SAML 2.0 | Bidirectional SAML 2.0 federation with assertion-level inspection | Password sprawl and insecure application access across multiple platforms |
| 05 | PAM Fundamentals — CyberArk Architecture | 🔄 In Progress | CyberArk (Vault, PVWA, CPM, PSM) — CyberArk University labs | Core PAM architecture: vault, web access, credential rotation, session isolation | Foundational PAM knowledge gap before enterprise deployment work |
| 06 | CyberArk Enterprise Lab + Entra ID SAML | ⬜ Queued | CyberArk Privilege Cloud · Microsoft Entra ID (SAML IdP) | Enterprise PAM safe integrated with Entra ID as the SAML identity provider | Disconnected identity silos between CyberArk and Entra ID, creating audit gaps and compliance failures |
| 07 | Cloud IAM Policy Design — AWS | ⬜ Queued | AWS IAM · Policy Simulator · Access Analyzer | Least-privilege cloud policies, validated and tightened using AWS's own analysis tools | Over-permissive cloud IAM policies increasing attack surface |
| 08 | Access Reviews & Audit Readiness | ✅ Completed | Microsoft Entra ID (Identity Governance) · Excel | Recurring access reviews with inactive accounts flagged and results documented for audit | Failed compliance audits from excessive, unreviewed access permissions |
| 09 | IAM Automation — PowerShell + Graph API | ⬜ Queued | PowerShell · Microsoft Graph API | Script that creates a user, assigns a group, and generates an access report | Manual IAM operations that should be automated for consistency and scale |

Completed items are documented in full in the Completed Projects section above.

---

## 📫 Connect

- Email: josiah.azimi@gmail.com

---

<sub>All projects are built in personal lab / non-production tenants for hands-on skills development. </sub>
