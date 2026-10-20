# Authored first-session journey

**Status:** Source-recorded implemented journey direction, with scene-specific differences. Consult the canonical system document for current production behavior.

## Why this chapter exists

The broad vertical-slice outline describes a simple **gather → restore → dungeon → recover** loop. The detailed [First-Time Player Journey](https://github.com/Shashakar/RPG-Kingdom/blob/main/docs/systems/FirstTimeJourney.md) adds important narrative, training, equipment, and soul-restoration steps that should not be lost in the creative bible.

## Authored narrative progression

1. **Talk to the House Soul.** The Wisp asks for the resources needed to repair the home.
2. **Restore the House.** The resident's home anchor is satisfied, moving directly from Wisp to Restored.
3. **Talk to the restored resident.** Learn about the recovered Power Strike training manual.
4. **Read the training manual.** Learn the capability before progressing to the Blacksmith.
5. **Talk to the Blacksmith's Soul.** Discover the Forge restoration requirement.
6. **Restore the Forge.** The Blacksmith reaches Spectre: meaningful progress, but not complete restoration.
7. **Talk to the Blacksmith again.** Learn about the missing Hammer and begin the Ruined Gate adventure.
8. **Explore and fight.** The approach includes a Basic Sword reward/equipment opportunity before the Gate confrontation.
9. **Find the Hammer.** The protected reward claim advances the objective; simply possessing the item does not fully restore the Blacksmith.
10. **Give the Hammer to the Blacksmith.** The authored hand-in completes the identity-anchor consequence.
11. **See the Blacksmith restored and the route open.** The restored person and world consequence make the adventure meaningful.

An optional conversation with the restored House resident can provide a Ruined Gate clue. Exact order, objective activation, and scene wiring are maintained in the canonical implementation document.

## Creative acceptance questions

- Is the House Wisp's need comprehensible without requiring players to decode fragments?
- Does the first restoration visibly change both the home and its resident?
- Does the training manual feel earned rather than an arbitrary tutorial popup?
- Is the Blacksmith's Spectre state clearly incomplete after the Forge is restored?
- Does the missing Hammer create a convincing reason to adventure?
- Is the Basic Sword equipment interaction discoverable?
- Does the hand-in visibly complete the Blacksmith's identity?
- Can players understand why the route opens afterward?

## Scope and caveats

The game repository distinguishes the `VerticalSlice` and `PlaytestScene` journey compositions; do not assume their sequences and endings are identical. Automated tests demonstrate mechanical coverage, not first-time-player comprehension. External playtest observations remain necessary.

**Related sources:** [Soul Restoration](https://github.com/Shashakar/RPG-Kingdom/blob/main/docs/systems/SoulRestoration.md) · [Building Restoration](https://github.com/Shashakar/RPG-Kingdom/blob/main/docs/systems/BuildingRestoration.md) · [Equipment](https://github.com/Shashakar/RPG-Kingdom/blob/main/docs/systems/Equipment.md) · [World Phase](https://github.com/Shashakar/RPG-Kingdom/blob/main/docs/systems/WorldPhase.md).
