---
id: closeness-vs-orchestration
title: Closeness Vs Orchestration
kind: tension
related_harnesses:
  - aider
  - claude-code
  - pi
  - langgraph
  - autogen
  - openai-agents-sdk
related_concepts:
  - repository-as-memory
  - graph-orchestration
  - terminal-as-agent-body
  - explicit-state
related_histories:
  - the-rise-of-terminal-coding-agents
related_comparisons:
  - repo-vs-graph-agency
  - trust-through-closeness-vs-structure
source_basis:
  type: mixed
  notes: "Grounded in current official docs and current comparison notes; the polarity is an observatory interpretation."
---
# Closeness Vs Orchestration

This is one of the strongest tensions currently visible in the observatory.

On one side are systems that want to stay close to the working environment:

- Aider
- Claude Code
- Pi
- Cursor

Their wager is that agency becomes useful by remaining near the repository, terminal, IDE, permissions, and human review surfaces.

On the other side are systems that want legible orchestration:

- LangGraph
- OpenAI Agents SDK
- AutoGen
- Semantic Kernel

Their wager is that agency becomes durable by making coordination structures explicit: graphs, handoffs, traces, plugins, teams, checkpoints.

What closeness sees clearly:

- concrete work
- environmental truth
- human collaboration
- fast movement from intent to action

What orchestration sees clearly:

- control flow
- resumability
- routing
- inspectability across longer or more complex runs

What closeness tends to miss:

- implicit structure can stay hidden until it breaks
- context-rich systems can become hard to reason about over longer tasks

What orchestration tends to miss:

- structure can outrun immediate usefulness
- explicit control can become its own bureaucracy

Why this matters:

This is not a stylistic difference. It shapes where trust comes from, where complexity accumulates, and what the architecture thinks the hard part of agency actually is.

The observatory should preserve this tension as a live polarity rather than prematurely declaring one side mature and the other primitive.
