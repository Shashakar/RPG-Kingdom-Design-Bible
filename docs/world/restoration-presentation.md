# Restoration-state visual contracts

**Status: System semantics recorded from the game repository; visual acceptance criteria proposed.**

| Layer | Authoritative state | Visual consequence |
| --- | --- | --- |
| Building | Ruined, Stabilized, Restored | Authored building stage appearance and usability |
| Soul | Wisp, Spectre, Restored | Identity coherence based on recovered anchors |
| World | Derived authored phase | Routes, markers, NPC presence, interactables, and settlement changes |

These layers are distinct. Building Restoration owns building-stage visuals. Soul Restoration derives state from anchor facts. World Phase applies broader scene consequences without taking over individual building stage roots.

## Not every soul follows three steps

The House resident can go directly from Wisp to Restored after the home anchor is satisfied. The Blacksmith becomes Spectre after the Forge is restored and only becomes Restored after the Hammer is returned. The Hammer being in inventory alone is not the final hand-in.

## Proposed acceptance criteria

1. The location remains recognizable through each phase.
2. Stabilized communicates partial rather than completed recovery.
3. A person's identity is legible across soul states.
4. The player can understand the action that caused the change.
5. Opened routes and services are visible in the world.
6. Save/Continue restores the correct presentation.
7. Rejected actions never show final success feedback.

**Sources:** [Building Restoration](https://github.com/Shashakar/RPG-Kingdom/blob/main/docs/systems/BuildingRestoration.md), [Soul Restoration](https://github.com/Shashakar/RPG-Kingdom/blob/main/docs/systems/SoulRestoration.md), [World Phase](https://github.com/Shashakar/RPG-Kingdom/blob/main/docs/systems/WorldPhase.md).
