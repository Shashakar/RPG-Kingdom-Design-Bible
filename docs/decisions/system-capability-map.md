# Designer's system capability map

**Status: Documentation snapshot, not a live implementation dashboard. Recheck canonical game contracts before scheduling work.**

| Player-facing requirement | Documented system capability |
| --- | --- |
| Player, NPC, neutral, hostile, boss | Shared Character state with role-specific composition |
| Select and interact | Player Controls and Interaction |
| Combat and enemy encounters | Combat, Ability Execution, Enemy, Basic AI, Encounter |
| Gather and carry | Resource Nodes, Items, Inventory |
| Starter weapon | Equipment |
| Restore a building | Building Restoration stages and contributions |
| Restore a person | Soul Restoration identity anchors |
| Settlement recovery | Village |
| Open routes and change scenery | World State and World Phase |
| Guide the first session | Objectives and First-Time Journey |
| Explore a dungeon | Dungeon and Encounter |
| Claim loot and rewards | Rewards and World Loot |
| Continue after saving | Save/Load |
| Show health, resources, progress | Presentation and Notifications/UI |

These contracts establish a foundation for authoring content, **not** proof that every experience is polished, fully playtested, or production-ready.

## Not established as current V1 features

Networked co-op; autonomous regional markets; full class/profession specialization; multiple shared-world player characters; procedural regions; a permanent actor art style; and unrestricted production-scene composition.

## Design preflight

Describe the player-visible result, locate the relevant system owner, check current capability and authored data, identify any missing capability, and require in-engine evidence for visual acceptance.

**Sources:** [Systems Index](https://github.com/Shashakar/RPG-Kingdom/blob/main/docs/systems/README.md), [Architecture Audit](https://github.com/Shashakar/RPG-Kingdom/blob/main/docs/ARCHITECTURE_AUDIT.md).
