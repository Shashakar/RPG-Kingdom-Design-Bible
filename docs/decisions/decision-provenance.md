# Decision provenance

**Status: Proposed documentation convention.** This is a way to record authority, not a retroactive approval.

| Label | Meaning |
| --- | --- |
| Approved creative direction | Explicit human creative approval, with linked evidence |
| Implemented behavior | Documented game behavior, not necessarily creatively accepted |
| Proposed direction | A candidate awaiting creative review |
| Deferred | Intentionally outside current scope |
| Verified | Evidence supports specified acceptance criteria |
| Superseded | Replaced by a newer decision |

Record source, date, owner, scope, status, acceptance criteria, and evidence for consequential decisions. Keep implementation evidence separate from visual sign-off. A merged PR or passing test does not itself confer creative approval.

For disputed or changing requirements, link both sources and identify the human decision required. Never silently elevate a Codex implementation or a design suggestion into approved creative direction.

Related: [Collaboration Boundaries](collaboration-boundary.md) and [Creative Quality](creative-quality.md).
