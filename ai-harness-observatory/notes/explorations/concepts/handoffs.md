---
id: handoffs
title: Handoffs
kind: concept
related_harnesses:
  - openai-agents-sdk
  - autogen
related_concepts:
  - agent-team
  - team-conversation
  - traces-as-residue
related_tensions:
  - autonomy-vs-permission
  - closeness-vs-orchestration
related_histories:
  - why-agent-teams-became-popular
  - why-graph-orchestration-emerged
related_comparisons:
  - shell-vs-runtime-worldviews
source_basis:
  type: mixed
  notes: "Grounded in current multi-agent framework material around agent transfer and coordination, with interpretive emphasis on handoffs as a visibility and boundary mechanism."
---
# Handoffs

Handoffs matter because they turn a vague idea of multi-agent cooperation into a visible architectural event. Instead of one agent somehow doing everything, the system has to say: now control moves, and it moves for a reason.

The OpenAI Agents SDK makes this explicit enough that handoffs start to feel like a design language rather than an implementation detail. AutoGen pressures the same space through agent conversation and role distribution. In both cases, the important shift is not just specialization. It is boundary declaration.

That boundary declaration has a human story underneath it. Builders reach for handoffs when monolithic agency starts feeling too magical to trust or too muddy to debug. A handoff says where responsibility changes shape. It gives the architecture a place to admit that different kinds of work may need different agents, tools, or control logics.

What this makes easier to see is why handoffs are attractive in multi-agent runtimes: they improve decomposition, traceability, and governability. What they can obscure is that every handoff also becomes a new point of fragility. If the boundary is wrong, the system gets more structure without getting more clarity.

