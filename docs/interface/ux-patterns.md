# UX patterns and acceptance scenarios

**Status:** Proposed UX checklist grounded in the game's objective and restoration requirements.

## Objective clarity

An evocative whisper may say “...forge... tool...” while the objective explicitly communicates **Restore the Forge** and **Find the Blacksmith's Hammer**. When one step completes, the other remains visible.

## Feedback rules

1. Show whether an action is possible.
2. Explain a blocked action in player language.
3. Show progress only when authoritative state changes.
4. Confirm a completed restoration with world evidence, not only a toast.
5. Keep persistent progress synchronized after load.

## Screen-specific review prompts

### HUD

Can the player read survival state, immediate threat, and active objective without covering the action?

### Inventory

Can the player identify item, quantity, selection, and transfer outcome? Are empty/disabled states understandable?

### Interaction panel

Is the target clear? Does a failed request explain what is missing? Is success feedback distinct from an attempted input?

### Menus and gamepad

Can a controller user identify focus and return safely? Are destructive actions explicit? Is text legible at typical display distance?

## Test scenarios

- Start with an incomplete restoration objective.
- Attempt a restoration with insufficient materials.
- Gather the required materials and complete the stage.
- Verify the NPC/world state changes and objective advances.
- Save/reload and verify the same information is shown.

These scenarios are design acceptance checks; technical test ownership remains with the game repository.
