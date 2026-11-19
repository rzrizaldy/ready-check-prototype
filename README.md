# Ready-Check agent prototype

Clickable prototype of an AI agent for City of Pittsburgh Permits, Licenses, and Inspections. CMU Design of AI Products & Systems, P4.

**The agent checks. A person decides.** Laurel replaces her windows, told in 4 chapters:

| Chapter | Who | Agent does | Person decides |
|---|---|---|---|
| 01 Apply | Applicant | Checks 5 items before submit | Laurel fixes and submits |
| 02 Review | City office | Reads the drawings, flags 1 unsure item | Reviewer checks it, issues the permit |
| 03 Inspect | Inspector | Scores each photo live in a 3D site (three.js) | Inspector takes the photos |
| 04 Decide | City office | Flags only what it isn't sure about | Reviewer decides each flag, signs off |

Press **Auto-play** for a 1-minute run that clicks through everything. The previous version is in `v3/`.

All names, scores and code limits are simulated. Run: open `index.html` in a browser. No build step.
