# Flow Agent Execution Task — Scene 003 Shot 004

**Shot:** `ACT01_SCENE003_SHOT004_V01 — Boxer's Response`  
**Owner authorization:** 7 November 2026  
**Authorized scope:** EXACTLY ONE video output for exactly 10 credits, conditional on the final live UI recheck matching this audit.

## 1. Final live execution gate

The owner has authorized this shot for one generation based on the final pre-generation audit.

Immediately before clicking Generate, recheck the live Flow UI. Generate only if ALL items still match:

- Model: **Omni 1.2 Flash**
- Mode: **Reference-to-Video (R2V)**
- Resolution: **360p (640×360)**
- Aspect ratio: **16:9 landscape**
- Duration: **10 seconds**
- Output count: **exactly 1**
- Live displayed price: **exactly 10 credits**
- Exact three references remain attached: Boxer, Clover, Barn_Exterior (IDs below).
- The locked prompt from `FLOW_AGENT_PREPARATION_TASK_SHOT004.md` is entered verbatim and unchanged.

If ANY item differs, stop without generating and report the discrepancy. Do not reuse a stale quote. Do not substitute a reference, edit the prompt, or change settings.

## 2. Exact references

1. Boxer — `7e912af3-0d8f-45d1-8c7a-bfffa6cee3ba`
2. Clover — `b86cb0af-a9e4-4d02-8b25-0316f718481b`
3. Barn_Exterior — `3919fbb9-bf69-40e5-98f4-e02680cb077a`

Do NOT attach `BOXER_HAY_CART_CONTINUITY_REFERENCE`.

## 3. Locked shot and prompt

Use the complete canonical prompt verbatim from `FLOW_AGENT_PREPARATION_TASK_SHOT004.md`, section 5.

Shot framing: **medium close-up on Boxer as the primary subject; Clover's shoulder softly visible at the frame edge.** This is not a medium two-shot.

Exact approved dialogue, spoken only by Boxer:
> The work still needs doing, Clover.

Voice direction: warm adult male baritone, sincere, gentle and steady, simple phrasing. Clover remains silent. No narrator.

Native exact English speech and precise non-human lip-sync are not guaranteed. Do not invent alternate words. Report the actual dialogue/audio result after rendering; post-production dubbing and synchronization may be necessary.

## 4. Absolute generation limits

- Generate **exactly ONE** video output.
- Exact authorized price: **10 credits**; only proceed if live UI displays exactly 10 immediately before rendering.
- No batch, second take, variation, preview, automatic retake, retry or any additional credit spend.
- This authorization covers Shot004 only; do not generate Shot005 or any other shot.
- If generation fails, hangs, or produces an uncertain result, stop and report. Do not retry.
- The project default is one output per shot. Do not ask the owner to select output count.

## 5. After the one render

Return:
1. Media ID and asset name.
2. Actual output count (must be exactly one).
3. Actual credits charged (must be exactly 10).
4. Actual duration, resolution, aspect ratio and frame rate.
5. Video/audio codecs and audio-stream details.
6. Whether Boxer's exact line was spoken and whether synchronization is acceptable; explicitly identify any mismatch.
7. Confirmation that no extra output, preview, retry or other credit spend occurred.

Save the asset in `04_ACT_01_The_Old_World`. Mark it **GENERATED — AWAITING OWNER REVIEW**, never owner-approved. Stop after returning the asset and report.
