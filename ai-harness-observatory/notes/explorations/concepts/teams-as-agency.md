---
title: Teams As Agency
kind: concept
related_harnesses:
  - autogen
  - openai-agents-sdk
  - llamaindex
related_concepts:
  - agent-team
  - team-conversation
  - multi-agent-theater
  - handoffs
related_tensions:
  - closeness-vs-orchestration
related_comparisons:
  - repo-vs-graph-agency
source_basis:
  type: mixed
  notes: "Grounded in AutoGen and OpenAI Agents SDK docs plus current observatory comparison work; the architectural reading is interpretive."
---
# Teams As Agency

Some systems do not treat an agent as a single bounded actor at all. They treat agency as something that emerges from coordination among several specialized actors.

AutoGen is the clearest current example in this corpus. Teams, conversations, and runtime topology are not decorative language there. They are part of the architecture. The OpenAI Agents SDK reaches the same zone from a cleaner, more modular angle: handoffs let responsibility move between agents without pretending that one giant prompt should do everything.

Why this matters:

- it reframes “multi-agent” from marketing language into a real ontology choice
- it explains why routing, handoffs, and termination logic become first-class
- it makes visible that some architectures trust distributed specialization more than monolithic competence

What it reveals about agency:

- agency can be located in coordination rather than inside one loop
- message passing can be a cognitive mechanism, not just an implementation detail
- the unit of analysis may be the team, not the individual agent

What it makes easier to see:

- why orchestration-heavy systems care so much about traces and structure
- why team-based systems often accumulate complexity in topology rather than context

What it obscures:

- distributed roles can make responsibility harder to perceive
- “team” language can hide brittle routing or weak actual specialization
- the social metaphor can outrun the operational reality

Inside this observatory, `teams-as-agency` is therefore not a generic statement that multiple agents can collaborate. It is the stronger claim that the architecture places cognition in the coordination pattern itself.
