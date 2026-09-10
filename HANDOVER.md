# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and preserve newer durable state.

Permanent source-first workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

Historical-type authority:

1. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`;
2. `HISTORICAL_TAMIL_GLYPH_GATE.md`.

Active-work anti-loop authority: `works/iratha-kanneer/BATCH_EXECUTION_WORKFLOW.md`.

# CURRENT CHECKPOINT — இரத்தக் கண்ணீர் ACTIVE / SCANS 1–130 VERIFIED

Active work: `works/iratha-kanneer/`.

Controlling source: `TVA_BOK_0064189_இரத்தக்_கண்ணீர்.pdf`.

Source provenance: the user-supplied controlling PDF was downloaded from the **Tamil Digital Library (TDL)**. The TDL catalogue and Wikisource transport copy refer to this same scan set; they are **not independent secondary textual witnesses**. When the exact PDF is attached/readable locally, routine transcription and verification must use the local controlling PDF directly.

Current durable state:

- P0 source intake: **PASS**;
- physical scans: **188 / 188 confirmed**;
- canonical page transcription: **130 / 188**;
- initial visual verification: **130 / 188**;
- historical-glyph H-GATE: **130 / 188**;
- final verified pages: **130 / 188**;
- contiguous final-verified range: **scans 1–130**;
- Batches 01–13: **PASS / COMPLETE**;
- Batch 13: **PASS / COMPLETE / LOCKED FOR CURRENT SOURCE EVIDENCE**;
- historical-glyph corrections recorded: **29**;
- unresolved page-level source issues: **0**;
- `needs-review`: **0**;
- `blocked`: **0**;
- structural / scene assembly: **not started / blocked on page layer**;
- English translation: **not authorized / not started**.

The conversation preview exposes only 150 images; direct raw-PDF inspection established **188 physical scans**. Never stop at preview page 150.

## Mandatory startup

Read completely before source-dependent work:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`;
2. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`;
3. `HISTORICAL_TAMIL_GLYPH_GATE.md`;
4. this `HANDOVER.md`;
5. `NEXT_CHAT_PROMPT.md`;
6. `works/iratha-kanneer/BATCH_EXECUTION_WORKFLOW.md`;
7. `works/iratha-kanneer/README.md`;
8. `works/iratha-kanneer/metadata/source.md`;
9. `works/iratha-kanneer/indexes/page-map.md`;
10. `works/iratha-kanneer/HISTORICAL_GLYPH_AUDIT.md`;
11. `BATCH_01_REVIEW.md` through `BATCH_13_REVIEW.md`;
12. relevant page records through `pages/0130.md`.

Resolve / attach the exact controlling PDF before source-dependent page work. If it is locally readable, do not detour to TDL/Wikisource for routine transcription or verification.

## Source identity

- title **இரத்தக் கண்ணீர்**;
- author **மு. கருணாநிதி**;
- publisher **திராவிடப் பண்ணை**;
- edition **முதல் பதிப்பு — 1953**;
- SHA-256 `120428985bd327456df46b9e06271896b106332711f4c9063d4f0c7fe72b6441`;
- size **319,220,349 bytes**;
- image-only; source PDF not committed.

## Mandatory efficient batch workflow

For this work, each routine ten-scan batch follows a hard two-commit boundary:

1. **Pass A:** whole-page source read once from the local controlling PDF; canonical transcription + physical joins/scene structure + ordinary visual verification;
2. **durable Pass-A commit:** persist every processed page as `needs-review`, `initial_verification: passed`, `historical_glyph_gate: pending` before beginning H-GATE;
3. **Pass B:** targeted independent H-GATE only — mandatory historical families plus actual candidate/source-sensitive loci and joins; do not retranscribe settled prose;
4. create crops/enhancements only for a genuine unresolved locus and stop once resolved/held;
5. **final closure commit:** promote clean pages to `verified`, create batch review, synchronize controls.

Short rule:

> **Local PDF → Pass A once → commit → targeted H-GATE → final commit. No external detour and no settled-text loop.**

## Verified structural evidence through scan 130

- Scene 1: scans 8–13;
- Scene 2: scans 14–18;
- Scene 3: scans 19–21;
- Scene 4: scans 22–25;
- Scene 5: scans 26–29;
- Scene 6: scan 30 only;
- Scene 7: scans 31–33;
- Scene 8: scans 34–39;
- Scene 9: scans 40–41;
- Scene 10: scans 42–44;
- Scene 11: scans 45–46;
- Scene 12: scans 47–49;
- Scene 13: scans 50–51;
- Scene 14: scans 52–53;
- Scene 15: scans 54–57;
- Scene 16: scans 58–62;
- Scene 17: scans 63–65;
- Scene 18: scans 66–67;
- Scene 19: scan 68 only;
- Scene 20: scans 69–75;
- Scene 21: scans 76–80;
- Scene 22: scan 81 only;
- Scene 23: scans 82–83;
- Scene 24: scan 84 only;
- Scene 25: scans 85–88;
- Scene 26: scans 89–90;
- Scene 27: scans 91–94;
- Scene 28: scans 95–96;
- Scene 29: scans 97–98;
- Scene 30: scans 99–100;
- Scene 31: scans 101–104;
- Scene 32: scans 105–106;
- Scene 33: scan 107 only;
- Scene 34: scans 108–110;
- Scene 35: scans **111–115**, centred close-star on scan 115;
- Scene 36: scans **116–122**, centred close-star on scan 122;
- Scene 37: opens scan **123**, verified through **130**, and continues into scan **131**.

Scan 130 preserves the physical split `புறப்` → scan 131 `படுகின்றனர்.`. Scan 131 was inspected during Batch 13 **only** to establish that boundary and confirm the Scene-37 close; it is **not** a verified Batch-13 page and must be fully processed in Batch 14.

Do not declare a final whole-work scene inventory until the page layer closes.

## Historical-glyph gate

Required order:

**canonical transcription → initial visual verification → H-GATE → final verification.**

Mandatory minimum family set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`.

The list is a minimum, not a closed universe: Batch 05 additionally confirmed historical `ளா` look-alikes. Source pixels control. No global replacement. No grammar/spelling modernization. Same-edition comparison is preferred for doubtful clusters. Unresolved identity stays `needs-review`.

## Historical-glyph corrections through scan 130

Twenty-nine corrections are durably recorded in `works/iratha-kanneer/HISTORICAL_GLYPH_AUDIT.md`.

Batch 13 added six new loci:

24. scan 122 `இருப்பானு?` → `இருப்பானா?` (`னா`);
25. scan 124 first `கண்ணுடி` → `கண்ணாடி` (`ணா`);
26. scan 124 second `கண்ணுடி` → `கண்ணாடி` (`ணா`);
27. scan 127 `கண்ணுடியிடம்` → `கண்ணாடியிடம்` (`ணா`);
28. scan 130 `பெண்ணுகவும்` → `பெண்ணாகவும்` (`ணா`);
29. scan 130 `ஆணுகவும்` → `ஆணாகவும்` (`ணா`).

These were targeted character-identity adjudications from the controlling source, not lexical/grammar modernization.

## Batch 13 durable state

- `BATCH_13_PASS_A.md` records Pass-A completion before H-GATE;
- `pages/0121.md` through `pages/0130.md` are final `verified`;
- `BATCH_13_REVIEW.md` is **PASS / COMPLETE / LOCKED**;
- page map, glyph audit, work/root READMEs, this handover, and `NEXT_CHAT_PROMPT.md` are synchronized to the 130-page checkpoint.

## Exact next activity — Batch 14 / scans 131–140

Process scans **131–140** as the next ten-scan page batch:

1. use the attached/local controlling PDF directly;
2. Pass A: read each whole page once and create `pages/0131.md` through `0140.md`;
3. scan 131 begins with continuation `படுகின்றனர்.` from scan 130 and closes Scene 37 with a centred star; process the entire page and do not treat the prior boundary-only inspection as verification;
4. immediately commit the Pass-A page records with H-GATE pending;
5. Pass B: run only the targeted independent H-GATE on the mandatory family set plus actual candidate/source-sensitive loci and physical joins; do not retranscribe settled prose;
6. create crops only for genuine unresolved character identity;
7. promote clean pages to final `verified`; leave true unresolved identity as `needs-review`;
8. create `BATCH_14_REVIEW.md`, synchronize page map, glyph audit, READMEs, this handover and `NEXT_CHAT_PROMPT.md`;
9. fetch and report final live `main` SHA.

Do not begin scene assembly or English translation merely because Batch 14 completes.

# CLOSED WORK SAFEGUARDS

Keep completed `ஒரே முத்தம்` Tamil + English, `திருவாளர் தேசீயம்பிள்ளை`, `காகிதப்பூ`, `மணிமகுடம்`, and closed `கலைஞரின் நான்மணி மாலை` components closed unless explicitly reopened with genuinely new source evidence or a separately authorized phase.
