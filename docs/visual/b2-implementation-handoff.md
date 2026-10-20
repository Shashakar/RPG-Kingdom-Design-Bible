# B2 character direction — 3D production handoff

**Status: Preferred exploratory candidate, not an approved production art standard.** The creative director preferred the refined **B2 grounded painterly stylized** treatment over the original B1 exploration. This approval is limited to the direction being worth developing. The current Rekindle-Claude character style still requires a complete redesign.

## What B2 should communicate

| Role | Target | Explicit correction from B1 |
| --- | --- | --- |
| Player | Believable anatomy; recognizable traditional fantasy equipment; visually distinct armor, leather, robes, weapons | Avoid awkward armor constructions and repeated blue-and-gold faction-like uniforms |
| NPC | Expressive faces, slightly stronger shape language, varied ages and roles, believable work clothing | More personality and stylization than the B1 townspeople |
| Enemy | Physically credible anatomy, convincing materials and threat cues | Less exaggerated/cartoonish than B1 goblins, orcs and creatures |
| Boss | Clear creature/warrior anatomy, imposing size, distinctive silhouette | Avoid excessive abstraction or visually confusing supernatural forms |

Shared painterly materials and coherent lighting should unify these **different degrees of stylization**. Player progression does not imply a fixed class system; class-like outfits in concept art are visual archetypes only.

## Three validation tracks

### 1. 3D-ready model study

Build or source one representative **player**, **working resident**, **ordinary hostile**, and **boss silhouette** as test models, not a complete character catalog. Require front/side/rear turnarounds, neutral pose, locomotion and attack/cast frames, and gameplay-camera captures. Check that silhouette, proportions, equipment fit and expression survive translation from illustration to geometry.

### 2. Actual Rekindle-Claude world comparison

Use the [Rekindle-Claude visual baseline](rekindle-claude-baseline.md) as the **implementation evidence**, not the source of approved character styling. Stage B2 candidates in an actual restored settlement, wilderness route, damaged area, and encounter. Capture matching camera height, field of view, lighting, and scale where possible. A composited illustration is **not** evidence that the character is integrated in-engine.

### 3. Technical and production gate

Before purchasing or authoring a full character family, confirm in the **actual Rekindle-Claude branch**:

- Engine version, rendering pipeline, target platforms and hardware budgets.
- Rigging, humanoid/creature skeleton expectations, retargeting, root motion and animation integration.
- Material/shader workflow, texture resolution and texture packing.
- Equipment attachments, interchangeable parts and clipping rules if required.
- LOD and culling approach, expected simultaneous actor counts, draw calls, skinning and memory targets.
- NPC expressions, face rig or blend-shape needs, and animation budget.
- Asset licenses and whether redistribution in game builds is permitted.

**No numeric polycount, texture budget, NPC limit, or engine configuration is approved here.** Derive measurable budgets from profiling and architecture constraints of the starting implementation, not the legacy RPG Kingdom repo.

## Evaluation rubric (proposed)

Score each from 1–5 with screenshots and notes: silhouette at gameplay distance, character-to-environment cohesion, traditional equipment plausibility, role personality, enemy threat readability, boss legibility, animation quality, asset pipeline compatibility, and scalable production cost. Record strengths, blockers and proposed fixes; do not average away a critical failure.

## Concept-art provenance

The B2 concept sheets and the follow-up 3D-style/world-integration study were generated in the project conversation as **exploratory images**. They are **not committed as PNG files to this repository**. The diagrams on [Target Visual Identity](target-identity.md) are lower-fidelity schematic comparisons, not substitutes for those images. Archive the original concept images with explicit provenance and license before presenting them as the visual reference package for external artists or agents.

## Approval gate

A human decision is required to approve specific B2 model proportions, materials, character roles and production assets. A concept sheet, merged PR, or passing automated test does not satisfy that gate.
