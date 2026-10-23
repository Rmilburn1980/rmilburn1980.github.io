# Richard Milburn: Operations, Lean and EHS Evidence Portfolio

Live site: https://rmilburn1980.github.io/

A hub of working tools and dashboards built from 21 years on a caravan production line, for Operations Manager, Continuous Improvement and EHS or Production Supervisor roles. Every tool is a single HTML page. There is no build step, no server and no sign-in. Open a page and use it.

## What is in it

### Operations
| Tool | What it does |
|---|---|
| [SQCDP Interview Evidence Dashboard](https://rmilburn1980.github.io/sqcdp-dashboard/) | Interview evidence organised on Safety, Quality, Cost, Delivery and People. |
| [Skills Matrix and Cross-Training Dashboard](skills-matrix-dashboard.html) | Results from my own team: coverage, the 3x3 cross-training programme and how I developed people. |
| [Skills Matrix Builder](skills-matrix-builder.html) | Build a matrix for any team. A level only counts once someone other than the operator has signed it off, sign-offs expire, and SOP numbers are recorded per skill. |
| [Company Skills Dashboard](company-skills-dashboard.html) | Rolls up every team's matrix: cover against target, critical skills with too few signed-off people, sign-offs about to expire, and where the matrix claims more than the checks support. |

### Continuous improvement
5 Whys Root Cause Tool, DMAIC project board (first pass yield), SIPOC and Value Stream Map tool, Cycle Time and Waste Analysis tool, and the SMV tool.

### EHS
EHS Readiness dashboard, 7S audit dashboard, Risk Assessment dashboard, Swiss Cheese Model dashboard, Corrective Action Tracker, Bow-tie Builder, Causal Tree Builder and the Quick Exposure Check dashboard.

## How the safety tools behave

The safety and skills tools are built to show gaps, not to reassure. They never say "safe" or "compliant". They say either "Gaps found" or "No gaps found by these checks", and they remind the user that a competent person must still judge the result. Examples:

- A control or action only counts once someone other than its owner has checked that it works.
- Evidence marked as assumed is a gap until it is supported.
- Sign-offs expire.
- Example data is always labelled Example, so it cannot be mistaken for a real record.

## Your data

- The tools run in the browser. They do not send, upload or store any data on this site or on any server I run.
- Data stays in the browser's local storage and in any file the user chooses to save. Tools with a Save data file button write a JSON file to the user's own computer.
- The Skills Matrix Builder and Company Skills Dashboard can optionally save to and read from a folder the user picks (for example a SharePoint library synced to their computer). They only write the team data file. This needs Chrome or Edge on a computer.
- The site is hosted on GitHub Pages, which logs visitor IP addresses for security under GitHub's own privacy statement. The tools use no analytics and no third-party scripts.

### Skills and competence records are personal data

A matrix names employees and records judgements about them. That is personal data under UK data protection law, and the employer, not the person who builds the matrix, is responsible for it. Before using the skills tools with real names:

- Get approval from your employer's data protection lead or HR.
- Use company devices, and save only to the employer's approved, access-controlled location. Do not email data files or keep them on personal devices.
- Keep notes to what the assessor saw on the task. Do not record health, injury, disability, adjustments, absence, beliefs, union membership, criminal or disciplinary information.
- Agree a retention period and tell staff the records exist.

This is general information, not legal advice.

## Disclaimer

The tools are provided free and as they are, without warranty. They are decision support only. They are not a substitute for a suitable and sufficient risk assessment, a competent person's investigation, HR or legal advice, or your own legal duties.

## Running it yourself

Download the repository and open any `.html` file in a browser. Pages load a shared stylesheet from https://rmilburn1980.github.io/theme.css, so a local copy needs that file (or a copy of `theme.css`) to match the look. Each tool works without it.

## Contact

Richard Milburn, Medomsley, County Durham. LinkedIn: https://www.linkedin.com/in/richard-milburn-manufacturing
