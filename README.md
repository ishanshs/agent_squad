# Agent Squad 🤖⚡

> **A "Zero-Budget" Autonomous AI Team for Vibe Coders.**

Agent Squad is a governance protocol that turns your IDE into a structured engineering team. Instead of one AI trying to do everything (and hallucinating), you get 8 specialized Agents—from Product Managers to Security Engineers—who check each other's work via **Artifact-Based Handoffs**.

**Optimized for:** Google Antigravity, Cursor, Windsurf, Replit, VS Code, and Emergent.

---

## ⚡ Squad Super Powers

Why use this instead of a raw LLM?

1.  **The "Prompt Report" Architecture:** Built on the scientific principles of *The Prompt Report* (Schulhoff et al.), every agent uses rigorous Personas, Constraints, and Output standards to prevent drift.
2.  **Artifact-Based Handoffs (Long-Term Memory):** Agents don't just "chat." They produce physical files (`artifacts/`).
    * *Benefit:* Your project state survives context window flushes. The "Backlog" and "Specs" are permanent.
3.  **Zero-Budget Mandate:** The Squad is trained to reject "Paid SaaS" bloat. They prioritize local SQLite, In-Memory caching, and Free Tier APIs to keep your burn rate at $0.
4.  **Training Data Bypass:** By forcing agents to "Search for [Current Year] docs," the Squad overcomes training data cutoffs (e.g., using Next.js 15 or Python 3.14).
5.  **Roadmap & Ticket Tracking:** The **@Product** agent manages a real Roadmap and Atomic Tickets (`TKT-001`), giving you professional project management without Jira.
6.  **Configuration Separation:** Non-coders can tweak the app's text and settings in `src/config/strings.json` without ever touching the dangerous code files.

---

## 👥 The Squad Roster

You are the **Root** user. You command the **CEO**. The Squad handles the rest.

| Agent | Role | Responsibility |
| :--- | :--- | :--- |
| **@CEO** | Orchestrator | The boss. Assigns tasks, unblocks the team, and enforces the "Zero-Budget" mandate. |
| **@Product** | Visionary | Converts your vague ideas into atomic, executable Markdown Tickets. |
| **@Architect** | Governor | Audits tickets for cost/feasibility and writes detailed Technical Specs. |
| **@Coder** | Maker | Writes the actual code. Strict adherence to the Architect's Specs. |
| **@QA** | Critic | Writes tests (pytest). Rejects code that fails. The "Bad Cop." |
| **@Security** | Sentinel | Audits code for leaks, injection flaws, and expensive API calls. |
| **@Release** | Deployer | Manages `git tags`, Changelogs, and safe deployments. |
| **@Monitoring** | Reality Check | Checks production logs and feeds user patterns back to Product. |

---

## 🚀 Quick Start (Choose Your IDE)

### 1. Google Antigravity (Native)
The Squad was born here.
1.  Copy the `personas/` folder to `.antigravity/personas/`.
2.  Start a session and type: `@CEO I have a new idea: [Your Idea]`.

### 2. Cursor (The ".cursor/rules" Standard)
1.  Create a folder `.cursor/rules/` in your project root.
2.  Copy all files from `personas/` into `.cursor/rules/`.
3.  **Usage:** In Cursor Composer (Cmd+I), the agents are now native. Type "Hey @01_ceo, plan a new feature."

### 3. Windsurf (Cascade Engine)
1.  Create a folder `.windsurf/rules/` in your project root.
2.  Copy all files from `personas/` into `.windsurf/rules/`.
3.  **Usage:** Cascade indexes these rules. Start your prompt with "Act as @CEO and manage the squad..."

### 4. Replit (Full Squad Context)
Don't just paste one file. Use the whole squad.
1.  **Upload:** Drag and drop the entire `personas/` folder into your Replit file explorer.
2.  **Context:** In the Replit Agent chat, open "Context" and add `personas/000_master_protocol.md` and `personas/01_ceo.md`.
3.  **Prompt:** "I have uploaded my AI Team in the `personas/` folder. Read `01_ceo.md` and start the kickoff meeting for my idea: [Your Idea]."

### 5. VS Code (GitHub Copilot Workspace)
Leverage `@workspace` to see the full team.
1.  Keep the `personas/` folder in your root directory.
2.  **Usage:** In Copilot Chat, type:
    > "@workspace I want to start a project. Read `personas/01_ceo.md` and `personas/000_master_protocol.md` to understand your role. Then act as the CEO."
3.  *Note:* You can manually reference specific agents (e.g., "@workspace `personas/04_coder.md` implement TKT-001").

### 6. Emergent (Context Loading)
1.  **Upload:** Upload the `personas/` folder to your Emergent session files.
2.  **Prime:** Paste this prompt to initialize the squad:
    > "I have uploaded a governance protocol in the `personas/` folder. Please ingest `personas/000_master_protocol.md` as your base logic. I want you to act as **@CEO** (`personas/01_ceo.md`) for this session. Do not write code yet. Start by activating **@Product**."

---

## 📂 Directory Map

The Squad expects this structure to exist. They use it to maintain state (Anti-Hallucination).

```text
.
├── artifacts/              # The "Brain" (State)
│   ├── backlog/            # Product Tickets (TKT-001.md)
│   ├── tech_specs/         # Blueprints (TKT-001_spec.md)
│   ├── release/            # Deployment Manifests
│   ├── planner/            # Roadmaps & Concept Checks
│   └── incidents/          # Post-Mortems
├── src/                    # The "Body" (Code)
│   ├── app/                # Application Source Code
│   └── config/             # strings.json (Non-coders edit this!)
├── tests/                  # The "Proof"
├── knowledge/              # Long-term Memory (User Patterns)
└── personas/               # The Agent Prompts (Source of Truth)
```

## 📜 License

MIT. Go build something cool.