# Orcanaut — Pitch

**AI Agents That Do Your Processes**

Connect your tools. Define workflows. Agents reason, execute, get approval, and learn.

---

## The Problem

Every company runs on dozens of tools — Jira, Slack, CRM, databases, email, cloud services. Business processes span across all of them.

Automating these cross-tool processes requires either **expensive custom integrations** or **rigid workflow builders** that break when anything changes.

Teams spend weeks wiring tools together instead of doing actual work.

---

## The Solution

Orcanaut is an AI agent platform that automates business processes across your tools.

Connect your tools via MCP (Model Context Protocol). Define multi-step workflows with approval gates. Orcanaut's agents reason through each step, ask for human sign-off when it matters, delegate to specialized agents, and deliver results.

Unlike traditional automation (Zapier, n8n) which follows fixed rules:

- Orcanaut agents **reason** about what to do next
- **Human-in-the-loop** — agents pause for approval on sensitive actions, then continue autonomously
- **Multi-agent collaboration** — agents delegate tasks to specialized agents for complex processes
- They have **memory** — every run teaches them something new

---

## How It Works

1. **Connect your tools** — Plug in MCP servers for Jira, Slack, databases, APIs, or any service
2. **Define an agent or workflow** — Describe its role, which tools it can use, add approval steps where needed
3. **Give it a task** — "Process all new invoices" or "Onboard this new customer"
4. **Agent executes the process** — Calls the right tools, in the right order, pauses for approval when needed

**Example:** "Process new vendor invoices" -> Agent scans invoices from email, matches to purchase orders, flags high-value items for manager approval, then schedules payments after sign-off.

---

## Why Now

- **MCP is becoming the standard** for connecting AI to tools — one protocol, any tool
- LLMs can now **reliably plan multi-step processes** and use tools
- Companies are ready to move from **"AI chatbots" to "AI that does work"**

---

## Market

**$15B+** — Intelligent process automation market by 2028

Every company with 10+ SaaS tools is a potential customer. Land with dev/ops teams (API-first), expand to business teams (templates + UI).

---

## Business Model

- **Usage-based pricing** — per process execution
- Built-in usage tracking: tokens, execution time, tool calls
- Free tier for small teams -> paid for organizations

---

## Our Moat

| | |
|---|---|
| **Agents with memory** | Every run stores learnings. Run 1 takes 5 steps. Run 50 takes 2. Agents compound knowledge — no workflow builder can match that. |
| **Human-in-the-loop** | Built-in approval gates. Agents pause for human sign-off on sensitive actions, then resume autonomously. Trust without blind delegation. |
| **MCP-native** | Not locked to specific integrations. Any MCP-compatible tool works instantly. One protocol, infinite tools. |
| **Multi-agent teams** | Agents delegate to specialized agents. A coordinator handles the process while domain experts handle the details. |
| **Secure execution** | All tasks run in isolated sandboxes. Tool access is scoped per agent. Your data stays protected. |
| **Fully observable** | Every step is logged and streamable in real-time. Audit log for every workflow step, every approval, every decision. |

---

## Traction

- Working product: full agent loop (reason -> execute -> approve -> learn -> deliver)
- Multi-step workflow engine with human approval gates
- Multi-agent orchestration — agents delegate to specialized agents
- MCP tool integration, vector memory, file I/O, real-time streaming, scheduled runs
- Early access waitlist open

---

## The Ask

**Pre-seed round**

1. Launch public beta and onboard first 100 teams
2. Build MCP tool marketplace (pre-built connectors for popular tools)
3. Add web UI so non-developers can create and manage agents

---

*AI agents that do your processes across all your tools.*

[Get Early Access](https://orcanaut.com)
