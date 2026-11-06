# Next Actions and Google Flow Agent Checklist

## Priority order (as of 6 November 2026)

### P0 — Close Scene 001 editorially

**Completed source-asset audit (Flow Agent report, 6 November 2026):**
- [x] Six approved source assets verified in the Flow collection: 001 V01, 002 V03, 003 V01, 004 V01, 005 V01, 006 V01.
- [x] Planned order and aggregate source duration of exactly 60 seconds reported passed.
- [x] 16:9 aspect ratio and visual/character/environment continuity reported passed.
- [x] No generation credits spent during the audit.

**Still required for editorial sign-off:**
- [ ] Open and inspect the actual assembled 60-second master timeline / Full HD export; the Agent audit did not verify the assembled timeline.
- [ ] Confirm hard cuts between shots 001–005 and the planned 0.5s crossfade into shot 006 (if used).
- [ ] Confirm `MANOR FARM` title is tracked onto the blank gate sign; add it in the editor if missing.
- [ ] Confirm Music_001 and intended SFX are actual mixed audio, not just planned cue IDs.
- [ ] Verify the final export is 1920×1080 at 24fps. An earlier record lists an existing upscale, but it was not checked in this audit.
- [ ] Obtain the project owner's review and formal editorial approval.

See `04_ACT_01_THE_OLD_WORLD/DELIVERABLES/SCENE001/EDITORIAL_VERIFICATION_REPORT.md`.

### P1 — Assemble Scene 002

- [ ] In Google Flow Scenebuilder, add approved clips in this exact order: 001 V01 (12s), 002 V01 (10s), 003 V01 (10s), 004 V01 (10s), 005 V02 (8s), 006 V02 (10s).
- [ ] Confirm total 60 seconds.
- [ ] Download/export master MP4.
- [ ] Check video order, continuity, audio and transitions.
- [ ] Upscale/export 1920×1080 at 24fps.
- [ ] Upload master to `DELIVERABLES/SCENE002/` and update project status.

### P2 — Complete first master sequence S01

- [ ] Plan `ACT01_SCENE003` for timecode 02:00–03:00.
- [ ] Story objective: complete remaining “The Hungry Farm” opening beats and transition naturally into Old Major's night gathering, consistent with approved screenplay decisions.
- [ ] Prepare shot list, character/location references and audio cues.
- [ ] Do not confuse working `ACT01_SCENE002` with master sequence `S02 — Old Major's Dream`.

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
