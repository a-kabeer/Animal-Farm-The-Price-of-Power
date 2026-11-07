# Production Agent Instructions

Project: **Animal Farm — The Price of Power**. 30-minute serious 3D animated drama set on a 1940s English farm.

## Read only what the task needs

For routine production work, read:
1. `README.md` — current milestone and routing.
2. `00_FILM_BIBLE/PRODUCTION_TRACKING/01_MASTER_PROGRESS_TRACKER.md` — current status/next action.
3. The active scene's `SCENE_BREAKDOWN.md` — current prompt, references and shot-specific lessons.
4. Relevant rows in `02_SHOT_REGISTER.csv`.
5. `03_ASSET_REGISTER.csv` only when checking reusable asset IDs.

Do not scan the repository, reread completed scenes, open the original blueprint, or repeat status summaries unless the task explicitly requires it. The active scene breakdown is not an archive: keep previous versions as short outcome notes, not full duplicate prompts.

## Non-negotiable owner / Flow boundaries

- A prompt, audit, preflight report, or request to "check/verify/review" means **review only**. Do not treat it as generation authorization, do not issue an "Execute" command, and do not imply that the owner authorized spending.
- Only record a Flow generation after the owner reports that it was generated or supplies an execution report/media. Never claim to click Generate or operate Flow unless an actual Flow tool is available and used.
- Keep four states distinct: **prompt drafted → preflight passed → owner generated → owner reviewed/approved or rejected**. A live credit quote is not a charge or authorization.
- If the owner says a shot was generated but omits the execution report, record only "owner-reported generated; media ID/cost/output details pending". Do not invent a media ID, actual charge, approval or quality result.
- Never mark a generated shot approved without an explicit owner review decision.

## Failure prevention: exact animal counts

Treat the Scene004 Shot001 V01/V02 failures as mandatory lessons; do not repeat their approach.

- **V01 failure:** cows/sheep were described vaguely as background silhouettes and were not clearly visible. Do not use phrases such as "a few animals", "other animals", "background animals" or "animal silhouettes" when an exact group matters. Name every group, exact count, approved group reference and screen position.
- **V02 failure:** despite six references and a "four sheep" instruction, only three sheep were distinguishable early and only two later. A text count by itself did not preserve the group through motion. Do not assume that a correct opening frame guarantees count continuity.
- **V03 count-safe layout:** keep exactly nine animals in separate zones: two cows on the left, Boxer/Clover/Benjamin in the centre, four sheep on the right. The four sheep must be in one straight horizontal row at the same camera depth, with a visible gap between every animal and all four full bodies, heads, necks and legs readable. No staggering, line-of-sight overlap, posts/troughs/shadows obscuring animals, or edge cropping.
- All nine animals must already be in position at frame 0. For strict-count shots, no animal walks, enters, exits, crosses, changes place or passes behind another. Use a locked wide tripod camera; no dolly, pan, tilt, zoom, cut or reframing. Permit only tiny breathing/blinking/ear movement.
- Use the exact approved master references. For this shot: Boxer `7e912af3-0d8f-45d1-8c7a-bfffa6cee3ba`; Clover `b86cb0af-a9e4-4d02-8b25-0316f718481b`; Benjamin `0595b453-1a9c-4c11-9359-fd79a6eeb951`; The_Cows `29b393f6-15b1-4a74-bcba-8c23b73360f5`; The_Sheep `0b75ce22-ee53-439b-9ca0-4d051731a362`; Main_Barn `a9354e0f-70dc-4f02-8567-de36d2ab41ab`. Never substitute, silently omit, or use rejected V01/V02 videos as ingredients.
- Before spending video credits on a count-critical scene, prefer a still composition check using the approved references: verify all nine animals and their separation in one frame first. If still-image generation costs credits, report its live price and obtain the owner's separate approval before spending. Do not skip this check silently; if no approved still is available, state that risk before recommending video generation.
- If the selected resolution cannot make every animal individually countable, stop and propose a clearer composition/resolution or separate coverage; do not hide the problem in a prompt.
- After generation, inspect the opening, middle and ending, plus representative points (0s, 2s, 4s, 6s, 8s and near the end). Count the animals at each point. Any missing, merged, obscured, duplicated or changing animal is a continuity defect: do not approve the shot; record the exact failure and wait for owner direction.

## Continuity and visual rules

- Approved character, location and prop references are locked. Preserve identity, anatomy, proportions, coat markings and geography.
- Distinguish permanent design from temporary shot props/costume. Boxer's work harness is temporary; Clover remains unharnessed unless the active shot says otherwise.
- Respect story order. Do not introduce later characters, locations or events early.
- Ignore `assets/CONCEPT_ARCHIVE_NOT_MASTER/` for production unless the owner explicitly requests archive review.

## Generation preflight

Before any owner-authorized generation, verify the live model/mode, resolution, aspect ratio, duration, output count, exact reference attachments, verbatim prompt and displayed price. Stop if anything differs. Default to exactly one output; no batches, previews, retries or retakes unless separately approved. Do not estimate or assume current prices.

## Update only canonical records

- Shot/version/status/Flow ID/charge/review → `02_SHOT_REGISTER.csv`
- Project totals/next milestone → `project_status.json` and `01_MASTER_PROGRESS_TRACKER.md`
- Prompt, continuity and failure lessons → active `SCENE_BREAKDOWN.md`
- New reusable asset → `03_ASSET_REGISTER.csv`
- Major owner decision → append one concise row to `09_CHANGE_HISTORY.csv`

Group related edits into one logical commit. Do not create duplicate diaries, checklists, full-history documents or repeated prompt copies. Keep historical versions to a short outcome, media ID and failure note; retain the current prompt only.
