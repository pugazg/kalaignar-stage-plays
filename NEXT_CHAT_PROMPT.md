# Next Chat Prompt — நச்சுக்கோப்பை final Tamil scene consistency audit

Continue directly in `pugazg/kalaignar-stage-plays`, branch `main`, active work `works/nachuk-koppai/`.

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first and preserve newer durable work.

## Durable state

- canonical page layer: **63 / 63 reconciled**;
- verified pages: **62 / 63**;
- sole terminal page-layer hold: **scan 22**;
- Tamil scenes assembled / reviewed: **18 / 18 COMPLETE**;
- clean scenes: **17 / 18**;
- hold-bearing scene: **Scene 5 only**, inheriting scan 22;
- scene assembly iteration rule: **up to 15 scenes per iteration**;
- scan 20: **`வேணும்னாலும்` verified**;
- scan 35: **`சுடகோடி` verified**;
- final Scene 18 includes source-visible **`முற்றும்`**;
- English translation: **not started / blocked until final Tamil scene consistency audit closes**;
- P0 SHA-256: **pending / separate hold**.

## Exact next activity

Perform the **full 18-scene assembly consistency audit / Tamil scene-layer closure review**.

Check:

1. all `scenes/01.md` through `18.md` are present;
2. each scene's `source_scan_pages` matches the reconciled scene-to-scan map;
3. shared pages are split only at source-visible scene headings, with no duplicated or omitted dramatic text;
4. documented mechanical joins are correct, especially:
   - Scene 2: `மண்` + `ணில்` → `மண்ணில்`;
   - Scene 2: `செய்` + `திட்டான்` → `செய்திட்டான்`;
   - Scene 12: `எத்` + `தனையோ` → `எத்தனையோ`;
   - Scene 16: `விப` + `சாரமா?` → `விபசாரமா?`;
   - Scene 18: `அறிஞர் அண்ணா` + `வின்` → `அறிஞர் அண்ணாவின்`;
5. Scene 5 alone retains the scan-22 source-cluster hold and the user's song/performance interpretation only as a note;
6. running headers, accession marks and printer imprint are excluded appropriately;
7. Scene 18 retains `முற்றும்` but excludes non-authorial `4063` and the printer imprint from the dramatic body;
8. write the final Tamil scene consistency / closure record, update README/page-map/HANDOVER/NEXT_CHAT_PROMPT, and commit atomically.

Do not start English translation in this iteration.
