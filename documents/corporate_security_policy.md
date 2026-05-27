# Corporate Information Security Policy
**Document ID:** POL-SEC-001  
**Classification:** Internal Use Only  
**Effective Date:** May 01, 2026  

---

## 1.0 Purpose
The purpose of this policy is to establish a centralized, reusable framework to detect, analyze, and mitigate risks, ensuring the utmost protection of Mr. Repair's infrastructure. This policy is crafted to guarantee continuous business operations at all times.

## 2.0 Scope
This policy applies to all physical locations, third-party vendors, departments, and cloud infrastructures. The risk remediation timelines established herein are binding for all business unit heads.

## 3.0 Risk Assessment Framework & Methodology
The company utilizes a semi-quantitative risk calculation based on the highly recognized **NIST SP 800-30 framework** (the industry standard). 

All identified risks must be logged in the centralized risk register and calculated using the following formula:

$$\text{Risk Rating (RR)} = \text{Likelihood (L)} \times \text{Impact (I)}$$

### 3.1 Likelihood Scale (1–5)
*   **1 – Rare:** Highly improbable; requires a series of chained events or a very sophisticated, state-sponsored actor (likely to occur once every 5 years).
*   **2 – Unlikely:** Possible, but active monitoring and proper controls make it very difficult to exploit (likely to occur every 3–5 years).
*   **3 – Possible:** Expected to occur at some point; an industry-known threat vector (likely to occur once every calendar year).
*   **4 – Likely:** Expected to occur; the target is attacked frequently and exploitation requires minimal specialized skills (likely to occur several times within a calendar year).
*   **5 – Almost Certain:** An obvious, recurring, and imminent threat exposure (likely to occur every day or every week).

### 3.2 Impact Scale (1–5)
This scale defines the magnitude of harm from a security incident across financial, operational, and regulatory parameters.

*   **1 – Insignificant:** Financial loss under $500. No degradation of services; zero regulatory notification required.
*   **2 – Minor:** Financial loss between $500 and $5,000. Minor localized system downtime (under 2 hours); no data exfiltration.
*   **3 – Moderate:** Financial loss up to $25,000. Critical business applications degraded (2 to 12 hours); minor regulatory inquiry or audit finding.
*   **4 – Major:** Financial loss up to $100,000. Core business operations halted (12 to 24 hours); breach of customer data or device privacy resulting in mandatory regulatory notifications (e.g., PCI-DSS or local consumer privacy mandates).
*   **5 – Catastrophic:** Financial loss exceeding $300,000. Broad corporate database destruction, class-action lawsuits, or permanent loss of operating/business licenses.

---

## 4.0 Risk Appetite & Remediation Tiers
The Company defines its risk tolerance across four distinct tiers. Once an Inherent Risk score is established, the appropriate remediation path must be followed:

| Calculated Score | Risk Tier | Required GRC Action / Timeline |
| :--- | :--- | :--- |
| **1 – 4** | Low Risk | **Acceptable:** Risk is noted. Monitored via standard operational patch cycles and reviewed annually. |
| **5 – 11** | Medium Risk | **Mitigate / Accept:** Requires a documented mitigation plan. Risk must be reviewed and formally signed off by the Department Head or Operations Manager. |
| **12 – 19** | High Risk | **Remediate:** Requires management escalation. A formal remediation project must be authorized to apply controls and lower the score **within 30 days**. |
| **20 – 25** | Critical Risk | **Immediate Intervention:** Escalated directly to senior leadership. Controls must be applied immediately to mitigate the threat, or the underlying system/operation must be halted **within 48 hours**. |

---

## 5.0 Risk Treatment Options
When evaluating a risk entry, the Risk Owner must select one of four standard Governance, Risk, and Compliance (GRC) risk treatment strategies:

*   **Mitigation (Treat):** Implementing security controls (e.g., encryption, firewalls, MFA) to decrease the likelihood or impact score.
*   **Acceptance:** Retaining the risk without further mitigation if the cost of the control exceeds the potential impact. This requires formal leadership sign-off.
*   **Transference:** Shifting the financial impact of the risk to a third party (e.g., purchasing comprehensive cyber liability insurance).
*   **Avoidance:** Completely eliminating the risk by terminating the risky activity, software, or vendor configuration.

## 6.0 Policy Enforcement & Review
*   **Mandatory Cadence:** This policy must be reviewed, updated, and re-approved by the management steering committee annually.
*   **Ad-Hoc Assessments:** A localized risk assessment is mandatory prior to onboarding any critical retail vendor, migrating ticketing databases to new cloud infrastructure, or launching public-facing customer tracking platforms.
*   **Non-Compliance:** Failure to adhere to the remediation timelines specified in Section 4.0 will result in a formal escalation to senior leadership and an immediate operational evaluation of the non-compliant business unit.
