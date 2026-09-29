<div align="center">

  <br><br>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=32&pause=75&speed=150&color=FF0000&center=true&vCenter=true&width=600&lines=Hey!+%F0%9F%91%8B;I'm+Josiah+Azimi;Identity+%26+Systems+Engineer" alt="Typing Greeting" />

  <h3>Wayne | Secure Enterprises & Automation</h3>

  <p align="center">
    <a href="https://linkedin.com/">
      <img src="https://img.shields.io/badge/LinkedIn-0072b1?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <img src="https://komarev.com/ghpvc/?username=jossywayne23-bit&label=Visitors&color=blue&style=for-the-badge" alt="Visitors" />

  </p>
<br>

<p align="center">
  The projects in this portfolio simulate the real workflows of an Identity & Access Management professional in enterprise environments. Every project is built, broken, and documented from scratch — claims map to actual run output and actual error text, never to illustrative examples. My background in networking brings systems-level understanding of traffic flow and segmentation to identity architecture. Currently completing CyberArk Defender, targeting IAM Engineer roles in Privileged Access Management and Zero Trust identity governance.

📫 How to reach me **josiah.azimi@gmail.com**

</div>

---

## Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/Microsoft_Entra_ID-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/CyberArk_PAM-EF3B2D?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Okta-007DC1?style=for-the-badge&logo=okta&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS_IAM_Identity_Center-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/HashiCorp_Vault-000000?style=for-the-badge&logo=vault&logoColor=white" />
  <img src="https://img.shields.io/badge/Active_Directory-0078D4?style=for-the-badge&logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white" />
  <img src="https://img.shields.io/badge/Microsoft_Graph-2C2C2C?style=for-the-badge&logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure_Automation-0089D6?style=for-the-badge&logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/SCIM_2.0-6E4C9F?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/SAML_2.0_%2F_SSO-00B388?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Zero_Trust-333333?style=for-the-badge&logoColor=white" />
</p>
<p align="center"><b>Currently building:</b> entra-identity-governance — Access Packages · Access Reviews · PIM just-in-time elevation</p>

---

## Certifications

<p align="center">
  <img src="https://img.shields.io/badge/SC--900-Security_Compliance_%26_Identity_Fundamentals-0078D4?style=flat-square&logo=microsoft&logoColor=white" />
  &nbsp;
  <img src="https://img.shields.io/badge/SC--300-Identity_%26_Access_Administrator-0078D4?style=flat-square&logo=microsoft&logoColor=white" />
  &nbsp;
  <img src="https://img.shields.io/badge/CyberArk-Trustee-EF3B2D?style=flat-square&logoColor=white" />
  &nbsp;
  <img src="https://img.shields.io/badge/MTCNA-MikroTik_Certified_Network_Associate-293239?style=flat-square&logoColor=white" />
  &nbsp;
  <img src="https://img.shields.io/badge/CyberArk_PAM_Defender-In_Progress-EF3B2D?style=flat-square&logoColor=white" />
</p>
<p align="center"><sub>Foundational coursework: CyberArk University — Introduction to PAM · Full CyberArk PAM Defender course (Udemy)</sub></p>

---

## Portfolio Projects

### [entra-hr-provisioning-pipeline](https://github.com/jossywayne23-bit/entra-hr-provisioning-pipeline)
Unattended joiner-mover-leaver automation between an HRIS and Entra ID, running as Azure Automation runbooks under a managed identity. An HR system error propagates at machine speed, so there is a safety gate in front of every write and a read-only reconciliation control in front of the whole pipeline. Live-tested end to end — joiner, mover, leaver, and rehire — at 109 HR records.

**Key areas covered:** Volume-threshold circuit breaker, read-only reconciliation control, termination detection, duplicate prevention, post-run success validation, credential expiry monitoring, ISO 27001 / NIST 800-53 control mapping.

---

### [aws-iam-entra-id-saml](https://github.com/jossywayne23-bit/aws-iam-entra-id-saml)
SAML 2.0 federation and SCIM 2.0 provisioning connecting Microsoft Entra ID to AWS IAM Identity Center, replacing standing IAM user credentials with federated temporary access and least-privilege role mapping.

**Key areas covered:** SAML 2.0 SSO, SCIM automated provisioning, Entra ID enterprise app configuration, AWS IAM role mapping, elimination of static access keys, least-privilege session design.

---

### [entra-identity-governance](https://github.com/jossywayne23-bit/entra-identity-governance)
Access governance layer on an Entra ID P2 tenant with ID Governance, kept separate from the scripted pipeline so native tooling and custom automation can be compared on operating cost rather than theory.

**Key areas covered:** Lifecycle Workflows, Access Packages with approval and expiry policies, segregation of duties, recurring Access Reviews, PIM just-in-time elevation, break-glass account monitoring, Defender Secure Score remediation.

> Runbooks committed — full four-file documentation in progress.

---

### [Microsoft-Entra-ID-Okta-SAML-2.0-SSO-Integration](https://github.com/jossywayne23-bit/Microsoft-Entra-ID-Okta-SAML-2.0-SSO-Integration)
SAML 2.0 federation with Microsoft Entra ID as Identity Provider and Okta as Service Provider, including just-in-time provisioning, live assertion capture, and element-by-element validation.

**Key areas covered:** SAML 2.0 federation, metadata exchange, assertion validation, JIT provisioning, attribute and claims mapping, System Log analysis for mapping failures.

---

### [PAM-Fundamentals-CyberArk-Architecture](https://github.com/jossywayne23-bit/PAM-Fundamentals-CyberArk-Architecture)
Architecture reference documenting the CyberArk Vault's role in a PAM deployment — network isolation model, component communication design across PVWA, CPM and PSM, and Disaster Recovery design.

**Key areas covered:** Vault isolation architecture, single-firewall-exception communication model, component placement strategy, Safe-based access segregation, DR Vault failover design, communication port reference.

---

## Documentation Standard

Every project follows a consistent four-file structure: `README.md` (business problem + at-a-glance summary), `ARCHITECTURE.md` (design decisions and compliance mapping), `WALKTHROUGH.md` (full step-by-step build), and `TROUBLESHOOTING.md` (real errors encountered, root cause, and fix — no illustrative examples).

---

## Connect

<p align="center">
  <a href="[Your LinkedIn URL]">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>

---

<p align="center">
  <img src="https://img.shields.io/badge/-IAM-333?style=flat-square" />
  <img src="https://img.shields.io/badge/-PAM-333?style=flat-square" />
  <img src="https://img.shields.io/badge/-Zero_Trust-333?style=flat-square" />
  <img src="https://img.shields.io/badge/-Entra_ID-333?style=flat-square" />
  <img src="https://img.shields.io/badge/-CyberArk-333?style=flat-square" />
  <img src="https://img.shields.io/badge/-Okta-333?style=flat-square" />
  <img src="https://img.shields.io/badge/-JML_Automation-333?style=flat-square" />
  <img src="https://img.shields.io/badge/-AWS_IAM_Identity_Center-333?style=flat-square" />
  <img src="https://img.shields.io/badge/-Identity_Governance-333?style=flat-square" />
  <img src="https://img.shields.io/badge/-Conditional_Access-333?style=flat-square" />
  <img src="https://img.shields.io/badge/-SAML_%2F_SSO-333?style=flat-square" />
</p>
