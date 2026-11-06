# Next Actions and Google Flow Agent Checklist

## Priority order (as of 6 November 2026)

### P0 — Record completed scenes (owner-confirmed)

- [x] Scene 001 — Manor Farm Establishing: six approved shots and master scene complete per project-owner confirmation on 6 November 2026.
- [x] Scene 002 — The Animals' Work: six approved shots and master scene complete per project-owner confirmation on 6 November 2026.
- [ ] Record final master filenames, resolution, frame rate, codecs, runtime and storage paths for both scenes when available. Do not reopen completed work unless a specific defect is found.

### P1 — Prepare and approve Scene 003

**Scene:** `ACT01_SCENE003 — The Burden of the Day`  
**Timecode:** 02:00–03:00  
**Breakdown:** `04_ACT_01_THE_OLD_WORLD/SCENES/ACT01_SCENE003_THE_BURDEN_OF_THE_DAY/SCENE_BREAKDOWN.md`

- [x] Review the six-shot / 60-second breakdown and continuity from Scene 002 Shot 006.
- [x] Both exact dialogue lines approved by project owner on 6 November 2026: Clover (Shot 003) and Boxer (Shot 004). They are approved adaptation dialogue, not quotations from the novel.
- [x] Flow Agent verified the six Shot001 Ingredients and reported their exact media IDs.
- [x] Flow Agent verified the hay-cart / harness continuity reference for Shot001; the locked prompt explicitly preserves cart body, wheels, shafts, hay load and harness.
- [x] Shot001 final prompt and configuration recorded: Omni 1.2 Flash R2V, 360p, 16:9, 10s, one output; Flow Agent reported 10 credits displayed.
- [x] Dialogue approval complete; exact lines are recorded in the Scene 003 breakdown and audio/dialogue tracker.
- [x] Owner explicitly authorized exactly one Shot001 generation at exactly 10 credits on 6 November 2026, conditional on live Flow UI rechecking to exactly 10 credits and all locked settings/references matching.
- [ ] Flow Agent must execute only if the live price is exactly 10 credits; if price/settings/references differ, stop and ask the owner.

### P2 — Generate and review Scene 003

- [ ] Flow Agent to generate Shot001 once only under the exact 10-credit preflight condition; then retrieve the actual MP4 for owner review.
- [ ] Retrieve the actual MP4; verify duration, resolution, frame rate and audio.
- [ ] Review character identity, animal anatomy, cart/harness continuity, dusk-to-night continuity and exact dialogue speaker/line.
- [ ] Preserve all versions and obtain owner approval before marking any version approved.
- [ ] Update shot register, asset register if needed, decision log, progress tracker and project status after approval.

### P3 — Close S01 and prepare S02

- [ ] Assemble Scene 003 to exactly 60 seconds and obtain owner approval.
- [ ] Verify the complete S01 00:00–03:00 sequence across Scenes 001–003.
- [ ] Only then begin S02 — Old Major's Dream; verify/create Old Major, Napoleon and Snowball references and the barn interior before generation.

### P3 — Script and voice decisions

- [ ] Approve narrator voice profile (current suggestion: mature British-English male, warm low-mid register, measured, serious and restrained).
- [ ] Create narrator script for the full 30-minute film.
- [ ] Write exact character dialogue and map each line to a shot/timecode.
- [ ] Create and record voice references in Flow where appropriate.
- [ ] Record actual audio asset paths and status; cue IDs alone are not files.

### P4 — Main cast and location readiness

- [ ] Create/verify Old_Major master character reference and formal Flow Character entity.
- [ ] Create/verify Napoleon, Snowball and Squealer master references/entities.
- [ ] Verify Mr_Jones formal Flow Character entity (visual reference exists; formal entity not confirmed).
- [ ] Verify Main_Barn interior, Farmhouse interior and Windmill_Hill reusable locations before first use.

## Before every generation

- [ ] Correct shot ID and version.
- [ ] Approved storyboard/prompt.
- [ ] Exact reference assets and Flow IDs.
- [ ] Correct aspect ratio and duration.
- [ ] Verify model in UI; do not silently switch models.
- [ ] Verify displayed live credit cost.
- [ ] Confirm one output unless otherwise authorized.
- [ ] User authorization received.

## After every generation

- [ ] Retrieve actual MP4, not just queued status.
- [ ] Verify duration, width/height, fps, codecs, audio.
- [ ] Review multiple timestamps for continuity, character count and action.
- [ ] Record result and review evidence.
- [ ] Preserve all versions; mark one version approved only after user approval.
- [ ] Update shot register, asset register, change log, progress tracker and project_status.json.
- [ ] Commit/push updates to GitHub.
