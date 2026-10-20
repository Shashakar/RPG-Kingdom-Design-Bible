# Cooperative play direction

**Status:** Deferred until the single-player restoration loop is validated.

The game is designed to accommodate cooperation without becoming an MMO or depending on rigid party compositions.

## Intended initial model

- One player hosts and owns authoritative world state.
- Other players request actions; the host validates and commits changes.
- The persistent world save belongs to the host.
- Visual effects follow committed gameplay facts.
- Dedicated servers and host migration are later evaluations, not current commitments.

## First experimental milestone

After the slice is proven: synchronize **two** characters, one interaction/inventory transfer, one building restoration, and one encounter/dungeon completion; test disconnect and late join. Expand toward two to four players only when playtests justify it.

## Party scale and area loading

Past project conversations explored larger party counts, NPC population limits, and defining gameplay areas for loading/unloading. Those discussions established **performance questions**, not an approved 30-player concurrency target, 200-character area size, or specific spatial streaming scheme.

Before specifying such numbers, measure Unity performance with representative actors, assets, AI, animation, combat, and scene geometry. An 'area' must be defined by actual player visibility, gameplay activity, and persistence needs rather than an arbitrary square or headcount.

**Source:** [Multiplayer Direction](https://github.com/Shashakar/RPG-Kingdom/blob/main/docs/MULTIPLAYER.md). **Conversation context:** project discussions on party sizes, NPC limits, and spatial loading (August 2026); no final sizing decision recorded.
