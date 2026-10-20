# Framework evaluation decisions

**Status: Source-recorded engineering decisions.**

**Principle: Own the domain. Rent the machinery.** RPG Kingdom retains authoritative gameplay state while evaluating replaceable third-party authoring and presentation machinery.

## Game Creator 2

Game Creator 2 is not the V1 foundational runtime framework.

**Inventory 2: rejected for the first backpack UI.** Its Bag and RuntimeItem model, UI mutation paths, and persistence would require mirroring and reconciling a second inventory truth. The project instead uses its native uGUI presentation over RPG Kingdom inventory snapshots and validated commands.

This is a scoped rejection, not a blanket prohibition. Dialogue and other modules can be evaluated separately for future milestones.

## Future evaluation gates

An adapter must preserve Core tests, public contracts, authoritative saves, and integration boundaries. It must measurably reduce implementation, maintenance, or authoring cost, and remain replaceable without rewriting unrelated domain systems.

**Source:** [Asset Strategy](https://github.com/Shashakar/RPG-Kingdom/blob/main/docs/ASSET_STRATEGY.md).
