# Process

## What This Document Is

This document explains the process behind building a typed exploratory observatory.

It is independent of the specific topic of AI harnesses, but it uses the harness observatory in this repository as the running example. The goal is to show both:

- the content process: how the subject matter is investigated, shaped, and refined
- the implementation process: how software, files, folders, and generated outputs support that investigation

In another domain, the same process could be used for papers, protocols, companies, tools, design patterns, or schools of thought.

## Overview

The process has a simple core loop:

1. start with a small but varied first wave of entities
2. ask a stable set of structural questions
3. record the answers in canonical typed data
4. generate an exploration surface from that data
5. notice where navigation, comparison, or explanation feels thin
6. add concepts, relationships, comparisons, syntheses, or explorations only where pressure appears
7. refine the schema and process based on what the observatory has started to reveal

This means the process is neither only research nor only software.

It is a conversation between:

- curiosity
- structure
- generation
- exploration
- reflection

## Core Process For Content

### 1. Choose a first wave

Do not begin with the whole landscape.

Start with a deliberately small first wave that is varied enough to create contrast. The purpose of the first wave is not completeness. The purpose is to pressure-test the ontology.

In the harness observatory, this meant starting with a small set of systems that were meaningfully different from one another: repo-close coding agents, graph runtimes, typed orchestration systems, multi-agent frameworks, and data-centered systems.

### 2. Ask recurring structural questions

A good observatory does not begin by collecting arbitrary facts. It begins by deciding which questions expose deep structure.

In the harness example, the recurring questions became:

- what is the substrate of agency?
- how does the system become trustworthy?
- where does complexity accumulate?
- what hidden bet is the architecture making?
- what does it refuse?
- what tension does it live inside?

These questions are domain-specific in wording, but the pattern is general: choose a handful of questions that reveal worldview, structure, tradeoffs, and failure.

### 3. Separate fact from interpretation

Not everything belongs in the same layer.

Some information is comparatively stable and should become typed data. Some information is interpretive and belongs in prose.

In the harness observatory:

- canonical facts and classifications live in YAML
- relationships live in typed graph data
- syntheses, comparisons, review packets, and explorations live in Markdown

That separation matters because structured data supports comparison and generation, while prose supports explanation and human insight.

### 4. Let repeated pressure shape the ontology

Do not try to invent the perfect schema on day one.

Instead, add fields and categories when repeated reading pressure makes them necessary. In the harness observatory, fields such as `primary_substrate`, `trust_model`, `failure_modes`, `cognitive_style`, and `hidden_bet` were not all present at the start. They became necessary because the corpus kept asking for them.

The principle is:

> a field should exist because it repeatedly helps the map see better

### 5. Reflect before expanding

At regular intervals, stop adding entities and instead review what the observatory already knows.

This is where syntheses and review packets matter. They turn accumulation into insight.

In practice, this means asking:

- which patterns are emerging?
- which concepts are becoming gravity wells?
- which fields produce signal?
- which fields produce noise?
- where is the map still thin, cold, or misleading?

This reflection step is what prevents the project from becoming a pile of records.

## Core Process For Implementation

### 1. Keep one canonical data layer

The implementation should make it obvious which layer leads.

In this repository, the current operating decision is:

- YAML is canonical
- HTML is the primary exploration surface
- Markdown is the human-deepening layer

This avoids a common failure mode: parallel truth surfaces that drift apart.

### 2. Generate the exploration layer

The browser-facing experience should be generated from the canonical data rather than maintained by hand.

That makes the atlas explorable, repeatable, and easy to extend. It also allows repeated fields to become browsable surfaces instead of being restated in many notes.

In the harness observatory, this led to generated pages for:

- harnesses
- concepts
- relationship types
- primary substrates
- trust models
- failure modes
- hidden bets
- cognitive styles
- representative groupings

### 3. Add prose where human understanding actually needs it

Not every page should be equally dense.

Thin routing nodes are acceptable. But when a concept, tension, historical pattern, or harness page still feels cold, add prose where it creates understanding rather than duplication.

This is why the observatory has separate exploration notes for:

- concepts
- harness stories
- tensions
- historical emergence

### 4. Verify the generated layer continuously

Once HTML becomes the main exploration surface, broken links are not a cosmetic issue. They are structural damage.

So the process should include:

- validation of canonical data
- regeneration of the site
- link checking of generated output

In this repository, those checks are explicit scripts, not informal habits.

## Running Example: The Harness Observatory

The current observatory implements this process in a concrete way.

### Canonical signal layer

- `ai-harness-observatory/data/harnesses/*.yaml`
- `ai-harness-observatory/data/concepts/*.yaml`
- `ai-harness-observatory/data/relationships.yaml`

This layer captures typed facts, classifications, and graph structure.

### Generated exploration layer

- `ai-harness-observatory/site/index.html`
- `ai-harness-observatory/site/harnesses/`
- `ai-harness-observatory/site/concepts/`
- `ai-harness-observatory/site/browse/`
- `ai-harness-observatory/site/notes/`

This layer is what the reader should actually explore in the browser.

### Human-deepening layer

- `ai-harness-observatory/notes/syntheses/`
- `ai-harness-observatory/notes/comparisons/`
- `ai-harness-observatory/notes/review-packets/`
- `ai-harness-observatory/notes/explorations/`

This layer adds interpretation, explanation, tension, and story.

### Transitional wrapper layer

- `ai-harness-observatory/notes/harnesses/`

These notes are intentionally thin wrappers now. They exist as bridges, not as a second canonical record system.

## File And Folder Roles

The current repository structure expresses the process directly.

### Top level

- `ai-harness-observatory-charter.md`
  The project charter and conceptual intent.
- `process.md`
  The reusable process explanation.

### Inside `ai-harness-observatory/`

- `README.md`
  Short orientation and current operating decision.
- `codex-onboarding.md`
  Implementation-facing working rules.
- `project-charter.md`
  Local copy of the charter for the observatory folder.
- `data/`
  Canonical typed records and graph structure.
- `notes/`
  Human-authored interpretation and review layers.
- `site/`
  Generated HTML exploration layer.
- `scripts/`
  Validation, generation, and link-checking tools.
- `sources/`
  Supporting source material and references when needed.

This is not just a file layout. It is the process made visible.

## Questions That Drive The Work

The most important part of a process like this is not the generator. It is the questions.

The harness observatory became useful because it kept returning to a small number of high-signal questions. Those questions can be adapted to another domain.

Examples:

- What is the thing actually built around?
- What problem does it believe is central?
- Where does complexity accumulate?
- What does it trust?
- What does it refuse?
- What hidden architectural wager is it making?
- Which neighboring entities are it actually similar to, and why?
- Which distinctions matter enough to become relationships or comparisons?

The generic rule is:

> ask questions that reveal worldview, structure, and tradeoff, not just features

## Evolution Of The Process

The current process did not arrive fully formed.

It evolved through a few important turns:

1. The project began with both YAML and Markdown carrying overlapping harness content.
2. Repeated friction made it clear that one canonical data layer was needed.
3. YAML became the source of truth for structured records and graph data.
4. HTML became the primary exploration surface.
5. Markdown became more selective: syntheses, comparisons, review packets, and exploration notes.
6. New browse surfaces were added when repeated reading pressure appeared.
7. Human-deepening notes were added only where the atlas felt too thin for meaningful wandering.

That evolution matters because it shows the process correcting itself rather than defending an early design forever.

## Practical Workflow

The day-to-day loop in this repository is now fairly clear:

1. inspect or update canonical data in `data/`
2. validate with `./scripts/validate-data`
3. regenerate with `./scripts/generate-site`
4. verify navigation with `./scripts/check-site-links`
5. review the result in `site/index.html`
6. if the atlas feels thin or hard to traverse, decide whether the pressure should be answered by:
   - a new field
   - a new concept
   - a stronger relationship
   - a generated browse surface
   - a comparison note
   - a synthesis
   - an exploration note

This is the software loop and the editorial loop at the same time.

## Design Principles

Several principles have emerged from the work so far.

### One canonical data layer

Facts should have one leading home.

### HTML is the main exploration surface

If something cannot be reached through the generated atlas, it is not yet properly surfaced.

### DRY for facts, selective repetition for pedagogy

Repeated facts are drift. Repeated explanation can be helpful.

### Browse surfaces before prose duplication

If people repeatedly want to inspect a field across many entities, generate a browse surface instead of restating the field in many places.

### Thin wrappers are acceptable

A small bridge note is fine if the richer generated surface already exists elsewhere.

### Stop and synthesize

Do not let accumulation outrun reflection.

## How To Reuse This Process In Another Domain

To reuse this process elsewhere, keep the structure and swap the subject.

### Keep

- a small first wave
- a canonical typed record layer
- a concept and relationship layer
- a generated exploration surface
- synthesis and review loops
- selective human-deepening notes

### Replace

- the domain entities
- the driving questions
- the ontology fields
- the concept vocabulary
- the comparison axes

For example:

- in a paper observatory, the primary entity might be a paper
- in a protocol observatory, it might be a standard or system
- in a company observatory, it might be an organization or product line

What stays constant is the process:

1. choose the right questions
2. record the right structured signal
3. generate an explorable map
4. notice where the map is weak
5. deepen only where real pressure exists

That is the transferable method.
