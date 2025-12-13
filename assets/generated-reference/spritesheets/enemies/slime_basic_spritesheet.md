# Asset Generation Record

**Generated:** 2025-12-11T22:22:07.366Z
**Tool:** generate_sprite_sheet_from_reference
**Output:** `/home/josh/idleopolis/game/ui/public/assets/generated/spritesheets/enemies/slime_basic_spritesheet.png`

## Prompt

```
Reference-based sprite sheet: Idle, Attack, Hit, Death
```

## Full Prompt (sent to API)

```
2048x2048 pixel game sprite sheet, 4 rows by 6 columns grid, 341x512 pixels per frame, 24 total frames, a round, gelatinous blue slime creature with glossy highlights, hand-drawn cartoon style.

Row 1 Idle: 6 frames the slime gently pulses, compressing and expanding its body slightly while remaining stationary.
Row 2 Attack: 6 frames the slime lunges forward, stretching its body into a teardrop shape before retracting back to its original form.
Row 3 Hit: 6 frames the slime ripples and compresses violently as if struck, temporarily losing its smooth shape before reforming.
Row 4 Death: 6 frames the slime loses cohesion, splattering outwards and dissolving into smaller droplets that fade away.

Pure white background #FFFFFF, no shadows, no ground, no speech bubbles, no floating symbols, no UI elements, character body only, character perfectly centered in each cell, identical canvas per frame, pixel-perfect grid alignment, clean cell edges, consistent side view, game-ready asset.
```

## Parameters

- **animations:** `["Idle","Attack","Hit","Death"]`
- **frames_per_animation:** `6`
- **rows:** `4`
- **columns:** `6`
- **style:** `undefined`
- **resolution:** `"2K"`
- **subdirectory:** `"spritesheets/enemies"`
- **filename:** `"slime_basic_spritesheet"`
- **background_removed:** `true`

## Reference Images

- `/home/josh/idleopolis/game/ui/public/assets/enemies/world-01-forest/Slime RPG Basic.png`
