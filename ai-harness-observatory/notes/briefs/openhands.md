---
id: openhands-brief
title: OpenHands - Why This Exists
kind: brief
related_harnesses:
  - openhands
related_concepts:
  - sandbox-as-agent-body
  - sandboxed-agency
  - developer-tool-embodiment
source_basis:
  type: mixed
  notes: "Grounded in OpenHands docs and repository materials, with interpretation centered on embodied coding agency and sandbox breadth."
---
# OpenHands - Why This Exists

## The Short Version

OpenHands exists because thinner coding assistants can fail simply by lacking a practical body. The docs emphasize agents that can work through code, shell, browser, APIs, and multiple product surfaces. The architectural argument is that coding agency becomes meaningfully stronger when the agent has a broader environment to act inside.

## Plain Vanilla

Plain vanilla is a coding assistant that mostly chats, maybe edits a file, and depends on the human to perform the rest of the workflow. Tool use is narrow. Environment setup is manual. Browser actions, commands, repo manipulation, and external systems are either missing or loosely connected.

## The Pain It Responds To

That thinner setup breaks down when the job is not just "suggest a patch" but "do the work a developer would do." The pain is practical incompleteness: the assistant knows what should happen but lacks the embodied affordances to do it. OpenHands appears to respond to that frustration by widening the agent body rather than narrowing the task.

## The Architectural Argument

The docs emphasize CLI, GUI, cloud, SDK, skills, and MCP because the architecture is making a maximalist claim: capability comes from environment, not only from reasoning. The implicit bet seems to be that agent power depends heavily on the practical surfaces it can inhabit and the tools it can reach.

## What It Makes Possible

OpenHands makes broader software work easier to delegate. It supports richer end-to-end tasks, more customization, and more continuity between local and hosted operation. It also makes it easier to treat the repo as one part of a larger working environment instead of the whole scene.

## What Would Be Missing Without It

Without this pattern, the ecosystem would lose a strong example of sandbox-centered coding agency. We would have many assistants that can discuss code, but fewer that defend the idea that an agent needs a fuller developer body to be meaningfully capable.

## Similar To

- Cursor also expands the agent body beyond a narrow chat loop, especially through background agents and broader IDE action surfaces.
- Claude Code shares the belief that coding agency should act through real tools, though it stays closer to terminal composability and permission boundaries than to a broad product/platform shape.

## Very Different From

- PydanticAI focuses on typed boundaries and validation rather than giving the agent a rich embodied environment.
- Pi deliberately keeps the core small, while OpenHands accepts more system breadth as the cost of practical power.

## Opposes / Corrects

OpenHands pushes against the assumption that coding assistants mainly need better prompting or better patch generation. The inferred correction is that many failures are actually failures of embodiment: the agent cannot act like a useful worker because it lacks the right body.

## Core Tradeoff

OpenHands gains breadth and practical reach by giving the agent a fuller environment, but that same breadth increases system heaviness, safety complexity, and customization overhead.

## The One-Sentence Memory Hook

> OpenHands argues that coding agency gets serious when the agent has a real body, not just a better prompt.

## Sources

- https://docs.openhands.dev/overview/introduction
- https://docs.openhands.dev/usage/about
- https://github.com/OpenHands/OpenHands
