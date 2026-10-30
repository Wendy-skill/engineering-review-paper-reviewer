# Optional v3 Research-Group Interface

Use only for a real cross-Skill handoff. Standalone use remains the default.

## Scope and routing

- **Own:** Engineering review-paper scope, search coverage, critical synthesis and novelty evidence.
- **Do not replace:** Generic experimental manuscript review or language correction.
- **Chinese triggers:** 综述论文审稿、文献覆盖度、批判性综合.
- **English triggers:** review paper methodology, research synthesis audit.
- **Do not trigger:** unrelated writing polish, generic research planning, or an all-Skill audit when only a narrow task was requested.
- **Optional recipients:** ai-strict-reviewer for scientific synthesis; ai-literature-member for genuine source searches. Route only if available and useful; never claim a named Skill was run merely because it is mentioned.

## Handoff schema

Use `ID | owner | document/version/location | issue | located evidence | source status | assessment | local consequence | proposed action | author decision | workflow state`.

Source status: `Reported / Documented / Independently checked / Not available`. Assessment: `Confirmed / Reasoned inference / Unverified` (specify what was verified). Workflow state: `Open / Waiting for evidence / Awaiting author / Resolved / Recheck needed`. Scientific reviewer **Severity** and inspector **Impact** are distinct; do not force a shared score.

## Ledger and loops

When authorised and helpful, reuse `Claim ID, Data ID, figure/table, units, case conditions, baseline, dataset/script version, document version, evidence status and linked issue ID`. It is not automatically shared or saved. One issue owner; another specialist handles only a separate question. Default loop: literature → approved execution → scientific review → editing → final QA; send changed evidence to the responsible member and rerun only affected checks. No invented delegation, calculations, sources or persistent storage. Author approval is required for meaning-changing edits or new execution.
