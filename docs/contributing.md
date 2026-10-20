# Contributing and review workflow

The Design Bible is a **creative contract and reference**, not a substitute for Unity inspection or the game's technical architecture.

## For a design change

1. **Identify the player-facing problem.** Describe what the player sees, feels, or fails to understand.
2. **Locate existing direction.** Check this bible and the [game documentation](https://github.com/Shashakar/RPG-Kingdom/tree/main/docs).
3. **State the proposal.** Include alternatives, constraints, and explicit non-goals.
4. **Attach evidence.** Use appropriately licensed reference imagery, annotated in-engine screenshots, or clear diagrams.
5. **Obtain creative approval.** Approval must be explicit; a document PR merge is not necessarily approval.
6. **Implement separately.** Technical implementation follows the game's AGENTS.md, architecture, and scene-authoring contract.
7. **Verify the result.** Compare evidence against approved criteria in the actual gameplay camera and relevant game states.

## For AI contributors

- **Claude:** technical architecture decisions in the game repository.
- **ChatGPT/design contributors:** creative documentation, comparison, design options, and review criteria.
- **Supervisor/Codex:** scoped implementation and evidence under the authorized tooling/permissions.
- **Human creative director:** final creative acceptance.

Do not treat this page as permission to modify a production scene. The [scene authoring contract](https://github.com/Shashakar/RPG-Kingdom/blob/main/docs/SCENE_AUTHORING.md) and explicit issue-scoped approvals govern that work.

## Evidence standard

For an environment or interface change, show a **before**, **after**, and **gameplay-distance** view where practical. Record camera context, the intended player task, and known limitations. A screenshot can show visual composition; it cannot by itself prove interaction, navigation, save/load, or performance.

## Keeping pages maintainable

- Prefer one topic per page and descriptive headings.
- Link to canonical technical contracts rather than copying them.
- Label *source-backed*, *proposed*, and *approved* statements.
- Record dates and superseding decisions when direction changes.
- Avoid adding proprietary third-party asset imagery without publication rights.
