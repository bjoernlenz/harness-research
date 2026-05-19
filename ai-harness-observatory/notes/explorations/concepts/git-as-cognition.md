---
id: git-as-cognition
title: Git As Cognition
kind: concept
related_harnesses:
  - aider
related_concepts:
  - repository-as-memory
  - diff-as-interface
  - memory-as-residue
related_tensions:
  - closeness-vs-orchestration
related_histories:
  - the-rise-of-terminal-coding-agents
related_comparisons:
  - repo-vs-graph-agency
source_basis:
  type: mixed
  notes: "Grounded in Aider's official repo-close framing and interpreted as a broader design stance about git as part of the cognitive loop."
---
# Git As Cognition

This concept matters because some coding harnesses do not treat git as a cleanup step after thinking. They treat it as part of thinking itself. The diff is how the system sees what changed, the commit history is how it remembers what happened, and the branch state is how it stays honest about where the work actually stands.

In Aider this is especially visible. The system does not build trust through a rich orchestration runtime or a heavy planning graph. It builds trust by staying close to the repository and by making changes show up as inspectable residue. That makes git feel less like plumbing and more like a shared cognitive organ between human and agent.

This reveals something human underneath the architecture. Developers already rely on git to remember what they forgot, show them what they broke, and let them reverse course without panic. A harness that leans into git is really leaning into an emotional truth: people trust work more when it leaves a trail in a tool they already use to recover from mistakes.

What this makes easier to see is why repo-close agents can feel practical very quickly. They inherit a memory surface, a review surface, and a repair surface all at once. What it obscures is that git is a very domain-specific kind of cognition. It is strong for code change and weak for broader task memory, longer-running plans, or non-repository work.

