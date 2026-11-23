# Homework 06 — Wireframes and screen structure
Source: Figma page “Homework 6 — Park Zone”.
## Screens
1. **Select location:** search street/address, map/current-location placeholder, use location, choose location.
2. **Area result:** area type, eligibility summary, rules summary and next action.
3. **Rules & payment:** eligibility, hours, exceptions, restrictions, conditional payment, authority and last-verified date.
4. **Check complete:** decision summary, official source, finish check.
5. **Location not matched:** no zone match; do not assume parking is allowed; adjust/retry.
6. **Cannot verify rules:** missing/conflicting information; check authority or change location.
7. **Large-screen area result:** map panel and decision details in two columns.
## Connections
Main: Select location → Area result → Rules & payment → Check complete. Error: Select location → Area not found → Adjust location. Exception: rules → Cannot verify → official information/change location.
## Hierarchy
Location/area; eligibility; rules/action; payment if applicable; official source.