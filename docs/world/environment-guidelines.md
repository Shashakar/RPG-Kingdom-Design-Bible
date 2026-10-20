# Environmental composition guide

**Status:** Proposed review rubric, not an approved final art style.

## Visual hierarchy

From the third-person gameplay camera, the eye should find: **destination → traversable route → interactable objects → supporting environment**. Natural composition should guide rather than obscure.

### Ground and materials

- Use distinct material families for roads, soil, grass, rock, and architectural foundations.
- Blend transitions according to geography and wear rather than arbitrary straight boundaries.
- Maintain visual continuity across adjacent terrain tiles and at scene boundaries.
- Evaluate tiling, repetition, and texture scale from gameplay distance, not only the Scene view.

### Vegetation and props

- Place trees and rocks to create rhythm, enclosure, and landmark silhouettes.
- Leave enough visual and physical space for camera, player, enemies, and navigation.
- Cluster vegetation by plausible local conditions instead of uniformly random scatter.
- Prefer coherent asset families and deliberate scale over maximal prop density.

### Architecture

- Damaged and restored variants should remain recognizably the same building.
- A restoration phase should communicate newly usable space, services, or occupation.
- Check doors, foundations, thresholds, and terrain grounding from multiple views.

## Quality evidence

| View | What it reveals |
| --- | --- |
| Gameplay approach | First-time-player readability and destination framing |
| Reverse view | Route continuity and return-trip comprehension |
| Elevated overview | Spatial composition and density |
| Close-up | Material joins, grounding, collision mismatches |
| In motion | Camera obstruction, navigation, animation, and scale |

## Definition of visual acceptance

A successful authoring operation, valid NavMesh, or merged PR is **not** sufficient by itself. The scene must be judged in-engine at the expected camera height and during representative play.

**Canonical constraints:** [Asset Strategy](https://github.com/Shashakar/RPG-Kingdom/blob/main/docs/ASSET_STRATEGY.md) · [Scene Authoring](https://github.com/Shashakar/RPG-Kingdom/blob/main/docs/SCENE_AUTHORING.md) · [Visual Readability Audit](https://github.com/Shashakar/RPG-Kingdom/blob/main/docs/VERTICAL_SLICE_VISUAL_READABILITY_AUDIT.md).
