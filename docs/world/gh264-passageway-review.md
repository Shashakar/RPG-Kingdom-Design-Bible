# GH-264 — Passageway design review

**Status:** Proposed design corrections; not approved as a final composition.

**Context:** The GH-264 work and PR #266 produced an initial passageway implementation. The creative director described it as a useful rough draft but below the desired authored-environment quality. PR #266 was subsequently merged. Merge is not visual acceptance.

**References:** [RPG Kingdom issue #264](https://github.com/Shashakar/RPG-Kingdom/issues/264) · [PR #266](https://github.com/Shashakar/RPG-Kingdom/pull/266) · [Scene authoring contract](https://github.com/Shashakar/RPG-Kingdom/blob/main/docs/SCENE_AUTHORING.md).

## Observed concerns reported in review

1. New passageway lacks sufficient material separation.
2. There are no trees or meaningful natural/environmental dressing in the new area.
3. The route meets a basic passageway requirement without convincing authored composition.
4. The initial movement tutorial may require changes to fit the revised route.
5. The existing terrain square constrained the layout. The creative director added neighboring terrains manually to reach the desired result.

These are **review observations**, not a fresh Unity scene inspection. Screenshots and precise terrain dimensions still need to be attached and checked.

## Proposed acceptance criteria (requires human approval)

- **Materials:** Deliberate, legible distinction among traversable route, adjacent ground, and terrain features. Avoid uniform prototype-like surfaces.
- **Natural dressing:** Trees, vegetation, rocks, and terrain transitions placed with a consistent visual language and navigational readability; avoid arbitrary clutter.
- **Composition:** A clear route with purposeful framing, sightlines, landmarking, and coherent connection to neighboring areas.
- **Terrain continuity:** Evaluate terrain expansion beyond the original tile when required; no visible seams, inaccessible edges, or unsupported assumptions that one tile is enough.
- **Tutorial compatibility:** Verify opening movement instructions, player path, camera sightlines, and navigable geometry against the changed route.
- **Evidence:** Include entrance-facing, exit-facing, and overhead images plus a Unity scene inspection and explicit human visual sign-off.

## Quality bar

The stated target is authored work comparable to an environment/level designer with **at least four years of professional experience**, aspiring toward senior-level judgment. This is a target for review, **not** a claim that an agent currently meets it. An objectively valid terrain operation is not sufficient evidence of visual quality.

## Implementation boundary

The game repository's [AGENTS.md](https://github.com/Shashakar/RPG-Kingdom/blob/main/AGENTS.md) and [SCENE_AUTHORING.md](https://github.com/Shashakar/RPG-Kingdom/blob/main/docs/SCENE_AUTHORING.md) govern permissions. Existing production-scene creative composition requires explicit, scene/issue-bound human authorization. Do not infer permission from this design document.

## Evidence and outstanding decisions

- [ ] Add source screenshots (entrance, exit, overhead) with provenance and rights to publish.
- [ ] Compare current scene against these proposed criteria.
- [ ] Confirm the route and tutorial constraints with the creative director.
- [ ] Obtain explicit design approval.
- [ ] Track follow-up implementation and verification independently.
