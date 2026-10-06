# JobSniper

> Autonomous Enterprise Career Intelligence, Live Opportunity Sourcing, and Pipeline Acceleration Engine.

JobSniper is an AI-augmented career intelligence engine designed to automate end-to-end opportunity discovery, hiring manager intelligence mapping, tailored application packaging, and live pipeline tracking across enterprise tech, AI enablement, and talent systems roles.

Built to run alongside AI pair-programming agents and the Model Context Protocol (MCP), JobSniper pairs real-time job sourcing with strict individual contributor (IC) filtering, verified metrics validation, and a standalone interactive web dashboard.

---

## Key Capabilities

* **Real-Time Opportunity Ingestion:** Queries live listings across enterprise tech, AI operations, and enablement, filtering for remote roles, freshness (past 24 to 72 hours), and IC scope without middle-management overhead.
* **Hidden Role Discovery:** Scans informal leadership posts and network updates to identify early-stage initiatives before positions hit saturated job boards.
* **Hiring Manager & Leadership Intelligence:** Identifies direct decision-makers (VP of IT, CIO, Head of Enablement, Lead Technical Recruiter) and analyzes public technical focus areas to guide personalized outreach.
* **Master Two-Page Application Tailoring:** Synchronizes master resume templates and custom cover letters in Google Docs, aligning domain experience with employer technical priorities while maintaining strict two-page layout fidelity.
* **Standalone Interactive Dashboard:** Modern web dashboard (`index.html`) featuring pipeline metric cards, direct job verification links, and live synchronization with Google Sheets trackers.
* **Zero-Defect Persona Standards:** Built-in validation rules enforce zero fabrication, verified metrics only, and low-friction, human outreach drafts.

---

## Architecture & Directory Structure

```text
JobSniper/
├── index.html                           # Standalone interactive dashboard (GitHub Pages ready)
├── config/
│   └── mcp_config.example.json          # Example Model Context Protocol client configuration
├── skills/
│   └── job-application-engine/
│       └── SKILL.md                     # Agentic skill workflow and execution specification
├── materials/
│   ├── securityscorecard_materials.md   # Sample tailored application package
│   └── restaurant365_materials.md       # Sample tailored application package
├── .gitignore                           # Git ignore rules
└── README.md                            # Project documentation
```

---

## Interactive Dashboard (`index.html`)

The repository includes a responsive dashboard built with Tailwind CSS that can be opened locally in any browser or deployed directly to **GitHub Pages**:

* **Pipeline Overview:** Displays real-time status counters across applications drafted, submitted, and active interview stages.
* **Intelligence Scan Tab:** Displays verified roles with direct links, compensation bands, remote status, and targeted alignment breakdowns.
* **Live Pipeline Tracker Tab:** Embedded table of submitted opportunities with quick links to live Google Sheets trackers for collaborative updates.

### Deploying to GitHub Pages

1. Navigate to your repository settings on GitHub (**Settings > Pages**).
2. Under **Build and deployment > Source**, select **Deploy from a branch**.
3. Choose the `main` branch and `/ (root)` folder, then click **Save**.
4. Your dashboard will be live at `https://<your-username>.github.io/JobSniper/`.

---

## Model Context Protocol (MCP) Integration

JobSniper leverages the Model Context Protocol to query live platform intelligence via local runtime tools.

### Prerequisites

* Python 3.10+
* `uv` and `uvx` package runner installed (`https://docs.astral.sh/uv/`)

### Setup

Add the LinkedIn MCP server to your MCP client configuration (such as `~/.gemini/config/mcp_config.json` or your preferred MCP client settings):

```json
{
  "mcpServers": {
    "mcp-server-linkedin": {
      "command": "uvx",
      "args": [
        "mcp-server-linkedin@latest"
      ]
    }
  }
}
```

Authenticate the session in your terminal:

```bash
uvx mcp-server-linkedin@latest --login
```

This launches a browser session to authenticate and cache your credentials locally in `~/.linkedin-mcp/`.

---

## Operating Rules & Ground Truth Principles

JobSniper strictly enforces zero-fabrication guidelines:

1. **Verified Metrics Only:**
   * 1,040+ hours of manual review eliminated via automated audit pipeline at Zillow
   * 30-minute automated QA and evaluation pipeline at Zillow
   * Millions of interaction records ingested and queried via LRS data pipeline at Zillow
   * 150+ operational learning plans and notification pipelines at Northwestern Mutual
   * 18% reduction in cross-system sync errors at Northwestern Mutual
   * 27% lift in stakeholder satisfaction via Administrator Playbook and SOPs at Northwestern Mutual
   * 1,200+ employees supported in zero-defect environment at Kiewit Nuclear
   * 32% increase in platform adoption via SAP SuccessFactors implementation at Kiewit Nuclear
2. **Accurate Positioning:**
   * Enterprise Systems, Talent Technology, HRIS, Learning Platforms, and Internal Operations.
   * Hands-on AI prototyping in Python, OpenAI Codex, and automated evaluation pipelines.
3. **Outreach Style:**
   * Short (3 to 5 sentences), natural, conversational, and low friction.
   * Free of resume jargon, sales pitches, and em-dashes.

---

## License

MIT License. Designed for personal career acceleration and agentic workflow orchestration.
