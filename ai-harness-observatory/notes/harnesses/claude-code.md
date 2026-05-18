# Claude Code

## Essence

Claude Code is a terminal-native coding agent that composes with existing developer tools, uses MCP and subagents, and asks permission when actions cross meaningful boundaries.

## Architectural Worldview

This system assumes that strong coding agency should live inside the terminal and cooperate with existing tooling rather than trying to replace it with a sealed environment.

## Center of Gravity

Terminal workflow, permissions, and composable developer tooling.

## Complexity Lives In

- Context management
- Permission boundaries
- Terminal composition
- Subagent and MCP customization

## Primary Substrate

- Terminal
- Repository
- Context
- Permissions

## Trust Model

- Permissioned agency
- Terminal transparency
- Human approval

## Memory Model

The visible architecture leans on session context, repository state, settings, and subagent files more than on a distinct memory subsystem.

## Human Role

The human is an operator and approver who works in close collaboration with the agent and can shape specialization through subagents.

## Playfulness / Surprise

The elegant move is importing unix composability into agentic coding. Pipes, scripts, and markdown-defined subagents make specialization feel tangible.

## What It Makes Easy

- Working with an agent directly in terminal workflows
- Composing coding agency with existing tools
- Keeping permission and safety boundaries visible

## What It Makes Awkward

- Expressing high-level orchestration as a visible graph
- Treating the system like a batteries-included orchestration framework

## Failure Modes

- Context overreach
- Permission fatigue
- Sparse high-level orchestration visibility

## What It Refuses

- A sealed GUI-only agent world
- Unbounded action without permission checks
- Ignoring existing developer toolchains

## Core Tension

Its strength is terminal intimacy and composability. Its tradeoff is that staying close to raw developer workflows can make higher-level orchestration feel intentionally sparse.

## Archetype

The Cognitive Shell

## Representative For

- Terminal-native collaborator
- Permissioned coding agent

## Related Concepts

- [[unix-composability]]
- [[permissioned-agency]]
- [[subagents-as-files]]
- [[terminal-as-agent-body]]

## Open Questions

- Where does the permission model most improve trust versus merely add interaction overhead?
- How far can subagents carry specialization before users want more explicit orchestration structure?

## Animal or Transport

Border collie. It is agile, attentive, responsive to commands, and strongest when working in close collaboration with a human operator.

## Sources

- https://docs.anthropic.com/en/docs/claude-code/overview
- https://docs.anthropic.com/en/docs/claude-code/settings
- https://docs.anthropic.com/en/docs/claude-code/security
