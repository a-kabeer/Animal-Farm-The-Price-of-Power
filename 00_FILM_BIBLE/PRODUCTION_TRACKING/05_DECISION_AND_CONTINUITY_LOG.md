# 05 — DECISION & CONTINUITY LOG

**Last updated:** 6 November 2026

## A. Major production decisions and changes

| # | Area | Original / issue | Decision / update | Current rule/status |
|---:|---|---|---|---|
| 1 | Master structure | 30-minute movie cannot be made with one prompt | Blueprint organized film into 10 sequences × 3 minutes; 180 ten-second clips is theoretical minimum | Use S01–S10 master map; generate individually and review each clip |
| 2 | Generation settings | Blueprint recommended Omni Flash 1.1, 720p where available | Actual working sessions used Omni 1.2 Flash, 360p, 16:9, one output | Current operational setting; recheck live Flow model and credits each time |
| 3 | Scene 001 timing | Original six shot durations totaled 46 seconds | Revised to 12+10+10+10+8+10 = 60 seconds | Approved 60-second scene breakdown |
| 4 | Scene 001 Shot 002 | V01 showed Mr_Jones outside; V02 still failed | Created composition reference with Jones inside lit window, holding bottle; V03 passed | V03 is approved; V01/V02 retained but superseded |
| 5 | Mr_Jones design | Two character sheets | User selected Option 1 | Visual master reference approved; formal reusable Flow Character entity remains unverified |
| 6 | The_Cows | Assistant recommended Option B initially | User later selected Option A and locked it | Option A is authoritative; exactly two cows in specified group shots |
| 7 | Scene 001 Shot 003 | Barn exterior/interior reference ambiguity | Created/used distinct Barn_Exterior asset separate from Main_Barn interior | Always reference Barn_Exterior for outside shots |
| 8 | Scene 001 assembly | Six approved shots require an actual edit | Assembly sheet specified hard cuts 1–5, 0.5s crossfade into Shot 006, music/SFX, tracked MANOR FARM sign | Scene 001 60s Full HD file exists; exact assembly/editing details need final content review |
| 9 | Full HD | Source clips 360p | 60s Scene 001 video upscaled to 1920×1080 | Upscale file exists; it does not restore native 1080p detail |
| 10 | Scene 002 timing | First proposed shot mix totaled 60 seconds | Kept 12+10+10+10+8+10 = 60 seconds | Approved plan |
| 11 | Boxer / cart | Harness/cart not part of permanent character design | Created `BOXER_HAY_CART_CONTINUITY_REFERENCE` from Shot 001 | Harness is a temporary working prop; same cart, wheels, shafts and hay load for relevant shots |
| 12 | Clover | Initial note said she steadies the cart | Corrected action to walking alongside Boxer, looking concerned | Clover remains unharnessed in Scenes 002 Shots 002 and 006 |
| 13 | Benjamin | Feed sacks need credible placement | Added simple rope/pack straps | Sacks should sit naturally on back; no human-like posture |
| 14 | Scene 002 Shot 005 | V01 showed only three sheep | Created composition reference: two cows left, four sheep right; V02 approved | V02 approved; exactly two cows and four sheep when this group is specified |
| 15 | Scene 002 Shot 006 | V01 looked like daytime, not dusk | V02 video-to-video lighting correction | V02 approved; preserve V01; deep blue twilight and warm farmhouse glow |
| 16 | Horse size | User observed Boxer and Clover appeared large | Added relative proportion guide: Boxer most muscular, Clover similar shoulder height but lighter, Benjamin shorter/slimmer | Do not force scale changes if they distort anatomy/perspective |
| 17 | Dialogue/audio | Shot prompts had no spoken lines | Current Scene 001/002 shots have no dialogue; master blueprint defines voice directions and separate narrator track | Write/approve dialogue and narration before those sequences are generated |

## B. Locked visual continuity rules

### Characters
- **Boxer:** chestnut-brown muscular draft horse; dark mane; distinctive white blaze; gentle brown eyes. Largest/most muscular horse.
- **Clover:** sturdy chestnut mare; lighter golden-brown mane; soft brown eyes; protective presence. Similar shoulder height to Boxer if perspective allows, but lighter/less bulky. No harness unless a future shot explicitly requires one.
- **Benjamin:** older grey donkey; charcoal mane; long upright ears; narrow muzzle; tired eyes. Visibly smaller and slimmer than draft horses.
- **Mr_Jones:** Option 1 selected; flat tweed cap, weathered face, rough dark beard, worn brown jacket, trousers and muddy boots. Bottle is a separate prop; cane/rifle not permanent accessories.
- **The_Cows:** Option A selected; exactly two black-and-white cows with locked individual markings.
- **The_Sheep:** Option A selected; exactly four white sheep, consistent wool and anatomy.

### Environment
- `Manor_Farm_Exterior` fixes farmhouse/barn/yard geography.
- `Barn_Exterior` is separate from `Main_Barn` interior.
- `Fields_And_Orchard` provides the working fields, pasture, orchard, fence, haystack and muddy track.
- `Animal_Paddock` provides the enclosure and trough.
- The gate sign remains blank in generated media; add `MANOR FARM` as an editor overlay.

### Continuity props
- Same wooden hay cart, wheels, shafts, hay load and temporary leather harness wherever the same working cart is shown.
- Feed sacks carried by Benjamin use simple natural pack straps.
- Chain and padlock remain the gate insert props.

## C. Version selection / rejected versions

| Shot | Superseded version(s) | Current approved version | Reason |
|---|---|---|---|
| ACT01_SCENE001_SHOT002 | V01, V02 | V03 | Earlier videos placed Jones outside; V03 correctly places him inside the lit window with bottle |
| ACT01_SCENE002_SHOT005 | V01 | V02 | V01 showed only three sheep; V02 shows exactly two cows and four sheep |
| ACT01_SCENE002_SHOT006 | V01 | V02 | V01 looked like daytime; V02 corrected to dusk |

Keep rejected versions for comparison/audit. Never use them in the master edit.

## D. Open continuity checks

- Confirm the final Scene 001 assembly includes the exact six approved source versions and title overlay/music/SFX plan.
- Confirm Scene 002 Scenebuilder assembly uses Shot 005 V02 and Shot 006 V02.
- Verify the actual Flow Character entities for the image references before relying on named Character/Voice objects. A saved reference image is not automatically proof of a formal Character Entity.
- Maintain the 10-sequence master plan while using one-minute working scene modules; document mapping clearly.

## E. Scene 003 Shot001 execution record — 6 November 2026

- Owner authorized exactly one generation, one output, conditional on 10 credits and unchanged settings/references.
- Flow Agent reports this single generation completed and 10 credits were charged.
- Media ID: `8a46a89f-c131-4f63-868a-c729b7bf8c7c`; asset name: `Boxer stopping cart by barn`.
- Reported output: 10 seconds, 640×360, 16:9, 24fps; audio present.
- Agent reports locked prompt used verbatim and six references attached.
- Status: **GENERATED — AWAITING OWNER REVIEW**. Report alone does not prove visual/audio quality. Review character identities/count, cart body/wheels/shafts/hay/harness, Boxer harness, Clover unharnessed, Benjamin near barn, exterior-only geography, dusk light and ambient audio. No Shot002 or retake is authorized.


## F. Scene 002 → Scene 003 transition audit and owner decision — 6 November 2026

- Scene 002 Shot 006 V02 is officially approved and locked as the final shot of Scene 002. Owner-reported media ID: `e3c06bbd-2245-427a-8fbd-3b9bbd1cf891`; 10s; 1280×720; 24fps; 16:9; AAC stereo.
- Scene 003 Shot 001 V01 media ID `8a46a89f-c131-4f63-868a-c729b7bf8c7c` is retained and locked for editing, not retaken. Owner-approved continuity decision: preserve the clip and correct the bright/overcast opening by NLE cool-blue exposure/color matching against Scene 002 Shot 006. The editorial grade remains pending; do not claim it has been applied.
- Character and prop continuity (Boxer, Clover, Benjamin, cart, harness and barn) is accepted across the cut. The identified mismatch is principally lighting/color and source resolution (Scene 002 final: 720p; Scene 003 opening: 360p).
- No generation credits are authorized or spent for this transition decision. No Shot 001 retake is authorized.

## G. Next production step — Scene 003 Shot 002 preparation only

- Prepare `ACT01_SCENE003_SHOT002_V01 — The Weight of the Work` with Boxer, Barn_Exterior and the exact hay-cart continuity reference.
- Required staging: cart remains stationary and loaded beside the barn; Boxer keeps the same temporary leather harness; medium side profile from shoulder to forelegs; small weight shift, natural harness settling and one controlled tired breath; subtle push-in; late-dusk exterior.
- Avoid repeating Scene 002 Shot 004's face close-up; no collapse, no dialogue, no new character and no interior.
- Flow Agent must only verify references, settings, prompt and live displayed credit quote. No Generate/Run action. Preparation does not constitute generation authorization. A separate explicit owner authorization is required before rendering.


## F. Scene 002 → Scene 003 transition audit and owner decision — 6 November 2026

- Scene 002 Shot 006 V02 is officially approved and locked as the final shot of Scene 002. Owner-reported media ID: `e3c06bbd-2245-427a-8fbd-3b9bbd1cf891`; 10s; 1280×720; 24fps; 16:9; AAC stereo.
- Scene 003 Shot 001 V01 media ID `8a46a89f-c131-4f63-868a-c729b7bf8c7c` is retained and locked for editing, not retaken. Owner-approved continuity decision: preserve the clip and correct its brighter/overcast opening by NLE cool-blue exposure/color matching against Scene 002 Shot 006. The editorial grade remains pending; do not claim it has been applied.
- Character and prop continuity (Boxer, Clover, Benjamin, cart, harness and barn) is accepted across the cut. The identified mismatch is principally lighting/color and source resolution (Scene 002 final: 720p; Scene 003 opening: 360p).
- No generation credits are authorized or spent for this transition decision. No Shot 001 retake is authorized.

## G. Next production step — Scene 003 Shot 002 preparation only

- Prepare `ACT01_SCENE003_SHOT002_V01 — The Weight of the Work` with Boxer, Barn_Exterior and the exact hay-cart continuity reference.
- Required staging: cart remains stationary and loaded beside the barn; Boxer keeps the same temporary leather harness; medium side profile from shoulder to forelegs; small weight shift, natural harness settling and one controlled tired breath; subtle push-in; late-dusk exterior.
- Avoid repeating Scene 002 Shot 004's face close-up; no collapse, no dialogue, no new character and no interior.
- Flow Agent must only verify references, settings, prompt and live displayed credit quote. No Generate/Run action. Preparation does not constitute generation authorization. A separate explicit owner authorization is required before rendering.


## H. Scene 003 Shot 002 preflight audit — 6 November 2026

- Owner-supplied Flow Agent report confirms the expected three references were attached: Boxer `7e912af3-0d8f-45d1-8c7a-bfffa6cee3ba`, Barn_Exterior `3919fbb9-bf69-40e5-98f4-e02680cb077a`, and BOXER_HAY_CART_CONTINUITY_REFERENCE `d86c8a63-b658-4216-9740-0132bcf86282`.
- Reported setup: Omni 1.2 Flash / R2V / 360p / 16:9 / 10 seconds / one output; native ambient audio enabled; live displayed quote 10 credits.
- Preparation only: no render performed and zero credits spent. The displayed quote is not generation authorization and must be rechecked after any prompt change.
- Audit finding: shoulder-to-forelegs framing could crop out Boxer's head despite the required head-lowering action.
- Prompt correction: use medium three-quarter side-profile framing that includes Boxer's full head and neck, shoulder/harness and forelegs, with a readable portion of the stationary hay cart behind him.
- Corrected preflight instruction is stored in `FLOW_AGENT_PROMPT_REVISION_SHOT002.md`. Flow Agent must reconfirm the corrected prompt, exact references/settings and live quote. No generation is authorized.


## C. Scene 003 Shot002 — generation result and continuity review (6 November 2026)

- Owner supplied Flow execution report for `ACT01_SCENE003_SHOT002_V01`; media ID `a8d3301a-6e49-4fc2-91d1-d4d2ae5ba86a`; asset name `Boxer lowering head by cart`; collection `04_ACT_01_The_Old_World`.
- Flow reports the live authorization conditions were met: exactly one output, exactly 10 credits charged, Omni 1.2 Flash / R2V / 360p / 16:9 / 10 seconds; all three references attached and corrected prompt used verbatim.
- Actual uploaded MP4 metadata independently verified: 10.000s video, 640×360, 24fps, H.264/AVC; AAC-LC stereo at 48kHz.
- Visual continuity accepted for character identity, white blaze, temporary harness, stationary loaded hay cart, Barn_Exterior and cool subdued dusk. The required head-lowering action is clear, with visible breath vapor.
- **Framing deviation:** the camera push-in tightens too much in the latter half and crops Boxer's forelegs out of the final frames, contrary to the prompt's request to keep them visible throughout. Head, harness and cart remain readable.
- Editorial recommendation: keep the single V01 take for editing; use the push-in as an intentional tightening of the emotional focus. No retake recommended or authorized.
- Audio stream existence verified; sound quality/listening review remains pending.
- Status remains **GENERATED — AWAITING OWNER REVIEW** until the project owner explicitly approves. No Shot003 generation is authorized by this record.


## D. Owner decision — retain Scene 003 Shot002 V01 for editing (6 November 2026)

The project owner accepted the assistant's recommendation and approved `ACT01_SCENE003_SHOT002_V01` for editing. The single take is retained with the known minor framing deviation: the push-in crops Boxer's forelegs during the latter half. No retake is planned or authorized. Native audio stream presence is verified; detailed listening review remains pending. This decision does not authorize Shot003 or any other generation.


## E. Scene 003 Shot003 — preflight passed; render on hold (6 November 2026)

Flow Agent reports all five exact approved references attached without substitution and the prompt entered verbatim. Live setup: Omni 1.2 Flash / Reference-to-Video / 360p / 16:9 / 10s / one output; displayed price 10 credits. Native audio enabled. Exact English dialogue and precise animal lip-sync are not guaranteed, so review the result and plan post-production dubbing/synchronization if necessary.

No generation performed; zero credits spent. Shot003 remains **PREFLIGHT PASSED — AWAITING EXPLICIT GENERATION AUTHORIZATION**. Recheck live price and settings immediately before any render. No preview, retake, variation or generation is included without separate explicit owner authorization.


## F. Scene 003 Shot003 — generation and editorial review (7 November 2026)

Exactly one output was generated; Flow reports 10 credits charged. Media ID: `868918c2-e7c3-4e18-83d2-ed8bca8f40ff`. Actual MP4 metadata verified: 10s, 640×360, 16:9, 24fps, H.264/AVC, AAC-LC stereo 48kHz.

Continuity passes visually: Clover and Boxer identities, harness states, stationary loaded cart and red barn remain coherent. Composition reads as a restrained medium two-shot; the gradual push-in crops lower legs near the end but retains both heads/upper bodies. Lighting is cool but a little brighter/greyer than the preceding deep blue twilight; modest cool-blue grading recommended. Native audio is ambient horse vocalization and evening wind according to Flow report; exact Clover dialogue was not generated. Dub and synchronize the approved line in post. Detailed listening review remains pending.

Assistant editorial disposition: **recommend retain V01 for editing; no retake recommended.** Owner review remains pending. Do not begin Shot004 generation without its own explicit shot-specific authorization; default one output per shot.


## G. Scene 003 Shot003 accepted; Shot004 preparation started — 7 November 2026

Owner acknowledges the Shot003 audit and accepts V01 for post-production editing. No retake required. Preserve media ID `868918c2-e7c3-4e18-83d2-ed8bca8f40ff`. Apply a modest cool-blue grade to the opening and dub/synchronize Clover's exact approved line during final audio editing. The owner reports zero credits spent during review.

Shot004 — Boxer's Response — is prepared for Flow UI preflight only. Its owner-approved line is “The work still needs doing, Clover.” Use exact Boxer, Clover and Barn_Exterior references. Preflight task file: `FLOW_AGENT_PREPARATION_TASK_SHOT004.md`. Do not generate, preview or spend credits. Wait for a separate explicit owner authorization after the live UI price/settings and reference attachments are reported. Default remains one output per shot.


## H. Scene 003 Shot004 — generation and review (7 November 2026)

Exactly one output generated; Flow reports 10 credits charged. Media ID `0b69c62d-2094-4ca6-835d-24346f727361`. Actual uploaded MP4 verified: 10s, 640×360, 24fps, 16:9, H.264/AVC, AAC stereo 48kHz.

Independent visual review finds the corrected medium close-up works: Boxer is the primary subject, Clover is partly visible at the left edge, harness and white blaze are readable, and the red barn setting is consistent. Assistant recommendation: retain V01 for editing; no retake recommended. Flow reports ambient horse vocalization and evening wind only; dub and synchronize the approved Boxer line in post. Detailed listening review remains pending. Owner review is still pending; no Shot005 generation is authorized.


## I. Scene 003 Shot004 — detailed visual audit (7 November 2026)

Actual MP4 sampled at 0.5s, 2s, 4s, 6s, 8s and 9.5s and compared with Shot003. The medium close-up correctly centers Boxer; the white blaze, mane, ears and temporary harness remain readable, with the red Barn_Exterior consistent. Clover's partial head/muzzle is visible at the left edge rather than only her shoulder, but remains cropped/secondary and does not create a full two-shot. Lighting is cool subdued dusk but a little brighter/greyer than Shot003; modest cool-blue continuity grading recommended. Push-in crops more of Boxer's body but retains his head/ears.

Technical metadata verified: 10.000s, 640×360, 16:9, 24fps, H.264/AVC, AAC stereo 48kHz. Flow reports ambient audio only; exact approved Boxer line requires post-production dubbing/synchronization. Detailed listening review pending.

Assistant recommendation: **retain V01 for editing; no retake recommended.** Owner review remains pending.
