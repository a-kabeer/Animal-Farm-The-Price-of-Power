# Next Actions and Google Flow Agent Checklist

## Priority order (updated 6 November 2026)

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
- [x] The one authorized Shot001 render completed; 10 credits were reported charged. Authorization is consumed.

### P2 — Generate and review Scene 003

- [x] Flow Agent reports one Shot001 output generated; 10 credits charged; media ID `8a46a89f-c131-4f63-868a-c729b7bf8c7c`; reported metadata 10s / 640x360 / 16:9 / 24fps / audio present.
- [x] Actual MP4 inspected; owner accepted Shot001 V01 for editing and explicitly chose no retake.
- [x] Record lighting discrepancy against Scene 002 Shot 006; apply cool-blue exposure/color matching in NLE during final assembly.
- [ ] Apply and review the color grade; verify it bridges the deep-blue twilight of Scene 002 Shot 006 without crushing detail.
- [ ] Complete a separate listening review of Shot001 native audio.
- [x] Shot002's one conditional authorized output generated; media ID `a8d3301a-6e49-4fc2-91d1-d4d2ae5ba86a`; actual MP4 inspected; owner approval pending. Do not proceed to Shot003 until owner approves Shot002 and separately authorizes Shot003.

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


### Scene 003 Shot001 — owner accepted for editing (6 November 2026)

- [x] One-output generation reported completed; 10 credits charged.
- [x] Actual uploaded MP4 visually inspected in this conversation.
- [x] Owner elected to preserve V01 and not spend credits on a retake.
- [ ] NLE cool-blue color/exposure match required against Scene 002 Shot 006.
- [ ] Native audio listening review remains separate.
- [x] Shot001 authorization consumed; no retake authorized.

### Scene 003 Shot002 — initial preparation (historical; superseded by generation)

- [ ] Verify Boxer reference, Barn_Exterior and BOXER_HAY_CART_CONTINUITY_REFERENCE by exact Flow media ID.
- [ ] Verify Omni 1.2 Flash / R2V (or report the actual available selector without silently changing it), 360p, 16:9, 10 seconds, one output.
- [ ] Show proposed final prompt and live displayed credit quote.
- [ ] Confirm stationary loaded cart, same temporary harness, shoulder-to-forelegs side profile, subtle weight shift, harness settling, one controlled breath, late-dusk exterior.
- [ ] **STOP after preparation. Do not click Generate/Run. No credits may be spent.**
- [ ] Wait for a separate explicit owner authorization for this exact shot/settings/price.


### Scene 003 Shot002 — preflight audit and prompt correction

- [x] Agent reported all three required references attached: Boxer, Barn_Exterior and hay-cart continuity video.
- [x] Agent reported Omni 1.2 Flash / R2V / 360p / 16:9 / 10s / one output; live quote 10 credits.
- [x] No generation was performed; 0 credits spent.
- [x] Audit identified a crop/action conflict: shoulder-to-forelegs framing could hide Boxer's head-lowering action.
- [ ] Flow Agent to enter corrected medium three-quarter side-profile prompt showing full head/neck, shoulder/harness, forelegs and part of stationary cart.
- [ ] Reconfirm all exact references/settings and recheck live quote after prompt revision.
- [ ] Stop at preflight. No generation until separate explicit owner authorization for the corrected prompt and exact live price.


### Scene 003 Shot002 — revised preflight passed (6 November 2026)

- [x] Exact Boxer, Barn_Exterior and hay-cart continuity references re-verified and reported attached.
- [x] Omni 1.2 Flash / R2V / 360p / 16:9 / 10s / one output re-confirmed by Flow Agent.
- [x] Corrected medium three-quarter side-profile prompt reported entered verbatim; Boxer head/neck, shoulder/harness and forelegs remain visible, with the stationary cart partly visible.
- [x] Live displayed quote rechecked and reported as 10 credits.
- [x] No generation performed; 0 credits spent.
- [ ] Await separate explicit owner authorization for exactly one output at 10 credits; recheck live displayed price/settings immediately before any render. If they differ, stop and ask owner.


### Scene 003 Shot002 — conditional owner authorization received (6 November 2026)

- [x] Owner explicitly authorized exactly one output of `ACT01_SCENE003_SHOT002_V01`.
- [x] Authorization ceiling: exactly 10 credits; Flow live UI must still display exactly 10 immediately before generation.
- [x] Locked target: Omni 1.2 Flash / R2V / 360p / 16:9 / 10 seconds / one output / exact three verified references / corrected head-visible prompt.
- [x] Flow Agent reported the live recheck passed and exactly one output was generated at 10 credits.
- [x] No retake, second output, alternate version or other shot was included in that authorization.
- [x] Flow execution report and media ID returned; actual MP4 independently inspected; owner review is pending.


### Scene 003 Shot002 — generation and assistant media review (6 November 2026)

- [x] Conditional owner authorization consumed: exactly one output; Flow reports exactly 10 credits charged.
- [x] Media ID `a8d3301a-6e49-4fc2-91d1-d4d2ae5ba86a`; saved in `04_ACT_01_The_Old_World`.
- [x] Actual uploaded MP4 inspected: 10.00s; 640×360; 16:9; 24fps; H.264; AAC-LC stereo 48kHz.
- [x] Visual review: Boxer identity, white blaze, temporary harness, stationary loaded cart, red barn exterior, head-lowering action and subdued dusk all read clearly.
- [x] Framing deviation recorded: the push-in crops Boxer's forelegs out in the latter half; head, harness and cart remain readable.
- [x] Audio stream presence verified; detailed listening review remains pending.
- [ ] Obtain explicit owner approval or rejection of Shot002 V01. Assistant recommendation: retain for editing with the foreleg-crop note; no retake.
- [ ] Do not generate Shot003 until owner approval of Shot002 and a separate explicit, shot-specific authorization for Shot003.

### Scene 003 Shot002 — owner acceptance (6 November 2026)

- [x] Owner accepted V01 for editing; status: **OWNER ACCEPTED FOR EDITING — MINOR FRAMING DEVIATION**.
- [x] Preserve the single take; no retake authorized or required.
- [x] Keep the late-shot foreleg-crop note visible for the editor.
- [ ] Complete detailed listening review of the native audio.
- [ ] Prepare Shot003 only; no generation until a separate explicit owner authorization for the exact live price/settings/references.
