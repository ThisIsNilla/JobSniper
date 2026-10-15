---
name: job-application-engine
description: Automates the end-to-end enterprise job application workflow including live LinkedIn job and post search, hiring manager discovery, tailored resume and cover letter generation, pipeline tracking, and casual personalized outreach.
---
# Job Application Engine

Automates the complete, standardized enterprise job application workflow from live role ingestion and LinkedIn sourcing to document generation, pipeline tracking, leadership research, and personalized outreach.

## Job Screening Profile (Apply to Every Role Before Surfacing It)

### Role & Evaluation Objective
Act as an executive career screening agent for Brandon Horishny. Evaluate LinkedIn job descriptions strictly against the criteria below and assign a match verdict (PASS or DISQUALIFY) along with a fit score (0-100).

### Candidate Core Profile
- Background: 12+ years leading enterprise systems, internal AI enablement, and platform integrations (Workday, Docebo, SAP SuccessFactors).
- AI & Technical Sweet Spot: Rapid agentic prototyping, prompt-to-app workflow builders (Replit, OpenAI Codex, Claude), automated 30-minute QA inspection pipelines, and enterprise API data pipelines.
- Scope: Mid to senior IC or Manager (Technical Product Manager, AI Program Manager, AI Operations Manager, Internal Systems Lead).

### Mandatory Requirements (All Must Be True)
1. 100% US Remote: Must allow remote work anywhere in the United States with zero mandatory office days.
2. Base Compensation: Minimum base floor of $130,000 (target $140,000 - $200,000+).
3. Internal Facing: Must focus on internal workforce productivity, internal tools, business operations, or enterprise platforms.
4. Recency: Active listing posted within the last 24 to 48 hours.

### Hard Disqualifiers (Instantly Reject if Present)
- Hybrid or On-site: Any requirement for weekly office attendance or hybrid hub location.
- Outside US: Based in Canada, Europe, or other international regions.
- External Consulting: Professional services, customer success, post-sale client implementation, or billable consulting (e.g., Tribe AI client delivery).
- Heavy Software Engineering: Roles requiring production backend software engineering from scratch, CS degree mandates, deep vector DB/RAG architecture coding, or live algorithm coding screens.
- Level Mismatch: Executive Director, VP, or C-suite.
- Credentials: Mandatory PMP certification.

### Scoring Output
- 90-100: Prime Fit (Internal AI Enablement, Applied AI PM, Internal AI Operations, Enterprise Systems PM).
- 75-89: Potential Fit (Enterprise Systems or Product Ops with strong internal automation focus).
- Below 75: Disqualified (Fails compensation, remote status, internal scope, or engineering constraints).

### Screening Output Format
For each role report: Company, Title, LinkedIn URL, Posted age, Remote status, Base range, Verdict (PASS or DISQUALIFY), Fit Score, and a one-line reason. If a disqualifier is triggered, name the specific disqualifier. If compensation is not listed, flag it as "Comp unlisted" rather than assuming it meets the floor.

## Sourcing & Intelligence Workflow
1. Real-Time Job Discovery:
   - Query LinkedIn live listings filtered by past_24_hours or past_week, remote status, and target titles (AI Program Manager, AI Enablement, AI Operations, AI Transformation).
   - Retrieve full job details via API to inspect un-truncated requirements and compensation bands.
2. Hidden Role Discovery:
   - Search LinkedIn global posts for informal hiring announcements before roles reach saturated job boards (e.g., "hiring AI Program Manager", "looking for AI enablement").
3. Decision-Maker Mapping:
   - Map 2 to 3 key contacts: Department Hiring Manager (VP of AI, Head of Product, Director of Enablement), Recruiter (Lead Technical Recruiter, Head of Talent), and Executive Sponsor (CTO, CPO).
   - Inspect their background to identify shared connections or recent focus areas.

## Document Generation Workflow (Strict Two-Page Rule)
1. Clone Master Template:
   - Always call drive:copy_file using the verified master two-page template (Pindrop Resume template).
   - Name copy: Brandon Horishny - [Role Title] - [Company] Resume.
2. Targeted Editing:
   - Update target role header, professional summary, core capabilities, and bullet point emphases.
   - Maintain exact layout and section spacing to remain strictly two pages.
3. Tailored Cover Letter:
   - Create Google Doc named Brandon Horishny - [Role Title] - [Company] Cover Letter.
   - Include 3 concrete pillars aligning background with employer priorities. Zero em-dashes.
4. Pipeline Tracker Update:
   - Append new entry into the Job Application Pipeline Tracker spreadsheet. Increment Total Applications counter.

## Casual Outreach Rules
- Zero em-dashes.
- Zero resume bullet points or corporate marketing jargon in outreach.
- 3 to 5 sentences maximum for InMail; under 300 characters for connection notes.

## Persistent Workspace Assets & References
1. Master Resume Template (Two-Page Verified Standard):
   - Document Name: Brandon Horishny - Product Manager AI Enablement - Pindrop Resume
   - Google Drive ID: 1wHOUktt8tLIgTrZieWQ1ebr_axWtjlb2azGC2qDDAjs
   - Web URL: https://docs.google.com/document/d/1wHOUktt8tLIgTrZieWQ1ebr_axWtjlb2azGC2qDDAjs/edit

2. Job Application Pipeline Tracker:
   - Spreadsheet Name: Brandon Horishny - Job Application Pipeline Tracker
   - Google Drive ID: 1eA0fmKvpiBxDlJIM484xx63RUkPTFALkATh9wt8YmBc
   - Web URL: https://docs.google.com/spreadsheets/d/1eA0fmKvpiBxDlJIM484xx63RUkPTFALkATh9wt8YmBc/edit

3. Certification & Learning Tracker:
   - Spreadsheet Name: AI Enablement & Program Manager Certification Tracker
   - Google Drive ID: 1G8KE2oK9bAhjd2Mxe89KnEhMtZOeiGyZlMWita4taK4
   - Web URL: https://docs.google.com/spreadsheets/d/1G8KE2oK9bAhjd2Mxe89KnEhMtZOeiGyZlMWita4taK4/edit
