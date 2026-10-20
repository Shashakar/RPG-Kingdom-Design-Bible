# Production character art — decision study

**Status: Exploratory; no candidate approved.** The current Rekindle-Claude character appearance is to be completely replaced. The approved *world* style is stylized fantasy, but it does not settle character proportions, faces, clothing, armor, creatures, or rendering.

## Three candidate families

| Candidate | Visual target | Advantages | Risks |
| --- | --- | --- | --- |
| **A — Heroic stylized** | Clear, moderately exaggerated heroic shapes, readable faces and equipment | Readable combat silhouettes and strong hero identity | Generic fantasy armor; NPCs may look too heroic |
| **B — Painterly grounded stylized** | Mature proportions, material-rich clothing and equipment, hand-authored texture language | Natural fit with grounded, lived-in settlements | More art production effort; details may vanish at gameplay distance |
| **C — Simplified stylized** | Cleaner, reduced-detail forms with expressive proportions | Clear small-scale readability and scalable NPC production | Can look overly cartoonish or visually disconnected from architecture |

These are comparison hypotheses, **not** asset-pack endorsements or a request to reuse current characters. See the [illustrated exploratory comparison](target-identity.md).

## Required proof before approval

1. **Player:** front, side, rear, facial close-up, idle, locomotion, weapon-ready and attack.
2. **Resident:** multiple ages/body types and occupational roles, at work in a restored settlement.
3. **Hostile:** melee, ranged/caster and elite/boss silhouettes against relevant terrain.
4. **Soul-state:** same character shown as Wisp, optional Spectre, and Restored.
5. **Camera test:** each candidate at the real gameplay camera distance and under normal scene lighting.
6. **Technical fit:** rigging/animation, performance, rendering pipeline, equipment attachment, license, and authoring workflow.

Evaluate candidates together with the [Rekindle-Claude implementation baseline](rekindle-claude-baseline.md), but **do not copy the current character aesthetic**.

## Review questions

- Which candidate feels distinctively RPG Kingdom rather than interchangeable fantasy art?
- Are residents believable as people rebuilding a community?
- Can enemies and bosses be identified quickly without target frames?
- Does the chosen treatment work across humans, spirits, monsters, and equipment?
- Can the visual standard be produced consistently by our actual art pipeline?

**Decision required:** Select a character style family after seeing full-resolution, multi-role concepts; then approve proportions, shape language, material treatment, and character-role standards separately.
