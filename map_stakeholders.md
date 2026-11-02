# Map Stakeholders

## Economic buyer
Potential titles: VP/Director of Marketplace Operations, Trust & Safety, or Compliance Operations.
Cares about: Operational cost, compliance risk, throughput, and measurable ROI.
Your pitch: “We want to reduce the time your team spends processing one defined category of compliance cases, without sacrificing decision quality.”
Ask: “Who owns the budget for improving this workflow, and how would you evaluate its financial impact?”

## Internal champion
Potential title: Head of Compliance Operations or Senior Program Manager.
Cares about: Backlogs, manual investigation, repeated work, and meeting service-level targets.
Your pitch: “Let's measure one workflow and demonstrate whether evidence gathering and case preparation can be automated.”
Ask: “Which case type causes the most repeated manual work, and can we inspect anonymised examples?”
Why this role matters: The champion helps you obtain data, coordinate stakeholders, and navigate internal approval.

## End users
Potential titles: Compliance analysts, seller-enforcement specialists, case investigators, and team leads.
Cares about: Accurate evidence, fewer repetitive tasks, easy review, and clear escalation paths.
Your pitch: “The system prepares the case and evidence; you retain control over the decision.”
Ask: “Walk me through the last case you handled, from receipt to resolution.”
Risk: Users may resist a tool that adds review work or makes decisions harder to explain.

## IT / Engineering / Security
Potential titles: Enterprise Architect, Platform Engineering Lead, Information Security, or AI Governance Lead.
Cares about: API access, architecture, identity and permissions, data isolation, observability, and production reliability.
Your pitch: “We will start with least-privilege, read-only access and documented controls, then request write permissions only when justified.”
Ask: “What are the approved integration patterns and security requirements for a third-party AI workflow?”
Risk: Security review, inaccessible APIs, or restrictions on using company data with external AI providers. Amazon's published vendor security policy illustrates why data handling and vendor controls require early review. Amazon Vendor Security Policy

## Legal / Privacy / Compliance Policy
Potential titles: Corporate Counsel, Privacy Counsel, Compliance Policy Lead.
Cares about: Correct policy interpretation, evidence traceability, seller fairness, data protection, and accountability.
Your pitch: “The system cites approved policies, records its recommendations, and leaves consequential decisions to authorised employees.”
Ask: “Which decisions must remain human-controlled, and what evidence must be retained for an audit?”
Amazon's published marketplace legal roles explicitly cover seller services, marketplace trust, consumer protection, privacy, and related matters. Amazon Jobs

## Procurement / Finance
Potential titles: Strategic Sourcing, Vendor Management, Procurement, Finance Business Partner.
Cares about: Commercial justification, vendor due diligence, contracts, payment terms, and supplier risk.
Your pitch: “The pilot has a defined scope, acceptance criteria, data boundaries, and an explicit decision point before expansion.”
Ask: “What vendor onboarding, security documentation, and commercial approvals are required for a paid pilot?”
Risk: An enthusiastic business team cannot proceed until vendor qualification and contracting are complete.

## Likely blockers to plan for
- No clear budget owner: operations may feel the pain, while a separate technology or shared-services group controls spend.
- Fragmented ownership across business units: each unit may use different case definitions, policies, or approval paths, undermining a shared workflow.
- Data-access constraints: marketplace case data may not be available through an approved API or export; do not assume a connector is permitted.
- Security or privacy objections: external processing, data retention, model usage, or broad MCP permissions may be unacceptable without a constrained data path.
- Legal concern about agent authority: counsel may object if the system appears to decide compliance outcomes or submit appeals without a human.
- Frontline resistance: analysts may distrust recommendations if they create extra review work or fail on edge cases.
- Unproven ROI: “70% faster” is not established; without a baseline and agreed measures, the champion may struggle to secure funding.
- Procurement friction: vendor onboarding, liability terms, or a lack of an approved purchasing route can delay a pilot.