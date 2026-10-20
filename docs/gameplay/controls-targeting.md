# Player controls, camera and targeting

**Status:** Source-recorded intended control model; tuning remains playtest-dependent.

RPG Kingdom uses a **cursor-first third-person** model inspired by familiar MMO interaction, rather than permanently captured mouse-look.

## Default movement

| Input | Intent |
| --- | --- |
| W / S | Forward / backward |
| A / D | Turn left / right |
| Q / E | Strafe left / right |
| Left mouse drag | Orbit camera independently of character facing |
| Right mouse drag | Turn camera and character together |
| Tab | Cycle eligible hostile targets |

A future option may swap turn/strafe keys without changing movement semantics. Right-drag temporarily makes A/D strafe. The cursor is normally available; mouse capture is temporary after a drag threshold.

## Selection is not combat permission

- Left click selects a valid world actor without firing the primary attack.
- Right click on a hostile selects and requests auto-attack.
- Right click on an authored non-hostile target can select without attacking.
- Contextual right-click interactions route through the interaction system.
- Drag gestures must not become accidental clicks.
- UI pointer interactions must not fall through to world targeting.
- A selected target can still be out of range, obstructed, friendly, or invalid for an ability.
- Tab cycling is hostile-focused; exact priority, angle, range, and repeat behavior need playtesting.

## Camera acceptance checks

1. Orbit while stationary; releasing drag preserves the camera angle.
2. Move forward/backward; camera smoothly follows character facing when not actively overridden.
3. Strafe alone; camera does not unexpectedly rotate.
4. Turn with keyboard; camera maintains relative yaw appropriately.
5. Move mouse over UI; no world action fires underneath.
6. Confirm equivalent intentions can later map to controller input.

**Canonical source:** [Player Controls and Targeting](https://github.com/Shashakar/RPG-Kingdom/blob/main/docs/PLAYER_CONTROLS_AND_TARGETING.md). This page is a design summary, not a replacement for exact runtime behavior.
