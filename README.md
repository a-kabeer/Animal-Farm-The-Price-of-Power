# ANIMAL FARM — THE PRICE OF POWER

**30-minute cinematic 3D animated film production repository**  
**Production platform:** Google Flow  
**Tracking baseline:** 6 November 2026

> This repository is a production-control archive and reference package. It is not a live mirror of Google Flow. Generated media and references saved in Flow are tracked by IDs where known; some Flow-only assets do not have local binary copies here.

## Current production status

- Scene 001 — `Manor Farm Establishing`: 6/6 individual source clips approved and locked. The Agent has supplied the 60-second master assembly specification (clip order, transition, title, audio and target export settings), but explicitly says timeline editing, title compositing, audio mixing and export are Flow UI / NLE operations. The actual rendered master MP4 has not been supplied or verified; final 1080p export and owner sign-off remain pending. See the Final Master Assembly Verification Report.
- Scene 002 — `The Animals' Work`: 6/6 individual shots approved. Approved shot video binaries are intentionally excluded from this GitHub package. Scene assembly/export is pending.
- Approved shot footage: 12 shots, 120 seconds (2:00), equal to 6.7% of the 30-minute runtime. This is footage coverage, not overall film completion.
- Current working scenes 001 and 002 provisionally cover 00:00–02:00 of master sequence S01 — `The Hungry Farm` (00:00–03:00). Minute 02:00–03:00 is not planned yet.
- Exact narrator script and character dialogue have not been written/approved. All 12 approved shot plans specified no dialogue.

## Start here

1. Read [`00_FILM_BIBLE/PROJECT_SCOPE_AND_SOURCE_OF_TRUTH.md`](00_FILM_BIBLE/PROJECT_SCOPE_AND_SOURCE_OF_TRUTH.md).
2. Open [`00_FILM_BIBLE/PRODUCTION_TRACKING/00_MASTER_CONTROL_BOARD.md`](00_FILM_BIBLE/PRODUCTION_TRACKING/00_MASTER_CONTROL_BOARD.md).
3. Check [`01_MASTER_PROGRESS_TRACKER.md`](00_FILM_BIBLE/PRODUCTION_TRACKING/01_MASTER_PROGRESS_TRACKER.md).
4. Review the shot registers and asset register in `00_FILM_BIBLE/PRODUCTION_TRACKING/`.
5. Read each scene breakdown under `04_ACT_01_THE_OLD_WORLD/SCENES/`.
6. Follow the next actions in [`06_NEXT_ACTIONS_AND_AGENT_CHECKLIST.md`](00_FILM_BIBLE/PRODUCTION_TRACKING/06_NEXT_ACTIONS_AND_AGENT_CHECKLIST.md).

## Repository structure

```text
00_FILM_BIBLE/             Original blueprint, Agent rules, production tracking
01_CHARACTERS/             Approved local character refs and review archive
02_LOCATIONS/              Approved local environment refs and Flow-only asset index
03_PROPS_AND_SYMBOLS/       Continuity prop references and specifications
04_ACT_01_THE_OLD_WORLD/    Scene breakdowns, media indices, audit revisions, export requirements
05_ACT_02_REBELLION/        Reserved for Act 02 planning and production
06_ACT_03_THE_NEW_ORDER/    Reserved for Act 03 planning and production
07_ACT_04_FEAR_AND_WINDMILL/ Reserved for Act 04 planning and production
08_ACT_05_THE_FINAL_BETRAYAL/ Reserved for Act 05 planning and production
90_AUDIO_AND_MUSIC/         Voice cast, audio cues and audio assets
91_SCREENPLAY_AND_DIALOGUE/ Master story map and script status
92_EDITING_AND_EXPORT/      Export and final edit requirements
99_APPROVED_SCENES/         Approval index and assembly manifests
```

## What is included

- Original user-supplied Google Flow blueprint.
- Updated master control board and progress/shot/asset/credit/change registers.
- Scene 001 and Scene 002 detailed approved shot breakdowns and Flow prompts.
- No approved shot-video binaries are included (all 12 approved clips are excluded by request).
- No Scene 001 source MP4 or Full HD export is included (excluded by request).
- Rejected/superseded video takes remain in the clearly marked audit archive.
- Selected approved character/environment/composition reference images that were available as local uploads.
- Rejected/superseded video takes retained in a clearly marked archive for audit; never use them in final assembly.
- Audio/dialogue/narration status and templates.
- GitHub instructions and issue templates.

## Important asset limitation

Google Flow asset IDs are recorded in the Asset Register. Not every Flow reference image/Character/Location asset was uploaded as a local binary. See `02_LOCATIONS/FLOW_ONLY_REFERENCE_INDEX/` and the Asset Register; retrieve missing originals from the relevant Flow collection if a standalone local copy is required.

## GitHub upload

See [`GITHUB_SETUP.md`](GITHUB_SETUP.md). The repository includes `.gitattributes` for future Git LFS media additions. The ZIP itself should be extracted before pushing the folder. This archive contains only the retained reference images and audit media, not the approved video binaries or Scene 001 exports.

## Rights note

This is an adaptation of George Orwell's *Animal Farm*. Copyright and adaptation rights vary by country/territory and by publication/monetization method. Verify rights before public release. The project does not include a license grant.
