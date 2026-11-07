# Production Agent Instructions

Project: **Animal Farm — The Price of Power**. 30-minute serious cinematic 3D animated drama set on a 1940s English farm. Use natural animal anatomy, realistic fur/bristles/wool, restrained expressions and believable motion; avoid childish or slapstick styling.

## Start-up: minimum context

Read only:
1. `README.md` for current milestone and file routing.
2. `00_FILM_BIBLE/PRODUCTION_TRACKING/01_MASTER_PROGRESS_TRACKER.md` for next action.
3. The active scene's `SCENE_BREAKDOWN.md` for the requested shot/task.
4. Relevant rows in `02_SHOT_REGISTER.csv`; consult `03_ASSET_REGISTER.csv` only for required assets.

Do not scan all folders, read the original blueprint, or reopen completed scenes unless the task requires it. Do not recreate status summaries already in the tracker/registers.

## Continuity

- Approved character, location and prop references are locked. Do not redesign identity, anatomy, markings, proportions, wardrobe or geography.
- Distinguish permanent design from temporary shot-specific props/costume. Boxer's work harness is temporary; Clover remains unharnessed unless the active shot explicitly says otherwise.
- Use only references and exact prompt specified by the active scene breakdown. No silent substitutions or extra assets.
- Respect story order. Do not introduce later characters, locations or events early.

## Generation authorization gate

- Default: exactly **one output per shot**; no batches, variants, previews, retries or retakes.
- This default is not permission. Obtain separate explicit owner authorization for the exact shot before generating.
- Immediately before Generate, verify live displayed price, model/mode, resolution, aspect ratio, duration, output count, exact references and verbatim prompt.
- If any detail differs or is unavailable, stop and report. Never estimate credits or silently change inputs.
- After generation, report only observed/reported facts: media ID, asset name, actual displayed charge, settings, references, prompt confirmation and technical metadata.
- Do not mark a render approved. Await owner review. Distinguish Flow-reported information from independently inspected media.

## Updates

Update only the canonical record affected:
- Shot/version/status/Flow ID/charge/review → `02_SHOT_REGISTER.csv`
- New reusable asset → `03_ASSET_REGISTER.csv`
- Project totals/next milestone → `project_status.json` and `01_MASTER_PROGRESS_TRACKER.md`
- Story/prompt/continuity → active `SCENE_BREAKDOWN.md`
- Major owner decision → append to `09_CHANGE_HISTORY.csv`

No duplicate diaries, checklists or full-history reports. Use `11_AGENT_STATUS_UPDATE_TEMPLATE.md` only when a user-facing execution report is requested. Group related edits into one commit.

