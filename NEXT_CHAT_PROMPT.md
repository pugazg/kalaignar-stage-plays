# Next Chat Prompt — நச்சுக்கோப்பை Tamil scene assembly / Scenes 1–5

Continue directly in `pugazg/kalaignar-stage-plays`, branch `main`, active work `works/nachuk-koppai/`.

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first and preserve newer durable work.

## Controlling authority

The attached `ACL-TDD_00314_நச்சுக்_கோப்பை.pdf` remains the controlling source, but routine scene assembly must assemble from the now-reconciled canonical page records rather than retranscribing the PDF from scratch.

## Durable page-layer state

- canonical page records: **63 / 63**;
- word-by-word fidelity: **63 / 63 COMPLETE**;
- full page-state reconciliation: **COMPLETE**;
- verified pages: **61 / 63**;
- terminal source-condition holds: **2 / 63** — scans **22, 35**;
- blocked pages: **0**;
- physical-page drift: **fully repaired through scan 63**;
- final scan 63: **final dialogue + முற்றும் + printer imprint**;
- P0 SHA-256: **still pending / separate hold**;
- English translation: **not started**.

Terminal holds must not be guessed away:

- scan 22 — two unidentified source clusters after `சாந்தா` in the `ஏகா — பாட்டு.` line;
- scan 35 — damaged word before `சூர்ய நாராயண`, provisionally carried as `சுடகோடி`.

Resolved user correction:

- scan 20 — **`வேணும்னாலும்`**; page is now verified and Scene 3 carries no hold.

## Exact next activity

Assemble **Scenes 1–5** into:

- `works/nachuk-koppai/scenes/01.md`
- `works/nachuk-koppai/scenes/02.md`
- `works/nachuk-koppai/scenes/03.md`
- `works/nachuk-koppai/scenes/04.md`
- `works/nachuk-koppai/scenes/05.md`

Source scan spans:

- Scene 1 — scans **5–8**;
- Scene 2 — scans **8–18**;
- Scene 3 — scans **18–20**;
- Scene 4 — scans **20–21**;
- Scene 5 — scans **22–24**.

Assembly rules:

1. assemble only from canonical page records;
2. on shared boundary pages, take only the text belonging to the target scene;
3. remove mechanical page breaks only; do not alter wording, punctuation, labels or stage directions;
4. include `source_scan_pages` provenance in scene front matter;
5. propagate the scan 22 terminal hold into **Scene 5**; Scene 3 is clean after scan 20 was resolved as `வேணும்னாலும்`;
6. do not use OCR, TDL, Wikisource, another edition, grammar or context to repair source wording;
7. review all five assembled scenes against the page records;
8. write a durable assembly-review checkpoint, update README/page-map/HANDOVER/NEXT_CHAT_PROMPT, and commit atomically.

Do not start English translation in this iteration.
