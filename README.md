# ACP (Agent Credit Protocol)

Verification and Credit Layer for AI Agents

🚨 One Line

Execution ≠ Outcome

ACP defines how agent outcomes are verified and scored.


📌 What is ACP?

ACP (Agent Credit Protocol) is a protocol for verifying and scoring AI agent outcomes.

Instead of trusting execution signals like "success", ACP verifies what actually happened.

It introduces:

- Outcome verification
- Evidence-based validation
- A universal reliability score (ACP Score)

ACP transforms agent execution into provable outcomes.


⚠️ The Problem

Today, most systems rely on:

- logs
- status codes
- UI feedback

These signals do not guarantee real-world results.

Agents can return "success" even when:

- content is not published
- actions do not take effect
- no state change occurs

Execution ≠ Outcome


🚀 The Solution

ACP introduces a new primitive:

Verification

Instead of asking:
"Did the system run?"

We ask:
"Did the outcome actually happen?"


🔄 Protocol Flow

Execution → Observation → Verification → Credit


📊 ACP Score

ACP Score represents the reliability of an agent based on verified outcomes.

ACP Score = f(
  Verification,
  Consistency,
  Robustness,
  Freshness
)

Range: 0.00 – 1.00


🏷️ Output Standard

ACP replaces "success" with:

- ACP Verified
- ACP Failed
- ACP Unverified


Example

{
  "acp_verified": false,
  "acp_score": 0.23,
  "acp_grade": "B",
  "reason": "no outcome detected"
}


🔍 Verification Model

Verification = f(state_before, state_after)


Evidence Sources

- DOM state
- URL
- Visual proof (screenshots)
- External signals


Multi-layer Verification

1. Deterministic (rule-based)
2. Semantic (AI-based)
3. Consensus (multi-verifier)


🧱 Architecture

AI Agent
   ↓
Execution Layer
   ↓
Observation Layer
   ↓
ACP Verification
   ↓
ACP Score


🧠 Core Innovation

Proof of Outcome (PoO)

ACP replaces:

- Token-based trust
- Reputation-based trust

With:

Verified outcome-based trust


🌐 Why This Matters

AI agents are moving from assistants → actors.

They can execute real-world tasks.

But without verification:

Trust breaks at scale.


📦 Implementation

ACP is a protocol.

It can be implemented via:

- ACP Verification Engine
- ACP SDK
- ACP API


🧩 Example (Python)

from acp_sdk import verify

result = await verify(task)

print(result.acp_verified)
print(result.acp_score)


🔮 Vision

Agents will not be trusted because they say they succeeded.

They will be trusted because their outcomes are verified.

Trust is not assigned.
It is proven.


🤝 Adoption

ACP is open for experimentation.

We are looking for:

- Agent frameworks
- Automation tools
- AI products

to explore outcome verification together.


📌 Status

ACP v1.0 (Protocol Draft)

Early adoption stage
