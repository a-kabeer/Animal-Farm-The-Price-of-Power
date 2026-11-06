# ANIMAL FARM — THE PRICE OF POWER
## Google Flow Production Blueprint | 30-minute animated short film

**Production approach:** Google Flow for character creation, video generation, generated clip audio, and scene assembly; CapCut or DaVinci Resolve for final dialogue/music/SFX mixing and final export.

**Important:** A 30-minute movie will not be generated with one prompt. At 10 seconds per generated clip, the absolute minimum is 180 clips. Plan for additional takes, transitions, and cutaways.

---

## 1. Project setup in Google Flow

1. Open **https://flow.google.com/** in Chrome on a computer.
2. Create a new project named:
   `ANIMAL FARM — THE PRICE OF POWER — 30M`
3. Set up these collections (Flow supports nested collections):

```text
00_FILM_BIBLE
01_CHARACTERS
   Old_Major
   Napoleon
   Snowball
   Squealer
   Boxer
   Clover
   Benjamin
   Mr_Jones
   Supporting_Animals
02_LOCATIONS
   Manor_Farm_Exterior
   Main_Barn
   Farmhouse
   Windmill
   Fields_And_Orchard
03_PROPS_AND_SYMBOLS
04_ACT_01_The_Old_World
05_ACT_02_Rebellion
06_ACT_03_The_New_Order
07_ACT_04_Fear_And_Windmill
08_ACT_05_The_Final_Betrayal
90_AUDIO_AND_MUSIC
99_APPROVED_SCENES
```

4. Use **16:9 landscape** for the film.
5. For the main character shots, start with **Gemini Omni Flash 1.1, 720p, 10 seconds** where available. It supports Ingredients-to-Video at 4, 6, 8, and 10 seconds and supports voice references. Use 360p for cheap tests if available; use 720p for approved final shots.
6. Before generation, check the displayed credit price in Flow's model/settings menu. Costs can change.
7. In project Settings, make sure **Return silent videos** is OFF when you want generated sound.

### Which model to choose

| Use | Model | Why |
|---|---|---|
| Main character scenes | Gemini Omni Flash 1.1 | Ingredients, 10-second clips, reusable voice references, video editing |
| Extending a Veo clip | Veo 3.1 Lite | Supports 8-second Veo clip extension |
| Reference-free landscape / establishing shots | Veo 3.1 Quality or Fast | Good option when no character ingredient is needed; Quality does not support Ingredients-to-Video |

For this character-driven film, prioritize **Omni Flash with Ingredients**. Do not choose Veo 3.1 Quality for shots that require character reference ingredients.

---

## 2. Paste this into Flow Agent Instructions

In the project prompt box, turn on **Agent**. Open **Agent Instructions** and add the following project-wide instruction. Add the clean character/location reference images as Agent context when available.

```text
You are the production assistant and continuity supervisor for a 30-minute cinematic 3D animated adaptation titled “Animal Farm: The Price of Power.”

VISUAL STYLE
Create a serious cinematic animated drama set on a working English farm in the 1940s. Use natural animal anatomy, realistic fur/bristle/feather textures, expressive but restrained faces, physically believable movement, detailed rural environments, atmospheric lighting, warm earthy colors, and feature-film composition. The mood is dramatic and emotionally grounded, never silly or slapstick.

CONTINUITY RULES
1. Treat saved Flow Characters as locked character designs. Do not alter species, age, body size, coat color, face shape, markings, eye color, or distinctive features.
2. Reuse the same saved character assets and their attached voices in every relevant shot.
3. Treat saved location assets as fixed sets. Preserve barn layout, farmhouse appearance, windmill design, fences, weather, and time-of-day continuity unless the shot description explicitly changes them.
4. Do not introduce new clothing, jewelry, props, markings, or accessories unless the shot asks for them.
5. When a shot has dialogue, identify exactly who speaks. Do not make another character speak. Keep dialogue short enough for the clip duration. Do not invent extra dialogue.
6. Keep each generation focused on one shot, one main action, and one camera setup. Avoid packing multiple scene changes into one clip.
7. Use English for prompts and spoken dialogue. Keep dialogue natural and period-appropriate.
8. Avoid on-screen captions, subtitles, logos, watermarks, and illegible writing. Add titles and subtitles later in the video editor.
9. Prefer 16:9 landscape. Generate a clean establishing shot, medium shot, close-up, reaction shot, or insert as specified.
10. When continuity matters, use Ingredients-to-Video or a saved start frame. Match the prompt to the supplied references; never contradict them.

WORKFLOW
Before generating a sequence, help me divide it into individual shots. For each shot, provide: shot ID, duration, characters/assets required, camera framing and movement, visible action, exact dialogue (if any), sound/ambience, and a concise Flow-ready prompt. Do not generate media until I ask you to generate that shot or batch.
```

---

## 3. Create reusable characters in Flow

For each main character:

1. Open **Characters** on the left.
2. Click **New Character**.
3. Enter the character description below.
4. Upload or generate 1–2 clean reference images showing only that character. Avoid using the full text-heavy collage as the actual ingredient; use a clean portrait or crop of the individual character.
5. Generate the character, give it the exact name below, select/create a voice, add its character information, and click **Done**.
6. In later prompts, refer to the saved character with `@Old Major`, `@Napoleon`, etc. (Use the exact asset name shown in your project.)

### Character descriptions

**OLD MAJOR**
```text
An elderly, large white boar with coarse silver-white bristles, a broad kind face, slightly drooping ears, visible lower tusks, wise deep-set eyes, and a dignified but physically aged body. Calm, compassionate, thoughtful presence. Preserve this exact design in every shot.
```
Voice direction: elderly male, deep and warm, slow measured delivery, gentle authority, slight gravel in the voice.

**NAPOLEON**
```text
A large, heavy, powerful black Berkshire boar with dense charcoal-black bristles, a broad blunt snout, small watchful eyes, thick neck, and a physically imposing body. His expression is controlled, calculating, and intimidating. No clothing or accessories. Preserve this exact design in every shot.
```
Voice direction: adult male, low register, controlled, clipped phrases, cold authority, rarely raises his voice.

**SNOWBALL**
```text
A lean, agile pale-pink pig with short clean bristles, a narrow intelligent face, alert upright ears, bright attentive eyes, and energetic posture. He looks idealistic, articulate, and active rather than intimidating. Preserve this exact design in every shot.
```
Voice direction: adult male, clear mid-range voice, quick thoughtful delivery, persuasive and energetic.

**SQUEALER**
```text
A short, round pink pig with soft pale bristles, round cheeks, a small snout, quick darting eyes, and round spectacles. Expressive and ingratiating, with a practiced public-speaking smile. Preserve spectacles and body proportions in every shot.
```
Voice direction: adult male, higher mid-range, fast persuasive delivery, polished and falsely reassuring.

**BOXER**
```text
A very large, muscular chestnut-brown working horse with a broad chest, strong legs, a dark mane, gentle brown eyes, and a distinctive white blaze down the face. He looks powerful but kind and tired. Preserve the same blaze and body shape in every shot.
```
Voice direction: adult male, warm baritone, sincere, simple phrasing, steady and gentle.

**CLOVER**
```text
A sturdy chestnut mare with a lighter golden-brown mane, soft brown eyes, a gentle face, and a protective maternal presence. Natural horse anatomy; no human clothing. Preserve exact coat and mane colors.
```
Voice direction: adult female, warm, calm, empathetic, slightly concerned.

**BENJAMIN**
```text
An older grey donkey with a charcoal mane, long upright ears, a narrow muzzle, deep-set tired eyes, and a reserved, skeptical expression. Lean but sturdy body. Preserve his grey coat and dark mane in every shot.
```
Voice direction: older male, dry low voice, restrained, slow, wry but not comic.

**MR JONES**
```text
A middle-aged English farm owner with a weathered face, unshaven beard, flat cap, worn brown work jacket, muddy boots, and a tired, neglectful expression. Human character; same face and outfit throughout the opening scenes.
```
Voice direction: adult male, rough, impatient, slurred only when drunk.

Optional supporting characters: Muriel (white goat, thin spectacles, intelligent face), Moses (black raven with glossy feathers), a small group of sheep, and two intimidating black-and-tan farm dogs.

---

## 4. Create reusable location ingredients

Create one clean wide reference image for each location, save it to the project, and reuse it as an Ingredient.

**MANOR FARM — EXTERIOR**
```text
A weathered 1940s English farm in a broad rural valley: old red timber barn, modest stone farmhouse, muddy farmyard, split-rail fences, orchard, animal paddocks, distant rolling fields. Overcast English sky, realistic rural detail, cinematic 3D animation, 16:9 wide establishing view. No people or animals in the reference image.
```

**MAIN BARN — INTERIOR**
```text
Interior of an old timber animal barn, rough wooden beams, hayloft, straw-covered floor, feeding troughs, dusty shafts of moonlight through gaps in the boards, large open central gathering space. 1940s English farm, cinematic 3D animated film environment, no animals in the reference.
```

**FARMHOUSE**
```text
A modest but worn English farmhouse from the 1940s, stone walls, small windows, wooden front door, dim warm interior, old furniture and a dining table. The house should feel human-owned and slightly neglected. Cinematic 3D animation.
```

**WINDMILL HILL**
```text
A grassy exposed hill on an English farm with a simple stone-and-timber windmill under construction, scaffolding, stacked stones, muddy track, distant fields and dramatic changing skies. Keep the windmill's design and hill layout consistent in all later shots.
```

**FIELDS AND ORCHARD**
```text
Wide English farm fields, grazing pasture, old orchard trees, wooden fences, muddy paths, hay stacks and distant hedgerows. Rural 1940s atmosphere, cinematic 3D animated feature film.
```

---

## 5. Global visual suffix for every video prompt

Append this at the end of each clip prompt:

```text
Serious cinematic 3D animated feature film, realistic animal anatomy and movement, detailed natural fur and bristles, expressive restrained facial acting, physically believable motion, 1940s English countryside, warm earthy color grading, dramatic natural lighting, film-quality composition, 16:9 landscape. Preserve all supplied character and location references exactly. No cartoon comedy, no extra limbs, no duplicate characters, no visual morphing, no random accessories, no text, no subtitles, no watermark.
```

### Flow prompt template for every shot

```text
SHOT ID: [A01_S01_C001]

Use @CharacterName and @LocationName as visual references. Preserve their saved appearance exactly.

SHOT: [wide / medium / close-up / over-the-shoulder / insert]
CAMERA: [locked / slow push-in / tracking / pan / crane]
ACTION: [one clear action that happens during this clip]
PERFORMANCE: [emotion and body language]
DIALOGUE: [exact words and speaker, or “no dialogue”]
SOUND: [specific ambience and sound effects; no music unless requested]
LIGHTING: [time of day and lighting]

[Append the global visual suffix.]
```

---

## 6. Full 30-minute story and scene structure

Target: **10 sequences × 3 minutes = 30 minutes.** With 10-second Omni Flash clips, plan around **18 clips per sequence = 180 clips minimum**. This is a runtime map, not a promise that every generation will produce a perfect 10-second usable take. Create extra takes where needed.

| Sequence | Time | Story beats | Main assets |
|---|---:|---|---|
| S01 — The Hungry Farm | 00:00–03:00 | Establish Manor Farm; Jones neglects the animals; Boxer and Clover discuss hardship; Benjamin observes. | Jones, Boxer, Clover, Benjamin, farm, barn |
| S02 — Old Major's Dream | 03:00–06:00 | Animals gather at night; Old Major explains their exploitation; he imagines a farm without human oppression; Napoleon watches silently. | Old Major, Napoleon, Snowball, Boxer, Clover, Benjamin, barn |
| S03 — The Rebellion | 06:00–09:00 | Jones forgets to feed the animals; hunger triggers revolt; animals drive Jones and his men away; the farm gate closes behind them. | Jones, dogs, all animals, farmyard |
| S04 — A New Order | 09:00–12:00 | Animals celebrate; Snowball and Napoleon organize the farm; commandments are painted; harvest is completed; early optimism. | Snowball, Napoleon, Squealer, Boxer, Clover, barn, fields |
| S05 — Two Visions | 12:00–15:00 | Snowball proposes the windmill; Napoleon opposes him; debate grows; Squealer influences the animals; tension rises. | Snowball, Napoleon, Squealer, sheep, barn, windmill hill |
| S06 — Napoleon Takes Control | 15:00–18:00 | Dogs chase Snowball away; Napoleon announces new leadership; meetings are ended; Squealer explains the new rules. | Napoleon, Snowball, Squealer, dogs, animals |
| S07 — Work and Propaganda | 18:00–21:00 | Windmill construction begins; food becomes scarce; Boxer works harder; sheep repeat slogans; hens resist the new demands. | Boxer, Clover, Napoleon, Squealer, sheep, hens, windmill |
| S08 — The Windmill and War | 21:00–24:00 | Storm damages the windmill; blame falls on Snowball; humans attack; animals fight back; the windmill is rebuilt at a cost. | Napoleon, Boxer, Snowball as blamed figure, animals, Jones/men, windmill |
| S09 — The Cost of Loyalty | 24:00–27:00 | Confessions and purges; animals become afraid; Boxer is exhausted and injured; a van arrives to take him away; Benjamin realizes the truth too late. | Napoleon, Squealer, Boxer, Clover, Benjamin, dogs, animals |
| S10 — The Final Betrayal | 27:00–30:00 | Pigs adopt human habits; farmhouse dinner with human farmers; animals watch through the window; final image reveals that oppressor and ruler have become indistinguishable. | Napoleon, Squealer, other pigs, human farmers, animals, farmhouse |

### Recommended shot mix within each 3-minute sequence

For 18 ten-second slots, use approximately:
- 3 establishing / environment shots
- 5 character action shots
- 5 dialogue or reaction shots
- 3 detail / insert shots (trough, painted rule, hoof, windmill, empty food bowl)
- 2 transitions or quiet emotional holds

Do not make every shot a talking close-up. Use reaction shots and visual storytelling to avoid excessive dialogue.

---

## 7. Generate each clip in Google Flow

For every shot:

1. Open the correct project and sequence collection.
2. Use the standard prompt box or Flow Agent. For repeatability, use the standard prompt box after the Agent Instructions have been saved.
3. Select **Video** and choose **Gemini Omni Flash 1.1**.
4. Choose **Ingredients** and add the required saved Characters and Location. Type `@` to select saved assets by name.
5. Paste the shot prompt from the shot template.
6. Select 16:9, the target duration (prefer 10 seconds for the main cut), and one output at first.
7. Generate. Review the result. Keep the best version and rename it using the shot ID, e.g. `A01_S01_C001_FarmEstablishing`.
8. Save the best still frame from a completed clip when you need a reference for the next shot. Use it as a start frame or Ingredient to help with visual continuity.
9. Repeat for the next shot. Do not generate all 180 in one unreviewed batch.

### Audio inside Flow

- Keep **Return silent videos** OFF.
- For a character's consistent voice, create/select a voice in the Character setup and attach it to that saved character.
- For Omni Flash, voice references are added through **Video → Ingredients → Add → Voices**; reference the chosen voice in the prompt using `@Voice` if the UI shows that option.
- When prompting dialogue, give one speaker and one short exact line per clip. Example: `BOXER speaks gently: “I will work harder.” No other character speaks.`
- Ask for relevant farm ambience and specific effects in the same clip (wind, hoofsteps, barn creaks, crowd reaction). Audio generation can be imperfect; review each output. Keep a separate clean narration/music track for final mixing.
- For shots needing precise long dialogue, generate/record the dialogue separately and sync it in CapCut or DaVinci Resolve rather than relying on a single video generation.

---

## 8. Assemble scenes in Flow Scenebuilder

1. On an approved clip, click **More → Add to Scene**.
2. Add the other clips for that sequence.
3. Open Scenebuilder.
4. Drag clips into the planned order.
5. Trim the start/end handles of each clip to remove weak frames.
6. Preview the full 3-minute sequence.
7. Download the scene.
8. Repeat for S01–S10.

Flow Scenebuilder is documented to sequence, reorder, trim, preview, and download scenes. Do the final multi-track sound mix in an external editor.

---

## 9. Final audio and movie assembly

Use CapCut Desktop or DaVinci Resolve for the final 30-minute edit.

Tracks:

```text
V1  Flow scene exports (S01 through S10)
A1  Character dialogue / recorded replacement dialogue
A2  Narrator voice-over
A3  Farm ambience and sound effects
A4  Background score / music
A5  Optional subtitles or captions
```

Final steps:
1. Import S01–S10 in order.
2. Place each scene export on the video track and check transitions.
3. Keep usable generated dialogue; replace unclear or inconsistent lines with separately generated/recorded dialogue.
4. Add narrator voice-over, ambience, sound effects, and music on separate tracks.
5. Lower music under dialogue; use silence deliberately for dramatic moments.
6. Add title card, end credits, and subtitles in the editor (do not ask the video model to generate readable text).
7. Export one MP4 in 16:9 at the editor's available 1080p setting.

---

## 10. Credit planning — check this before committing

Google's current published Flow credit table lists these example costs (the live UI is authoritative and prices can change):

- Omni Flash 720p, 10 seconds: **15 credits per generation**.
- Omni Flash 360p, 10 seconds: **7 credits per generation**.
- A 30-minute cut made from 180 ten-second clips therefore starts at about **2,700 credits at 720p** or **1,260 credits at 360p**, before retries, alternate takes, edits, and extensions.

This is a minimum planning estimate, not the full production budget. Make a 1-clip test first, inspect the cost in Flow, and do not generate the entire movie before approving the visual style and voices. Flow's official credit page lists 50 daily credits without a subscription, while its access page and account eligibility may still vary; trust the generation access and credit balance shown in your own account.

---

## 11. First test shot — copy into Flow

**Collection:** `04_ACT_01_The_Old_World`

**Shot ID:** `A01_S01_C001`

**Ingredients:** `@Manor_Farm_Exterior` (location only; no character needed)

**Prompt:**
```text
A 10-second cinematic establishing shot of Manor Farm in the English countryside in the 1940s. Begin with a wide view of the weathered red timber barn, the modest stone farmhouse, muddy yard, split-rail fences, and rolling fields beneath a cold overcast evening sky. The camera makes a very slow forward push toward the barn. Bare tree branches move slightly in the wind; a loose barn door creaks gently. The farm feels neglected, quiet, and oppressive. No dialogue, no visible people, no visible animals. Natural ambient wind and a faint wooden door creak only; no music.

Serious cinematic 3D animated feature film, realistic detailed rural environment, warm earthy color grading, dramatic natural lighting, feature-film composition, 16:9 landscape. Preserve the supplied Manor Farm location reference. No cartoon comedy, no text, no subtitles, no watermark.
```

Generate this one shot first. Check the look, movement, and audio. If it is acceptable, proceed to the character setup and the rest of S01.

---

## Official Google references

- Google Flow: https://flow.google.com/
- Getting started: https://support.google.com/flow/answer/16353333
- Create videos, Ingredients, Frames, and voice references: https://support.google.com/flow/answer/16353334
- Models and supported features: https://support.google.com/flow/answer/16352836
- Edit videos and Scenebuilder: https://support.google.com/flow/answer/16935718
- Projects, characters, assets, and collections: https://support.google.com/flow/answer/16935308
- Flow Agent: https://support.google.com/flow/answer/17093911
- Credits: https://support.google.com/flow/answer/16526234
- Supported regions: https://support.google.com/flow/answer/16353544

**Release note:** This is an adaptation of George Orwell's novel. Copyright status and adaptation rights can differ by country. Check the rules in every territory where you plan to publish or monetize the finished film, and do not copy scenes, dialogue, or designs from existing film adaptations.
