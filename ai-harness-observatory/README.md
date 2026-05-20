# AI Harness Observatory

An exploratory atlas for mapping AI harness architectures.

This repo studies agent frameworks, coding agents, workflow runtimes, memory surfaces, and orchestration systems through a few structural questions:

- what is the substrate of agency?
- how does the system become trustworthy?
- where does complexity accumulate?
- what hidden bet is the architecture making?

## Onboarding

Start with these files:

- [../process.md](../process.md)
- [project-charter.md](./project-charter.md)
- [codex-onboarding.md](./codex-onboarding.md)
- [notes/review-packets/002-emergence-review.md](./notes/review-packets/002-emergence-review.md)
- [notes/review-packets/004-exploration-layer-review.md](./notes/review-packets/004-exploration-layer-review.md)

`../process.md` is the reusable big-picture explanation of the method behind this repo. The files below are the observatory-specific operating surfaces.

## Current Operating Decision

The observatory should move toward **one canonical data layer** plus generated views.

Current target direction:

- YAML is the source of truth
- HTML is the primary exploration surface
- anything not reachable by clicks from `site/index.html` should be treated as not yet surfaced
- generated note-to-note navigation should resolve through stable note ids, not ad-hoc path building
- Markdown should stop duplicating YAML and instead become:
  - synthesis
  - comparison
  - concept gravity
  - review packets
  - exploration notes only where they add real human value

## Current Review Surfaces

- [site/index.html](./site/index.html)
- [site/browse/index.html](./site/browse/index.html)
- [site/harnesses](./site/harnesses)
- [notes/syntheses](./notes/syntheses)
- [notes/comparisons](./notes/comparisons)
- [notes/review-packets](./notes/review-packets)

## Verification

Useful local checks:

- `./scripts/validate-data`
- `./scripts/generate-site`
- `./scripts/check-site-links`

## Open Tasks

These are the current tasks before further expansion:

1. Keep harness Markdown thin and non-duplicative so YAML and generated HTML continue to lead.
2. Selectively deepen only the concept clusters that still feel cold, instead of expanding every node equally.
3. Make concept, comparison, relationship, and exploration navigation complete enough that no important field is stranded outside the atlas.
4. Add more generated browse surfaces where repeated reading pressure appears, instead of solving it with prose duplication.
5. Keep strengthening comparative links so the atlas feels argumentative, not merely catalog-like.
6. Keep adding comparative links only after the one-source-of-truth direction is explicit in code and docs.
