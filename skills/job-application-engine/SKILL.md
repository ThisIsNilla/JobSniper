---
name: job-application-engine
description: Automates the end-to-end enterprise job application workflow including live LinkedIn job and post search, hiring manager discovery, tailored resume and cover letter generation, pipeline tracking, and casual personalized outreach.
---
# Job Application Engine

Automates the complete, standardized enterprise job application workflow from live role ingestion and LinkedIn sourcing to document generation, pipeline tracking, leadership research, and personalized outreach.

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
