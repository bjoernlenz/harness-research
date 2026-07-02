---
id: cursor-brief
title: Cursor - Why This Exists
kind: brief
related_harnesses:
  - cursor
related_concepts:
  - mode-gated-agency
  - background-agents
  - ide-as-agent-body
source_basis:
  type: mixed
  notes: "Grounded in Cursor documentation and product materials, with interpretation focused on mode-shaped capability surfaces and remote background work."
---
# Cursor - Why This Exists

## The Short Version

Cursor exists because coding agency does not always want one fixed posture. The docs emphasize multiple modes and background agents, with the IDE remaining the main habitat. The architectural argument is that different tasks deserve different capability surfaces, and heavier work can move into separate environments.

## Plain Vanilla

Plain vanilla is the IDE assistant with one default interaction model: ask a question, get a suggestion, maybe accept a patch. It is helpful, but it flattens very different tasks into one stance. Read-only reasoning, local edits, autonomous code changes, and long-running remote work all get squeezed into the same surface.

## The Pain It Responds To

That flattening creates friction. Users want help at different intensities, and they do not always want heavy autonomy in the foreground. Cursor appears to respond to that by making modes explicit and by providing a path for asynchronous work in background agents.

## The Architectural Argument

The docs emphasize Ask, Agent, Manual, Custom, and background agents because the architecture is making a boundary argument. The hidden bet is that agency becomes easier to trust when capability surfaces are mode-shaped instead of pretending every task wants the same level of power.

## What It Makes Possible

Cursor makes it easier to scale from lightweight IDE assistance to more autonomous and even remote coding work without forcing the same interface for everything. It also makes environment separation a design feature: the background worker can carry heavier tasks without turning every foreground interaction into a full agent run.

## What Would Be Missing Without It

Without this pattern, the ecosystem would lose a strong example of mode-gated agency inside the IDE. We would still have editor assistants and remote agents, but less evidence that a single product can connect those through explicit capability boundaries.

## Similar To

- OpenHands shares Cursor's interest in giving the agent a richer practical body, though OpenHands is broader and more sandbox/platform-oriented.
- Claude Code also cares about trust boundaries, but Cursor expresses them through visible modes and remote environment separation rather than terminal permissions.

## Very Different From

- LangGraph centers explicit runtime control flow, while Cursor centers ergonomic task-shaping at the user surface.
- PydanticAI derives reliability from typed contracts, whereas Cursor derives it from interaction modes and environment boundaries.

## Opposes / Corrects

Cursor pushes against the assumption that coding agents should present one uniform level of autonomy. The correction is that users often need multiple stances, from light consultation to heavier delegated work.

## Core Tradeoff

Cursor gains flexibility and a cleaner gradient of autonomy, but it introduces more boundaries for the user to understand: mode choice, background trust, and local-versus-remote environment drift.

## The One-Sentence Memory Hook

> Cursor argues that coding agency should come in modes, not one undifferentiated power level.

## Sources

- https://cursor.com/docs
- https://docs.cursor.com/en/background-agents
