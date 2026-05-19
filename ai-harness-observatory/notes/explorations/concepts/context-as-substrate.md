---
id: context-as-substrate
title: Context As Substrate
kind: concept
related_harnesses:
  - claude-code
  - cursor
  - pi
related_concepts:
  - context-files
  - terminal-as-agent-body
  - ide-as-agent-body
related_tensions:
  - closeness-vs-orchestration
related_histories:
  - the-rise-of-terminal-coding-agents
related_comparisons:
  - shell-vs-runtime-worldviews
source_basis:
  type: mixed
  notes: "Grounded in current product docs for Claude Code, Cursor, and Pi, with interpretive framing about context functioning as working medium."
---
# Context As Substrate

In this observatory, context is not just background information. In several coding harnesses it behaves more like the working medium that keeps agency coherent from turn to turn.

Claude Code shows this clearly. The terminal, the current repository, MCP connections, and project configuration together form the space in which the agent can stay oriented. Cursor does something similar through IDE context, mode boundaries, and optional background environments. Pi keeps the same pattern in a leaner form: context files, extensions, and local terminal state do much of the coherence work that heavier runtimes push into orchestration layers.

This matters because it explains a family resemblance across systems that otherwise look different. They are not primarily trying to build memory-heavy agents or graph-heavy agents. They are trying to preserve usefulness by keeping the agent close to the active working surface.

What this makes easier to see:

- why repo-close and terminal-close systems often feel practical quickly
- why these harnesses invest in context loading, command surfaces, and configuration files
- why trust often comes from environmental closeness rather than explicit control-flow structure

What it obscures:

- context can look coherent while still being shallow
- these systems can underdescribe long-running state once the work leaves the immediate environment
- “more context” can become a substitute for better architectural memory

This suggests a useful distinction:

> In some harnesses, context is not support material around the agent. It is the material the agent is made of while it works.
