# Alderline Civic Systems | Vendor incident response tabletop

**Portfolio author** Cierra Jennings  
**Exercise type** Fictional, discussion-based walkthrough with scripted evidence  
**Scope** LanternQueue Messaging (V-03), finding F-02, and supplier participation in incident response under NIST CSF 2.0 GV.SC-08

## Objective and starting conditions

Alderline depends on LanternQueue to send municipal permit notifications. LanternQueue processes email addresses, phone numbers and delivery metadata. In the exercise, the vendor discovers that a new delivery subcontractor may have made delivery logs accessible beyond the approved support group. The affected population and whether anyone retrieved the logs are unknown. Alderline treats the event as suspected exposure while it establishes scope.

The proposed vendor policy calls for notice within 24 hours of discovery. Use that as an **exercise benchmark**. Whether the existing vendor agreement contains the same requirement remains unverified. The exercise assumes Security Operations should acknowledge notice within one hour and that the business owner should reach a backup contact within one hour if the primary contact fails. These are local test criteria. [Vendor policy draft](https://github.com/sageassurance/grc-intellectual-property-governance/blob/1018b38317bec7a77919bd34b0eccc43b3b15acc/case-studies/alderline-civic-systems/alderline-third-party-data-protection-policy.md) · [Assessment workbook](https://github.com/sageassurance/grc-intellectual-property-governance/blob/1018b38317bec7a77919bd34b0eccc43b3b15acc/case-studies/alderline-civic-systems/alderline-govtech-cybersecurity-grc.xlsx)

## Exercise roles

- **LanternQueue incident lead** provides the discovery time, affected service, known data categories, containment steps and next update.
- **Security Operations** acknowledges the notice, opens the incident record and coordinates evidence preservation.
- **Product Security** owns F-02, confirms the subcontractor and leads supplier reassessment.
- **Legal and municipal account lead** determine notification responsibilities and prepare an update that distinguishes confirmed facts from unknowns.
- **Security Assurance** scores the exercise and independently reviews any later closure evidence.

## Scenario timeline and decision log

All times are scripted, UTC, on the same fictional exercise day.

| Time | Exercise event | Expected decision | Scripted evidence or outcome |
|---|---|---|---|
| 09:00 | Vendor discovers suspected exposure of delivery logs | Preserve vendor exports and identify the discovery timestamp. Request the affected period and data fields. | TT-01. Discovery time recorded. Scope and confirmed access remain unknown. |
| 10:10 | Vendor alerts Alderline’s security intake channel | Acknowledge, open the incident record and assign a coordinator. | TT-02. Notice arrives 70 minutes after discovery. Security Operations acknowledges at 10:25 and records incident IR-EX-01. |
| 10:30 | Listed primary vendor contact stops responding | Try the backup route and record who can provide the next update. | TT-03. The listed backup mailbox bounces. The vendor account team identifies an alternate contact at 11:50, 80 minutes after the first failed contact. |
| 12:00 | Vendor confirms the logs may contain resident contact information | Preserve logs and access history, pause nonessential data transfers if feasible, maintain a route for essential notices, and brief Legal. | TT-04. The script records a preservation request and a continuity decision. No source-system evidence accompanies this exercise. |
| 13:00 | Municipal account lead requests a status update | Describe the suspected exposure and remaining unknowns. Assign Legal to review notification obligations and confirm the next update time. | TT-05. Draft update and Legal review owner recorded. The exercise sends no notifications. |

## Results and corrective actions

| Check | Exercise result | Evidence |
|---|---|---|
| Vendor initial notice within 24 hours of discovery | Pass · 70 minutes | TT-01, TT-02 |
| Alderline acknowledgement within one hour of receipt | Pass · 15 minutes | TT-02 |
| Verified backup contact within one hour of failed primary route | Fail · 80 minutes | TT-03 |
| Preservation and notification decisions assigned and recorded | Pass in the exercise | TT-04, TT-05 |

**Finding F-02 remains open.** Product Security owns correction by the existing simulated due date, **January 22, 2027**. Update the vendor contact roster with a named backup and maintained escalation channel. Verify the escalation route with the vendor and reassess the new subcontractor’s access, data handling, and incident obligations.

**Independent retest.** Security Assurance should run a second exercise with a deliberately unavailable primary contact. Record discovery, notice, acknowledgement and backup-contact timestamps. Confirm that the backup meets the one-hour exercise criterion, the incident record contains the preservation and notification decisions, and Product Security has recorded the signed subcontractor reassessment. Record the evidence locator, verifier and date in the Finding Tracker only after review.

The scripted evidence references identify exercise entries. They do not establish real vendor performance or a verified control fix.
