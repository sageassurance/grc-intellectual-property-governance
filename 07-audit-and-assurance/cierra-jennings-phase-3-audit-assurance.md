# Cierra Jennings | Phase 3 audit assurance

**Engagement:** Enterprise Intellectual Property Governance & Compliance Assessment  
**Report date:** November 25, 2026  
**Status:** Simulated audit exercise complete. Authorized lab testing, organizational evidence collection, and remediation validation are pending.

Use the companion [Control Testing Workbook](cierra-jennings-phase-3-control-testing.xlsx) for the risk and control matrix, individual workpapers, evidence requests, and findings tracker. IDs follow the [Phase 2 enterprise GRC workbook](https://github.com/sageasssurance/grc-intellectual-property-governance/blob/5148016d0fb5bcf53ffcabbe5860784b769dbea4/03-risk-management/cierra-jennings-enterprise-grc-workbook.xlsx).

## Audit charter

The proposed independent oversight sponsor commissions a review of controls governing use of third-party proprietary software. The reviewer reports to that sponsor and documents scope changes, conflicts of interest and evidence limitations. HR, Legal, IT and Security own the processes and proposed corrective actions. The reviewer and the closure approver remain independent of corrective action ownership. Any organizational fieldwork requires documented authorization, access and approved handling of confidential material.

## Scope and audit plan

| Area | Scope | Work performed |
|---|---|---|
| Larger employer | Acquisition and licensing, installation approval, software inventory, incident escalation and independent exception review | Mapped proposed criteria to Phase 2 control IDs and evaluated fictional workpapers |
| Smaller employer | Prior-employer IP acknowledgments, source-code grants and reviews, personnel separation and asset return | Mapped proposed criteria and evaluated fictional workpapers |
| Shared dependencies | Incident evidence custody, transition readiness and rights determination | Carried forward evidence requests and routed ownership questions to Legal |

The scope excludes real system access, assessment of legal liability, organization-wide compliance assertions, and any opinion on actual design or operating effectiveness. For authorized work, agree the review period and population with process owners, obtain the records listed in the workbook, verify provenance and completeness, and then test the criteria. Escalate missing or inconsistent evidence to independent oversight. Record the evidence locator, reviewer and result for each sampled record.

## Sampling and decision rules

The exercise uses two deliberately selected fictional records for each of seven controls. The records cover both ordinary paths and plausible failures where applicable. Each record passes only when it meets its stated criterion. An unmet criterion triggers a sample exception. A missing assessment remains pending. The dataset does not support population estimates or a comparison between employers.

For actual fieldwork, reconcile the population to its system of record before sampling, document the period and exclusions, and target high-risk items such as urgent installs, privileged grants, involuntary departures and cases involving management. Include ordinary transactions when assessing repeatability. Set sample size after assessing population size, frequency and reliance. Expand testing when deviations suggest a recurring issue. Treat insufficient evidence as inconclusive and preserve the distinction between failed and untested controls.

## Internal audit report

The exercise evaluated **14 synthetic records across seven controls**. Five records failed their exercise criteria, generating five illustrative findings. The IP onboarding and management exception records met their criteria in this exercise. The Phase 2 workbook's implementation and operating-effectiveness statuses remain unverified.

| Finding | Synthetic condition | Proposed management response and owner | Independent validation required |
|---|---|---|---|
| AF-001 / C-02 | One installation lacked documented origin verification, license and approval | IT and Legal adopt a release gate and reconcile endpoint discoveries against valid licenses. A04. | Examine approval timestamps, license scope and endpoint records. Confirm an unapproved request is blocked or routed for review in an authorized test environment. |
| AF-002 / C-03 | One write grant lacked owner approval and a review record | Security requires repository-owner approval and scheduled access recertification. A05. | Trace a grant from request through approval and recertification. Test denied write access using a designated lab account and approved repository. |
| AF-003 / C-04 | One fictional departure retained repository access beyond the effective time | HR and IT reconcile separation triggers, asset return and revocation times. A05. | Compare effective departure and revocation events. Confirm denied access for an authorized lab identity after revocation. |
| AF-004 / C-05 | One installation had no approved inventory or entitlement match | IT Asset Management reconciles endpoint discovery to inventory and routes unmatched items. A05. | Reperform reconciliation and verify that an approved lab discrepancy creates a tracked exception. |
| AF-005 / C-06 | One report went solely to implicated management | GRC, HR and Legal establish independent routing and record reporter protection follow-up. A01. | Conduct a tabletop and verify independent intake, evidence custody and scheduled follow-up without exposing personal data. |

Management responses above are proposed. Request a response with an accountable owner, milestone and acceptance evidence. Escalate overdue high-priority items using the Phase 2 POA&M and retain an auditable record of any approved schedule changes.

## Remediation validation report

**Current disposition:** All five illustrative findings remain open. Retesting and closure approval are pending. Complete validation under Phase 2 action A07 after the responsible owners supply evidence for the applicable A01, A04 or A05 action.

For each finding, record the original condition, change or implementation record, post-change population and period, independent sample, observed results, evidence IDs, reviewer and date. Close only after repeat testing satisfies the criterion, exceptions are addressed, and independent oversight approves the disposition. If the control still fails or the evidence is incomplete, keep it open and record the next action. Update residual risk only after evidence-backed review.

## Authorized technical lab boundaries

Use a dedicated, authorized lab with disposable test accounts and files. Record the environment, intended criteria, expected and observed behavior, and the exact evidence captured. Keep lab evidence labeled with its environment and date. A successful lab result supports the tested configuration; organizational effectiveness still depends on independent evidence from the relevant environment.
