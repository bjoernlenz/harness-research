# Cursor

## Essence

Cursor treats coding agency as a mode-shaped IDE experience, with different capability surfaces for asking, editing, autonomous work, and asynchronous remote agents.

## Architectural Worldview

This system assumes one agent shape is not enough. Coding work varies, so the harness should expose explicit modes with different tool powers and let heavier work move into a remote environment when needed.

## Center of Gravity

Mode selection, IDE-native context, and the split between local foreground work and remote background execution.

## Complexity Lives In

- Choosing the right mode
- Remote environment setup
- Trust boundaries around auto-run behavior
- Bridging foreground and background workflows

## Primary Substrate

- IDE context
- Repository
- Modes
- Remote agent environment

## Trust Model

- Mode boundaries
- Review before merge
- Environment separation

## Memory Model

The first architectural signal is contextual access and workspace continuity rather than a separate typed memory layer. Background agents extend that continuity into a remote machine.

## Human Role

The human is an operator choosing mode, deciding when to escalate into background execution, and reviewing the resulting work.

## Playfulness / Surprise

The fun move is that Cursor does not pretend every task wants the same kind of agent. It turns capability boundaries into explicit modes, then adds asynchronous remote labor on top.

## What It Makes Easy

- Switching between read-only exploration and active coding
- Working inside an IDE-native agent flow
- Offloading longer-running work to remote background agents

## What It Makes Awkward

- Keeping the system mentally simple
- Reasoning about the trust and setup implications of remote background work

## Failure Modes

- Mode confusion
- Remote-environment drift
- Trust gaps between foreground and background work

## What It Refuses

- A single fixed interaction mode for every task
- Keeping all coding agency only in the local foreground session
- Forcing either full autonomy or full manual control with no middle ground

## Core Tension

Its strength is matching capability surface to task shape, from read-only Ask mode to remote background agents. Its tradeoff is that more modes and environments mean more boundaries for the user to understand and trust.

## Archetype

The Repo Companion

## Representative For

- Mode-gated IDE agent
- Remote background coding agent

## Related Concepts

- [[mode-gated-agency]]
- [[background-agents]]
- [[remote-coding-labor]]
- [[ide-as-agent-body]]

## Open Questions

- Where does the boundary between foreground agent and background agent become confusing rather than empowering?
- How much of Cursor’s distinctiveness comes from mode design versus the underlying model and repo context work?

## Animal or Transport

Seaplane. It can stay close and maneuver locally, but it can also lift off into a separate environment when the work needs more range.

## Sources

- https://docs.cursor.com/agent
- https://docs.cursor.com/en/background-agents
- https://docs.cursor.com/chat/overview
