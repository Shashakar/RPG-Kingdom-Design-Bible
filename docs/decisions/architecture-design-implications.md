# Architecture implications for designers

**Status: Source-recorded implementation constraints, not new creative approvals.**

## One living-actor foundation

The architecture audit consolidated common health and lifecycle under **Character**. **Enemy** supplies hostile-role metadata and consequences; it is not a second living-actor model. Players, villagers, neutral creatures, companions, and bosses can therefore differ through roles, controllers, presentation, and authored behaviors rather than duplicating common state.

## State drives visible consequences

Combat results, building stages, soul states, world changes, and UI must reflect committed gameplay facts. An animation or visual effect cannot independently award progress.

## Authored content and persistence

Stable IDs and data-driven definitions support distinct characters, locations, stages, and encounters. Designs should specify the gameplay fact that changes and the player-visible outcome. Avoid scene-only tricks that cannot survive Save/Continue.

## Future co-op

Validated state ownership is already an architectural goal, but networked co-op is not part of the present vertical slice.

**Sources:** [Architecture Audit](https://github.com/Shashakar/RPG-Kingdom/blob/main/docs/ARCHITECTURE_AUDIT.md), [Character](https://github.com/Shashakar/RPG-Kingdom/blob/main/docs/systems/Character.md), [Enemy](https://github.com/Shashakar/RPG-Kingdom/blob/main/docs/systems/Enemy.md). The game repository remains authoritative for implementation.
