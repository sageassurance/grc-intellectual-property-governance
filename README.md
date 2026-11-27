# Enterprise Intellectual Property Governance & Compliance Assessment

**Portfolio author:** Cierra Jennings

**Status:** Five-phase educational portfolio complete; organizational implementation, lab testing, and remediation validation pending | **Type:** Independent simulated enterprise GRC engagement | **Role:** GRC Program Manager (simulated)

## Cybersecurity focus

This project examines how an organization could protect proprietary source code, prevent unauthorized software deployment, and detect or escalate control failures. The assessment links preventive controls such as least privilege and software approval to detective controls such as logging and inventory reconciliation. It also defines the evidence an independent reviewer would need to test those controls and verify remediation.

## Executive summary
An employee adapts and installs proprietary customer-service software from a former employer without authorization. Management proposes wider deployment and rejects negotiating with the original owner. This project evaluates copyright, software licensing, insider risk, governance accountability, and operational exposure, then designs a risk-based remediation and assurance program.

The scenario is adapted from *Who Can Change Proprietary Source Code?* (originally *Property*), Center for the Study of Ethics in Society, Western Michigan University, edited by Michael Pritchard. This is an educational simulation, not a real client engagement. Ratings, proposed controls, and schedules are illustrative; no actual audit or implementation is claimed.

## Scope
Corporate governance; enterprise risk; copyright and licensing; source-code protection; insider risk; software acquisition; onboarding and offboarding; asset management; incident response; audit and assurance; business continuity; ethics and non-retaliation.

## Assessment criteria
- U.S. Copyright Act, 17 USC §§ 101, 106, 201; U.S. Copyright Office Circular 30.
- NIST CSF 2.0 and SP 800-53 Rev. 5.
- ISO/IEC 27001:2022 and ISO 31000:2018.
- CIS Controls v8.1, COBIT 2019, ACM Code of Ethics.

Frameworks are voluntary assessment criteria here, not asserted legal obligations.

## Incident analysis
The employee contributed to the original system, received an ethical warning, installed an adapted version, and later proposed licensing when management expressed interest in wider deployment. Management rejected negotiation. The method of transfer, actual deployment scope, existing controls and realized losses remain unverified. Investigate repository logs, offboarding records, endpoint installation logs, licensing records, training acknowledgments and management communications before concluding control failures.

## Preliminary risk register
Illustrative inherent scores: likelihood × impact, each 1–5. Residual risk pending evidence and testing.

| ID | Risk | L | I | Score |
|---|---|---:|---:|---:|
| R-001 | Copyright infringement | 5 | 5 | 25 |
| R-002 | Unauthorized enterprise deployment | 5 | 5 | 25 |
| R-003 | Management override | 4 | 5 | 20 |
| R-004 | Loss of intellectual property | 4 | 5 | 20 |
| R-005 | Litigation and financial liability | 4 | 5 | 20 |
| R-006 | Unauthorized code modification | 4 | 4 | 16 |
| R-007 | Reputational damage | 4 | 4 | 16 |
| R-008 | Retaliation | 3 | 5 | 15 |
| R-009 | Operational disruption | 3 | 4 | 12 |
| R-010 | Inventory inaccuracies | 3 | 4 | 12 |

## Preliminary control mapping
| Control | Objective |
|---|---|
| NIST CM-8 | Component inventory |
| NIST CM-10 | Software usage restrictions |
| NIST CM-11 | User-installed software |
| NIST PS-4 | Personnel termination |
| NIST AC-6 | Least privilege |
| NIST IR-4 | Incident handling |
| ISO 27001 A.5.32 | Intellectual property rights |
| ISO 27001 A.8.4 | Source-code access |
| ISO 27001 A.8.19 | Operational software installation |
| ISO 27001 A.5.11 | Return of assets |

## Proposed response
Suspend unauthorized use and expansion in coordination with legal and IT, preserve evidence, determine ownership and deployment scope, obtain a valid license or replace the software, and escalate management override through independent governance channels. Design preventive controls including DLP, application allowlisting, repository access restrictions, software inventory, licensing reviews, centralized logging and protected reporting.

## Proposed 90-day roadmap
| Days | Workstream |
|---|---|
| 0–7 | Containment |
| 0–21 | Legal investigation |
| 7–30 | Risk assessment |
| 15–40 | Control gap analysis |
| 25–55 | Policy development |
| 35–75 | Control implementation planning |
| 45–80 | Training and awareness |
| 70–90 | Testing and closure planning |

## Proposed performance indicators
Zero unauthorized installations, overdue critical remediation items and unapproved exceptions; 100% licensing compliance, inventory coverage, offboarding completion, IP training completion and critical control testing pass rate. These are targets, not measured results.

## Portfolio workstreams
The scenario assessment and initial control designs are documented below. Ten proposed governance policies and a master policy register are published. The integrated Phase 2 workbook is published below. The Phase 3 simulated audit is published below. The Phase 4 dashboard and briefing are published below. Authorized lab testing remains planned.

### Assessment documents
- [Stakeholder and accountability assessment](01-project-governance/stakeholder-accountability.md)
- [Incident assessment and evidence gaps](02-incident-investigation/case-assessment.md)
- [Risk treatment decision](03-risk-management/risk-treatment-decision.md)
- [Legal and ethical analysis](04-compliance/legal-and-ethical-analysis.md)
- [Preventive governance and control design](05-policies-and-controls/preventive-governance.md)
- [Corrective action plan](06-remediation/action-plan.md)

### Governance policy suite
[Master policy register and ten proposed policies](05-policies-and-controls/policy-register.md). Drafting complete; approval, adoption, framework validation and testing remain pending.

### Phase 2 · Enterprise GRC management workbook

[Download the integrated Excel workbook](03-risk-management/cierra-jennings-enterprise-grc-workbook.xlsx). Its 14 worksheets cover executive reporting, risk scoring and heat maps, obligations, controls, framework mappings, gaps, remediation, policies, evidence, exceptions, performance indicators, and audit follow-up. Open **Risk Methodology** to set the simulated reporting date and trace inputs to their source documents.

Inherent ratings and schedules are illustrative. Residual ratings await evidence-backed review. Control implementation, operating effectiveness, and framework mappings remain unverified. The audit findings register contains scenario observations and test hypotheses for Phase 3.

### Phase 3 · Control testing and audit assurance

- [Audit assurance report](07-audit-and-assurance/cierra-jennings-phase-3-audit-assurance.md)
- [Control testing workbook](07-audit-and-assurance/cierra-jennings-phase-3-control-testing.xlsx)

The exercise evaluated 14 synthetic records across seven proposed controls and documented five illustrative findings. Organizational evidence collection, authorized lab testing and remediation validation remain pending.

### Phase 4 · Executive reporting

- [Executive dashboard](08-executive-reporting/cierra-jennings-phase-4-executive-dashboard.xlsx)
- [Executive briefing](08-executive-reporting/cierra-jennings-phase-4-executive-briefing.pptx)

The dashboard is a point-in-time snapshot of the Phase 2 risk assessment and Phase 3 exercise. The briefing presents the containment, licensing or replacement, and independent oversight decisions proposed for leadership. Organizational control effectiveness and residual risk await evidence.

### Phase 5 · Project closeout and handoff

[Project closeout and handoff](09-project-closure/cierra-jennings-phase-5-project-closeout.md) records portfolio acceptance status, lessons learned, the seven open remediation actions, proposed monitoring, and the evidence required for an independent operational closure decision.

### Remaining scenario work and optional portfolio extensions

| Workstream | Planned deliverables |
|---|---|
| 01 Project governance | Charter, stakeholder register, RACI |
| 02 Incident investigation | Incident report and timeline; collect and verify requested evidence |
| 03 Risk management | Evidence-backed residual risk assessment |
| 04 Compliance | Confirm applicability, validate framework alignment, and assess gaps through testing |
| 05 Policies and controls | Ten proposed policy drafts published; detailed incident response playbook and assurance pending |
| 06 Remediation | Implementation, acceptance evidence, and closure |
| 07 Audit and assurance | Authorized lab testing, evidence collection, and independent remediation validation |
| 08 Executive reporting | Refresh the dashboard and briefing after evidence-backed reassessment |
| 09 Project closure | Evidence-backed risk disposition and independent operational closure approval |

## Professional competencies
GRC analysis, enterprise risk assessment, compliance mapping, control design and testing, incident governance, cross-functional accountability, remediation planning and executive reporting.

## Additional cybersecurity case study

[Alderline Civic Systems](case-studies/alderline-civic-systems/README.md) is a fictional govtech provider that runs a municipal permit portal. The case study links vendor data protection, selected NIST CSF 2.0 gaps, a policy approval workflow, and corrective actions with independent retest criteria.

## Future extension
A separate AI governance simulation may evaluate proprietary source-code exposure through external generative AI services using NIST AI RMF and ISO/IEC 42001. This is outside the original incident scope.
