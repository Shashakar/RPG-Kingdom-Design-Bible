# Visual reference governance

**Status: Proposed documentation workflow.**

## Reference metadata template

For every externally sourced or project-sourced image, record:

- **Title and subject**
- **Category:** in-game evidence, exploratory reference, or approved reference
- **Creator/source URL and license/usage permission**
- **Source date and capture version/commit** when known
- **What to emulate** and **what to avoid**
- **What it actually demonstrates**, including limits
- **Approval:** approver, date, scope, and exact qualities approved
- **Superseded by** if replaced

## Source policy

1. Prefer screenshots from the actual game or legitimately licensed project assets.
2. For external references, link to the source or use imagery with clear reuse permission. Do not copy arbitrary online images into the repository.
3. Never claim approval from presence in a mood board, a merged PR, or a passing test.
4. Avoid hotlinking third-party image files without permission.
5. Preserve source links and capture provenance for generated images; mark generated concepts as exploratory until approved.
6. When a reference becomes canonical, record precisely which qualities were approved. Other depicted elements remain nonbinding.

## Recommended asset layout

Place approved, distributable images in `docs/assets/visual/` with descriptive names and companion attribution/decision notes. Until an image is available and licensed, use an explicit **Needed imagery** requirement instead of a fabricated example.

## Submission workflow

Gather references → annotate qualities → compare against existing game evidence → human review → record scoped approval → update linked World/Characters/Interface pages.

See [Decision Provenance](../decisions/decision-provenance.md) and [Visual Evidence](../decisions/visual-evidence.md).
