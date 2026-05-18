# OpenAI Agents SDK

## Essence

OpenAI Agents SDK treats agents as configurable runtime objects that can use tools, hand off work to one another, and leave a visible trace of what happened.

## Architectural Worldview

This system assumes that agentic applications become more reliable when orchestration primitives are explicit: agents, tools, handoffs, guardrails, and traces.

## Center of Gravity

Tool use, handoff design, and observability.

## Complexity Lives In

- Tool integration
- Handoff boundaries
- Guardrails
- Trace interpretation

## Primary Substrate

- Agent objects
- Tools
- Handoffs
- Traces

## Trust Model

- Explicit handoffs
- Trace visibility
- Guardrails

## Memory Model

The visible emphasis is more on execution trace and orchestrated action than on a deep native memory model. Memory looks delegated to context and external systems.

## Human Role

The human is a framework developer and orchestrator designing agents, tools, and transfers of control.

## Playfulness / Surprise

The playful move is naming handoffs directly. Multi-agent behavior stops being implicit magic and becomes a visible routing decision.

## What It Makes Easy

- Building modular agent workflows
- Observing what happened during execution
- Splitting work across specialized agents

## What It Makes Awkward

- Pretending orchestration complexity has disappeared
- Relying on one giant prompt as the whole architecture

## Failure Modes

- Handoff mismatch
- Tool-routing confusion
- Guardrail gaps

## What It Refuses

- Single giant undifferentiated agent prompts
- Unobservable multi-agent behavior
- Treating orchestration as hidden magic

## Core Tension

Its strength is modular orchestration with explicit traces and handoffs. Its tradeoff is that the modularity can move complexity into system design and coordination boundaries.

## Archetype

The Tool Router

## Representative For

- Handoff-centric agent runtime
- Trace-first orchestration SDK

## Related Concepts

- [[handoffs]]
- [[guardrails]]
- [[traces-as-residue]]
- [[tool-augmented-agents]]

## Open Questions

- How much of the system’s practical ergonomics comes from tracing versus from the core primitives themselves?
- Where does long-term memory want to live in real deployments built on this SDK?

## Animal or Transport

Airport hub. It coordinates departures, arrivals, transfers, and routing between specialized actors while keeping movement visible.

## Sources

- https://platform.openai.com/docs/guides/agents-sdk/
- https://platform.openai.com/docs/guides/agents
- https://openai.com/index/new-tools-for-building-agents/
