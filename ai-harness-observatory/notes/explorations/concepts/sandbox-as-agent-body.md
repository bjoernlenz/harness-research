---
id: sandbox-as-agent-body
title: Sandbox As Agent Body
kind: concept
related_harnesses:
  - openhands
  - cursor
related_concepts:
  - sandbox-as-agent-body
  - sandboxed-agency
  - developer-tool-embodiment
  - remote-coding-labor
related_tensions:
  - minimal-core-vs-batteries-included
related_histories:
  - the-rise-of-terminal-coding-agents
source_basis:
  type: mixed
  notes: "Grounded in OpenHands custom sandbox and microagent docs plus Cursor background-agent docs; the body metaphor is interpretive."
---
# Sandbox As Agent Body

The sandbox matters in this observatory because some systems do not merely *use* an execution environment. They treat that environment as the agent’s practical body.

OpenHands makes this unusually visible. Its coding agent identity depends on having a shell, browser, APIs, repository access, MCP, and customizable sandbox boundaries. Cursor’s background agents push in the same direction from another angle: once work moves into an isolated remote machine, the environment is no longer incidental infrastructure. It becomes the place where the agent actually senses, acts, and iterates.

Why this matters:

- it separates “tool use” from embodiment
- it explains why environment configuration becomes a major architectural concern
- it clarifies why sandbox decisions shape trust, autonomy, and failure modes all at once

What this concept solves:

- it gives language for systems whose leverage comes from environmental breadth rather than orchestration elegance
- it explains why practical coding agents often need richer bodies than chat-centric systems

What it reveals:

- agency changes when the environment can run tests, install packages, browse, or persist setup
- permissions and isolation are not just safety wrappers; they are part of the cognitive design

What it obscures:

- a stronger body can make the system feel more capable than it is
- environmental richness can hide weak planning or poor internal structure

The key observatory reading is this:

> In embodied coding systems, the sandbox is not a box around the agent. It is the body through which the agent becomes operationally real.
