# Next Chat Prompt — நச்சுக்கோப்பை full page-state reconciliation

Continue directly in `pugazg/kalaignar-stage-plays`, branch `main`, active work `works/nachuk-koppai/`.

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first and preserve newer durable work.

## Controlling source

Use only attached `ACL-TDD_00314_நச்சுக்_கோப்பை.pdf`.

## Durable state

- canonical page records: **63 / 63 present**;
- word-by-word visual fidelity: **63 / 63 COMPLETE**;
- fidelity PASS: **60** — scans **1–19, 21, 23–34, 36–63**;
- remaining fidelity holds: **3** — scan **20** (`வேணும்லும்`), scan **22** (two adjacent unidentified source glyph clusters after `சாந்தா`), scan **35** (damaged/overinked word before `சூர்ய நாராயண`, provisionally `சுடகோடி`);
- H-GATE PASS / verified: **60 / 63**;
- H-GATE needs-review: **3 / 63** — the same scans **20, 22, 35**;
- cumulative source-proven fidelity correction loci: **280**;
- downstream physical-page drift has been repaired through scan 63;
- final physical scan **63** contains the **final dialogue + முற்றும் + printer imprint**;
- P0 SHA-256 remains **pending** and is outside this reconciliation unless separately authorized;
- scene assembly and English translation remain blocked.

## Exact next activity

Perform the **full 63-page state reconciliation**.

1. Reinspect the three remaining holds on scans **20, 22 and 35** against the strongest attached-source pixels available. Resolve a locus only if the attached source itself is secure; otherwise preserve it explicitly.
2. Reconcile all **63 page records** against the completed fidelity results: front matter, printed-page values, scene boundaries, page types, H-GATE, `status`, and `visual_text_fidelity`.
3. Remove stale pre-fidelity / pre-realignment notes and ensure no downstream record still assumes the old one-page drift.
4. Reconcile `indexes/page-map.md`, `README.md`, `VISUAL_TEXT_FIDELITY_AUDIT.md`, root `HANDOVER.md`, and this prompt.
5. Write a durable reconciliation record, e.g. `PAGE_STATE_RECONCILIATION.md`.
6. Commit atomically.

Do **not** start scene assembly or English translation in the same iteration unless reconciliation is fully complete and a later user instruction authorizes the next phase.
