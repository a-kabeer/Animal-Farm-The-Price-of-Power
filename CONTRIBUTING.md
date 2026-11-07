# Production Update Rules

Follow `00_FILM_BIBLE/Agent_Instructions_MASTER.md`. Keep updates in the existing source-of-truth files; do not create duplicate tracking documents.

- **Shot update:** edit the relevant row in `02_SHOT_REGISTER.csv` (status, version, Flow ID, charge, metadata, review).
- **New reusable asset:** also update `03_ASSET_REGISTER.csv`.
- **Project milestone/count:** update `project_status.json` and `01_MASTER_PROGRESS_TRACKER.md`.
- **Story/prompt/continuity change:** update only the affected `SCENE_BREAKDOWN.md`.
- **Major owner decision:** append one concise entry to `09_CHANGE_HISTORY.csv`.
- Commit related changes together.

## Integrity

- Never overwrite approved media; version new work (V02, V03…).
- A queued job is not a generated asset. Record actual output only after it exists.
- Only owner review can approve a version. Preserve rejected/superseded evidence.
- Record Flow IDs exactly. Label unverified reports as agent-reported.
- Never invent IDs, dialogue, costs, paths, approvals or missing metadata.
- Keep dialogue/narration separate from voice direction. Keep character master design separate from temporary props/costumes.
- Scene durations must equal the approved runtime.

Do not duplicate full history or status in PR descriptions, new checklists or diaries.
