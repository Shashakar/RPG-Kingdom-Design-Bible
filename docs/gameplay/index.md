# Gameplay: adventure that restores the world

**Status:** Source-recorded vertical-slice loop and future directions, with proposed review questions.

## First playable arc

1. Arrive at a ruined settlement and meet remaining inhabitants.
2. Learn what prevents recovery.
3. Explore the surrounding region and gather essential materials.
4. Restore a few buildings through authored stages.
5. Improve basic character capability.
6. Enter an authored dungeon and defeat its boss.
7. Return to a settlement that has visibly changed.

The current slice targets **one region, one settlement, three to five restorable buildings, at most four resource types, one dungeon, and one boss**. It includes third-person movement, a basic combat kit, inventory, objectives, save/load, and debug support.

## The core loop

**Observe a need → venture out → overcome danger / gather / discover → return → restore → unlock new possibilities.**

Every major step should communicate causality. The dungeon should matter to the settlement; the settlement should matter to later exploration.

## Friction and earned convenience

The game's [Design Principles](https://github.com/Shashakar/RPG-Kingdom/blob/main/docs/DESIGN_PRINCIPLES.md) distinguish meaningful friction from wasted time. Distance, danger, scarcity, and preparation can create memorable progress **when restoration later removes the obstacle**. Poor controls, unclear objectives, and pointless repetition do not become good design simply because they are inconvenient.

**Review question:** Can a player explain what became easier and *what they did to earn it*?

## Combat and pacing

The current slice uses one player archetype and one weapon style, with basic health, stamina, damage, dodge, and death. The longer-term direction favors deliberate pacing and meaningful preparation, but this is not permission to implement a full class or profession system now.

## Longer-term progression — directional, not V1 scope

- Start without a formal class; advanced class dedication follows competence and world access.
- Professions eventually matter in crafting, exploration utility, and character expression.
- Advanced specialization introduces real opportunity cost.
- Hybrid paths may emerge from qualifying intersections rather than arbitrary class stacking.

These are future design directions. Exact classes, prerequisites, and profession systems are not specified for the slice.

## Test the player experience

| Question | Observable evidence |
| --- | --- |
| Does the player know what to do? | First-time player identifies the next restoration goal without developer coaching |
| Is adventure worthwhile? | Dungeon/gathering outcomes change settlement possibilities |
| Does restoration feel permanent? | The same place has a clearly recognizable before-and-after state |
| Is management optional? | The arc completes without mandatory settlement busywork |
| Does the experience persist? | Save/load preserves the resulting progress |

**Sources:** [Vertical Slice](https://github.com/Shashakar/RPG-Kingdom/blob/main/docs/VERTICAL_SLICE.md) · [Design Principles](https://github.com/Shashakar/RPG-Kingdom/blob/main/docs/DESIGN_PRINCIPLES.md) · [Class, Profession and Pacing Directions](https://github.com/Shashakar/RPG-Kingdom/blob/main/docs/CLASS_PROFESSION_AND_PACING_DIRECTIONS.md).
