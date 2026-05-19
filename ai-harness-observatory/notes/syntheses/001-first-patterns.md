---
id: 001-first-patterns
kind: synthesis
---
# 001 First Patterns

This synthesis is based on the current first-wave corpus of **11 harnesses** and **44 concept records**.

The strongest early pattern is that the field already splits into several different answers to the question:

> What is the actual body or substrate of agency?

## 1. Three Major Families Are Already Visible

### 1.1 Repo-close coding agents

Examples:

- Aider
- Claude Code
- Pi
- Cursor
- OpenHands

These systems place agency close to the working codebase and the developer environment.

Their substrates are things like:

- repository
- git
- terminal
- IDE context
- sandbox
- diff

They tend to believe:

- agency should stay close to concrete work
- human collaboration is not a temporary crutch
- environment matters as much as prompting
- the codebase itself is part of cognition

Their main differences are not whether they are “coding agents,” but **where exactly they let complexity live**:

- Aider: repo + diff + git
- Claude Code: terminal + permissions + composability
- Pi: minimal core + extensions
- Cursor: modes + remote background agents
- OpenHands: broad embodied tool surface + sandbox

### 1.2 Explicit orchestration frameworks

Examples:

- LangGraph
- OpenAI Agents SDK
- Semantic Kernel
- AutoGen

These systems treat agent design as an orchestration problem.

But they do not mean the same thing by orchestration:

- LangGraph: graph + state + checkpoints
- OpenAI Agents SDK: agents + handoffs + traces
- Semantic Kernel: kernel + plugins + connectors
- AutoGen: teams + conversations + layered runtime

This is an important early insight:

> “Orchestration framework” is too coarse a category.

Inside it, there are already distinct worldviews:

- graph orchestration
- routing orchestration
- middleware orchestration
- social / team orchestration

### 1.3 Data-centered agent systems

Example:

- LlamaIndex

LlamaIndex is the clearest first-wave case where the main substrate is not repo, graph, or team, but **data itself**:

- indexes
- retrieval
- workflows
- knowledge surfaces

This suggests that retrieval-heavy systems deserve their own lane rather than being treated as a minor variation of generic agent frameworks.

## 2. The Real Question Is Substrate

The newly added `primary_substrate` field already looks valuable.

Across the corpus, agency is being externalized into very different materials:

- repository
- git
- diff
- terminal
- IDE context
- graph
- state
- handoffs
- traces
- kernel
- plugins
- data
- indexes
- workflows

This looks more promising than feature comparison because it reveals what each project thinks the agent is *made of*.

Working hypothesis:

> Primary substrate may become one of the strongest top-level organizing dimensions in the observatory.

## 3. Current Archetypal Tension

A recurring split is visible between:

- **agents as collaborators in a working environment**
- **agents as orchestrated runtime structures**

The first group wants closeness:

- repo
- terminal
- IDE
- sandbox

The second group wants legibility:

- graph
- handoff
- kernel
- team

LlamaIndex introduces a third pole:

- data as substrate

This gives the observatory an early triangle:

1. environment-close agency
2. orchestration-close agency
3. data-close agency

## 4. What Feels Alive

Several design moves already feel like real invention rather than style:

- Aider: git / repo / diff as cognition
- LangGraph: visible loops and resumable graph state
- OpenAI Agents SDK: handoffs plus trace-first orchestration
- Pi: minimal core with extensibility as the main surface
- Cursor: mode-gated foreground agency plus remote background labor
- OpenHands: sandbox as an actual agent body
- Semantic Kernel: kernel as cognitive spine
- LlamaIndex: retrieval and agent workflows treated as one design surface

## 5. What The Current Corpus Still Undersamples

The current first wave is already strong for:

- coding agents
- orchestration runtimes
- tool-heavy developer harnesses

It is still relatively weak on:

- evaluation harnesses
- memory-first systems
- local-first assistants outside coding
- workflow engines outside developer tooling

## 6. Provisional Taxonomy Recommendation

Before scaling much further, treat these as provisional top-level families:

- Repo / Terminal / IDE Companions
- Graph / Runtime Orchestrators
- Team / Multi-Agent Coordinators
- Middleware / Capability Spines
- Data / Retrieval-Centered Agent Systems

These are better than flattening everything into “agent framework” or “coding agent.”
