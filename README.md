# acp-verification-engine
ACP Verification Engine is the core module of ACP (Agent Credit Protocol), responsible for verifying whether an AI agent has actually achieved a real-world outcome.
ACP Verification Engine — Proving What AI Agents Actually Achieve

## 🚨 Problem

AI agents can execute tasks, but there is no reliable way to verify:

- Did the task actually succeed?
- Was the outcome real or simulated?
- Can we trust this agent again?

Current systems rely on:
- Tokens
- Reputation
- Identity

None of them verify outcomes.

---

## ✅ Solution

ACP Verification Engine introduces a closed-loop system:

Execution → Observation → Verification → Credit

---

## 🔥 Core Concept

Agent Credit = Accumulated Verified Outcomes

---

## ⚙️ System Architecture

- Agent Runner (Playwright)
- Observation Layer (HTML, Screenshot)
- Verification Engine (Rule + AI)
- Credit Engine
- API Layer

---

## 🧪 Demo

This repo includes a working demo:

```bash
python demo/run_demo.py

What happens:

1.Agent executes a task

2.System captures evidence

3.Verification engine evaluates success

4.Credit is updated
