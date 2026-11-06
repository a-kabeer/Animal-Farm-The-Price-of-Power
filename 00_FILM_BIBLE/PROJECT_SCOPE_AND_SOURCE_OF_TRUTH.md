# Project Scope and Source of Truth

**Project:** Animal Farm — The Price of Power  
**Target runtime:** 30 minutes  
**Production platform:** Google Flow; final editorial sound mix in CapCut or DaVinci Resolve  
**Tracking baseline:** 6 November 2026

## Source-of-truth hierarchy

1. User-approved Film Bible and master visual references.
2. User-approved scene and shot breakdowns, including exact durations and selected versions.
3. `00_FILM_BIBLE/PRODUCTION_TRACKING/` — status, registers, decisions, costs and next actions.
4. The Shot Register and Flow asset IDs for the approved versions; approved video binaries are intentionally excluded from this GitHub package.
5. Google Flow collections — original generated media and Agent-reported Flow asset records.

## Important project state

- Two one-minute working scenes have six individually approved shots each.
- These two working scenes provisionally cover minutes 00:00–02:00 of master sequence S01 — The Hungry Farm (00:00–03:00). This mapping is a working interpretation of the story content and must be confirmed in the screenplay/sequence plan.
- Scene 001 has an uploaded 60-second 360p source MP4 and a 1080p upscale in the working production workspace. Their binaries are intentionally excluded from this GitHub package. Technical metadata is recorded; final editorial sign-off remains pending.
- Scene 002 has six approved individual shots; their binaries are intentionally excluded from this GitHub package. Its assembled master MP4 has not been supplied/verified in the project record.
- Full dialogue, narrator script, and final sound mix are not yet written/approved.

## Status vocabulary

- `APPROVED`: user reviewed the actual media and approved this exact version.
- `AGENT-REPORTED`: Flow Agent stated an asset was saved; local binary/Flow UI verification is not available here.
- `PENDING`: not completed or not reviewed.
- `NEEDS CONFIRMATION`: evidence is incomplete or ambiguous.
- `REJECTED/SUPERSEDED`: retain for audit only; never include in final assembly.

## ChatGPT tracking limitation

This repository is the persistent project record that the user can re-upload or reference in future conversations. There is no automatic live synchronization from this repository to Google Flow. When returning to the project, provide the latest repository ZIP or updated tracker files and any new media. Update all relevant registers after each generation, review, approval, rejection, asset lock or export.
