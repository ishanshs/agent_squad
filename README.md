# Agent Squad 🤖⚡

> **A "Zero-Budget" Autonomous AI Team for Vibe Coders.**

Agent Squad is a governance protocol that turns your IDE into a structured engineering team. Instead of one AI trying to do everything (and hallucinating), you get 8 specialized Agents—from Product Managers to Security Engineers—who check each other's work.

**Optimized for:** Google Antigravity, Cursor, Windsurf, Replit, and VS Code.

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

### 2. Cursor (The "Composer" Method)
Cursor uses `.cursor/rules` to give context to its AI.
1.  Create a folder `.cursor/rules` in your project root.
2.  Copy all files from `personas/` into `.cursor/rules/`.
3.  **Usage:** In Cursor Composer (Cmd+I), you can now explicitly mention agents like `@02_product` or `@000_master_protocol`.
4.  *Pro Tip:* Paste the content of `01_ceo.md` into your "General Instructions" in Cursor settings for a permanent CEO mode.

### 3. Windsurf (Cascade Flow)
Windsurf uses `.windsurf/rules` for its Cascade agent.
1.  Create a folder `.windsurf/rules` in your project root.
2.  Copy all files from `personas/` into `.windsurf/rules/`.
3.  **Usage:** Cascade will now index these rules. Start your prompt with "Act as @CEO..." or explicitly reference the rule files.

### 4. Replit (Agent Context)
Replit Agent reads `replit.md` to understand your project intent.
1.  Copy the content of `personas/000_master_protocol.md` and `personas/01_ceo.md`.
2.  Paste it into a new file named `replit.md` in your root directory.
3.  **Usage:** Replit Agent will now automatically adopt the "Zero-Budget" and "State Persistence" mindset during generation.

### 5. VS Code (GitHub Copilot)
Copilot Chat looks for `.github/copilot-instructions.md`.
1.  Create `.github/copilot-instructions.md`.
2.  Paste the content of `personas/000_master_protocol.md` into it.
3.  **Usage:** Copilot will now respect the "Chain of Custody" and "No Magic Strings" rules during chat.

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
│   └── config/             # strings.json (No magic strings in code!)
├── tests/                  # The "Proof"
├── knowledge/              # Long-term Memory (User Patterns)
└── personas/               # The Agent Prompts (Source of Truth)

## 🛑 The "Zero-Budget" Philosophy

This Squad is designed for the **Indie Hacker** and **Bootstrapper**.

1. **No Paid SaaS:** The Architect will reject expensive Vector DBs in favor of SQLite/FAISS.
2. **No Polling:** The Coder will insist on Webhooks to save compute.
3. **No Cloud Bloat:** The Protocol favors local execution (or Free Tier) over massive scale infrastructure until proven necessary.

---

## 📜 License

MIT. Go build something cool.