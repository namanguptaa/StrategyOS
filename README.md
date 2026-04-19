# Strategy OS

**A versioned strategy layer for your org. Write it once, inherit it everywhere — from roadmaps to sales decks to agent prompts.**

---

Strategy lives in Notion pages nobody reads, slide decks that go stale, and Slack threads nobody finds. Every new hire re-asks the same questions. Every AI session starts from scratch.

This repo fixes that. Strategy is code. Versioned, readable, and inherited by everything downstream.

---

## How It Works

**Set up once (10 min).** Open in Claude Code. The agent interviews you, does research, and writes the entire foundation — vision, OKRs, constraints, decisions, messaging, ICP.

**Use everywhere.** Every session — Claude Code, Claude chat, any agent — reads the same context. No re-explaining. No drift.

**Stay current (15 min/week).** Sunday ritual: update what's changed, log decisions, regenerate the agent brief. Done.

---

## The Files

```
AGENT.md          ← Paste into any AI for instant context. Regenerated weekly.
CONTEXT.md        ← What's actually happening right now. Updated weekly.
DECISIONS.md      ← Append-only log of every key decision.
CONSTRAINTS.md    ← Hard limits: team, budget, tech, non-negotiables.

strategy/         ← Vision and OKRs. Everything traces back to here.
product/          ← PRDs, each linked to an OKR.
marketing/        ← Campaigns and messaging, linked to OKRs.
sales/            ← Playbooks and outreach, grounded in ICP.
experiments/      ← Hypothesis-driven tests, tied to OKRs.

ops/
  stack.md        ← Current tools across every function.
  rituals.md      ← The 15-min Sunday update process.
```

---

## The Rule

Every artifact — PRD, campaign, playbook, experiment — links to an OKR. If it can't, it doesn't get built.

---

## Getting Started

```
1. Fork this repo
2. Open in Claude Code
3. Say: "Let's get started"
```

The agent interviews you, fills the repo, and brief is ready to share with the whole team — and any AI you use.

---

## One Repo Per Product

Fork once per product. Each instance is independent. The agent initializes fresh context for each.
