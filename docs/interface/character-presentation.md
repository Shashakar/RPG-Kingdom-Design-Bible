# Character frames, action bar and combat readability

**Status:** Source-recorded interface architecture summarized for design reference; exact visual treatment remains open.

## Character frames

The game uses a reusable **CharacterFrame** concept for player and selected-character presentation. Health, resources, and timed actions should share consistent visual grammar without duplicating unrelated UI hierarchies.

The player needs to distinguish:
- current health and resource availability;
- selected actor identity and health;
- cast or timed action progress;
- default melee swing readiness versus an active ability.

## Combat actions

The initial hotbar has **six fixed slots** and routes input through authored action definitions. This is the current implementation slice, not a declaration that the final game will always use exactly six slots.

A free default melee attack is distinct from active resource-consuming abilities. Readiness feedback should communicate that distinction rather than implying every attack spends Energy or Mana.

## Feedback checklist — proposed

- Health and resources are visually distinct.
- Selected target is obvious and clears when no longer valid.
- Casting and melee readiness are distinguishable at a glance.
- Disabled or unavailable actions explain their state.
- Interaction prompts do not conflict with cursor-first camera/targeting.
- New abilities or training produce visible feedback only after a committed grant.

**Sources:** [Vertical Slice Playtest](https://github.com/Shashakar/RPG-Kingdom/blob/main/docs/VERTICAL_SLICE_PLAYTEST.md) · [Player Controls and Targeting](https://github.com/Shashakar/RPG-Kingdom/blob/main/docs/PLAYER_CONTROLS_AND_TARGETING.md) · [Capability Unlock Phases](https://github.com/Shashakar/RPG-Kingdom/blob/main/docs/CAPABILITY_UNLOCK_PHASES.md). **Project conversation:** player health-bar and inventory/UI planning (August–September 2026).
