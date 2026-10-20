# Design decisions and provenance

This section distinguishes **source-recorded direction** from **new proposals**. Neither a merged PR nor a functioning scene automatically establishes creative acceptance.

## Read the existing decisions

- [Asset Standards](asset-standards.md) — source-backed asset selections and limitations.
- [Collaboration Boundaries](collaboration-boundary.md) — responsibilities and escalation.
- [Visual Direction Worklist](../world/visual-direction-worklist.md) — artistic questions still requiring decisions.

## Status vocabulary

| Status | Meaning |
| --- | --- |
| **Proposed** | A candidate awaiting a decision |
| **Approved** | Creative director explicitly accepted the design |
| **Implemented** | Work exists in the game; not necessarily accepted visually |
| **Verified** | Evidence demonstrates accepted behavior and visual result |
| **Superseded** | Replaced by a later recorded decision |

These are distinct dimensions in practice: an approved design may not be implemented, and an implementation may still fail visual review. Record the approval, implementation, and verification evidence separately.

## Decision record template

```markdown
# DD-000: Descriptive title

Status: Proposed
Creative owner:
Date:
Source / related issues / PRs:

## Problem and player impact
## Options considered
## Decision and rationale
## Visual or gameplay references
## Acceptance criteria
## Explicit exclusions
## Approval evidence
## Implementation evidence
## Verification evidence
## Superseded by
```

## Rules for agents

Do not manufacture approval. Quote the source, link the originating document, and mark interpretations as interpretations. When a new proposal conflicts with existing direction, record the conflict and ask for a creative decision rather than silently changing the specification.
