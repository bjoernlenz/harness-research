---
id: minimal-core-vs-batteries-included
title: Minimal Core Vs Batteries Included
kind: tension
related_harnesses:
  - pi
  - openhands
  - claude-code
  - semantic-kernel
related_concepts:
  - minimal-core-agent-design
  - extension-driven-runtime
  - sandbox-as-agent-body
  - plugins-as-capabilities
related_histories:
  - the-rise-of-terminal-coding-agents
source_basis:
  type: mixed
  notes: "Grounded in Pi, OpenHands, Claude Code, and Semantic Kernel docs; the polarity is interpretive."
---
# Minimal Core Vs Batteries Included

This tension asks where architectural mass should live.

It is partly a technical decision, but also a philosophical and emotional one. Should a harness arrive like a small instrument that becomes powerful through composition, or like a capable machine that already contains much of the body it needs?

Pi is the cleanest minimal-core case in the corpus. It stays small and pushes behavior outward into extensions, packages, prompt templates, and skills. Claude Code is not as minimal, but it shares part of the same instinct: stay close to existing tools and keep composability high.

OpenHands stands much closer to the batteries-included pole. Its value proposition is that the agent should arrive with a broad practical body already available. Semantic Kernel does this in a different register: not a coding body, but a capability spine of plugins, connectors, and services.

The human story inside this tension is a familiar software story. Minimal cores come from distrust of bloat, lock-in, and framework gravity. Batteries-included systems come from distrust of fragmentation, setup burden, and the fantasy that users always want to assemble their own power stack.

What the minimal-core side sees clearly:

- small cores stay legible
- extensibility can preserve flexibility
- not every workflow should be baked into the runtime

What the batteries-included side sees clearly:

- real work often needs embodied affordances immediately
- users do not always want to assemble power from many optional parts
- environment and capability breadth can be the feature

What each side tends to miss:

- minimal cores can outsource too much burden to composition
- batteries-included systems can become heavy, sprawling, and harder to trust

Where hybrids are emerging:

- Claude Code and Cursor are not truly tiny, but they inherit the minimal-core instinct by leaning on existing developer environments
- Semantic Kernel tries to keep a coherent spine even while expanding through plugins and connectors
- OpenHands suggests that once an agent gets a full practical body, the question shifts from composition to governance
- Pi shows the strongest version of the claim that a small core can become expressive if extension surfaces are good enough

Why this matters:

This tension is really about where a harness wants complexity to reside:

- inside the runtime
- in extensions and plugins
- in the environment
- in the user’s configuration work

That makes it a genuine architectural polarity, not just a packaging preference.

Underneath it is a deeper difference in temperament. Minimal-core systems trust ecosystems. Batteries-included systems trust embodiment.
