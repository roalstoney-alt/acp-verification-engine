# acp-verification-engine
ACP Verification Engine is the core module of ACP (Agent Credit Protocol), responsible for verifying whether an AI agent has actually achieved a real-world outcome.

AI systems can silently change outcomes.

ACP verifies what actually happened.

## 🚨 Problem

AI agents can execute tasks, but there is no reliable way to verify:

- Did the task actually succeed?
- Was the outcome real or simulated?
- Can we trust this agent again?

  EVEN worse , when Type "we can make success"

After sending, it changed to:

"we haven't made success"

I didn’t edit it.

The system did.

---

This is the real problem with AI systems:

Not that they fail.

But that they silently change outcomes.

---

If we cannot prove what actually happened,
we cannot trust any agent.

---

We don’t need smarter AI.

We need verifiable outcomes.

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
