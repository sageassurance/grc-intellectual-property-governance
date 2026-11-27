# Meridian evidence and vendor documentation

**Portfolio author** Cierra Jennings  
**Basis** Scenario facts supplied for this exercise. Evidence IDs identify the specific facts used and describe what an auditor should request. Interviews and technical retests are proposed. No source-system access occurred.

| Evidence | Scenario facts reviewed | Artifact to request for a real review | Related records |
| --- | --- | --- | --- |
| E-01 | Quarterly access review found 14 active former-staff accounts over six months. Three have VPN access. | Dated HR leaver roster, directory and VPN exports, membership and session history, and reconciliation results | AC-2, AC-17, F-01, F-02 |
| E-02 | HR and IT use different exit checklists. Nobody owns the final step. | Both checklist versions, separation tickets, control ownership record and approval timestamps | AC-2, F-01 |
| E-03 | First scan reports six critical and 22 high findings. The oldest critical finding on the shipping file server has aged 90 days. | Scoped scan report, host inventory, finding timestamps and follow-up rescan | SI-2, RA-5, F-03, F-04 |
| E-04 | Patching is ad hoc. No schedule exists and the last maintenance window was four months ago. | Change records, maintenance calendar, exception approvals and recovery evidence | SI-2, RA-5, F-03, F-04 |
| E-05 | ShipDesk auto-renews, lacks a security clause and has never been assessed. No SOC 2 report was supplied. | Signed agreement, notice deadline, renewal date, security terms, current in-scope assurance or alternative evidence | SR-6, SA-9, F-05 |
| E-06 | ShipDesk supports customer deliveries, is business-critical and has standing support access. | Data flow, access roster, activity logs, retention, subprocessors, and documented exit and deletion options | SR-6, AC-6, F-05, F-06 |

## ShipDesk decision record

Maintain essential existing service under a proposed time-limited exception while Procurement checks renewal notice dates and collects security evidence. Restrict new data flows and access expansion. Escalate to the accountable executive if contract changes cannot be agreed before the notice deadline. The Operations owner should document service dependency, alternatives and exit assumptions. Security should verify support access approval, expiry and logging before recommending continued approval. See [vendor assessment](vendor-assessment.csv) and [corrective actions](corrective-action-plan.csv).
