---
id: repo-vs-graph-agency
kind: comparison
---
# Repo vs Graph Agency

## Essence

This is the contrast between agency that stays close to the working repository and agency that becomes explicit runtime structure.

## Representative Harnesses

- Aider
- Claude Code
- LangGraph

## Primary Substrates Involved

- Repository / git / diff
- Terminal / repo context
- Graph / state / checkpoints

## Trust Models Involved

- Trust through visible diffs and human review
- Trust through explicit control flow and inspectable state

## Failure Modes Involved

- Repo-local drift
- Patch misalignment
- Graph sprawl
- State-shape brittleness

## Hidden Bets

- Repo-side: useful coding agency comes from staying close to files and edits
- Graph-side: explicit state graphs outperform opaque autonomous loops

## What Each Side Sees Clearly

- Repo-side sees the reality of concrete work and human review
- Graph-side sees the reality of long-running structure, loops, and resumability

## What Each Side Tends To Miss

- Repo-side can underweight architectural legibility
- Graph-side can overbuild structure before concrete usefulness appears

## Open Questions

- Where is the crossover point where repo intimacy stops being enough and explicit orchestration becomes worth the burden?
