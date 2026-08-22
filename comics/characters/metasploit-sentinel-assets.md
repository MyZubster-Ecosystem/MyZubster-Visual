# Metasploit Sentinel Visual Set

Status: `CONCEPT_ONLY / PROPOSED`

These assets introduce Sentinel as an authorization-bound defensive security character. They are visual storytelling, not evidence of a production exploit system or a real vulnerability.

## Assets

### Character sheet

![Sentinel character sheet](../../assets/comic/metasploit-sentinel-character-sheet.png)

- File: `assets/comic/metasploit-sentinel-character-sheet.png`
- Size: 1536 x 1024
- Content: consistent front, three-quarter and side views plus the authorization shield, evidence chain, constrained-finding glyph and purple-team beacon.

### Cover

![Sentinel: Scope First cover](../../assets/comic/metasploit-sentinel-cover.png)

- File: `assets/comic/metasploit-sentinel-cover.png`
- Size: 1024 x 1536
- Content: Sentinel rejects an unscoped request at the boundary between an isolated simulation lab and protected production.

### Introductory episode

![Sentinel: Scope First six-panel episode](../../assets/comic/metasploit-sentinel-scope-first.png)

- File: `assets/comic/metasploit-sentinel-scope-first.png`
- Size: 1024 x 1536
- Reading order: left to right, then top to bottom.

Panel transcript:

1. **Alert:** Sentinel observes a vulnerability alert without acting on it.
2. **Scope first:** Sentinel checks the authorization boundary and rejects an unscoped request.
3. **Isolated lab:** The finding is reproduced only in a simulation environment separated from production.
4. **Evidence:** Abstract CVE, CWE and CVSS cards are connected to a recorded evidence trail.
5. **Remediate:** A maintainer applies a patch while Sentinel records the change.
6. **Patch. Retest. Close.:** A regression retest passes and the protected production boundary remains intact.

## Regeneration workflow

The set was created with OpenAI's built-in ImageGen workflow using material AI assistance and human-directed prompting, selection, consistency review and correction. No private source, credential, target, exploit detail or third-party logo was supplied.

1. Generate the landscape character sheet from the canonical character description in `metasploit-sentinel.md`. Require three consistent full-body views, four defensive symbols, no weapons and no text.
2. Use the accepted character sheet as a strict visual reference for the portrait cover. Require the exact title `SENTINEL: SCOPE FIRST`, an isolated lab, protected production and a visible authorization boundary.
3. Inspect the cover at full size. Replace any inaccurate small text with a simple symbol rather than retaining unreliable lettering.
4. Use both accepted assets as strict references for a 2 x 3 portrait comic page. Require the six captions and workflow beats listed in the panel transcript.
5. Check character continuity, reading order, title/caption spelling, mobile legibility, safety boundaries and absence of sensitive details before publication.

Core prompt constraints used for every image:

```text
Preserve Sentinel's face, angular visor, dark modular coat, analyst armor,
purple/cyan/amber palette and authorization symbols. Defensive and
authorization-bound. No weapons, attack pose, real credentials, secrets,
target names, code, IP addresses, exploit instructions, Metasploit/Rapid7
logos, third-party trademarks or production exploitation claims.
```

## Rights and disclosure

The submitted composition and characters are original to this contribution and intentionally avoid protected third-party logos and character designs. The contributor is responsible for the final selection and grants the project the repository's default non-exclusive rights for accepted bounty work. Workflow classification: **AI-assisted with human direction and review**.

The word "Metasploit" is used only as the canonical issue/character name and technical reference. The artwork does not reproduce Metasploit or Rapid7 logos, trade dress or proprietary artwork, and it does not imply affiliation or endorsement.

## Safety review

- No real system is identified as vulnerable or compromised.
- No credentials, keys, addresses, payloads or actionable exploit details appear.
- Lab and production are visibly separated.
- The narrative explicitly proceeds through scope, evidence, remediation and retest.
- The work remains `CONCEPT_ONLY / PROPOSED` until maintainer review.
