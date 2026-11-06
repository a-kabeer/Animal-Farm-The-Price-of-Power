# 07 — CREDIT & EXPORT REGISTER

## A. Estimated video-generation usage based on reported generations

This is a **modelled estimate**, not an official Flow billing statement. It is calculated from the per-shot estimates stated by the Agent in the conversation. The Flow credit balance/history is authoritative.

### Scene 001

| Shot | Generated versions reported | Estimated credits |
|---|---|---:|
| Shot 001 (12s) | V01 | 14 |
| Shot 002 (10s) | V01 + V02 + V03 | 30 |
| Shot 003 (10s) | V01 | 10 |
| Shot 004 (10s) | V01 | 10 |
| Shot 005 (8s) | V01 | 8 |
| Shot 006 (10s) | V01 | 10 |
| **Scene 001 estimate** | **8 video generations** | **82** |

Original approved-shot budget was 62 credits; Shot 002 required two additional 10-credit attempts, adding an estimated 20 credits.

### Scene 002

| Shot | Generated versions reported | Estimated credits |
|---|---|---:|
| Shot 001 (12s) | V01 | 14 |
| Shot 002 (10s) | V01 | 10 |
| Shot 003 (10s) | V01 | 10 |
| Shot 004 (10s) | V01 | 10 |
| Shot 005 (8s) | V01 + V02 | 16 |
| Shot 006 (10s) | V01 + V02 | 20 |
| **Scene 002 estimate** | **8 video generations** | **80** |

Original approved-shot budget was 62 credits; Shot 005 V02 adds an estimated 8 credits and Shot 006 V02 adds an estimated 10 credits.

### Combined

| Item | Estimated credits |
|---|---:|
| Scene 001 reported video generations | 82 |
| Scene 002 reported video generations | 80 |
| **Estimated total to date** | **162** |

**Not included:** image generation, which the Agent reported as zero under the account's Pro/Plus entitlement; actual image charges are not independently verified. Also not included: upscale/export costs, any unreported retries, taxes/subscription charges, or any discrepancy between estimated and actual Flow charges.

## B. Export file verification

The following local files were checked with media metadata tools on 6 November 2026:

| File | Duration | Resolution | FPS | Codecs | Status |
|---|---:|---|---:|---|---|
| `Untitled_Scene_11-06_10_46_40_20261106155030.mp4` | 60.000s | 640×360 | 24 | H.264 + AAC stereo, 48kHz | Source video exists; likely Scene 001 source upload; check full content against approved shot list |
| `Animal_Farm_Scene_001_Full_HD_1080p.mp4` | 60.000s | 1920×1080 | 24 | H.264 + AAC stereo, 48kHz | Full HD upscale exists and metadata is verified; not yet independently confirmed that edit, title and audio meet the assembly sheet |

### Scene 002 clip outputs available locally in this session

- Shot 001: `Horse_pulling_cart_through_mud_d86c8a63.mp4` (12s)
- Shot 002: `Horses_walking_alongside_hay_cart_d3a61af9.mp4` (10s)
- Shot 003: `Donkey_walking_across_muddy_farm…_86a3c252.mp4` (10s)
- Shot 004: `Boxer_exhaling_breath_vapor_844bd6fb.mp4` (10s)
- Shot 005 V02: `Cows_and_sheep_looking_expectantly_93a65a39.mp4` (8s)
- Shot 006 V02: `Horses_pulling_cart_at_dusk_e3c06bbd.mp4` (10s)

The files above are available in this current working session. They are not evidence that ChatGPT has a live link to your Google Flow project.

## C. Final quality target

- Scene masters: 1920×1080 (Full HD), 16:9, target 24fps, MP4/H.264 with AAC audio.
- For 360p source footage, upscaling increases output dimensions but cannot restore native detail that was not generated.
- Confirm exact duration after edit; transitions/crossfades may alter total runtime unless clip lengths are adjusted accordingly.
