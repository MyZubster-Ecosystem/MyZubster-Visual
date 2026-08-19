# How MyZubster Uses GitHub, JSON Metadata and SHA-256 to Build a Verifiable Asset Registry

Modern digital ecosystems generate far more than source code. They generate images, AI outputs, documentation, robotics designs, datasets, evidence, marketplace content and community contributions.

One challenge is simple: **how do we know which artifact is canonical?**

Inside MyZubster, I am experimenting with a straightforward architecture based on technologies developers already understand:

**GitHub + JSON metadata + SHA-256 + automation.**

The goal is to turn ordinary files into structured, traceable digital artifacts that humans, software and eventually AI agents can verify.

## 1. Start with the artifact

The MyZubster Visual repository contains the Cyberpunk Series:

https://github.com/MyZubster-Ecosystem/MyZubster-Visual/tree/main/assets/cyberpunk-series

Instead of treating the PNGs only as media files, each canonical visual is registered with a stable asset ID such as:

```text
MYZ-CYBER-001
MYZ-CYBER-002
MYZ-CYBER-003
MYZ-CYBER-004
MYZ-CYBER-005
MYZ-CYBER-006
```

A stable ID lets other systems reference the artifact without relying only on a filename.

## 2. Add a machine-readable manifest

The collection manifest is public:

https://github.com/MyZubster-Ecosystem/MyZubster-Visual/blob/main/metadata/cyberpunk-series/manifest.json

A simplified entry looks like this:

```json
{
  "asset_id": "MYZ-CYBER-004",
  "filename": "MyZubster-Cyberpunk-Serie-03-Robot-Riciclo-Invenzioni.png",
  "category": "cyberpunk-series",
  "mime_type": "image/png",
  "repository_path": "assets/cyberpunk-series/MyZubster-Cyberpunk-Serie-03-Robot-Riciclo-Invenzioni.png",
  "status": "published",
  "metadata_ready": true
}
```

A person can browse the image. A bot can read the manifest. An API can index it. A bounty workflow can reference the asset ID.

## 3. Fingerprint the bytes with SHA-256

The checksum inventory is here:

https://github.com/MyZubster-Ecosystem/MyZubster-Visual/blob/main/metadata/cyberpunk-series/sha256.txt

A verifier can calculate:

```bash
sha256sum artifact.png
```

and compare the result with the registered digest.

If the digest matches, the downloaded bytes match the registered artifact.

This is an integrity check. It does not by itself prove legal ownership, authorship, truthfulness or entitlement to a reward.

## 4. Use Git history as another provenance layer

When the asset and metadata are committed, Git records when they entered the repository and how later versions change.

The architecture becomes:

```text
ARTIFACT
   ↓
ASSET ID
   ↓
JSON METADATA
   ↓
SHA-256
   ↓
GIT COMMIT
   ↓
PUBLIC REPOSITORY
```

Each layer answers a different question.

## 5. Automate deterministic checks

Once the structure is predictable, CI or verification agents can validate contributions automatically:

```text
Detect new artifact
  ↓
Validate filename and path
  ↓
Check metadata schema
  ↓
Calculate SHA-256
  ↓
Check asset ID uniqueness
  ↓
Compare manifest
  ↓
Run policy checks
  ↓
Produce verification result
```

The deterministic parts can be automated while human reviewers remain responsible for judgment calls.

## 6. Connect artifacts to bounty workflows

A bounty can define an expected deliverable. The resulting artifact can then be registered and verified before any reward is recorded.

```text
BOUNTY
   ↓
CONTRIBUTION
   ↓
ARTIFACT
   ↓
METADATA
   ↓
HASH
   ↓
VERIFICATION
   ↓
APPROVAL
   ↓
REWARD RECORD
```

This separation matters. **UPLOAD ≠ PAYMENT.**

Publishing a file is not equivalent to approving or settling a bounty.

Current public bounty examples:

https://github.com/MyZubster-Ecosystem/MyZubster-Visual/issues/2

https://github.com/MyZubster-Ecosystem/MyZubster-Visual/issues/3

## 7. Let AI agents read the same state

Structured metadata makes the registry easier for agents to inspect. An agent could eventually:

- catalog assets;
- detect missing metadata;
- compare hashes;
- identify duplicates;
- connect artifacts to issues;
- prepare releases;
- assist bounty verification;
- generate documentation.

The principle is simple: automated systems work better when the underlying state is structured and inspectable.

## 8. Extend the model beyond images

The same pattern can describe software contributions, robotics designs, datasets, 3D models, IoT evidence, documentation and research outputs.

A connected device might eventually produce:

```text
sensor-data.json
operation-log.json
photo-before.png
photo-after.png
device-metadata.json
```

Those outputs can themselves become artifacts with IDs, hashes and provenance.

## Where this is going

The roadmap I am exploring looks roughly like this:

```text
GitHub Artifacts
       ↓
Metadata Registry
       ↓
Automated Verification
       ↓
AI Agents
       ↓
Bounty Engine
       ↓
MYZ Rewards
       ↓
Marketplace
       ↓
Robotics / IoT
       ↓
Real-World Contributions
```

The objective is not simply to create a repository full of media.

The objective is to create infrastructure where a digital or physical contribution can eventually become:

**identifiable → inspectable → verifiable → attributable → rewardable.**

Main repository:

https://github.com/MyZubster-Ecosystem/MyZubster-Visual
