# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and preserve newer durable state.

Permanent source-first workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

Historical-type authority:

1. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`;
2. `HISTORICAL_TAMIL_GLYPH_GATE.md`.

# CURRENT CHECKPOINT — இரத்தக் கண்ணீர் ACTIVE / SCANS 1–80 VERIFIED

Active work: `works/iratha-kanneer/`.

Controlling source: `TVA_BOK_0064189_இரத்தக்_கண்ணீர்.pdf`.

Source provenance: the user-supplied controlling PDF was downloaded from the **Tamil Digital Library (TDL)**. The TDL catalogue/record documents provenance for this exact supplied source; it is **not an independent secondary textual witness** and must not be treated as one.

Current durable state:

- P0 source intake: **PASS**;
- physical scans: **188 / 188 confirmed**;
- canonical page transcription: **80 / 188**;
- initial visual verification: **80 / 188**;
- historical-glyph H-GATE: **80 / 188**;
- final verified pages: **80 / 188**;
- contiguous final-verified range: **scans 1–80**;
- Batches 01–08: **PASS / COMPLETE**;
- Batch 08: **PASS / COMPLETE / LOCKED FOR CURRENT SOURCE EVIDENCE**;
- historical-glyph corrections recorded: **20**;
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
6. `works/iratha-kanneer/README.md`;
7. `works/iratha-kanneer/metadata/source.md`;
8. `works/iratha-kanneer/indexes/page-map.md`;
9. `works/iratha-kanneer/HISTORICAL_GLYPH_AUDIT.md`;
10. `BATCH_01_REVIEW.md` through `BATCH_08_REVIEW.md`;
11. relevant page records through `pages/0080.md`.

Resolve the controlling PDF before page-level visual work. Do not substitute OCR, web text, later editions or memory for source pixels.

## Source identity

- title **இரத்தக் கண்ணீர்**;
- author **மு. கருணாநிதி**;
- publisher **திராவிடப் பண்ணை**;
- edition **முதல் பதிப்பு — 1953**;
- SHA-256 `120428985bd327456df46b9e06271896b106332711f4c9063d4f0c7fe72b6441`;
- size **319,220,349 bytes**;
- image-only; source PDF not committed.

## Verified structural evidence through scan 80

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
- Scene 21: scans 76–80.

Do not declare a final whole-work scene inventory until the page layer closes.

## Historical-glyph gate

Required order:

**canonical transcription → initial visual verification → H-GATE → final verification.**

Mandatory minimum family set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`.

The list is a minimum, not a closed universe: Batch 05 additionally confirmed historical `ளா` look-alikes. Source pixels control. No global replacement. No grammar/spelling modernization. Same-edition comparison is preferred for doubtful clusters. Unresolved identity stays `needs-review`.

## Historical-glyph corrections through scan 80

Twenty corrections are durably recorded in `works/iratha-kanneer/HISTORICAL_GLYPH_AUDIT.md`.

Batch-08 additions:

19. scan 77 `மலபோல்` → `மலைபோல்` (`லை`);
20. scan 78 `வீரனில்ல` → `வீரனில்லை` (`லை`).

Scan 75 `அவனை` (`னை`) was adjudicated before its canonical page record was committed and reconfirmed during the full Batch-08 H-GATE, so it does not increase the correction count. Scan 72 `நானோ` is a secure positive same-edition `னோ` witness.

Batch 08 also corrected ordinary source-transcription mismatches during enlarged source reconciliation. Those are documented in `works/iratha-kanneer/BATCH_08_REVIEW.md` and remain separate from the historical-glyph correction count.

## Exact next activity — Batch 09 / scans 81–90

Process scans **81–90** as the next ten-scan page batch:

1. resolve the controlling PDF and inspect native/enlarged source pixels;
2. create `pages/0081.md` through `0090.md` with direct source transcription;
3. complete ordinary initial visual verification;
4. run the separate full H-GATE on every page, covering the mandatory family set plus any additional historical look-alikes;
5. preserve source spelling, punctuation, scene structure and physical scan-boundary continuations; no global replacement or silent modernization;
6. promote only clean pages to final `verified`;
7. create `BATCH_09_REVIEW.md` and synchronize `indexes/page-map.md`, `HISTORICAL_GLYPH_AUDIT.md`, READMEs, this handover and `NEXT_CHAT_PROMPT.md`;
8. fetch and report final live `main` SHA.

Do not begin scene assembly or English translation merely because Batch 09 completes.

# CLOSED WORK SAFEGUARDS

Keep completed `ஒரே முத்தம்` Tamil + English, `திருவாளர் தேசீயம்பிள்ளை`, `காகிதப்பூ`, `மணிமகுடம்`, and closed `கலைஞரின் நான்மணி மாலை` components closed unless explicitly reopened with genuinely new source evidence or a separately authorized phase.