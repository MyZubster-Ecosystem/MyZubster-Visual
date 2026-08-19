# MyZubster Comic Universe

Canonical, versioned structure for the MyZubster comic and story project.

## Purpose

The comic universe turns real MyZubster discoveries, documented observations, photos, metadata, contributors and project history into cyberpunk storytelling while keeping a strict boundary between verified real-world evidence and fictional narrative interpretation.

## Canon rule

Every story artifact should identify whether it is:

- `REAL_EVIDENCE` — backed by a real photo/observation/metadata record;
- `CANON_INTERPRETATION` — a cyberpunk retelling of a real event;
- `FICTION` — narrative material created for the comic universe;
- `CONCEPT_ONLY` — visual or narrative exploration not yet canonical.

A fictional scene, nickname, MYZ amount, blockchain event, bounty status or settlement state must never be presented as real unless independently supported by the canonical MyZubster records.

## Repository structure

```text
comics/
  README.md
  canon/
    daniel-sourcebook.md
    daniel-character-bible.md
    daniel-canon-timeline.md
    story-artifacts-index.json
  characters/
    README.md
  series/
    daniel-origins/
      README.md
  contributors/
    README.md
  templates/
    episode-card.md
    character-card.md
    evidence-link.json
```

Artwork remains under `assets/comics/`. Public real photographs remain canonical in `MyZubster-Photos`; this repository references them instead of duplicating source evidence.

## GitHub vs Drive

- **GitHub:** canonical text, timelines, schemas, metadata links, story status and version history.
- **Google Drive:** working artwork, sketches, generated panels, visual references, drafts and publication exports.

Drive workspace: `MyZubster Visual Assets / MyZubster Comic Universe`.

## Story pipeline

```text
REAL LIFE / DISCOVERY
        ↓
PHOTO / OBSERVATION / METADATA
        ↓
EVIDENCE LINK + PRIVACY REVIEW
        ↓
CANON STORY CARD
        ↓
SCRIPT / STORYBOARD
        ↓
CYBERPUNK ARTWORK
        ↓
EDITORIAL + TECHNICAL QA
        ↓
CANON / PUBLICATION
```

## Related repositories

- `MyZubster-Photos` — canonical public photographic evidence
- `myzubster` — observations, bounty rules and ecosystem truth
- `MyZubster-Visual` — visual identity and comic canon
