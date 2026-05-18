# Pi

## Essence

Pi is a minimal terminal coding harness that keeps the core intentionally small and pushes workflow-specific behavior into extensions, skills, prompt templates, and packages.

## Architectural Worldview

The project treats minimalism as an architectural principle. Instead of shipping a giant built-in agent operating system, it keeps the base harness lean and expects richer behavior to emerge from composition.

## Center of Gravity

Terminal interaction, extensibility, and a small-core runtime philosophy.

## Complexity Lives In

- Extension and package composition
- Provider integration
- Context-file loading
- Choosing what belongs in core versus ecosystem

## Primary Substrate

- Terminal
- Repository
- Extensions
- Context files

## Trust Model

- Minimal-core transparency
- Local context
- Extension choice

## Memory Model

Core memory appears intentionally light. The docs emphasize context files, settings, extensions, and packages more than a large built-in memory substrate.

## Human Role

The human is an operator and composer: running the harness in the terminal, shaping context, and extending the system when the default core is not enough.

## Playfulness / Surprise

The fun move is that Pi leaves out a lot of the ceremony other agent tools treat as mandatory. It is playful in its restraint, betting that a small core plus extensions is a better long-term shape.

## What It Makes Easy

- Running a coding agent directly in the terminal
- Adapting behavior through extensions and packages
- Keeping the base workflow relatively understandable

## What It Makes Awkward

- Expecting every advanced workflow feature to exist in core by default
- Comparing it directly to heavier batteries-included agent platforms

## Failure Modes

- Extension fragmentation
- Capability ambiguity
- Outsourced complexity through packages

## What It Refuses

- A bloated batteries-included core
- Bundling every workflow abstraction by default
- Hiding extensibility behind a monolith

## Core Tension

Its elegance comes from restraint, but that same restraint pushes meaningful complexity outward into extension choice and composition.

## Archetype

The Cognitive Shell

## Representative For

- Minimal-core coding harness
- Extension-driven terminal agent

## Related Concepts

- [[local-first-terminal-agents]]
- [[extension-driven-runtime]]
- [[context-files]]

## Open Questions

- How stable is the long-term boundary between core features and extensions?
- Which workflows consistently end up rebuilt by the ecosystem and therefore want to migrate into core?

## Animal or Transport

Cargo bike. It stays light, direct, and practical, while attachments and carried gear determine how much specialized work it can do.

## Sources

- https://pi.dev/docs/latest
- https://pi.dev/docs/latest/usage
- https://pi.dev/news/2026/5/7/pi-has-a-new-home
