# Awesome-Governance-Risk-n-Compliance

## Top Governance, Risk & Compliance (GRC) Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Compliance Automation, Risk Management, Audit Preparation & Control Monitoring*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Governance, Risk & Compliance (GRC)**. These tools help security teams, compliance officers, and startups achieve SOC 2, ISO 27001, HIPAA, GDPR, and NIS2 compliance through automated evidence collection, risk registers, control mapping, and audit workflows.

**Examples** include Vanta, Drata, Secureframe, Hyperproof, LogicGate, AuditBoard, MetricStream, ServiceNow GRC, OneTrust, and ZenGRC (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom compliance frameworks, and transparent audit trails — ideal for startups that need SOC 2 without $20k/year SaaS fees, and enterprises that want full data ownership.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Vanta](https://www.vanta.com/)**
  Automated compliance platform covering SOC 2, ISO 27001, HIPAA, and GDPR. Provides continuous control monitoring, evidence collection, vendor risk management, and a Trust Center. The category leader for startups seeking rapid compliance.

- **[Drata](https://drata.com/)**
  Compliance automation platform with 100+ integrations. Automates evidence collection, personnel compliance, and control monitoring across SOC 2, ISO 27001, HIPAA, PCI DSS, and GDPR.

- **[Secureframe](https://secureframe.com/)**
  Compliance automation platform with AI-powered capabilities. Covers SOC 2, ISO 27001, HIPAA, PCI DSS, GDPR, and CCPA with continuous monitoring and risk assessment.

- **[Hyperproof](https://hyperproof.io/)**
  GRC platform with a unique approach to cross-framework compliance. Allows teams to map controls across multiple standards simultaneously, reducing duplicate work. Known for flexibility and integration breadth .

- **[LogicGate Risk Cloud](https://www.logicgate.com/)**
  No-code GRC platform for custom risk and compliance workflows. Strong enterprise adoption (61% enterprise customers) with modular applications and workflow builder . Pricing typically enterprise-focused with no free tier .

- **[AuditBoard](https://www.auditboard.com/)**
  Connected risk platform for audit, risk, and compliance teams. Strong in SOX compliance and internal audit with 48% enterprise adoption. Features regulatory change management and control testing .

- **[MetricStream](https://www.metricstream.com/)**
  Enterprise GRC platform covering risk management, compliance, audit, and cyber risk. Used by large financial institutions and regulated industries.

- **[ServiceNow GRC](https://www.servicenow.com/)**
  GRC module within the ServiceNow platform. Integrates risk management, policy compliance, and audit management into enterprise service management workflows.

- **[OneTrust](https://www.onetrust.com/)**
  Privacy, security, and data governance platform. Primarily known for privacy management (GDPR, CCPA) and consent management, with broader GRC capabilities.

- **[ZenGRC](https://www.zengrc.com/)**
  GRC platform (formerly Reciprocity) focused on compliance automation and risk management. Mid-market focused with 59% mid-market adoption .

## Open-Source GitHub Projects

- **[Probo](https://github.com/getprobo/probo)**
  Self-hostable GRC platform built for engineering and security teams. AI-native design with 270+ MCP tools exposing every entity for LLM agents (Claude, Cursor, Continue). Full GRC coverage: risk management, controls, vendor risk, data privacy (DPIA/TIA), access reviews, audit programs. Multiple interfaces: Web console, `prb` CLI (44+ command groups), MCP API, GraphQL, n8n community node. ISC licensed, Docker deployment .

- **[CISO Assistant](https://github.com/intuitem/ciso-assistant-community)**
  Open-source cybersecurity management and GRC platform from French firm intuitem. Ships with **134+ compliance frameworks** including ISO 27001, NIST CSF, PCI DSS, GDPR, NIS2, DORA, SOC 2, CMMC, HIPAA. Automatic cross-framework control mapping: satisfy a control in one framework, platform identifies equivalents across others. Evidence propagates. Docker deployment in hours. Community Edition free, Pro tier €2,400/year. AGPL v3 .

- **[Cairn](https://github.com/frousselet/cairn)**
  Self-hosted GRC platform with ISO 27001, GDPR, NIS2 compliance tracking. Enforces governance via record lifecycles (no status dropdowns — state changes are permissioned transitions leaving audit trails). Full REST API + built-in MCP server. Optional AI (Mistral, OpenAI, Claude, Ollama) off by default. Django 5.2, PostgreSQL 16, Bootstrap 5.3 + HTMX. Single container deployment. AGPL v3 .

- **[Eramba](https://www.eramba.org/)**
  Open-source GRC platform for information security. Includes risk management, compliance management, incident management, and policy management. Community edition available; Enterprise pricing ~$208/mo on-premise, ~$417/mo SaaS. Beats LogicGate Risk Cloud on overall scoring in recent comparisons .

- **[Comp AI](https://github.com/trycompai/comp)**
  AI-native compliance platform positioned as direct Vanta/Drata alternative. Automated evidence collection with AI agent that builds collection automations from plain-language prompts. AI Policy Editor with diff viewer. Device Agent for macOS/Windows/Ubuntu checks (disk encryption, antivirus, password policy, screen lock). Cloud integrations (AWS, GCP, Azure). AGPL v3 with Open Core model — ~99% of codebase open source .

- **[Unicis Platform CE](https://github.com/UnicisTech/unicis-platform-ce)**
  All-in-one GRC solution positioned as open-source alternative to Vanta, Drata, and AuditBoard. Features standards/frameworks mapping, Statement of Applicability (SoA) export (HTML/PDF/Excel), REST API with OpenAPI 3.0, webhooks, audit logs, RBAC, dark mode, i18n (7 languages), WCAG 2.1 AA accessibility. Coming soon: Custom Framework Support, Jira integration, Continuous Control Monitoring .

- **[Compliance Gap Analyzer](https://github.com/CyberEnthusiastic/compliance-gap-analyzer)**
  RAG-based policy analyzer mapping security docs against SOC 2 and ISO 27001. Zero dependencies (pure Python stdlib). Keyword matching + TF-IDF cosine similarity + negation detection (catches "we do NOT have MFA"). Outputs coverage scores, COVERED/PARTIAL/MISSING status, verbatim evidence snippets, remediation hints. Interactive dark-mode HTML report. MIT licensed .

- **[Evidentia](https://pypi.org/project/evidentia/)**
  Open-source GRC tool with OSCAL (NIST open standard) for inputs/outputs — no vendor lock-in. 89 frameworks bundled. Library-first, CLI-second, API-third architecture. AI via LiteLLM + Instructor with provider-agnostic access (OpenAI, Anthropic, Google, Ollama, vLLM). Federal compliance features: POA&M lifecycle, CONMON cycle calendar, FedRAMP-aligned severity filtering. Python-based .

- **[Openlane](https://github.com/theopenlane/core)**
  Open-source compliance and risk management platform. Go-based with GraphQL API, multi-tenant file storage (S3, R2, disk), entitlement management, and provider integrations. Includes catalog management, event emitters, and background job specifications .

- **[ConsentOS](https://github.com/consentos/consentos)**
  Self-hosted consent management platform — open-source alternative to OneTrust/Cookiebot for the consent/privacy layer of GRC. Single `<script>` tag embed. Standards-complete: IAB TCF v2.3, GPP v1 (six US state sections), Google Consent Mode v2, GPC. Auto-blocking of non-consented scripts, Playwright cookie scanner with 2,200+ patterns, dark pattern detection, compliance rules for GDPR/CNIL/CCPA/ePrivacy/LGPD. Elastic Licence 2.0 .

### Additional Strong Open-Source Options

- **Compliance Automation**: **Probo** (AI-native, MCP-first), **Comp AI** (Vanta/Drata alternative), **CISO Assistant** (134+ frameworks).
- **Risk Management**: **Eramba** (risk/compliance/incident), **Cairn** (ISO 27005/EBIOS RM risk assessments), **Openlane** (catalog + entitlements).
- **Policy Analysis**: **Compliance Gap Analyzer** (SOC 2/ISO 27001 gap analysis, zero deps).
- **Standards & Mapping**: **Evidentia** (OSCAL-native, 89 frameworks), **Unicis** (cross-framework mapping).
- **Privacy & Consent**: **ConsentOS** (self-hosted CMP, IAB TCF v2.3).

**Frameworks for building custom systems**: Combine **CISO Assistant** or **Probo** for core GRC, **ConsentOS** for privacy/consent management, **Compliance Gap Analyzer** for policy gap analysis, and **Evidentia** for OSCAL-compliant reporting. Add **PostgreSQL** for persistence and **Ollama** for self-hosted AI assistance.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- GRC platforms handle sensitive compliance and risk data; ensure proper access controls, audit logging, and data protection.
- Self-hosted open-source solutions require security hardening, regular updates, and compliance team ownership. Open-source GRC covers the software license, not the operational cost of running compliance programs.

---

**Made for security engineers, compliance officers, CISO teams, and startup founders.**
Let's make compliance more open, transparent, and accessible.
