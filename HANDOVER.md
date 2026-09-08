# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and preserve newer durable state.

Permanent source-first workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

Historical-type authority:

1. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`;
2. `HISTORICAL_TAMIL_GLYPH_GATE.md`.

# CURRENT CHECKPOINT — இரத்தக் கண்ணீர் ACTIVE / SCANS 1–30 VERIFIED

Active work: `works/iratha-kanneer/`.

Controlling source: `TVA_BOK_0064189_இரத்தக்_கண்ணீர்.pdf`.

Current durable state:

- P0 source intake: **PASS**;
- physical scans: **188 / 188 confirmed**;
- canonical page transcription: **30 / 188**;
- initial visual verification: **30 / 188**;
- historical-glyph H-GATE: **30 / 188**;
- final verified pages: **30 / 188**;
- contiguous final-verified range: **scans 1–30**;
- Batch 01: **PASS / COMPLETE**;
- Batch 02: **PASS / COMPLETE**;
- Batch 03: **PASS / COMPLETE / LOCKED FOR CURRENT SOURCE EVIDENCE**;
- historical-glyph corrections recorded: **8**;
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
10. `BATCH_01_REVIEW.md`, `BATCH_02_REVIEW.md`, `BATCH_03_REVIEW.md`;
11. relevant page records.

Resolve the controlling PDF before page-level visual work. Do not substitute OCR, web text, later editions or memory for source pixels.

## Source identity

- title **இரத்தக் கண்ணீர்**;
- author **மு. கருணாநிதி**;
- publisher **திராவிடப் பண்ணை**;
- edition **முதல் பதிப்பு — 1953**;
- SHA-256 `120428985bd327456df46b9e06271896b106332711f4c9063d4f0c7fe72b6441`;
- size **319,220,349 bytes**;
- image-only; source PDF not committed.

## Verified structural evidence through scan 30

- Scene 1: scans 8–13;
- Scene 2: scans 14–18;
- Scene 3: scans 19–21;
- Scene 4: scans 22–25;
- Scene 5: scans 26–29;
- Scene 6: scan 30 only.

Do not declare a final whole-work scene inventory until the page layer closes.

## Historical-glyph gate

Required order:

**canonical transcription → initial visual verification → H-GATE → final verification.**

Minimum family set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`.

Source pixels control. No global replacement. No grammar/spelling modernization. Same-edition comparison is preferred for doubtful clusters. Unresolved identity stays `needs-review`.

## Historical-glyph corrections through scan 30

1. scan 9: `வயதுடையவனு அல்லது கிழவனு` → `வயதுடையவனா அல்லது கிழவனா` (`னா`);
2. scan 11: `அஞ்சல் மண்ணில்` → `அஞ்சல் மனையில்` (`னை`);
3. scan 12: `அஞ்சல் மண்` → `அஞ்சல் மனை` (`னை`);
4. scan 16: `அஞ்சல் மண்` → `அஞ்சல் மனை` (`னை`);
5. scan 17: `மருத்துவக் கிழவனூர்` → `மருத்துவக் கிழவனார்` (`னா`);
6. scan 18: `ஏன் வந்தேனு?` → `ஏன் வந்தேனா?` (`னா`);
7. scan 21: `சரிதானு?` → `சரிதானா?` (`னா`);
8. scan 29: `பெண்ணு பெற்று வைத்திருக்கிறாய்` → `பெண்ணை பெற்று வைத்திருக்கிறாய்` (`ணை`), proven by same-edition `ணை` evidence rather than grammar.

## Exact next activity — scans 31–40 / Batch 04

Process physical scans **31–40**:

1. create `pages/0031.md` through `0040.md`;
2. transcribe directly from source pixels;
3. perform initial visual verification;
4. run post-verification H-GATE on the full family set;
5. promote only clean H-GATE-passed pages to final `verified`;
6. record every glyph correction / unresolved locus;
7. create `BATCH_04_REVIEW.md` only after all ten scans complete the gate;
8. update page map, glyph audit, work/root README, handover and next prompt;
9. fetch final live `main` SHA.

Do not begin scene assembly or English translation merely because a page batch completes.

# CLOSED WORK SAFEGUARDS

Keep completed `ஒரே முத்தம்` Tamil + English, `திருவாளர் தேசீயம்பிள்ளை`, `காகிதப்பூ`, `மணிமகுடம்`, and closed `கலைஞரின் நான்மணி மாலை` components closed unless explicitly reopened.