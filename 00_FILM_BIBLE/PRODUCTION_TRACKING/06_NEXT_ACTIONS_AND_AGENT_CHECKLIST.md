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
- [x] Shot002's one conditional authorized output generated; media ID `a8d3301a-6e49-4fc2-91d1-d4d2ae5ba86a`; actual MP4 inspected; owner accepted V01 for editing with a minor foreleg-crop note on 6 November 2026. Detailed audio listening review remains pending.

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
- [x] Obtain explicit owner acceptance of Shot002 V01 for editing on 6 November 2026; retain with the foreleg-crop note; no retake.
- [x] Shot002 owner acceptance is recorded. Shot003 still requires its own separate, explicit, shot-specific generation authorization.

### Scene 003 Shot002 — owner acceptance (6 November 2026)

- [x] Owner accepted V01 for editing; status: **OWNER ACCEPTED FOR EDITING — MINOR FRAMING DEVIATION**.
- [x] Preserve the single take; no retake authorized or required.
- [x] Keep the late-shot foreleg-crop note visible for the editor.
- [ ] Complete detailed listening review of the native audio.
- [ ] Prepare Shot003 only; no generation until a separate explicit owner authorization for the exact live price/settings/references.


### Scene 003 Shot003 — prompt preparation and Flow preflight (6 November 2026)

- [x] Prepare exact shot prompt for Clover's Concern with the owner-approved dialogue line: “You have carried enough for one day, Boxer.”
- [x] Record five precise reference IDs: Clover, Boxer, Barn_Exterior, Manor_Farm_Exterior and BOXER_HAY_CART_CONTINUITY_REFERENCE.
- [x] Create copy-paste task: `04_ACT_01_THE_OLD_WORLD/SCENES/ACT01_SCENE003_THE_BURDEN_OF_THE_DAY/FLOW_AGENT_PREPARATION_TASK_SHOT003.md`.
- [x] Update Scene 003 breakdown, project status and shot register to show prompt-prepared / preflight-pending / not authorized.
- [ ] In Flow, attach all five exact references, enter the prompt verbatim, verify current model/mode/resolution/aspect/duration/output count, and report the exact live displayed credit price.
- [ ] Report whether the chosen Flow mode supports the exact spoken line and reliable lip-sync; do not guess.
- [ ] **STOP after preflight. Do not click Generate, create a preview or spend credits.**
- [ ] Wait for a separate explicit owner authorization for this exact shot and live price. This preparation does not authorize rendering.



### Scene 003 Shot003 — Flow preflight passed (6 November 2026)

- [x] Flow Agent reports all five exact references attached without substitutions.
- [x] Flow Agent reports prompt entered verbatim.
- [x] Live UI preflight report: Omni 1.2 Flash / R2V / 360p / 16:9 / 10 seconds / exactly one output.
- [x] Live displayed quote reported as **10 credits** (point-in-time quote; recheck immediately before any authorized render).
- [x] Native Omni Flash audio enabled.
- [x] Dialogue limitation recorded: exact English speech and precise animal lip-sync are not guaranteed; inspect the result and dub/synchronize in post if needed.
- [x] No generation performed; **0 credits spent**.
- [ ] Obtain separate explicit owner authorization for exactly one Shot003 output at 10 credits, conditional on live price/settings/references matching immediately before generation.
- [ ] Do not generate, preview, or create a variation before that authorization.


### Scene 003 Shot003 — owner authorized one render (7 November 2026)

- [x] Owner explicitly authorized exactly **one** Shot003 video output at exactly **10 credits**, based on the passed preflight.
- [x] Locked settings: Omni 1.2 Flash / R2V / 360p / 16:9 / 10 seconds / output count 1.
- [x] All five exact references verified attached during preflight; locked prompt entered verbatim.
- [x] Created execution task: `04_ACT_01_THE_OLD_WORLD/SCENES/ACT01_SCENE003_THE_BURDEN_OF_THE_DAY/FLOW_AGENT_EXECUTION_TASK_SHOT003.md`.
- [ ] Flow Agent: immediately recheck the live UI. Generate exactly one output only if the displayed price is still exactly 10 credits and all settings/references/prompt match.
- [ ] If any item differs, stop without generating; do not substitute, batch, preview, retry or retake.
- [ ] After the single output, return media ID and actual metadata/audio/dialogue/lip-sync report. Mark **GENERATED — AWAITING OWNER REVIEW**; do not mark approved.
- [ ] Stop after delivering Shot003. Shot004 is not included in this authorization.

**Standing production default:** one output per video shot; never ask whether to batch or make multiple takes. This output-count preference does not authorize future shots; each new shot still needs separate explicit owner authorization.


### Scene 003 Shot003 — generation and media review (7 November 2026)

- [x] Final Flow UI execution report received; exactly one output generated and exactly 10 credits charged.
- [x] Media ID recorded: `868918c2-e7c3-4e18-83d2-ed8bca8f40ff`, asset name “Clover expresses concern for Boxer”, collection `04_ACT_01_The_Old_World`.
- [x] Owner-uploaded MP4 independently inspected: 10.000s; 640×360; 16:9; 24fps; H.264/AVC; AAC-LC stereo 48kHz; audio stream duration 10.026667s.
- [x] Visual continuity review: approved Clover/Boxer identities, Clover unharnessed, Boxer in temporary harness, loaded cart and red barn visible; restrained medium two-shot reads clearly.
- [x] Editorial findings recorded: cool but somewhat brighter/greyer than deep blue twilight; apply modest cool-blue continuity grade. Camera tightens, cropping lower legs while heads/upper bodies remain readable.
- [x] Dialogue status: Flow produced ambient horse vocalization and evening wind, not the exact spoken line. Record Clover's approved line in post and synchronize.
- [x] Assistant recommendation: retain V01 for editing; no retake recommended.
- [ ] Owner review/approval remains pending; do not mark shot owner-approved until explicitly accepted.
- [ ] Detailed listening review of native ambient audio remains pending.
- [ ] Do not generate Shot004 until it is separately prepared and separately authorized. Default remains exactly one output per shot.


### Scene 003 Shot003 — owner acceptance (7 November 2026)

- [x] Owner acknowledged audit and accepted `ACT01_SCENE003_SHOT003_V01` for post-production editing.
- [x] No retake required; preserve the single output.
- [x] Log modest cool-blue grade on the opening of Shot003 to match Shot002.
- [x] Log Clover's exact approved dialogue for dubbing and lip-sync synchronization in post-production.
- [x] Owner reports review spent 0 credits; no new generation during this review.
- [ ] Complete detailed listening review of the native ambient audio.
- [ ] Apply and review color grade and dialogue dub/synchronization in NLE.

### Scene 003 Shot004 — preparation task created (7 November 2026)

- [x] Existing approved shot breakdown and exact dialogue retained: Boxer — “The work still needs doing, Clover.”
- [x] Create Flow preparation task: `04_ACT_01_THE_OLD_WORLD/SCENES/ACT01_SCENE003_THE_BURDEN_OF_THE_DAY/FLOW_AGENT_PREPARATION_TASK_SHOT004.md`.
- [x] Record exact three reference IDs: Boxer, Clover and Barn_Exterior.
- [x] Lock the existing breakdown prompt verbatim and target one output.
- [ ] Run Flow preflight only; report current model/mode/settings, all attached references, exact live displayed price and speech/lip-sync capability.
- [ ] **Do not click Generate, create a preview or spend credits.** No Shot004 generation authorization exists yet.
- [ ] After preflight report, wait for separate explicit owner authorization for one output.


### Scene 003 Shot004 — first preflight mismatch (7 November 2026)

- [x] Initial Flow report received; model/settings were reported as Omni 1.2 Flash / R2V / 360p / 16:9 / 10s / one output; displayed quote 10 credits.
- [x] No generation or preview; Flow reported zero credits spent.
- [x] Identified reference mismatch: Flow reports Boxer + Clover + `BOXER_HAY_CART_CONTINUITY_REFERENCE`; canonical preparation task requires Boxer + Clover + `Barn_Exterior`.
- [x] Identified framing/prompt mismatch: Flow reports medium two-shot; locked Scene Breakdown/task requires medium close-up on Boxer with Clover's shoulder softly visible at frame edge.
- [ ] Re-run preflight with exact canonical references and prompt from `FLOW_AGENT_PREPARATION_TASK_SHOT004.md`.
- [ ] Recheck the live displayed credit price after corrections.
- [ ] Stop after preflight. No generation, preview, or credit spend until a separate explicit owner authorization for the corrected setup.
