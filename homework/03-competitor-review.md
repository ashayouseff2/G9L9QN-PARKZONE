# Homework 03 — Competitor review: Parker
Usability and accessibility review of the parking-information-to-payment journey in Pécs, Hungary.
## Six interface findings
1. **Map coverage:** Reviewed map shows zones but does not clearly explain areas without zone information. Missing data could be mistaken for permission. Label unknown coverage explicitly.
2. **Zone legend:** Colour requires a separate legend. Pair each colour with a readable name or symbol.
3. **Local hours/prices:** Assess whether values are zone-specific. A reported mismatch is not independently verified. Show source/update date and verify before calling it a defect.
4. **SMS eligibility:** Reviewed route depends on eligible Hungarian mobile subscription; foreign SIM users may not qualify. Explain eligibility and alternatives.
5. **Empty message state:** “No message” provides little context. Explain whether there are no updates or content failed to load.
6. **External map hand-off:** Opening Apple/Google Maps interrupts the task. Preserve destination and make returning clear.
## Design priorities
Make unknown coverage explicit; pair colour with labels; show accurate zone-specific rules; explain payment eligibility; clarify empty states and navigation hand-offs.
## Accessibility/evidence boundary
Check WCAG 1.4.1 (not colour alone) and 1.4.4 (200% text resize) manually. These are interface observations, not a completed payment test. Local price/hour mismatch remains unverified.