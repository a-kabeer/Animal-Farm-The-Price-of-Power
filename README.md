# Animal Farm — The Price of Power

30-minute cinematic 3D animated film production project. Google Flow is used for generation; final editing and audio work are handled in an NLE.

## Current status — 7 November 2026

**S01 — The Hungry Farm (00:00–03:00) is complete.** The owner confirms the three one-minute scenes have been merged into a ready three-minute master.

- Completed master sequences: **1 / 10**
- Completed working scenes: **3**
- Accepted source shots: **18**
- Completed runtime: **03:00 / 30:00 (10%)**
- Next: **S02 — Old Major's Dream (03:00–06:00)** — planning and character/location preparation.

The merged S01 master file is not stored in this repository. Its filename and technical export metadata are not yet recorded.

## Open only what the task needs

| Need | Canonical file |
|---|---|
| Current progress and next action | [Master Progress Tracker](00_FILM_BIBLE/PRODUCTION_TRACKING/01_MASTER_PROGRESS_TRACKER.md) |
| Machine-readable status | [project_status.json](00_FILM_BIBLE/PRODUCTION_TRACKING/project_status.json) |
| Approved versions, media IDs and review notes | [Shot Register](00_FILM_BIBLE/PRODUCTION_TRACKING/02_SHOT_REGISTER.csv) |
| Character/location/prop IDs | [Asset Register](00_FILM_BIBLE/PRODUCTION_TRACKING/03_ASSET_REGISTER.csv) |
| 10-sequence story outline | [Master Story Map](91_SCREENPLAY_AND_DIALOGUE/MASTER_STORY_MAP_30_MIN.md) |
| Current shot prompts | Each scene's `SCENE_BREAKDOWN.md` |
| Audio and approved dialogue | [Audio / Dialogue Tracker](00_FILM_BIBLE/PRODUCTION_TRACKING/04_AUDIO_DIALOGUE_AND_NARRATION.md) |
| Original production plan | [Original Blueprint](00_FILM_BIBLE/Animal_Farm_Google_Flow_Blueprint_ORIGINAL.md) |

## Fast update rule

For a normal shot update, use only:
1. `02_SHOT_REGISTER.csv` — status, Flow ID, charge report, metadata and review note.
2. `project_status.json` — current project/scene counts and next action.
3. `03_ASSET_REGISTER.csv` only when a new asset/reference is created.

Change a scene breakdown only when its story, prompt or continuity requirement changes. Add major owner decisions to `09_CHANGE_HISTORY.csv`. Update this README only when the project structure or milestone status changes.

## Production safeguards

- One output per shot by default; this is not generation permission.
- Every new render needs separate, explicit shot-specific owner authorization.
- Recheck the live Flow price, selectors, prompt and exact references immediately before Generate.
- Never estimate live credits or silently substitute references/prompts/settings.
- Mark a generated clip approved only after owner review. Owner-confirmed inclusion in a completed master supersedes an earlier shot-level pending state.
- Google Flow does not sync automatically with this repository; user-supplied Flow reports/media are recorded here.

Approved video binaries remain outside GitHub. Rejected/superseded media is retained in the audit-only folder.
