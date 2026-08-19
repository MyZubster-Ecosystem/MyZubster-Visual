# MyZubster Cyberpunk Discovery Series — Global Comic Bounty

## Mission

The **MyZubster Cyberpunk Discovery Series** invites people around the world to transform their **real-life discoveries made through MyZubster** into original cyberpunk comic series.

This is not a generic fan-art program.

The core idea is:

```text
REAL LIFE
   -> EXPLORE WITH MYZUBSTER
   -> DISCOVER SOMETHING
   -> DOCUMENT / VERIFY / LEARN
   -> TURN THE EXPERIENCE INTO A CYBERPUNK STORY
   -> SHARE THE SERIES WITH THE COMMUNITY
```

A discovery can be small or large. Examples include:

- finding a new plant, tree, garden or biodiversity observation;
- discovering an interesting public place, street, building or cultural landmark;
- learning something about the environment or local community;
- documenting a useful public service or urban detail;
- building or repairing something;
- creating a robot, sensor, tool or software project;
- discovering a new skill or capability in yourself;
- meeting collaborators or contributing to a community mission;
- completing a safe, authorized MyZubster bounty;
- following a chain of observations that changes how you understand your city or your life.

The comic is the **creative interpretation of a real journey**. It may use cyberpunk fiction, neon cities, AI companions, robots, future interfaces or imagined worlds, but the underlying discovery should come from the contributor's real experience.

## Core principle

**Everyone creates their own comic from their own discoveries.**

The contributor is not required to imitate Daniel or another creator.

Each participant creates:

- their own cyberpunk identity;
- their own city/world;
- their own discoveries;
- their own missions;
- their own visual language;
- their own continuing series.

MyZubster provides the shared framework for observation, evidence, discovery, community and rewards.

## Real discovery + fiction

A submission should clearly separate two layers.

### Real layer

Where appropriate and safe, the creator identifies:

- what was discovered;
- how MyZubster helped the exploration or documentation;
- approximate public location/category when appropriate;
- supporting public-safe evidence;
- related observation/bounty/reference IDs when they actually exist.

### Story layer

The creator may transform that experience into:

- fictional cyberpunk characters;
- future versions of real places;
- robots or AI companions;
- imagined missions and antagonists;
- symbolic interpretations of personal challenges;
- speculative technology.

Fiction must not be presented as proof that a fictional MyZubster feature, blockchain transaction, robot deployment or payment exists in the real platform.

## Who can participate

Anyone may propose a series, subject to these rules.

Contributors may participate as:

- writer;
- illustrator;
- photographer / visual storyteller;
- designer;
- AI-assisted creator;
- developer / maker;
- team or collective.

AI-assisted work is allowed when the contributor has the right to submit the resulting material and clearly states the workflow used. Human creative direction and responsibility remain with the contributor.

## Suggested episode structure

A strong episode can follow this pattern:

1. **The real discovery** — what did you encounter or learn?
2. **The evidence** — what did you safely document?
3. **The transformation** — how does the real discovery become cyberpunk?
4. **The mission** — what challenge does your character face?
5. **The MyZubster connection** — observation, map, community, bounty, robot, environment, creation or verification.
6. **The outcome** — what changed or what did you learn?
7. **The next discovery** — where does the next episode begin?

## Minimum deliverables

Each bounty submission must include:

- series title;
- creator/team name or public alias;
- at least **3 original comic pages/panels**;
- synopsis of 100–500 words;
- a short description of the **real MyZubster discovery** that inspired the episode;
- a `real / fictional` disclosure;
- language used in the comic;
- public-safe preview image;
- rights/consent declaration.

When public evidence exists and is safe to publish, a submission may additionally include:

- MyZubster observation ID;
- bounty ID;
- public photo/evidence URL;
- SHA-256;
- IPFS CID;
- generalized public location/category;
- GitHub reference.

These evidence fields must never be invented merely to make a comic appear more verifiable.

## Acceptance criteria

A submission can reach `VERIFIED` only after manual review confirms:

- [ ] the comic is substantially original;
- [ ] it is based on the creator's own real-life discovery, experience or contribution;
- [ ] the MyZubster connection is explained;
- [ ] the real discovery and fictional cyberpunk interpretation can be distinguished;
- [ ] it meets the minimum page/panel requirement;
- [ ] any evidence claimed as real actually corresponds to the stated discovery;
- [ ] public evidence has been privacy/safety reviewed;
- [ ] no private addresses, credentials, sensitive locations or confidential material are exposed;
- [ ] recognizable people are handled with appropriate rights/consent;
- [ ] third-party copyrighted material is not submitted without appropriate rights;
- [ ] fictional MYZ, blockchain or settlement events are not represented as real platform transactions;
- [ ] the creator has the right to publish the submitted work.

A beautiful comic without a contributor-specific real-world discovery may still be showcased as art, but it does not automatically satisfy this discovery bounty.

## Reward model

Rewards are **proposed MYZ internal-platform rewards** and are not automatic.

| Tier | Minimum deliverable | Proposed MYZ |
|---|---:|---:|
| Discovery Spark | 3 pages/panels + 1 real discovery | 150 MYZ |
| Discovery Episode | 4–8 coherent pages + documented discovery + cover | 300 MYZ |
| Discovery Series | 3 connected episodes based on separate/connected discoveries | 750 MYZ |
| World Explorer | series + discovery index + character/world guide + multilingual edition | 1,000 MYZ |

Possible bonus bounty definitions may reward:

- multiple verified public-safe discoveries;
- environmental or educational value;
- high-quality translations;
- accessibility editions;
- safe integration of original photography/evidence;
- collaboration with other MyZubster explorers;
- reusable open visual assets.

These numbers remain proposed bounty definitions until a specific bounty is approved.

## Discovery metadata

Recommended public-safe metadata:

```json
{
  "program": "MyZubster Cyberpunk Discovery Series",
  "seriesId": "cyberpunk-series-...",
  "creatorAlias": "...",
  "episode": 1,
  "language": "it",
  "discovery": {
    "title": "...",
    "category": "plant|place|environment|technology|skill|community|other",
    "observationId": null,
    "bountyId": null,
    "evidenceUrl": null,
    "sha256": null,
    "cid": null,
    "privacyReviewed": true
  },
  "fictionDisclosure": true,
  "status": "SUBMITTED",
  "reward": {
    "asset": "MYZ",
    "amount": 300,
    "model": "internal-platform-ledger"
  }
}
```

Unknown fields remain `null` or absent. They must not be fabricated.

## MYZ truth

**MYZ is currently an internal MyZubster reward/accounting ledger.**

The discovery/comic lifecycle is:

```text
DISCOVERY
 -> EVIDENCE / STORY CREATION
 -> BOUNTY SUBMISSION
 -> UNDER_REVIEW
 -> VERIFIED
 -> REWARD_RECORDED
```

Within the canonical bounty lifecycle this maps to:

```text
PROPOSED
 -> VALIDATED
 -> APPROVED
 -> ACTIVE
 -> SUBMITTED
 -> UNDER_REVIEW
 -> VERIFIED
 -> REWARD_RECORDED
```

A discovery, photo, comic, GitHub merge, publication or issue closure does **not** automatically create MYZ credit.

External XMR/token/blockchain settlement, if ever explicitly included in a specific bounty, remains a separate process and requires independent verification before `PAID` or `SETTLED`.

## Safety and privacy

Discoveries must come from safe, authorized activity.

The program must not reward or require:

- trespassing;
- access to restricted or sensitive infrastructure;
- photographing security-sensitive details;
- disclosure of precise sensitive locations;
- harassment or non-consensual portrayal of private individuals;
- publication of private medical, financial or family information;
- dangerous real-world stunts;
- unauthorized computer access;
- weapons, explosives or hazardous-device construction.

The goal is to **discover more about the world without creating harm**.

## Identity and consent

Creators can use a public alias instead of a legal name.

A contributor may tell deeply personal stories, but participation never requires publishing sensitive personal information. Real people, especially minors or vulnerable persons, require careful consent/privacy treatment.

## Languages

The program is global. Comics can be submitted in any language.

For international discovery, include:

- original-language title;
- language code where practical;
- short English summary.

Translations must preserve the distinction between real discoveries, fictional story elements, MYZ internal rewards and independently verified external settlement.

## Publication structure

Recommended structure in `MyZubster-Visual`:

```text
assets/comics/
  <creator-or-alias>/
    <series-slug>/
      discoveries/
      cover/
      episode-01/
      episode-02/
      metadata.json
```

A discovery index can connect real-world inspiration to the comic without exposing private or sensitive details.

## Review scorecard

Reviewers may score 0–5 on:

- real discovery connection;
- originality;
- storytelling;
- visual coherence;
- MyZubster connection;
- personal authenticity;
- evidence integrity;
- privacy/safety compliance;
- technical-claim accuracy;
- accessibility / multilingual value.

Scores support review but do not replace acceptance criteria.

## Community vision

Over time, individual creators can form a global anthology:

```text
PERSON A -> their discoveries -> their cyberpunk series
PERSON B -> their discoveries -> their cyberpunk series
PERSON C -> their discoveries -> their cyberpunk series
                    |
                    v
         MYZUBSTER CYBERPUNK WORLD
```

The shared world grows from **real people discovering the real world**.

Verified works may be selected for galleries, maps, community showcases, social content and future digital anthologies. Showcase selection is separate from bounty verification and does not create additional rewards unless explicitly defined.

## Canonical bounty rules

This program inherits and cannot weaken the canonical MyZubster bounty contract:

https://github.com/MyZubster-Ecosystem/myzubster/blob/main/BOUNTIES.md

If this document conflicts with the canonical bounty rules, the canonical rules prevail.
