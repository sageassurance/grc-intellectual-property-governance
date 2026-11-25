# Enterprise Intellectual Property Governance & Compliance Assessment

**Status:** Scenario assessment complete; implementation and assurance deliverables in progress | **Type:** Independent simulated enterprise GRC engagement | **Role:** GRC Program Manager (simulated)

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
The scenario assessment and initial control designs are documented below. Full standalone workbooks, policies, testing and executive dashboard remain planned.

### Assessment documents
- [Stakeholder and accountability assessment](01-project-governance/stakeholder-accountability.md)
- [Incident assessment and evidence gaps](02-incident-investigation/case-assessment.md)
- [Risk treatment decision](03-risk-management/risk-treatment-decision.md)
- [Legal and ethical analysis](04-compliance/legal-and-ethical-analysis.md)
- [Preventive governance and control design](05-policies-and-controls/preventive-governance.md)
- [Corrective action plan](06-remediation/action-plan.md)

### Remaining deliverables

| Workstream | Planned deliverables |
|---|---|
| 01 Project governance | Charter, stakeholder register, RACI |
| 02 Incident investigation | Incident report, timeline, root cause analysis, evidence register |
| 03 Risk management | Methodology, enterprise risk register, heat map |
| 04 Compliance | Legal obligations, framework mapping, control gap assessment |
| 05 Policies and controls | IP protection, licensing, acceptable use, secure development, offboarding, insider risk, ethics and non-retaliation, exceptions, incident response playbook |
| 06 Remediation | POA&M, roadmap, tracker |
| 07 Audit and assurance | Control testing workbook, audit assessment |
| 08 Executive reporting | Dashboard, executive summary, briefing |
| 09 Project closure | Lessons learned |

## Professional competencies
GRC analysis, enterprise risk assessment, compliance mapping, control design and testing, incident governance, cross-functional accountability, remediation planning and executive reporting.

## Future extension
A separate AI governance simulation may evaluate proprietary source-code exposure through external generative AI services using NIST AI RMF and ISO/IEC 42001. This is outside the original incident scope.
