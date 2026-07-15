# Gap Analysis — Findings and Risk Assessment

**Document:** 03-Gap-Analysis.md | **Assessment:** OmniCare Health IT Governance | **Total Findings:** 15

---

## Risk Rating Legend

| Rating | Color | Definition |
|---|---|---|
| **Critical** | Red | Immediate remediation required; regulatory or material risk |
| **High** | Orange | Significant risk; medium-term remediation required |
| **Medium** | Yellow | Moderate risk; should be addressed within planning cycle |

No findings were rated Low. The 3×3 impact-likelihood matrix produces 5 theoretical levels, but the methodology collapses 'Very Low' into 'Low' and 'Very High' into 'Critical' for reporting clarity.

---

## Findings Summary

| ID | Finding | Domain | Gap | Risk Rating | COSO Principles |
|---|---|---|---|---|---|
| F01 | No Formal IT Governance Framework | EDM01, APO01 | 2 | **Critical** | 1, 2, 3 |
| F02 | Absence of IT Steering Committee | EDM01, EDM05 | 2 | **Critical** | 1, 2, 16 |
| F03 | No IT Strategy Aligned to Business | APO02 | 2 | **High** | 2, 13 |
| F04 | Fragmented IT Decision-Making | APO01, APO08 | 2 | **High** | 1, 3 |
| F05 | No Enterprise IT Risk Management Process | EDM03, APO12 | 2 | **Critical** | 6, 7 |
| F06 | No Formal Benefits Realization Process | EDM02, BAI01 | 2 | **High** | 10, 16 |
| F07 | Post-Merger IT Integration Challenges | BAI01, BAI03 | 2 | **High** | 7, 11 |
| F08 | Inadequate IT Security Governance | APO13, DSS05 | 2 | **Critical** | 7, 11, 12 |
| F09 | No Enterprise Architecture Function | APO03 | 2 | **Medium** | 10, 13 |
| F10 | Weak IT Human Resource Management | APO07 | 1 | **Medium** | 3, 4 |
| F11 | No IT Performance Monitoring | MEA01 | 2 | **High** | 16, 17 |
| F12 | Lack of Internal Control Framework | MEA02 | 2 | **High** | 1, 2, 10, 11, 12 |
| F13 | Compliance Management Gaps | MEA03 | 2 | **High** | 1, 17 |
| F14 | No Formal IT Operations Management | DSS01 | 1 | **Medium** | 10, 11 |
| F15 | Ineffective Resource Optimisation | EDM04 | 1 | **Medium** | 3, 10 |

---

## 1. Governance Domain — Findings (EDM)

### F01 — No Formal IT Governance Framework

| Attribute | Detail |
|---|---|
| **Gap ID** | F01 |
| **COBIT Objectives** | EDM01 (Ensure Governance Framework), APO01 (Manage IT Management Framework) |
| **Current Maturity** | **1** — Performed (Ad-hoc) |
| **Target Maturity** | **3** — Defined (Standardized) |
| **Maturity Gap** | **2** |
| **Risk Rating** | **Critical** |
| **COSO Principles** | 1 (Demonstrates commitment to integrity/ethical values), 2 (Board oversight responsibilities), 3 (Establishes structure, authority, and responsibility) |
| **Description** | OmniCare has no formal IT governance framework. There is no governance charter, no defined IT decision rights, and no board-level IT oversight committee. Each of the three acquired entities brought a different governance model, none of which have been consolidated. IT governance is effectively absent at the enterprise level. |
| **Root Cause** | Rapid acquisition-driven growth outpaced governance maturity. Leadership focused on revenue integration rather than governance integration. No executive held formal accountability for IT governance. |
| **Business Impact** | Inconsistent IT decisions, uncontrolled technology proliferation, inability to demonstrate SOX readiness, increased compliance risk. |

### F02 — Absence of IT Steering Committee

| Attribute | Detail |
|---|---|
| **Gap ID** | F02 |
| **COBIT Objectives** | EDM01 (Ensure Governance Framework), EDM05 (Ensure Stakeholder Engagement) |
| **Current Maturity** | **1** — Performed (Ad-hoc) |
| **Target Maturity** | **3** — Defined (Standardized) |
| **Maturity Gap** | **2** |
| **Risk Rating** | **Critical** |
| **COSO Principles** | 1 (Board oversight), 2 (Establishes oversight responsibilities), 16 (Conducts ongoing and separate evaluations) |
| **Description** | There is no IT steering committee or equivalent governance body. IT investment prioritization is performed informally by the CEO and CFO without structured input from business units or IT leadership. No formal escalation path exists for IT issues requiring executive attention. |
| **Root Cause** | Historical culture of founder-led decision-making persisted through growth phase. No recognition of need for structured governance body until now. |
| **Business Impact** | Misaligned IT investments, duplication of technology spend, business unit frustration, no forum for strategic IT decision-making. |

### F05 — No Enterprise IT Risk Management Process

| Attribute | Detail |
|---|---|
| **Gap ID** | F05 |
| **COBIT Objectives** | EDM03 (Ensure Risk Optimisation), APO12 (Manage Risk) |
| **Current Maturity** | **1** — Performed (Ad-hoc) |
| **Target Maturity** | **3** — Defined (Standardized) |
| **Maturity Gap** | **2** |
| **Risk Rating** | **Critical** |
| **COSO Principles** | 6 (Specifies objectives with sufficient clarity to enable risk identification), 7 (Identifies and analyzes risks) |
| **Description** | No formal enterprise risk management process for IT. There is no IT risk register, no risk appetite statement, and no regular risk assessment cycle. The 2025 ransomware attack was handled reactively. HIPAA compliance risk is not formally integrated with IT risk management. |
| **Root Cause** | IT risk management viewed as a cybersecurity-only concern. Lack of risk management expertise. No board-level risk appetite definition. |
| **Business Impact** | Undetected and unmitigated IT risks, increased likelihood of security incidents, regulatory non-compliance exposure, potential for material financial loss. |

### F08 — Inadequate IT Security Governance

| Attribute | Detail |
|---|---|
| **Gap ID** | F08 |
| **COBIT Objectives** | APO13 (Manage Security), DSS05 (Manage Security Services) |
| **Current Maturity** | **2** — Managed (Basic) |
| **Target Maturity** | **4** — Measured (Quantitative) |
| **Maturity Gap** | **2** |
| **Risk Rating** | **Critical** |
| **COSO Principles** | 7 (Identifies and analyzes risks), 11 (Selects and develops general control activities over technology), 12 (Deploys controls through policies and procedures) |
| **Description** | While a CISO and security team exist, the security program is not mature. No ISO 27001-aligned ISMS, no formal vulnerability management, no security awareness program, and no security metrics. Security policies from acquired entities are inconsistent. |
| **Root Cause** | Security investment prioritized technology (tools) over governance (policies, processes, metrics). Acquisitions introduced heterogeneous security postures. |
| **Business Impact** | Elevated risk of data breach (healthcare data), HIPAA violation exposure, patient safety risk, reputational damage, potential HHS/OCR implications as company scales. |

*Cross-domain finding — primary domain: Management (APO/DSS)*

---

### F15 — Ineffective Resource Optimisation

| Attribute | Detail |
|---|---|
| **Gap ID** | F15 |
| **COBIT Objectives** | EDM04 (Ensure Resource Optimisation) |
| **Current Maturity** | **2** — Managed (Basic) |
| **Target Maturity** | **3** — Defined (Standardized) |
| **Maturity Gap** | **1** |
| **Risk Rating** | **Medium** |
| **COSO Principles** | 3 (Structure and authority), 10 (Control activities) |
| **Description** | IT budget management is siloed by department. Duplicate tools and platforms across acquired entities (3 EHR systems, 2 identity platforms) indicate resource inefficiency. IT spend at 5.2% of revenue (benchmark: 3.8%) suggests 25-30% cost optimization opportunity. |
| **Root Cause** | No enterprise-level IT resource planning or portfolio rationalization. Acquisitions integrated operationally but not technologically. |
| **Business Impact** | Higher than necessary IT operating costs, capital tied up in redundant systems, inability to redirect resources to strategic initiatives. |

---

## 2. Management Domain — Findings (APO)

### F03 — No IT Strategy Aligned to Business

| Attribute | Detail |
|---|---|
| **Gap ID** | F03 |
| **COBIT Objectives** | APO02 (Manage Strategy) |
| **Current Maturity** | **2** — Managed (Basic) |
| **Target Maturity** | **4** — Measured (Quantitative) |
| **Maturity Gap** | **2** |
| **Risk Rating** | **High** |
| **COSO Principles** | 2 (Board establishes oversight), 13 (Uses relevant information) |
| **Description** | There is an annual IT operating plan but no multi-year IT strategic plan aligned to OmniCare's enterprise strategy. Technology roadmaps are maintained in silos. Digital transformation goals are stated but not quantified, and no metrics track strategic IT contribution. |
| **Root Cause** | IT viewed as operational function rather than strategic partner. No formal strategic planning process exists for IT. |
| **Business Impact** | IT investments may not align with strategic business objectives. Missed opportunities for competitive advantage through technology. Inefficient allocation of capital. |

### F04 — Fragmented IT Decision-Making

| Attribute | Detail |
|---|---|
| **Gap ID** | F04 |
| **COBIT Objectives** | APO01 (Manage IT Management Framework), APO08 (Manage Relationships) |
| **Current Maturity** | **1** — Performed (Ad-hoc) |
| **Target Maturity** | **3** — Defined (Standardized) |
| **Maturity Gap** | **2** |
| **Risk Rating** | **High** |
| **COSO Principles** | 1 (Integrity and ethical values), 3 (Authority and responsibility) |
| **Description** | IT decisions are distributed across business units. Two business units independently procured SaaS solutions without IT involvement in the past 6 months. No formal IT demand management or intake process exists. There is no central IT decision authority. |
| **Root Cause** | Legacy of decentralized operations pre-acquisition. No formal IT governance charter defining decision rights. IT perceived as bottleneck. |
| **Business Impact** | Technology sprawl, redundant spend, integration complexity, security blind spots, inability to enforce standards. |

### F06 — No Formal Benefits Realization Process

| Attribute | Detail |
|---|---|
| **Gap ID** | F06 |
| **COBIT Objectives** | EDM02 (Ensure Benefits Delivery), BAI01 (Manage Programmes and Projects) |
| **Current Maturity** | **1** — Performed (Ad-hoc) |
| **Target Maturity** | **3** — Defined (Standardized) |
| **Maturity Gap** | **2** |
| **Risk Rating** | **High** |
| **COSO Principles** | 10 (Selects and develops control activities), 16 (Conducts ongoing evaluations) |
| **Description** | IT investments lack formal business cases, benefit profiles, or post-implementation reviews. Value tracking is limited to budget variance. Three major platform investments in the past 12 months cannot demonstrate delivered business value. |
| **Root Cause** | No PMO function to enforce investment governance. No culture of benefits accountability. |
| **Business Impact** | Inability to assess IT investment ROI, continued spend on low-value initiatives, difficulty justifying future IT budget requests to the board. |

*Cross-domain finding — primary domain: Governance (EDM)*

### F09 — No Enterprise Architecture Function

| Attribute | Detail |
|---|---|
| **Gap ID** | F09 |
| **COBIT Objectives** | APO03 (Manage Enterprise Architecture) |
| **Current Maturity** | **1** — Performed (Ad-hoc) |
| **Target Maturity** | **3** — Defined (Standardized) |
| **Maturity Gap** | **2** |
| **Risk Rating** | **Medium** |
| **COSO Principles** | 10 (Control activities), 13 (Information and communication) |
| **Description** | No enterprise architecture function, framework, or repository. System documentation is incomplete and outdated. No technology standards or reference architecture. Integration between the telemedicine platform and acquired EHR systems is managed via point-to-point integrations. |
| **Root Cause** | Engineering-led culture prioritized speed of delivery over architectural governance. No architect role established. |
| **Business Impact** | Increasing integration debt, higher cost of change, inability to assess technology landscape for strategic decisions, slower time-to-market for new features. |

### F10 — Weak IT Human Resource Management

| Attribute | Detail |
|---|---|
| **Gap ID** | F10 |
| **COBIT Objectives** | APO07 (Manage Human Resources) |
| **Current Maturity** | **2** — Managed (Basic) |
| **Target Maturity** | **3** — Defined (Standardized) |
| **Maturity Gap** | **1** |
| **Risk Rating** | **Medium** |
| **COSO Principles** | 3 (Authority and responsibility), 4 (Commitment to competence) |
| **Description** | IT roles and responsibilities are defined at the team level but not standardized enterprise-wide. No IT competency framework, no structured career paths, and no formal training program. Voluntary turnover in IT is 12% (vs. 8% benchmark). |
| **Root Cause** | Post-acquisition, key IT personnel left due to role ambiguity. HR and IT have not partnered to develop a workforce plan. |
| **Business Impact** | Loss of institutional knowledge, difficulty retaining talent, inconsistent skill levels across teams, increased recruitment cost. |

---

## 3. BAI Domain — Findings

### F07 — Post-Merger IT Integration Challenges

| Attribute | Detail |
|---|---|
| **Gap ID** | F07 |
| **COBIT Objectives** | BAI01 (Manage Programmes and Projects), BAI03 (Manage Solutions Identification and Build) |
| **Current Maturity** | **1** — Performed (Ad-hoc) |
| **Target Maturity** | **3** — Defined (Standardized) |
| **Maturity Gap** | **2** |
| **Risk Rating** | **High** |
| **COSO Principles** | 7 (Risk identification and analysis), 11 (General control activities over technology) |
| **Description** | Three acquisitions in 24 months have not been systematically integrated into OmniCare's IT environment. Each acquired entity operates on separate infrastructure, separate identity systems, and separate application stacks. Integration projects average 40% behind schedule. |
| **Root Cause** | No formal post-merger IT integration playbook. Integration treated as a project rather than a program. Insufficient resourcing of integration efforts. |
| **Business Impact** | Operational inefficiency, inability to realise acquisition synergies, security vulnerabilities from unintegrated systems, customer experience fragmentation. |

---

## 4. DSS Domain — Findings

### F14 — No Formal IT Operations Management

| Attribute | Detail |
|---|---|
| **Gap ID** | F14 |
| **COBIT Objectives** | DSS01 (Manage Operations) |
| **Current Maturity** | **2** — Managed (Basic) |
| **Target Maturity** | **3** — Defined (Standardized) |
| **Maturity Gap** | **1** |
| **Risk Rating** | **Medium** |
| **COSO Principles** | 10 (Control activities), 11 (General control activities over technology) |
| **Description** | IT operations rely on a basic Jira service desk. Incident response is reactive. No formal problem management, change management is informal, and no service catalogue exists. Unapproved changes are common. MTTR for critical incidents is 8.2 hours (target: 4 hours). |
| **Root Cause** | Operations team is understaffed and tasked with reactive issue resolution. No formal ITSM framework adopted. |
| **Business Impact** | Extended system downtime, user dissatisfaction, risk of change-related incidents, inability to support business-critical healthcare platforms with required uptime. |

---

## 5. MEA Domain — Findings

### F11 — No IT Performance Monitoring

| Attribute | Detail |
|---|---|
| **Gap ID** | F11 |
| **COBIT Objectives** | MEA01 (Monitor, Evaluate and Assess Performance and Conformance) |
| **Current Maturity** | **1** — Performed (Ad-hoc) |
| **Target Maturity** | **3** — Defined (Standardized) |
| **Maturity Gap** | **2** |
| **Risk Rating** | **High** |
| **COSO Principles** | 16 (Conducts ongoing and separate evaluations), 17 (Evaluates and communicates deficiencies) |
| **Description** | No IT balanced scorecard, performance dashboard, or regular performance reporting. Metrics are collected ad-hoc and not linked to strategic objectives. SLA compliance is not monitored. No benchmarking against industry peers. |
| **Root Cause** | No management requirement for IT performance data. IT leadership has not established a measurement culture. |
| **Business Impact** | No visibility into IT value delivery, inability to identify performance issues proactively, lack of data for strategic decision-making, weak business case for IT investments. |

### F12 — Lack of Internal Control Framework

| Attribute | Detail |
|---|---|
| **Gap ID** | F12 |
| **COBIT Objectives** | MEA02 (Monitor, Evaluate and Assess the System of Internal Control) |
| **Current Maturity** | **1** — Performed (Ad-hoc) |
| **Target Maturity** | **3** — Defined (Standardized) |
| **Maturity Gap** | **2** |
| **Risk Rating** | **High** |
| **COSO Principles** | 1 (Integrity), 2 (Oversight), 10 (Control activities), 11 (Technology controls), 12 (Policies and procedures) |
| **Description** | No internal control framework for IT exists. IT general controls (ITGCs) for SOX — including access controls, change management, and program development — are not documented, tested, or monitored. No segregation of duties controls have been defined for IT. |
| **Root Cause** | Company has not previously been subject to SOX requirements. No internal audit function focused on IT controls. |
| **Business Impact** | This is the highest-priority SOX readiness gap. External auditors have preliminarily flagged ITGCs as a material weakness area. Without remediation, SOX compliance is unachievable. |

### F13 — Compliance Management Gaps

| Attribute | Detail |
|---|---|
| **Gap ID** | F13 |
| **COBIT Objectives** | MEA03 (Monitor, Evaluate and Assess Compliance with External Requirements) |
| **Current Maturity** | **1** — Performed (Ad-hoc) |
| **Target Maturity** | **3** — Defined (Standardized) |
| **Maturity Gap** | **2** |
| **Risk Rating** | **High** |
| **COSO Principles** | 1 (Commitment to integrity), 17 (Communicates deficiencies) |
| **Description** | Compliance with HIPAA/HITECH is managed manually. No compliance management tool, no central register of obligations, and no automated monitoring. The compliance function is understaffed (1 FTE for 1,200 employees). Regulatory change monitoring is manual. |
| **Root Cause** | Compliance headcount not scaled with organizational growth. Compliance viewed as a manual, document-centric activity rather than a continuous process. |
| **Business Impact** | Risk of non-compliance with healthcare regulations, potential for regulatory fines, reputational damage, inability to demonstrate compliance to auditors efficiently. |

---

## Root Cause Analysis — Systemic Themes

| Theme | Findings Affected | Description |
|---|---|---|
| **No governance infrastructure** | F01, F02, F04 | The absence of a governance framework, steering committee, and defined decision rights is the foundational deficiency driving most other gaps. |
| **Acquisition integration gap** | F07, F09, F15 | Three acquisitions in 24 months without a systematic integration approach has created technical debt, duplication, and governance fragmentation. |
| **Immature risk and compliance culture** | F05, F08, F12, F13 | Risk management and compliance are treated as ad-hoc activities rather than embedded processes, exposing the company to regulatory and security threats. |
| **No performance measurement** | F06, F11 | Without metrics, dashboards, or benefits tracking, IT cannot demonstrate its value or identify areas for improvement. |
| **Underinvestment in processes** | F10, F14 | IT operations, people management, and service management processes are underdeveloped relative to the scale of the organization. |

---

**Next step:** See [04-Prioritized-Recommendations.md](./04-Prioritized-Recommendations.md) for the remediation roadmap addressing all 15 findings.
