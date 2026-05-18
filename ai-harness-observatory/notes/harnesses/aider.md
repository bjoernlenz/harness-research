# Aider

## Essence

Aider is a coding agent that stays close to the repository, using chat, diffs, and git as the practical substrate for collaboration.

## Architectural Worldview

This system assumes that useful coding agency is grounded in files, edits, and repo state. It privileges concrete change over elaborate orchestration metaphors.

## Center of Gravity

Repository context, code editing, and human collaboration loops.

## Complexity Lives In

- Context selection
- Patch generation
- Repo awareness
- Human review and approval

## Primary Substrate

- Repository
- Git
- Chat
- Diff

## Trust Model

- Repository closeness
- Diff review
- Human approval

## Memory Model

Memory mostly lives in the repository, chat transcript, and git history. The project feels closer to filesystem-as-memory than to separate cognitive memory stores.

## Human Role

The human is an active collaborator who steers prompts, reviews edits, and decides how much autonomy to allow.

## Playfulness / Surprise

The fun move is how little theater it needs: the repo itself becomes the agent body, and git becomes part of the cognition loop.

## What It Makes Easy

- Fast code edits in an existing repo
- Tight human-agent collaboration
- Working from concrete diffs

## What It Makes Awkward

- General-purpose multi-agent orchestration
- High-level workflow modeling outside the codebase

## Failure Modes

- Context drift in large repos
- Patch misalignment
- Repo-local optimization at the expense of broader planning

## What It Refuses

- Elaborate agent theater
- Heavy orchestration abstractions
- Separation from the actual codebase

## Core Tension

Its strength is staying close to the repo. Its limitation is that repo-closeness can make broader autonomous planning feel secondary.

## Archetype

The Repo Companion

## Representative For

- Repo-close coding agent
- Diff-mediated collaboration

## Related Concepts

- [[git-as-cognition]]
- [[repository-as-memory]]
- [[coding-agents]]

## Open Questions

- How much of Aider's effectiveness comes from UI discipline versus model prompting?
- Where does it start to strain on larger autonomous tasks?

## Animal or Transport

Sheepdog. It stays close to the working ground, takes direction well, and helps move concrete changes through the repo rather than disappearing into abstraction.

## Sources

- https://aider.chat/
- https://github.com/Aider-AI/aider
