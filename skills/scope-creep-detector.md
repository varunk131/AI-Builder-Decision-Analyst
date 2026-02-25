| name | description |
|------|-------------|
| scope-creep-detector | Reads a PRD, spec, or project brief line by line and flags every sentence that will cause scope creep. Identifies hidden engineering work, estimates additional effort, and draws a clear V1 vs V2 scope line. Use before sharing any spec with engineering. |

---

# Scope Creep Detector — Hidden Work Finder

This skill reads a document line by line and flags every statement that will silently expand scope. It finds the work your spec implies but doesn't acknowledge.

## PHASE 1: Input Collection

The PM pastes a PRD, spec, or project brief.

## PHASE 2: Line-by-Line Flag Scan

For each flagged sentence, produce:

| Field | Description |
|-------|-------------|
| **Exact Quote** | The sentence from the spec |
| **Why This Creeps** | How this innocent statement will expand scope |
| **Hidden Work** | Specific engineering tasks implied but not stated |
| **Tighter Version** | Rewrite with explicit boundaries |

Pay special attention to these known scope multipliers:

| Phrase/Pattern | Why It's Dangerous |
|----------------|-------------------|
| Notifications/emails | Always 3x estimated effort |
| Admin/settings | Always needs a UI nobody scoped |
| Export/import | Edge case explosion |
| "Real-time" / "seamless" / "automatic" | Each hides massive infrastructure |
| Mobile mentioned as afterthought | Full second platform |

## PHASE 3: Summary

| Metric | Value |
|--------|-------|
| **Total flags** | [N] |
| **Estimated hidden work** | [Additional person-weeks] |
| **Severity breakdown** | [Minor / Moderate / Major counts] |

## PHASE 4: The Scope Line

Draw a clear, opinionated V1 vs V2 line. Be decisive about what ships first and what waits.

## PHASE 5: The Engineering Question

End with: "Ask your engineering lead: '[specific question]' — their answer tells you if this is a 4-week or 12-week project."

## Rules

- Flag aggressively — false positives are better than missed scope
- Every flag must include specific hidden work, not vague warnings
- End with one question the PM should answer before proceeding
