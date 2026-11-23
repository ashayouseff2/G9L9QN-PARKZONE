# Design decisions
1. **Eligibility before payment.** A user should understand whether the area is suitable for them before being encouraged to pay.
2. **Explicit area status.** Distinguish public paid parking, permit-only, restricted and unknown information.
3. **Unknown is not permission.** Missing or conflicting data leads to an uncertainty state, not a positive parking decision.
4. **Payment is conditional.** Payment details are shown only for public paid parking.
5. **Rules are visible.** Hours, restrictions and relevant conditions should be easy to find.
6. **Source trust matters.** Official authority and last-verification information should be available when data integration is implemented.
7. **Accessible status.** Do not communicate status through colour alone; use text labels, visible focus and readable contrast.

These are design intentions. The prototype does not currently validate live rules or municipal source data.