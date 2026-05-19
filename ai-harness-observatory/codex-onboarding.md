# Codex Onboarding

This document is for implementation work inside the observatory repo.

## Repo Intent

The observatory is no longer just collecting harnesses.

It is trying to produce:

- a canonical data layer
- generated exploratory HTML views
- synthesis and comparison artifacts built from that data

The repo should optimize for exploration with minimal friction.

## Source Of Truth

Current decision:

- `data/` is canonical
- `site/` is generated view-layer output
- `notes/syntheses/`, `notes/comparisons/`, and `notes/review-packets/` are human-authored interpretation layers

More specifically:

- `data/harnesses/*.yaml` is the canonical harness record layer
- `data/concepts/*.yaml` and `data/relationships.yaml` are the canonical graph layer
- `scripts/generate-site` is the generator that turns canonical data into browser-visible exploration
- note-to-note navigation should use stable note ids from Markdown frontmatter, not filename guessing

Important consequence:

> If a fact is duplicated in both YAML and Markdown, YAML should lead.

## YAML vs Markdown

The current repo still contains duplicated harness material in:

- `data/harnesses/*.yaml`
- `notes/harnesses/*.md`

This should be treated as a transitional state, not a permanent design.

Target direction:

- harness YAML remains canonical
- harness Markdown either:
  - becomes a thin human wrapper generated from YAML, or
  - is retired and replaced by richer HTML browse surfaces

Markdown should remain strongest where it adds real value:

- syntheses
- comparisons
- review packets
- concept notes with gravity and tensions
- exploration notes that deepen selected harnesses, concepts, tensions, and histories

When a Markdown note is intended to participate in generated cross-linking, give it stable frontmatter:

- `id`
- `kind`

Use ids for cross-note references.
Do not build note links by hand from path prefixes if the generator can resolve them from typed metadata.

Exploration-linking rule:

- direct `related_harnesses` should drive harness-level tensions and histories
- concept overlap should mainly surface concept explorations

This keeps harness pages from accumulating weak indirect links.

Markdown should not be the long-term home of duplicated harness facts if those facts already exist in YAML.

## Data Flow

Current flow:

1. canonical data lives in `data/`
2. `scripts/validate-data` checks required structure
3. `scripts/generate-site` reads YAML and produces `site/`
4. `scripts/check-site-links` validates generated internal links inside `site/`
5. `site/index.html`, `site/browse/*.html`, `site/concepts/*.html`, and `site/harnesses/*.html` are the main current exploration surfaces
6. selected exploration notes also render inline on harness and concept pages where they materially deepen understanding

Target flow:

1. edit canonical YAML
2. regenerate site
3. explore everything from HTML

## HTML Rule

Assume:

> What is not reachable by clicks from `site/index.html` does not yet exist for exploration purposes.

HTML is not the data layer.
It is the main view layer.
But every important field should become visible there.

This means new ontology fields should usually trigger one of:

- a visible card section
- a generated index page
- a filter or cluster view
- a comparison or relationship surface

## Current Priority Tasks

These are the tasks that should be treated as active until resolved:

### 1. Remove harness duplication

Decide and implement one of:

- generated harness Markdown from YAML
- thin wrapper harness Markdown
- no harness Markdown, HTML only

Do not keep large duplicated descriptive bodies in both places indefinitely.

### 2. Deepen generated surfaces

These are now generated from YAML and reachable from the atlas:

- hidden bets
- primary substrates
- trust models
- failure modes
- cognitive styles
- representative-for groupings

Current next step:

The harness level now has generated detail pages. Likely next moves are:

- stronger relationship browse surfaces
- deeper cross-links from concepts and comparisons back into the atlas
- reduce reliance on duplicated harness Markdown now that harness pages exist

### 3. Prefer generated indexes over prose duplication

When a field becomes important enough to browse repeatedly, add a generated HTML view rather than repeating explanations in many harness notes.

### 4. Keep concepts, comparisons, and syntheses DRY

- harness YAML states facts
- concept notes collect shared meaning
- comparison notes express tensions
- synthesis notes describe emergent patterns
- exploration notes add story and explanation where a thin node or page would otherwise stay cold

One concept, many links.

## Files To Review First Before Further Work

- [README.md](./README.md)
- [project-charter.md](./project-charter.md)
- [scripts/generate-site](./scripts/generate-site)
- [scripts/check-site-links](./scripts/check-site-links)
- [data/harnesses/_template.yaml](./data/harnesses/_template.yaml)
- [data/relationships.yaml](./data/relationships.yaml)
- [notes/review-packets/002-emergence-review.md](./notes/review-packets/002-emergence-review.md)
- [notes/review-packets/004-exploration-layer-review.md](./notes/review-packets/004-exploration-layer-review.md)

## Immediate Suggested Follow-Up

The clean next implementation pass is:

1. reduce or remove duplicated harness Markdown once HTML browse surfaces are sufficient
2. selectively deepen only the concept clusters that still feel cold
3. make relationship, concept, and comparison navigation denser from the site itself
4. keep link checking in the loop with `./scripts/check-site-links`
