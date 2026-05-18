# AutoGen

## Essence

AutoGen is a framework for building coordinated agent systems through conversations, teams, event-driven runtimes, and a large extension surface.

## Architectural Worldview

This system believes that useful cognition can emerge from structured interaction among multiple agents. Conversation is not just UI here; it is part of the runtime substrate.

## Center of Gravity

Team topology, agent interaction, and layered runtime design.

## Complexity Lives In

- Team design
- Message routing
- Termination conditions
- Runtime and extension selection

## Primary Substrate

- Conversation
- Teams
- Events
- Extensions

## Trust Model

- Team structure
- Explicit termination
- Runtime layering

## Memory Model

Memory appears as conversation history, team state, and pluggable components, but the stronger signature is coordination rather than persistent inner memory.

## Human Role

The human is a designer of teams, runtimes, and interaction patterns rather than only a prompt author.

## Playfulness / Surprise

The architecture is surprisingly social. Swarms, group chats, and orchestrators are treated as ordinary building blocks, not just theatrical metaphors.

## What It Makes Easy

- Prototyping multi-agent conversations
- Escalating from simple chats to deeper runtimes
- Experimenting with team-based coordination patterns

## What It Makes Awkward

- Keeping the system conceptually small
- Avoiding premature multi-agent elaboration

## Failure Modes

- Agent-team sprawl
- Message-loop confusion
- Termination ambiguity

## What It Refuses

- A single-agent-only worldview
- One-layer orchestration models
- Keeping coordination implicit

## Core Tension

Its expressive power comes from team coordination and layered runtimes, but those same layers can make the system feel intricate before it feels stable.

## Archetype

The Multi-Agent Theater

## Representative For

- Team-based agent framework
- Multi-agent coordination runtime

## Related Concepts

- [[multi-agent-theater]]
- [[team-conversation]]
- [[event-driven-agency]]
- [[termination-conditions]]

## Open Questions

- Where do the most robust AutoGen systems stop looking like chat teams and start looking like distributed systems?
- Which layer actually becomes the long-term center of gravity in production use: AgentChat, Core, or Extensions?

## Animal or Transport

Flock of starlings. Its intelligence comes from many moving participants coordinating patterns rather than from a single heavy vehicle.

## Sources

- https://microsoft.github.io/autogen/stable/
- https://microsoft.github.io/autogen/0.6.4/index.html
- https://github.com/microsoft/autogen
