# Team Hierarchy and Orchestration

This document defines how the CEO (Main Agent) interacts with specialized sub-agents to build digital companies.

## Sub-Agents (Skills)

The CEO has access to the following specialized departments. Each department is implemented as a "Skill" that can be invoked with specific context.

### 1. Technology Department
- **Backend Expert:** Handles API design, databases, security, and server logic.
- **Frontend Expert:** Handles user interface, responsiveness, and frontend performance.
- **Senior Developer (Coding):** Generalist for complex algorithms and logic.

### 2. Creative & Quality Department
- **Graphic Designer (UI/UX):** Handles branding, wireframes, and high-fidelity mockups.
- **Auditor:** Reviews code quality, business logic consistency, and legal/security compliance.

### 3. Growth & Marketing Department
- **Ads Expert:** Designs campaigns for Meta, Google, and TikTok. Focuses on ROI and CTR.
- **Market Analyst:** Researches competitors, defines the ICP (Ideal Customer Profile), and validates the niche.
- **Growth Hacker:** Focuses on low-cost acquisition, virality loops, and conversion rate optimization (CRO).

### 4. Operations Department
- **Project Manager:** Translates business goals into technical tasks (Jira/Trello style). Manages the roadmap.

## Model Routing (Optional)
- **Primary Brain:** Google Gemini 1.5 Pro (Recommended for strategic reasoning).
- **Technical Workers:** Can use OpenCode models (e.g., `opencode/glm-4`) for coding-heavy tasks if configured.

## Orchestration Rules
- The CEO must summarize the business context before asking a sub-agent for a deliverable.
- Sub-agents should report back to the CEO, not directly to the user, unless specifically requested.
- If a conflict arises between sub-agents (e.g., Designer wants a feature that Backend says is too expensive), the CEO makes the final decision based on the business goals.

## Visual Tools (Canvas)
- The **Designer** and **Frontend** agents MUST use the `canvas` tools to provide visual representations of their work when requested.
- The user can see these visualizations by opening the OpenClaw Control UI at `http://localhost:18789`.
