# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and preserve newer durable state.

Permanent source-first workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

Historical-type authority:

1. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`;
2. `HISTORICAL_TAMIL_GLYPH_GATE.md`.

# CURRENT CHECKPOINT — இரத்தக் கண்ணீர் ACTIVE / SCANS 1–50 VERIFIED

Active work: `works/iratha-kanneer/`.

Controlling source: `TVA_BOK_0064189_இரத்தக்_கண்ணீர்.pdf`.

Current durable state:

- P0 source intake: **PASS**;
- physical scans: **188 / 188 confirmed**;
- canonical page transcription: **50 / 188**;
- initial visual verification: **50 / 188**;
- historical-glyph H-GATE: **50 / 188**;
- final verified pages: **50 / 188**;
- contiguous final-verified range: **scans 1–50**;
- Batches 01–05: **PASS / COMPLETE**;
- Batch 05: **PASS / COMPLETE / LOCKED FOR CURRENT SOURCE EVIDENCE**;
- historical-glyph corrections recorded: **13**;
- unresolved page-level source issues: **0**;
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
6. `works/iratha-kanneer/README.md`;
7. `works/iratha-kanneer/metadata/source.md`;
8. `works/iratha-kanneer/indexes/page-map.md`;
9. `works/iratha-kanneer/HISTORICAL_GLYPH_AUDIT.md`;
10. `BATCH_01_REVIEW.md` through `BATCH_05_REVIEW.md`;
11. relevant page records through `pages/0050.md`.

Resolve the controlling PDF before page-level visual work. Do not substitute OCR, web text, later editions or memory for source pixels.

## Source identity

- title **இரத்தக் கண்ணீர்**;
- author **மு. கருணாநிதி**;
- publisher **திராவிடப் பண்ணை**;
- edition **முதல் பதிப்பு — 1953**;
- SHA-256 `120428985bd327456df46b9e06271896b106332711f4c9063d4f0c7fe72b6441`;
- size **319,220,349 bytes**;
- image-only; source PDF not committed.

## Verified structural evidence through scan 50

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
- Scene 13: begins scan 50 and continues.

Do not declare a final whole-work scene inventory until the page layer closes.

## Historical-glyph gate

Required order:

**canonical transcription → initial visual verification → H-GATE → final verification.**

Mandatory minimum family set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`.

The list is a minimum, not a closed universe: Batch 05 additionally confirmed historical `ளா` look-alikes. Source pixels control. No global replacement. No grammar/spelling modernization. Same-edition comparison is preferred for doubtful clusters. Unresolved identity stays `needs-review`.

## Historical-glyph corrections through scan 50

Thirteen corrections are durably recorded in `works/iratha-kanneer/HISTORICAL_GLYPH_AUDIT.md`.

Latest Batch-05 additions on scan 48:

11. `முத்தன் வருவானு?` → `முத்தன் வருவானா?` (`னா`);
12. `முயன்றுள்` → `முயன்றாள்` (supplemental historical `ளா`);
13. `அலறினுள்` → `அலறினாள்` (supplemental historical `ளா`).

These were established by enlarged source pixels and same-edition family evidence, not grammar. Do not regress earlier corrections.

## Exact next activity — scans 51–60 / Batch 06

Process physical scans **51–60**:

1. create `pages/0051.md` through `0060.md`;
2. transcribe directly from source pixels;
3. perform initial visual verification;
4. run post-verification H-GATE on the full minimum family set plus any additional historical look-alike that appears;
5. promote only clean H-GATE-passed pages to final `verified`;
6. record every glyph correction / unresolved locus;
7. create `BATCH_06_REVIEW.md` only after all ten scans complete the gate;
8. update page map, glyph audit, work/root README, handover and next prompt;
9. fetch final live `main` SHA.

Do not begin scene assembly or English translation merely because a page batch completes.

# CLOSED WORK SAFEGUARDS

Keep completed `ஒரே முத்தம்` Tamil + English, `திருவாளர் தேசீயம்பிள்ளை`, `காகிதப்பூ`, `மணிமகுடம்`, and closed `கலைஞரின் நான்மணி மாலை` components closed unless explicitly reopened.