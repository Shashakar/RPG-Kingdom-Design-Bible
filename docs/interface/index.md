# Interface and interaction design

**Status:** Design guidance proposed here; implementation authority remains with the game repository.

## Principle: clarity without breaking the fiction

Soul whispers can be fragmented; objectives should not be. The player should not need to decode poetic dialogue to learn a basic required action.

**Source-recorded example:** a Wisp's desire for a home can lead to the explicit objective **Restore the House**. A Blacksmith may need both a forge and a lost hammer; the interface should preserve the unfinished requirement when the forge is repaired.

## Information hierarchy — proposed

| Priority | Show | Avoid |
| --- | --- | --- |
| Immediate survival | Health, stamina, danger feedback | Visual noise that hides threats |
| Current intent | Active objective and interaction affordance | Vague text without an actionable next step |
| Action result | Clear confirmation of gathered, restored, unlocked, or failed action | Treating an attempted command as success |
| Long-term change | Village and world consequences when relevant | Forcing the player into menus to notice the world improved |

## Interaction states

An interaction should communicate **available**, **blocked with reason**, **in progress**, and **completed** where relevant. Completion feedback should follow authoritative committed gameplay facts; it should not be inferred from animation or button press alone.

## Inventory and menus

The vertical slice requires a basic inventory, not a full crafting economy. Prioritize legible item identity, quantities, selection, and feedback. The implementation repository's inventory contracts remain authoritative; this bible does not prescribe a competing UI framework.

## Accessibility and readability checks — proposed

- Verify text at typical gameplay viewing distance.
- Do not rely on color alone for interaction eligibility or soul state.
- Keep HUD and objective text legible against both dark dungeons and bright outdoors.
- Ensure interaction prompts have predictable positioning and timing.
- Check gamepad focus, selected state, and confirmation behavior.
- Avoid UI elements that obscure important enemies or route landmarks.

## Design review scenarios

1. First encounter with a Wisp and activation of a clear objective.
2. Gather materials, attempt restoration with insufficient resources, then succeed.
3. Restore a building and observe the world/NPC response.
4. Enter combat, receive damage, dodge, and recover.
5. Save, reload, and confirm persistent progress is reflected accurately.

**Sources:** [World Restoration Foundation](https://github.com/Shashakar/RPG-Kingdom/blob/main/docs/WORLD_RESTORATION_FOUNDATION.md) · [Vertical Slice](https://github.com/Shashakar/RPG-Kingdom/blob/main/docs/VERTICAL_SLICE.md) · [Architecture](https://github.com/Shashakar/RPG-Kingdom/blob/main/docs/ARCHITECTURE.md).
