# Homework 09 — Design system
Source: Figma page “Homework 9 — Design system”.
## Reusable components
**Button:** Primary/Secondary; Default/Focus/Pressed/Disabled. Primary for main action; secondary for supporting action. Shared radius token radius/12.
**Field/Text:** Default/Focus/Filled/Error/Disabled. Keep label visible; error includes corrective message.
**Information card:** repeated for zone status, price, restrictions and payment. Title first, details below; not used for primary action.
## Component change test
All button variants share radius/12; changing token updates corner radius across the family.
## Handoff — Screen 02 / Zone result
“Pay for parking” opens Payment details; “Place information” opens rules/source. If zone cannot be verified, show exception and do not imply permission.
Accessibility: status in text, not colour alone; clear button labels; visible focus; readable contrast.
Development: button/field fills, spacing and radius use variables. Dev Mode token names and “Ready for dev” status were not confirmed.