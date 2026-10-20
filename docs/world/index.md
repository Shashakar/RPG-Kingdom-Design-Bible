# World and environmental storytelling

**Status:** Canonical world-restoration concepts summarized from the game repository; composition guidance below is proposed.

## The world must change for reasons

The Soul Dragon's catastrophe has left civilization devastated. Many souls remain anchored to places, objects, duties, memories, and relationships. Repairing civilization restores both physical spaces and the people connected to them.

A restored building should tell three stories at once: **what was lost**, **what the player did**, and **what is possible now**.

## World-state visual grammar

| State | Intended communication | Candidate art treatment (not approved) |
| --- | --- | --- |
| Damaged | Incomplete, dangerous, abandoned | Broken edges, missing functionality, obstructed access |
| Recovering | Progress has begun but is incomplete | Work-in-progress silhouettes, partial occupancy, changed props |
| Restored | A real service or community function has returned | Usable entrances, purposeful activity, populated spaces |

These are *design prompts*, not mandatory universal phase names or asset instructions. Exact world phases and state transitions belong to the game implementation.

## Settlements should not feel interchangeable

The [world restoration foundation](https://github.com/Shashakar/RPG-Kingdom/blob/main/docs/WORLD_RESTORATION_FOUNDATION.md) calls for distinct authored recovery problems. A starting settlement may emphasize homes and professions; another location may center on lost records, a mine, a coast, or damaged defenses. Shared systems should support distinct local stories.

## Environmental composition checklist — proposed

- **Readable geography:** the player can identify the route, destination, and obstacles from the gameplay camera.
- **Material hierarchy:** roads, vegetation, stone, and architectural surfaces have deliberate visual separation.
- **Natural continuity:** vegetation, terrain, and rocks look placed in relation to geography, not scattered randomly.
- **Purposeful landmarks:** changes in silhouette and landmarks help navigation without excessive UI.
- **Before/after continuity:** restored locations remain recognizably the same places.
- **Playable geometry:** art never silently breaks collision, pathing, objective access, or camera behavior.
- **Evidence:** compare screenshots at the same camera positions and verify in motion.

## Current approved asset sources

Townsmith is the preferred settlement architecture candidate; Fantasy Adventure Environment is the selective nature/connecting-space source; MysticDungeon's curated local subset supports the initial dungeon slice. Refer to [Asset Standards](../decisions/asset-standards.md) for exact qualifications.

## Next design work

The [Visual Direction Worklist](visual-direction-worklist.md) identifies unapproved palette, vegetation, scale, and composition choices. Do not treat those questions as settled.
