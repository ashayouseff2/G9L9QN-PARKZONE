# Homework 05 — Information architecture and user flow
## User goal
“I am here. Can I leave my car in this area, and what conditions apply?”
## Principle
Show parking permission and eligibility first. Show payment details only for public paid parking.
## Content priority
1. Area identity; 2. Area type (public paid, permit-only, restricted, unknown); 3. Eligibility; 4. Rules/hours/exceptions; 5. Required action; 6. Payment details if relevant; 7. Official source and last verification.
## Labels to validate
“Check this area”, “Who can park?”, “Parking rules & times”, “Payment options”, “Official information”. Label check has not yet been conducted.
## Sitemap
Check this area → select/confirm location → area result → eligibility, rules, payment (if paid), official information. If not eligible: alternative guidance. If uncertain: verify with authority.
## Main flow
Select/confirm location → identify zone → if unmatched, adjust location → show area type and eligibility → if ineligible, explain restriction → if public paid, show payment details → show official source.
## Exceptional states
Unmatched location; permit required/ineligible; missing/conflicting data; near a zone boundary. Never guess or imply permission.
## Scope
No accounts, profiles, favourites, notifications or booking. Unknown is not permission; payment never makes a permit-only area valid.