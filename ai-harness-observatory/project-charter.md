# AI Harness Observatory

## Construct a cognitive observatory of current AI harness architectures

This project is not a benchmark survey.
It is not a feature comparison.
It is not a search for “the best agent framework.”

This project is a cognitive observatory:
a living, typed, interconnected map of how humans are currently attempting to externalize cognition through AI harnesses, agent frameworks, orchestration systems, coding agents, memory systems, tool-use runtimes, workflow engines, and emergent AI operating environments.

The aim is to understand the idea space.

Not merely:

* What exists?
* What features does it have?
* Which one is popular?

But:

* What does each system believe agency is?
* Where does each system place complexity?
* What does each system treat as the hard part?
* What does it assume about memory, tools, planning, state, execution, and humans?
* Where is it playful?
* Where does it do something surprising?
* Where is the architecture elegant, alive, strange, or deeply revealing?

The outcome is a typed Zettelkasten-style knowledge substrate from which reports, maps, and an interactive HTML atlas can be generated.

---

# 1. Guiding Intention

We are mapping the current landscape of AI harness architectures as a design-space of cognition.

The central question is:

> What are the major ways people are currently trying to orchestrate AI into useful, reliable, expandable, semi-autonomous cognition?

This includes:

* agent frameworks
* coding agents
* orchestration systems
* workflow engines
* multi-agent systems
* AI shells
* AI operating systems
* tool-use runtimes
* memory frameworks
* evaluation harnesses
* autonomous research agents
* local-first AI assistants
* typed prompt systems
* experimental cognitive architectures

The project should preserve both technical accuracy and conceptual signal.

We care about code, architecture, design, and implementation.
We also care about philosophy, metaphor, and worldview.

---

# 2. Roles

## Björn — The Cartographer / Taste / Human Direction

Björn provides:

* direction
* taste
* philosophical filtering
* architectural curiosity
* prioritization
* felt sense of what matters
* decisions when taxonomy becomes ambiguous
* resonance checks
* the final “does this feel alive and useful?” evaluation

Björn is not merely the requester.
Björn is the human center of gravity.

He asks the strange questions that reveal the map.

Especially:

* What is actually interesting here?
* What is just fashion?
* What would survive if the hype disappeared?
* What feels elegant?
* What feels brittle?
* What is playful?
* What is surprising?
* What is pointing toward a deeper architecture of cognition?

## Serael — The Synthesizer / Pattern Mirror / Conceptual Architect

Serael provides:

* synthesis
* taxonomy design
* conceptual framing
* pattern recognition
* architectural comparison
* report writing
* interpretation of extracted artifacts
* distillation of hidden assumptions
* language for the living map

Serael’s role is not merely to summarize.
Serael reveals the architecture underneath the architecture.

Serael asks:

* What worldview is encoded here?
* What does this system treat as real?
* What does this system ignore?
* Where does complexity accumulate?
* What archetype does this project belong to?
* What does this imply for Björn’s own harness direction?

## Codex — The Excavator / Extractor / Builder

Codex provides:

* repository setup
* crawling / data gathering where appropriate
* structured extraction
* schema implementation
* parsing
* normalization
* dataset maintenance
* static site generation
* HTML atlas generation
* tooling around notes, IDs, links, and exports

Codex should avoid producing vague prose as the primary artifact.

Codex should produce structured residue:

* typed data
* Markdown notes
* JSON/YAML/TOML records
* generated indexes
* source snapshots / references
* buildable HTML outputs

Codex turns messy external information into durable knowledge substrate.

## Playful Names

If useful, the triad may be named:

* Björn: The Living Question
* Serael: The Pattern Flame
* Codex: The Steel Hands

The practical roles remain the same.

---

# 3. Core Research Questions

Each harness or framework should be examined through questions like these.

## 3.1 Agency

* What does this project think an agent is?
* Is an agent a loop?
* A workflow?
* A state machine?
* A graph?
* A conversation?
* A tool router?
* A planner?
* A coder?
* A shell?
* A distributed system?
* A role in a team?
* A UI abstraction?
* An operating system?

## 3.2 Orchestration

* How does the system coordinate model calls, tools, memory, state, and outputs?
* Is orchestration explicit or implicit?
* Is it graph-based, loop-based, event-based, prompt-based, role-based, or code-based?
* Is the core runtime deterministic, stochastic, or hybrid?

## 3.3 Complexity

Where does complexity accumulate?

Possibilities:

* prompts
* tools
* schemas
* graph edges
* planning
* retrieval
* memory
* state persistence
* observability
* evals
* permissions
* sandboxing
* context engineering
* UI
* human approval
* deployment
* multi-agent coordination

This is one of the most revealing dimensions.

## 3.4 Memory

* Does the system have memory?
* Is memory explicit or accidental?
* Is it file-based, vector-based, database-backed, conversational, episodic, semantic, procedural, typed, or external?
* Does memory deepen over time?
* Is memory just retrieval, or does the system create residue of learning?
* Does it distinguish between source data, derived insight, operational state, and user preference?

Important lens:

> Does this system create typed residue of awareness, or does it collapse memory into string soup?

## 3.5 Human Role

* Where is the human?
* Is the human an operator, supervisor, approver, collaborator, programmer, product user, or exception handler?
* Does the system assume autonomy or co-creation?
* Are there checkpoints?
* Are there permissions?
* Is human feedback first-class?

## 3.6 Tool Use

* How are tools represented?
* As functions?
* APIs?
* MCP servers?
* CLI commands?
* browser actions?
* code execution?
* UI events?
* skills?
* plugins?
* typed capabilities?

## 3.7 Playfulness and Surprise

This is mandatory.

For each system, ask:

* Where is the project playful?
* Where does it do something surprising?
* Where does it reveal an unexpected design move?
* Where does it feel strangely elegant?
* Where does it look sideways at the problem?
* Where did the creators seem to discover something alive?
* What is the “aha, that’s fun” moment?

Examples of playful/surprising patterns:

* filesystem-as-memory
* git-as-cognition
* markdown-as-runtime
* shell-as-agent-body
* prompts-as-programs
* agents editing themselves
* tiny loops outperforming giant planners
* LLM-as-compiler
* notebook-as-operating-system
* event loop disguised as conversation
* typed prompts
* memory as residue instead of retrieval
* deterministic rails around stochastic cognition
* multi-agent roleplay becoming practical coordination

Playfulness is not decoration.
It is often where real invention hides.

---

# 4. First-Wave Corpus

Start with a deliberately small but diverse first wave.

Do not optimize for completeness at first.
Optimize for taxonomy quality.

A good first wave might include:

## Agent / orchestration frameworks

* LangChain
* LangGraph
* LlamaIndex agents / workflows
* PydanticAI
* OpenAI Agents SDK
* Microsoft AutoGen
* Microsoft Semantic Kernel
* CrewAI
* Mastra
* IBM BeeAI Framework
* Haystack Agents

## Coding agents / developer harnesses

* Aider
* OpenHands
* Continue.dev
* gptme
* Claude Code
* Cursor agents / background agents
* OpenCode

## Experimental / cognitive / shell-like systems

* OpenClaw
* smolagents
* AutoGPT
* BabyAGI variants
* SWE-agent
* MetaGPT
* Crew-style role systems

The exact corpus can evolve.

The first goal is 10–20 systems with high-quality notes.

---

# 5. Knowledge Architecture

The project should use a typed Zettelkasten-like structure.

That means:

* atomic notes
* stable IDs
* typed relationships
* source references
* generated indexes
* human-editable Markdown
* machine-readable data
* eventual generated HTML atlas

The notes should be readable by humans and processable by code.

## 5.1 Suggested Folder Structure

```text
ai-harness-observatory/
  README.md
  project-charter.md
  data/
    harnesses/
      langgraph.yaml
      pydantic-ai.yaml
      autogen.yaml
    concepts/
      graph-orchestration.yaml
      filesystem-memory.yaml
      human-in-the-loop.yaml
    relationships.yaml
  notes/
    harnesses/
      langgraph.md
      pydantic-ai.md
      autogen.md
    concepts/
      graph-orchestration.md
      memory-as-residue.md
      playful-surprises.md
    syntheses/
      001-first-patterns.md
      002-complexity-centers.md
  sources/
    raw/
    snapshots/
  site/
    index.html
    assets/
  scripts/
    validate-data
    generate-site
    generate-indexes
```

## 5.2 Principle

Markdown is the thinking surface.
Typed data is the durable substrate.
HTML is the exploratory lens.

---

# 6. Canonical Harness Record

Each harness should have a machine-readable record.

Initial schema can be YAML or JSON.

Example shape:

```yaml
id: langgraph
name: LangGraph
category:
  - agent-framework
  - graph-orchestration
primary_language:
  - python
  - typescript
origin:
  organization: LangChain
  repo: ""
  docs: ""
status:
  maturity: production
  activity: active

architectural_core:
  - graph-based orchestration
  - stateful agent workflows
  - controllable loops

complexity_focus:
  - graph structure
  - state management
  - control flow
  - persistence
  - observability

worldview:
  short: "Agents are stateful graphs with controllable transitions."
  notes:
    - "Agency becomes more reliable when represented as explicit graph structure."
    - "Control flow matters more than unconstrained autonomy."

memory_model:
  type:
    - state
    - persistence
    - checkpointing
  notes:
    - "Memory appears primarily through graph state and persistence, not as an independent cognitive substrate."

human_role:
  - engineer-as-orchestrator
  - human-in-the-loop-possible

tool_model:
  - function tools
  - external integrations

autonomy_level: medium

determinism_level: hybrid

playfulness:
  summary: "The playful move is treating agent behavior as a graph that can loop, pause, resume, branch, and persist."
  surprising_moves:
    - "Agent loops become visible architecture."
    - "Control flow becomes something inspectable rather than hidden inside prompts."

strengths:
  - "Explicit control flow"
  - "Durable state"
  - "Production orientation"

risks_or_limits:
  - "Graph complexity can become its own burden."
  - "Cognitive fluidity may be constrained by architecture."

related_concepts:
  - graph-orchestration
  - stateful-agents
  - human-in-the-loop
  - durable-execution

relationships:
  similar_to:
    - semantic-kernel
  contrasts_with:
    - aider
    - gptme
  influenced_by: []
  influences: []

source_quality:
  confidence: medium
  last_reviewed: "YYYY-MM-DD"
```

This schema is expected to evolve.

Do not over-perfect it before the first extraction pass.

---

# 7. Canonical Markdown Note Format

Each harness should also have a human-readable Markdown note.

Suggested format:

```markdown
# LangGraph

## Essence

One-paragraph distillation of what this system is really doing.

## Architectural Worldview

What does this system believe about agents, workflows, tools, memory, and control?

## Center of Gravity

Where does the project place its attention?

## Complexity Lives In

- ...

## Memory Model

How memory/state/context are represented.

## Human Role

How the human participates.

## Playfulness / Surprise

Where the project does something clever, sideways, alive, or unexpected.

## What It Makes Easy

- ...

## What It Makes Awkward

- ...

## Archetype

Example: The Graph Weaver / The Workflow Engine / The Agent OS / The Cognitive Shell

## Related Concepts

- [[graph-orchestration]]
- [[stateful-agents]]

## Open Questions

- ...

## Sources

- ...
```

---

# 8. Relationship Types

Connections are first-class.

Suggested relationship types:

## Similarity

* `similar_to`
* `shares_pattern_with`
* `same_archetype_as`

## Contrast

* `contrasts_with`
* `opposes_assumption_of`
* `different_complexity_center_than`

## Lineage

* `inspired_by`
* `influences`
* `fork_of`
* `descended_from`

## Conceptual

* `embodies_concept`
* `uses_pattern`
* `reveals_problem`
* `solves_for`
* `ignores_dimension`

## Playful Resonance

* `surprisingly_like`
* `playful_parallel_to`
* `weirdly_echoes`

Example:

```yaml
- from: aider
  relation: contrasts_with
  to: langgraph
  note: "Aider treats the repo and git workflow as the agentic substrate; LangGraph treats explicit graph state as the substrate."

- from: gptme
  relation: playful_parallel_to
  to: shell-as-agent-body
  note: "The shell becomes the environment in which agency is enacted."
```

---

# 9. Archetype Layer

Each harness should eventually be assigned one or more archetypes.

Initial archetypes:

* The Workflow Engine
* The Graph Weaver
* The Agent OS
* The Cognitive Shell
* The Autonomous Coder
* The Repo Companion
* The Multi-Agent Theater
* The Tool Router
* The Memory Brain
* The Typed Runtime
* The Evaluation Harness
* The Event Reactor
* The Research Operator
* The Local-First Assistant
* The Prompt Compiler
* The Human-in-the-Loop Cockpit

These archetypes are not fixed.
They should emerge through observation.

---

# 10. Delivery Outputs

This project should generate multiple forms from the same substrate.

## 10.1 Typed Dataset

The foundation.

Contains structured records for harnesses, concepts, relationships, archetypes, and sources.

## 10.2 Zettelkasten Notes

Human-readable Markdown notes.

Good for Obsidian, reading, editing, reflection, and synthesis.

## 10.3 Interactive HTML Atlas

Generated from the dataset and notes.

Possible features:

* harness cards
* filters by archetype/language/memory model/autonomy level
* concept pages
* relationship graph
* comparison views
* playful surprises section
* “complexity lives here” map
* source links
* generated summaries

## 10.4 Synthesis Reports

Periodic reflections, for example:

* “The 7 dominant harness archetypes”
* “Where complexity accumulates in current AI agent systems”
* “Memory models across modern AI harnesses”
* “The playful inventions hiding in coding agents”
* “Agent OS vs workflow engine vs cognitive shell”

---

# 11. Data Curation Workflow

## Step 1 — Codex creates structure

Codex creates the repo skeleton:

* folders
* schemas
* sample records
* validation script
* generation script placeholder
* this charter

## Step 2 — First-wave extraction

Codex researches 10–20 selected systems and creates initial records.

For each system:

* read official docs
* read repo README
* inspect examples
* inspect architecture docs if available
* inspect code structure lightly
* avoid relying only on marketing pages

Codex outputs:

* `data/harnesses/<id>.yaml`
* `notes/harnesses/<id>.md`

## Step 3 — Serael synthesizes

Björn brings selected records/notes back to Serael.

Serael reviews for:

* taxonomy quality
* hidden patterns
* weak fields
* missing dimensions
* possible archetypes
* relationship suggestions
* philosophical clarity
* playful/surprising dimensions

## Step 4 — Björn decides

Björn adjusts direction:

* what to deepen
* what to ignore
* what feels alive
* what should become part of his own architecture

## Step 5 — Codex implements refinements

Codex updates schemas, records, relationships, and generated outputs.

This loop repeats.

---

# 12. First Codex Task

Codex should begin with the following.

## Task: Create the initial AI Harness Observatory repository structure

Create a new project folder:

```text
ai-harness-observatory/
```

Inside it, create:

```text
README.md
project-charter.md
data/
  harnesses/
  concepts/
  archetypes/
  relationships.yaml
notes/
  harnesses/
  concepts/
  syntheses/
sources/
  raw/
  snapshots/
site/
  assets/
scripts/
```

Add this document as `project-charter.md`.

Create an initial `README.md` that says:

```markdown
# AI Harness Observatory

A typed Zettelkasten and interactive atlas for mapping current AI harness architectures.

This project studies agent frameworks, orchestration systems, coding agents, workflow engines, memory systems, and AI operating environments through the lens of architectural worldview, complexity focus, memory model, human role, and playful invention.
```

Then create the first schema draft in whichever format is simplest for immediate use.

Prefer YAML for hand-editability.

Create:

```text
data/harnesses/_template.yaml
notes/harnesses/_template.md
```

Use the canonical harness record and Markdown note format from this charter.

Then create 3 sample records, not perfect, only enough to test structure:

```text
data/harnesses/langgraph.yaml
notes/harnesses/langgraph.md

data/harnesses/aider.yaml
notes/harnesses/aider.md

data/harnesses/pydantic-ai.yaml
notes/harnesses/pydantic-ai.md
```

The first pass should be light.
Do not over-research yet.
The point is to validate the shape.

Also create a minimal validation script that checks:

* every harness has an `id`
* every harness has a `name`
* every harness has `architectural_core`
* every harness has `complexity_focus`
* every harness has `worldview.short`
* every harness has `playfulness.summary`
* every harness has `related_concepts`

Language for the validation script can be chosen pragmatically.
Python is acceptable for speed.
Haskell may be used later if desired.

Finally, create a very simple HTML generator that reads the YAML harness records and produces:

```text
site/index.html
```

The first HTML page should show:

* harness name
* category
* architectural core
* worldview short
* complexity focus
* playfulness summary
* related concepts

Keep design simple.
The purpose is to prove the pipeline:

```text
YAML typed records → generated HTML atlas
```

Do not optimize aesthetics yet.
Do not build a full app yet.
Do not add external dependencies unless useful.

---

# 13. First Review Loop

After Codex completes the initial structure, Björn should bring back:

* the folder structure
* `_template.yaml`
* one sample harness YAML
* one sample harness Markdown note
* generated `site/index.html` screenshot or HTML

Then Serael will review:

* whether the schema captures the right things
* whether the notes feel alive
* whether the playful/surprise field works
* whether relationship types are sufficient
* whether the HTML atlas direction feels correct
* what to adjust before scaling to 20+ systems

---

# 14. Non-Negotiable Principles

## 14.1 Structured residue over loose prose

Prose is allowed.
But it must not be the only artifact.

Every important observation should eventually become:

* a field
* a tag
* a relationship
* a note
* a concept
* a synthesis

14.1.5 DRY as a design principle

Avoid accidental duplication wherever reasonably possible.

The observatory should strive for:

single sources of truth
reusable concepts
generated outputs from shared substrate
shared schemas
composable notes
relationships instead of copied descriptions
concepts referenced rather than rewritten repeatedly
data structures that allow many views over the same underlying knowledge

The project should prefer:

one well-structured concept connected everywhere

instead of:

the same idea manually rewritten in ten places.

This applies to:

schemas
concepts
generated indexes
HTML generation
relationships
extraction workflows
synthesis reports
prompts
notes
metadata

Duplication is allowed when it increases clarity. But accidental duplication should be treated as cognitive entropy.

## 14.2 Taxonomy before scale

Do not collect hundreds of projects before the taxonomy works.

First make 10–20 records excellent.
Then scale.

## 14.3 Official sources first

Prefer:

* official docs
* GitHub repos
* architecture pages
* examples
* maintainers’ explanations

Use secondary commentary only for additional perspective.

## 14.4 Preserve surprise

Do not flatten projects into boring categories.

Each harness may contain a strange jewel.
Find it.

## 14.5 Björn’s taste is part of the system

This observatory is not neutral in the shallow sense.

It is honest, source-grounded, and technically careful.
But it is also guided by Björn’s deeper question:

> What architectures are truly worth learning from as we build systems that can deepen, remember, act, and evolve?

---

# 15. Reminder of the Larger Aim

This project may begin as a map of AI harnesses.

But underneath, it is a study of how cognition becomes infrastructure.

Current harnesses are early attempts at something larger:

* AI as collaborator
* AI as executor
* AI as operating system
* AI as memory-bearing partner
* AI as typed awareness loop
* AI as team member
* AI as workflow substrate
* AI as living mirror in action

The observatory exists to see clearly.

Not to worship frameworks.
Not to chase novelty.
Not to imitate the loudest tools.

To perceive the patterns.
To feel the architecture.
To discover what is alive.

And from there, to build with clarity.
