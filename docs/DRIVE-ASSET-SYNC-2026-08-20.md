# Drive Asset Sync — 2026-08-20

This document records the curated Google Drive → GitHub classification performed on 2026-08-20. It is an inventory, not a bounty-verification or payment record.

## Canonical placement rules

- Binary comic artwork → `assets/comic/`
- Comic canon, series indexes and contributor documentation → `comics/`
- Social publication artwork → `assets/social/`
- AI/bot avatars → `assets/bots/`
- Real-world photographic evidence → `MyZubster-Ecosystem/MyZubster-Photos`, not this repository
- Project/institutional documents → `MyZubster-Ecosystem/myzubster-docs`

## Already present — do not duplicate

The Drive audit found these assets already represented in this repository:

- `MyZubster-Cyberpunk-Visual-01-Manifesto-Neon.png`
- `MyZubster-Cyberpunk-Visual-02-Daniel-Chronicler.png`
- `MyZubster-Cyberpunk-Visual-03-Alliance.png`
- `MyZubster-Cyberpunk-Visual-04-Real-Life-to-Story.png`
- `MyZubster-Bounty-526-Daniel-Combat-Concept.png`
- `MyZubster-Roadmap-High-Resolution-Source.png`
- `MyZubster-Visual-Catalog-Dashboard-Source.png`
- `MyZubster-Photos-Evidence-Dashboard-Source.png`
- AI/bot avatar set including `eva-ioni.png`, `myzubster-ai-bot.png`, `verifier-ai.png`, `telegram-bot.png`, `github-bounty-bot.png`, `crawler-bot.png`, `notification-bot.png`, `space-station-ai.png`, and `clowbot.png`

## Candidate binary imports from Drive

These files were present in the curated Drive comic folder and were not found by exact-name audit in the organization repositories. They should be imported only once, using the canonical paths below.

### `assets/comic/`

- `MyZubster-Robot-Cyberpunk-Comic-README.png`
- `MyZubster-Robot-Stack-Cyberpunk-Comic-README.png`
- `MyZubsterWeb-Cyberpunk-Comic-README-v2.png`
- `MyZubster-Core-Cyberpunk-Comic-README.png`
- `animal-registry-Comic-README.png`
- `myzubster-docs-Comic-README.png`
- `MyZubsterMarketplace-Comic.png`
- `MyZubsterVote-Comic-v2.png`
- `MyZubsterBounty-Comic.png`
- `MyZubsterAI-Comic.png`
- `MyZubsterGateway-Comic.png`
- `MyZubster-Repo-Comic-Grid-01.png`
- `MyZubster-How-It-Works-Comic-README.png`

### `assets/social/`

- `MYZ-SOC-002_MyZubster_Comic.png`
- `MyZubster_Comics_Quando_l_ignoto_diventa_alleato.png`

## Repository-specific artwork

Artwork whose filename names a specific repository may also be referenced from that repository's README or docs, but the binary source should remain canonical here unless there is a clear product-specific reason to store a copy elsewhere. Avoid duplicating multi-megabyte artwork across repositories.

## Canon already present

The `comics/canon/` tree already contains:

- `daniel-character-bible.md`
- `daniel-canon-timeline.md`
- `daniel-sourcebook.md`
- `story-artifacts-index.json`

The `comics/series/` tree already contains the `daniel-origins` series structure. New story episodes should extend these structures instead of creating parallel canon folders.

## Follow-up

1. Import pending binaries after duplicate/hash verification.
2. Update `metadata/` with stable asset IDs, SHA-256 hashes and canonical paths.
3. Add README references from relevant product repositories without copying canonical binaries unless necessary.
4. Keep real-world evidence in `MyZubster-Photos` with privacy review and provenance metadata.
