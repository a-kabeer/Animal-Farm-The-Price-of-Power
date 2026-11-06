# ACT01_SCENE003 — The Burden of the Day

**Act:** Act 01 — The Old World  
**Master sequence:** S01 — The Hungry Farm  
**Timecode:** 02:00–03:00  
**Target runtime:** 60 seconds  
**Status:** SHOT001 V01 OWNER ACCEPTED FOR EDITING — COLOR MATCH REQUIRED; SHOT002 PREPARATION ONLY NEXT; no generation authorized  
**Shot count:** 6 planned shots × 10 seconds  
**Generation authorization (6 November 2026):** The owner explicitly authorized exactly one generation of Shot001, one output, subject to the exact 10-credit live price and locked settings/references. Flow Agent reports this single authorized generation completed and 10 credits were charged. The authorization is consumed; no retake or other shot is authorized.

## 1. Story purpose

This is the final minute of S01. The original blueprint lists these S01 beats: establish Manor Farm; show Jones's neglect; Boxer and Clover discuss hardship; Benjamin observes. Scenes 001 and 002 are now recorded as master-complete based on the project owner's confirmation. Scene 003 stages the remaining Boxer/Clover hardship exchange, Benjamin's silent observation, and a visual transition toward the night gathering that begins in S02 at 03:00.

This scene must **not** begin Old Major's speech or show the S02 meeting itself. Old Major's first appearance and the night gathering belong to S02.

The two dialogue lines below are original adaptation lines, approved by the project owner on 6 November 2026. They are not quotations from the source novel.

## 2. Continuity and asset requirements

| Character | Locked appearance | Reference |
|---|---|---|
| Boxer | Large muscular chestnut-brown working horse; dark mane; white blaze; temporary work harness remains on while cart is stopped | Approved Boxer reference; Flow ID reported as 7e912af3-0d8f-45d1-8c7a-bfffa6cee3ba |
| Clover | Sturdy chestnut mare; lighter golden-brown mane; soft brown eyes; concerned manner; completely unharnessed | Approved Clover reference; Flow ID reported as b86cb0af-a9e4-4d02-8b25-0316f718481b |
| Benjamin | Older grey donkey; charcoal mane; long upright ears; narrow muzzle; tired observant eyes; slimmer than Boxer | Approved Benjamin reference; Flow ID reported as 0595b453-1a9c-4c11-9359-fd79a6eeb951 |

Use saved Flow Character entities if they exist. Otherwise, use approved reference images through Ingredients. Do not redesign or regenerate the characters.

### Locations and props

- Manor_Farm_Exterior — existing approved Flow location reference, ID reported as 8fa316c0-27e8-4df8-98af-56c73fa332f7.
- Barn_Exterior — existing approved Flow location reference, ID reported as 3919fbb9-bf69-40e5-98f4-e02680cb077a.
- BOXER_HAY_CART_CONTINUITY_REFERENCE — reuse the same wooden cart, wheels, shafts, hay load and temporary harness from Scene 002; media ID reported as d86c8a63-b658-4216-9740-0132bcf86282.

All shots remain outside the barn. No unverified Main_Barn interior asset is required. Keep the same barn architecture and yard geography. Scene 002 Shot 006 ends at dusk; Scene 003 begins in the same late-evening continuity and gradually moves toward blue night.

### Generation target

- Model used in recent production: Omni Flash 1.2; verify the live selector before generation.
- Draft target: 360p, 16:9 landscape, 10 seconds per shot, one output.
- Existing reviewed clips have been 640×360 at 24fps; verify actual settings and output metadata in Flow.
- Check live credit cost immediately before each generation. No fixed credit estimate is recorded.
- Generate one shot at a time. Retrieve and review the actual video, preserve every version, and request owner approval before marking a shot approved.

## 3. Shot list and timing

| Order | Shot ID | Working title | Duration | Status |
|---:|---|---|---:|---|
| 1 | ACT01_SCENE003_SHOT001 | The Cart Comes to Rest | 10s | OWNER ACCEPTED FOR EDITING — COLOR MATCH REQUIRED |
| 2 | ACT01_SCENE003_SHOT002 | The Weight of the Work | 10s | PREPARATION ONLY — NOT GENERATED; no authorization |
| 3 | ACT01_SCENE003_SHOT003 | Clover's Concern | 10s | DIALOGUE APPROVED — NOT GENERATED |
| 4 | ACT01_SCENE003_SHOT004 | Boxer's Answer | 10s | DIALOGUE APPROVED — NOT GENERATED |
| 5 | ACT01_SCENE003_SHOT005 | Benjamin Observes | 10s | PLANNED |
| 6 | ACT01_SCENE003_SHOT006 | Night Settles over the Farm | 10s | PLANNED |
| | **TOTAL** | | **60s** | **Not generated** |

### Shot 001 — The Cart Comes to Rest (10 seconds)

**References:** Boxer, Clover, Benjamin, Manor_Farm_Exterior, Barn_Exterior and the hay-cart continuity anchor.  
**Framing / action:** Ground-level medium-wide side angle; slow restrained lateral drift. The same hay cart stops beside the red barn. Boxer remains in the same temporary leather harness. Clover stands close beside him, unharnessed. Benjamin is farther back near the barn entrance.  
**Dialogue:** None.  
**Sound:** Evening wind, soft harness movement and one subdued cart-wheel creak.

**Preparation decision (6 November 2026): LOCKED FOR PRODUCTION PLANNING — NOT GENERATED.** The Flow Agent's corrected report verified all six selected references, Omni 1.2 Flash Reference-to-Video mode, 360p, 16:9, 10 seconds, one output and a live displayed quote of 10 credits. The quote is a point-in-time UI report, not a guarantee of future price. No credits spent.

**Selected references / Ingredients (exact reported media IDs):**
- Boxer — `7e912af3-0d8f-45d1-8c7a-bfffa6cee3ba`
- Clover — `b86cb0af-a9e4-4d02-8b25-0316f718481b`
- Benjamin — `0595b453-1a9c-4c11-9359-fd79a6eeb951`
- Manor_Farm_Exterior — `8fa316c0-27e8-4df8-98af-56c73fa332f7`
- Barn_Exterior — `3919fbb9-bf69-40e5-98f4-e02680cb077a`
- BOXER_HAY_CART_CONTINUITY_REFERENCE — `d86c8a63-b658-4216-9740-0132bcf86282`

**Locked Flow configuration (reported by Flow Agent):** Omni 1.2 Flash · Reference-to-Video (R2V) · 360p · 16:9 landscape · 10 seconds · one output · 10 credits displayed. Recheck the live price immediately before any authorized generation.

**Locked final Flow prompt:**

~~~text
ACT01_SCENE003_SHOT001_V01: Continue directly from Scene 002 Shot 006, preserving the same late-dusk farmyard and barn geography. Use the exact wooden hay cart from the supplied continuity video reference, preserving its original body, wheels, shafts, hay load and leather harness. Boxer remains connected to the cart and wears the same working harness throughout; do not remove or alter it. The cart rolls slowly to a complete stop beside the red timber barn and remains stationary. Clover stands beside Boxer, completely unharnessed. Benjamin watches quietly from near the barn entrance. Keep all action outside. No dialogue, no Old Major, no interior meeting and no new animals. Use a ground-level medium-wide side view with restrained lateral camera movement. Include only natural horse breathing, wooden cart creaks and evening wind.
~~~

**Authorization boundary:** Shot001 V01 has been generated and the owner has accepted it for editing, with cool-blue color/exposure matching still required in the NLE; do not retake. Shot002 may be prepared and preflighted only. Preparation and a displayed quote do not authorize generation. Obtain separate explicit owner authorization before any render.

### Shot 002 — The Weight of the Work (10 seconds)

**References:** Boxer, Barn_Exterior and hay-cart continuity anchor.  
**Framing / action:** Medium profile from shoulder to forelegs, stationary cart readable behind him. Boxer shifts his weight, the harness settles slightly as the cart remains stopped, and he lowers his head for one controlled breath. Do not remove the harness.  
**Dialogue:** None.  
**Sound:** Deep horse exhale, light leather creak and evening wind. Avoid repeating Scene 002 Shot 004's close-up exhaustion portrait.

~~~text
SHOT ID: ACT01_SCENE003_SHOT002_V01
Duration: 10 seconds, 16:9 landscape.

Use the approved Boxer reference, Barn_Exterior and the same hay-cart / harness continuity reference. Boxer is the same muscular chestnut working horse with dark mane and white facial blaze. Keep the same temporary leather harness; do not remove it or alter its design.

Medium side-profile shot beside the stationary loaded hay cart at late dusk. Frame Boxer's shoulder, harness and forelegs, with the cart still visible behind him. He slowly shifts his weight after the day's work, the harness settles naturally, and he lowers his head for one controlled tired breath. This is restrained physical action, not a dramatic collapse. Slow subtle push-in. No dialogue.

Serious cinematic 3D animated feature-film drama, natural horse anatomy, realistic harness physics, detailed chestnut coat and leather textures, restrained emotional performance, consistent 1940s English farm setting, late-evening light, 16:9 landscape. Preserve the approved character and cart references exactly. No text, subtitles, logos, watermark, extra limbs or duplicated equipment.
~~~

### Shot 003 — Clover's Concern (10 seconds)

**References:** Clover, Boxer, Manor_Farm_Exterior and Barn_Exterior.  
**Framing / action:** Medium two-shot at animal eye level; Clover in clear focus, Boxer listening. Clover takes one small step closer and looks at Boxer with quiet concern.  
**Approved dialogue — owner approved 6 November 2026:** Clover: “You have carried enough for one day, Boxer.”  
**Performance:** Warm, calm, empathetic voice; restrained concern. Only Clover speaks.  
**Sound:** Very low evening ambience under the line.

~~~text
SHOT ID: ACT01_SCENE003_SHOT003_V01
Duration: 10 seconds, 16:9 landscape.

Use only the approved Clover and Boxer character references and the same exterior barnyard location. Preserve Clover's chestnut coat and lighter golden-brown mane. Clover is completely unharnessed. Boxer remains in the same temporary leather work harness beside the stationary hay cart.

Medium two-shot at natural animal eye level. Clover takes one small step closer and looks at Boxer with gentle concern. Boxer remains still and listens, visibly tired but composed. Keep the camera steady with a very slight push-in.

APPROVED DIALOGUE — OWNER APPROVED 6 NOVEMBER 2026:
Clover speaks exactly: "You have carried enough for one day, Boxer."
Only Clover speaks. Boxer does not speak. Do not add, paraphrase or invent any words.

Voice direction: warm, calm, empathetic adult female voice, slightly concerned. No narrator.

Serious cinematic 3D animated feature-film drama, realistic horse anatomy and subtle facial acting, detailed natural coat textures, late-evening English farm exterior, 16:9 landscape. Preserve all approved character references. No text, subtitles, logos, watermark, extra limbs or duplicate characters.
~~~

### Shot 004 — Boxer's Answer (10 seconds)

**References:** Boxer, Clover and Barn_Exterior.  
**Framing / action:** Medium close-up on Boxer, Clover's shoulder softly visible at frame edge. Boxer raises his head slightly and turns his eyes toward Clover.  
**Approved dialogue — owner approved 6 November 2026:** Boxer: “The work still needs doing, Clover.”  
**Performance:** Warm sincere baritone; simple phrasing; gentle resolve, not heroic or boastful. Only Boxer speaks.  
**Sound:** One soft horse breath after the line; restrained evening wind.

~~~text
SHOT ID: ACT01_SCENE003_SHOT004_V01
Duration: 10 seconds, 16:9 landscape.

Use the approved Boxer and Clover references and the same Barn_Exterior setting. Preserve Boxer's chestnut coat, dark mane, distinctive white blaze and temporary leather working harness. Clover remains unharnessed and is only partly visible at the edge of frame.

Medium close-up on Boxer. After listening, he gently raises his head and turns his eyes toward Clover. His expression is tired but steady, kind and modest. Keep the camera nearly locked with a subtle push-in.

APPROVED DIALOGUE — OWNER APPROVED 6 NOVEMBER 2026:
Boxer speaks exactly: "The work still needs doing, Clover."
Only Boxer speaks. Clover remains silent. Do not add, paraphrase or invent any words.

Voice direction: warm adult male baritone, sincere, gentle and steady, simple phrasing. No narrator.

Serious cinematic 3D animated feature-film drama, natural horse anatomy, subtle believable facial acting, detailed chestnut coat and mane, late-evening English farm exterior, 16:9 landscape. Preserve the approved character reference. No text, subtitles, logos, watermark, extra limbs or duplicate characters.
~~~

### Shot 005 — Benjamin Observes (10 seconds)

**References:** Benjamin, Barn_Exterior and Manor_Farm_Exterior.  
**Framing / action:** Medium shot from outside the barn entrance; doorway frames Benjamin without requiring an unverified interior set. He stands in the doorway shadow, ears attentive, watches Boxer and Clover, then lowers his gaze slightly.  
**Dialogue:** None. Benjamin does not speak.  
**Sound:** Subtle evening wind and distant barn timber creak.

~~~text
SHOT ID: ACT01_SCENE003_SHOT005_V01
Duration: 10 seconds, 16:9 landscape.

Use the approved Benjamin character reference and the established Barn_Exterior location reference. Preserve his older grey donkey appearance, charcoal mane, long upright ears, narrow muzzle and tired observant eyes.

Medium shot from outside the barn entrance. Benjamin stands quietly within the shadow of the doorway, with the red timber exterior visible around him. His ears respond subtly as he watches Boxer and Clover speaking off-screen in the farmyard. After a moment, he lowers his gaze slightly. His expression is reserved and knowing, never comic. Slow restrained push-in. No dialogue, no lip movement and no other character entering frame.

Serious cinematic 3D animated feature-film drama, natural donkey anatomy and subtle expression, detailed grey coat and charcoal mane, realistic 1940s English barn exterior, late dusk, 16:9 landscape. Preserve the approved reference exactly. No text, subtitles, logos, watermark, extra limbs or duplicate animals.
~~~

### Shot 006 — Night Settles over the Farm (10 seconds)

**References:** Boxer, Clover, Benjamin, Manor_Farm_Exterior and Barn_Exterior.  
**Framing / action:** Wide rear three-quarter view; slow pull-back, barn entrance is the visual destination. The three animals turn toward the barn and begin moving toward it. Dusk deepens toward blue night. A soft warm light is visible through the doorway. Do not show Old Major or the meeting.  
**Dialogue:** None. No narrator.  
**Sound:** Evening wind softens; quiet timber creak; music can be added later in the NLE.

~~~text
SHOT ID: ACT01_SCENE003_SHOT006_V01
Duration: 10 seconds, 16:9 landscape.

Use the approved Boxer, Clover and Benjamin references with the established Manor_Farm_Exterior and Barn_Exterior locations. Preserve the same character designs and relative proportions. Boxer remains the largest and most muscular; Clover is sturdy but lighter-built and completely unharnessed; Benjamin is visibly shorter and slimmer.

Wide rear three-quarter view of the three animals in the farmyard at the end of dusk. They quietly turn their attention toward the old red barn entrance and begin moving toward it. The sky deepens into cool blue night while a soft warm glow is visible through the barn doorway. Slow continuous camera pull-back, ending with the barn entrance as the visual focus. Do not show Old Major, do not show the night meeting, and do not introduce any new identifiable characters. No dialogue and no narrator.

Serious cinematic 3D animated feature-film drama, natural animal anatomy and measured movement, detailed coats and weathered timber, atmospheric transition from dusk to blue night, consistent 1940s English farm geography, 16:9 landscape. Preserve all approved references exactly. No text, subtitles, logos, watermark, extra limbs or duplicate animals.
~~~

**Voice capability note (Flow Agent report, 6 November 2026):** Built-in voice presets are reported as selectable in the Flow UI; no saved custom voice-reference audio assets were found in the project. Exact spoken-line generation and lip-sync are not guaranteed. Plan to inspect/test voice and lip-sync in the UI only after the dialogue is approved; use post-production dubbing if needed.

## 4. Approved dialogue cue sheet — owner approved 6 November 2026

These are proposed original lines, not quotations from the source novel and not approved screenplay canon.

| Cue | Shot | Speaker | Draft line | Voice direction | Status |
|---|---|---|---|---|---|
| S003-DLG-001 | SHOT003 | Clover | “You have carried enough for one day, Boxer.” | Warm, calm, concerned female voice | OWNER APPROVED 6 Nov 2026 |
| S003-DLG-002 | SHOT004 | Boxer | “The work still needs doing, Clover.” | Sincere, gentle male baritone | OWNER APPROVED 6 Nov 2026 |

The exact text and speakers are approved. Keep each line assigned only to its named speaker; do not improvise, paraphrase or add words. Voice choice and lip-sync execution remain subject to the separate production workflow and review.

## 5. Audio and edit notes

- No narrator is written for this scene; the narrator profile remains unapproved.
- Keep character dialogue separate from music and effects where possible.
- Suggested ambience: evening wind, subtle harness movement, one cart creak, horse breathing and barn timber creak.
- Existing cue IDs such as SFX_001, SFX_004 and SFX_006 are cue names, not proof that standalone audio files exist.
- Use restrained ambience. Do not let music overwhelm Clover's concern or Boxer's answer.
- Six 10-second shots in order; target exactly 60 seconds. Use clean cuts unless the editor deliberately compensates for overlap.
- Final scene assembly and audio mix are post-production tasks.

## 6. Generation gate — mandatory

Before generating any shot, the Flow Agent must:

1. Confirm that the three character references and both exterior locations can be selected as Ingredients; report exact asset names/IDs.
2. Confirm the hay-cart continuity reference can be used for Shots 001–002; do not redesign the cart.
3. Show the final prompt, selected references, model, resolution, aspect ratio, duration, output count and live displayed credit cost for the specific shot.
4. Identify whether the selected Flow mode generates spoken audio for Shots 003–004 and confirm the character voices. Do not silently substitute voices.
5. Dialogue lines were owner-approved; the owner also separately authorized one Shot001 output subject to the exact 10-credit live preflight. That one-shot authorization has now been consumed.
6. Generate one output for one shot only after authorization. The Shot001 authorization has been used; obtain a new explicit authorization for any other shot or retake.
7. Retrieve the actual MP4, verify duration/resolution/frame rate/audio, review continuity, then request approval before proceeding.
8. Never mark a queued or generated clip approved without owner review.

**Current authorization:** The single Shot001 authorization was consumed by the reported generation. The output remains awaiting owner review. No retake, Shot002, or other generation is authorized.


## 7. Shot 001 execution result — 6 November 2026

**Status:** OWNER ACCEPTED FOR EDITING — COLOR MATCH REQUIRED (6 November 2026)

Flow Agent execution report:
- Asset name: `Boxer stopping cart by barn`
- Flow media ID: `8a46a89f-c131-4f63-868a-c729b7bf8c7c`
- Target collection: `04_ACT_01_The_Old_World`
- Actual credits charged (reported): **10**
- Outputs: exactly one
- Duration: 10.00 seconds
- Resolution: 640×360 (360p)
- Aspect ratio: 16:9 landscape
- Frame rate: 24.00 fps
- Audio: present; native Omni Flash ambient audio bed enabled
- Prompt: Flow Agent reports the locked prompt was used verbatim
- Ingredients: Flow Agent reports all six locked references were attached

The actual uploaded MP4 was inspected in this conversation. The owner accepted V01 for retention/editing and decided against a retake; the lighting mismatch with Scene 002 Shot 006 is assigned to NLE color matching. This is source-shot acceptance, not confirmation that the color grade or final Scene 003 assembly is complete. Native audio stream presence is verified; detailed listening review remains a separate check.


## 8. Owner transition decision and Shot 002 preparation — 6 November 2026

- Scene 002 Shot 006 V02 (`e3c06bbd-2245-427a-8fbd-3b9bbd1cf891`) is officially approved and locked as the final Scene 002 shot; owner-reported metadata: 10s, 1280×720, 24fps, 16:9, AAC stereo.
- Transition audit: Scene 002 Shot 006 ends in deep blue twilight; Scene 003 Shot 001 V01 opens brighter/overcast and is 360p. Character, cart/harness and barn identity continuity are accepted.
- Owner decision: retain Scene 003 Shot 001 V01 (`8a46a89f-c131-4f63-868a-c729b7bf8c7c`); no retake and no additional generation credits. Apply cool-blue color temperature, modest exposure/contrast matching and subtle vignette only if editorially appropriate in the NLE. This grade has not yet been applied or reviewed.
- Next task: prepare/preflight Scene 003 Shot 002 only. No generation is authorized. Preserve the one-shot-at-a-time rule and obtain explicit approval against the exact live price before rendering.
