# Awesome-Information-Protection-Rights-Management

## Top Information Protection & Rights Management Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Persistent File Encryption, Digital Rights Management (DRM/IRM), Usage Controls, Persistent Protection & Data-Centric Security*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Information Protection & Rights Management**. These systems apply persistent encryption and usage controls to documents and files so that protection travels with the data—regardless of where it is stored or shared—enforcing who can view, edit, print, or forward content.



**Examples** include Azure Information Protection / Microsoft Purview Information Protection, Virtru, Fasoo, Seclore, Ionic Security, OpenText Information Rights Management, SealPath, NextLabs, and Votiro (the category leaders).



**Open-source emphasis**: Full enterprise Information Rights Management (IRM/EDRM) with persistent protection, dynamic policy, and broad application integration is almost exclusively commercial. Open-source efforts focus on encryption libraries, policy engines, and limited DRM experiments. This section expands what exists while remaining realistic about the commercial gap.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Azure Information Protection / Microsoft Purview Information Protection](https://www.microsoft.com/en-us/security/business/information-protection/microsoft-purview-information-protection)**  

  Microsoft’s data-centric protection platform providing sensitivity labels, encryption, rights management, and integration across Microsoft 365 and beyond.



- **[Virtru](https://www.virtru.com/)**  

  Data protection platform focused on persistent encryption and access controls for email, files, and collaboration tools with strong privacy emphasis.



- **[Fasoo](https://www.fasoo.com/)**  

  Enterprise digital rights management (EDRM) platform offering centralized policy, persistent file protection, and dynamic usage controls.



- **[Seclore](https://www.seclore.com/)**  

  Information rights management solution that protects documents and controls usage after they leave the organization.



- **[Ionic Security](https://www.ionic.com/)**  

  Data security platform providing attribute-based access control and persistent protection for files and data (historically strong in IRM-style controls).



- **[OpenText Information Rights Management](https://www.opentext.com/)**  

  Enterprise IRM capabilities within the OpenText portfolio for protecting sensitive documents and enforcing usage rights.



- **[SealPath](https://www.sealpath.com/)**  

  Information protection and rights management platform focused on persistent document security and control.



- **[NextLabs](https://www.nextlabs.com/)**  

  Data-centric security and entitlement management platform that applies fine-grained controls and protection policies to information.



- **[Votiro](https://www.votiro.com/)**  

  Content disarm and reconstruction (CDR) and data protection platform that sanitizes and protects files entering the organization.



- **[Related Microsoft Purview & MIP ecosystem](https://www.microsoft.com/en-us/security/business/microsoft-purview)**  

  Broader Microsoft information protection stack that includes labeling, DLP, and rights management capabilities.



## Open-Source GitHub Projects

- **[Open Policy Agent (OPA)](https://github.com/open-policy-agent/opa)**  

  General-purpose policy engine that can enforce fine-grained access and usage decisions as part of a data-protection architecture.



- **[Cryptography and file-encryption libraries (libsodium, age, etc.)](https://github.com/)**  

  Foundational open-source encryption tools used to build custom persistent-protection solutions.



- **[age](https://github.com/FiloSottile/age)**  

  Simple, modern, and secure file encryption tool that can form the basis of controlled sharing workflows.



- **[OpenSSL / LibreSSL and related crypto tooling](https://github.com/openssl/openssl)**  

  Core cryptographic libraries underpinning most custom encryption and rights-management experiments.



- **[Experimental open DRM / key-system projects](https://github.com/)**  

  Research and community efforts exploring open implementations of digital rights management or key systems (limited production readiness).



- **[Document classification and labeling helpers](https://github.com/)**  

  Open tools that assist with content classification—often a prerequisite for applying protection policies.



- **[Self-hosted secure file-sharing platforms](https://github.com/)**  

  Projects that combine encryption with access controls for internal document sharing (partial alternative to full IRM).



- **[Policy-as-code frameworks for data access](https://github.com/)**  

  Tools that express and enforce who can do what with sensitive data using declarative policies.



- **[Documentation and encryption + policy playbooks](https://www.openpolicyagent.org/)**  

  Guides for combining open encryption libraries with policy engines to approximate rights-management controls.



- **[Audit and key-management open projects](https://github.com/)**  

  Community solutions for key lifecycle and access logging that support data-protection architectures.



### Additional Strong Open-Source Options

- Building custom persistent encryption workflows with **age**, **libsodium**, or similar libraries plus access-control logic.

- Using **Open Policy Agent** to enforce usage and sharing rules around protected content.

- Accepting that true enterprise IRM features—persistent protection that survives email, cloud storage, and endpoint use, dynamic policy revocation, broad application plugins, and centralized rights management—remain the domain of commercial platforms (Microsoft Purview Information Protection, Virtru, Fasoo, Seclore, SealPath, NextLabs, etc.).

- Focusing open-source efforts on encryption strength, policy flexibility, and data ownership rather than full replacement of commercial IRM.



**Frameworks for building custom systems**: Classify content → encrypt with open libraries → enforce access via policy engine or application-level controls → log usage. Suitable for specialized or internal use cases. Most regulated organizations adopt commercial information protection platforms for broad coverage and usability.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Information protection systems handle highly sensitive data. Custom or open-source encryption solutions require expert design and key management. This list is not security or compliance advice.



---

**Made for data protection teams, security architects, and open security advocates.**

Let's keep sensitive information protected, controlled, and as open as practical.
