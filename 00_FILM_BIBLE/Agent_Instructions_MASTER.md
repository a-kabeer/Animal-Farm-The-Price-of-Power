# Production Agent Instructions

Project: Animal Farm — The Price of Power. 30-minute serious 3D animated drama set on a 1940s English farm.

## Read only what the task needs
1. README.md — current milestone and routing.
2. 00_FILM_BIBLE/PRODUCTION_TRACKING/01_MASTER_PROGRESS_TRACKER.md — current status / next action.
3. The active scene's SCENE_BREAKDOWN.md — current prompt, references and lessons.
4. Relevant rows in 02_SHOT_REGISTER.csv.
5. 03_ASSET_REGISTER.csv only when checking reusable asset IDs.

Do not scan the repository, reread completed scenes, open the original blueprint, or repeat status summaries unless required. Keep previous shot versions to short outcome notes; retain only the current full prompt.

## Owner / Google Flow boundaries
- A prompt, audit, preflight report, or request to check/review means review only. Never treat it as generation authorization or issue an "Execute" command.
- Record generation only after the owner reports it or provides the output. Do not claim to operate Google Flow unless a Flow tool is actually available and used.
- Keep states distinct: prompt drafted → preflight passed → owner generated → owner reviewed / approved / rejected.
- A live price quote is neither an actual charge nor authorization.
- Never mark a generated shot approved without an explicit owner decision.

## Mandatory Shot001 failure lessons
These four attempts exposed different failure modes. Do not repeat them.

- V01: cows/sheep were vague or absent because they were described as background silhouettes and their group references were missing. Exact counts and approved group references must be explicit.
- V02: six references and a four-sheep instruction still produced only three distinguishable sheep early and two later. Text counts do not guarantee temporal continuity.
- V03: a fixed all-nine-at-frame-zero layout still produced only one visible cow and three sheep. The three main characters were already inside at the first frame, and the barn doors were already open. The requested entrance action was missing.
- Do not assume a static composition or a repeated count sentence will force the model to obey. Give explicit screen positions, action order, time windows and review checkpoints.

## Shot001 V04 sequence rules
The story action is: six animals wait inside; the barn gate opens; Boxer, Clover and Benjamin enter afterward.

- Start with exactly SIX residents already inside and visible: exactly TWO separate black-and-white cows on the left, and exactly FOUR separate white sheep on the right in one straight row at the same camera depth. Each animal must have a distinct visible head and full body; gaps between all individuals; no overlap, crop, shadow, post or trough obstruction.
- At frame 0, the heavy double barn entrance doors / gate must be fully CLOSED. The central entry lane is empty. Boxer, Clover and Benjamin are outside and must NOT appear in the barn or doorway.
- Show the gate visibly opening first. Do not show any of the three characters until both doors have finished opening.
- Only after the gate is fully open: Boxer enters first, Clover second, Benjamin third. Each crosses the threshold once, with visible separation; no teleporting, duplicating, swapping order or appearing inside before entry.
- Keep the two cows and four sheep stationary and visible during the entire door-opening and character-entry action. At the end, show exactly nine animals: two cows + four sheep + Boxer + Clover + Benjamin.
- Do not write "exactly nine animals in every frame" for this staged entrance: the intended visible interior count is six before entry, then seven, eight and nine as the three characters enter.
- Use one locked wide camera inside Main_Barn that shows the closed doors, both resident groups and a clear central entry lane. The entrants must not block the cow or sheep groups.
- Use exact approved references only: Boxer 7e912af3-0d8f-45d1-8c7a-bfffa6cee3ba; Clover b86cb0af-a9e4-4d02-8b25-0316f718481b; Benjamin 0595b453-1a9c-4c11-9359-fd79a6eeb951; The_Cows 29b393f6-15b1-4a74-bcba-8c23b73360f5; The_Sheep 0b75ce22-ee53-439b-9ca0-4d051731a362; Main_Barn a9354e0f-70dc-4f02-8567-de36d2ab41ab. Never use rejected V01/V02/V03 videos as ingredients.
- Audio must follow visible action: latch only when released; hinge/wood creak only while doors move; outside wind swells after doors open; hoofbeats and straw crunch only while each character visibly walks; footfalls stop when the character stops. Add only quiet barn ambience and restrained, plausible cow/sheep sounds. No off-screen animals, dialogue, narration or music.
- If a ten-second clip cannot clearly show the six residents, opening gate and three separate entries, redesign timing/framing before generation. Do not sacrifice count clarity for rushed action.
- Before spending video credits on another count-critical shot, prefer an owner-approved still composition check showing all six waiting animals, closed doors and clear entry lane. If that still costs credits, disclose the live price and obtain separate owner approval first.
- Review count and action order at opening, gate opening, each character's entry, middle and end. Missing/merged/hidden/duplicated animals or wrong order = continuity failure; do not approve.

## Continuity
- Approved character, location and prop references are locked. Preserve identity, anatomy, proportions, coat markings and geography.
- Boxer's work harness is temporary; Clover remains unharnessed unless the active shot says otherwise.
- Respect story order. Ignore assets/CONCEPT_ARCHIVE_NOT_MASTER/ unless owner requests archive review.

## Generation preflight
Before any separately authorized generation, verify live model/mode, resolution, aspect ratio, duration, output count, exact reference attachments, verbatim prompt and displayed price. Stop if anything differs. Default to one output; no batches, previews, retries or retakes unless separately approved. Never assume the previous price still applies.

## Update only canonical records
- Shot/version/status/Flow ID/charge/review → 02_SHOT_REGISTER.csv
- Project totals/next milestone → project_status.json and 01_MASTER_PROGRESS_TRACKER.md
- Prompt, continuity and failure lessons → active SCENE_BREAKDOWN.md
- New reusable asset → 03_ASSET_REGISTER.csv
- Major owner decision → append one concise row to 09_CHANGE_HISTORY.csv

Group related edits into one logical commit. Do not create duplicate diaries, checklists, full-history documents or repeated prompt copies.
