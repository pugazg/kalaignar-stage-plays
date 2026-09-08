# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and preserve newer durable state.

Permanent source-first workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

Historical-type authority for the active work:

1. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`;
2. `HISTORICAL_TAMIL_GLYPH_GATE.md`.

# CURRENT CHECKPOINT — இரத்தக் கண்ணீர் ACTIVE / SCANS 1–20 VERIFIED

Active work path: `works/iratha-kanneer/`.

Controlling source: `TVA_BOK_0064189_இரத்தக்_கண்ணீர்.pdf`.

Current durable state:

- P0 source intake: **PASS**;
- raw physical range: **188 / 188 scans confirmed**;
- canonical page transcription: **20 / 188**;
- initial visual verification: **20 / 188**;
- historical-glyph H-GATE: **20 / 188**;
- final verified pages: **20 / 188**;
- contiguous final-verified range: **scans 1–20**;
- Batch 01: **PASS / COMPLETE**, including retrospective scan-9 correction/re-pass;
- Batch 02: **PASS / COMPLETE / LOCKED FOR CURRENT SOURCE EVIDENCE**;
- historical-glyph corrections recorded: **6**;
- unresolved page-level source issues: **0**;
- structural / scene assembly: **not started / blocked on page layer**;
- English translation: **not authorized / not started**.

The conversation file preview exposes only **150** page images. Direct raw-PDF inspection established **188 physical scans**. The raw PDF count controls; never stop at preview page 150.

## Mandatory startup before further இரத்தக் கண்ணீர் work

Read completely:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`;
2. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`;
3. `HISTORICAL_TAMIL_GLYPH_GATE.md`;
4. this `HANDOVER.md`;
5. `NEXT_CHAT_PROMPT.md`;
6. `works/iratha-kanneer/README.md`;
7. `works/iratha-kanneer/metadata/source.md`;
8. `works/iratha-kanneer/indexes/page-map.md`;
9. `works/iratha-kanneer/HISTORICAL_GLYPH_AUDIT.md`;
10. `works/iratha-kanneer/BATCH_01_REVIEW.md`;
11. `works/iratha-kanneer/BATCH_02_REVIEW.md`;
12. relevant page records.

Resolve / attach the controlling PDF before source-dependent page work. Do not substitute OCR, web text, later editions or memory for source pixels.

## Source identity

- title: **இரத்தக் கண்ணீர்**;
- author as printed: **மு. கருணாநிதி**;
- publisher: **திராவிடப் பண்ணை**;
- title-page location: **தெப்பக்குளம் :: திருச்சி**;
- edition: **முதல் பதிப்பு — 1953**;
- source-visible price: **ரூ. 2-0-0.**;
- SHA-256: **`120428985bd327456df46b9e06271896b106332711f4c9063d4f0c7fe72b6441`**;
- size: **319,220,349 bytes**;
- physical scans: **188**;
- image-only: **yes**;
- source PDF committed to repository: **no**.

Internal front-matter dates are separately preserved:

- scan 4 `பதிப்புரை` — **14-4-1948**;
- scan 5 `முன்னுரை` — **20-11-53**, `திருச்சி மத்திய சிறை`, signed `மு. கருணாநிதி`.

Do not promote the 1948 internal date over the source-visible 1953 first-edition statement.

## Verified structural evidence through scan 20

- scan 8 — Scene 1 begins: `காட்சி 1]` / `[பழுதூர்`;
- scan 13 — Scene 1 closes with centred star;
- scan 14 — Scene 2 begins: `காட்சி—2]` / `[பழுதூர் மடாலயம்`;
- scan 18 — Scene 2 closes with centred star;
- scan 19 — Scene 3 begins: `காட்சி 3]` / `[பழுதூரின் தெரு`;
- scan 20 — Scene 3 continues.

Late intake spot checks remain:

- scan 180 — `காட்சி 59]`;
- scan 183 — `காட்சி 60]`;
- scan 184 — `காட்சி 61]`;
- scan 186 — `முடிவு` / closing prose;
- scan 187 — publisher catalogue advertisement;
- scan 188 — back wrapper / `திராவிடப் பண்ணை` device.

Do **not** declare a final whole-work scene inventory yet. Page transcription / verification precedes scene-boundary closure.

# Mandatory post-initial-verification historical-glyph gate

The user explicitly directed that historical Tamil glyph checking occur **after initial verification**.

Required page pipeline:

**canonical transcription → initial visual verification → H-GATE historical Tamil glyph audit → final page verification.**

Initial verification alone is not final `verified`.

Mandatory minimum family set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Permanent rules:

- source pixels control character identity;
- inspect complete page / complete glyph cluster at enlarged/native resolution;
- compare clearer same-edition witnesses when needed;
- OCR / grammar / familiar spelling / context are not proof;
- encode proven historical character identity into modern Unicode without modernizing source wording;
- no global replacement;
- unresolved glyph identity remains `needs-review`;
- `blocked` only after source-condition escalation is exhausted;
- historical-glyph corrections are logged separately from ordinary transcription corrections.

## Historical-glyph correction record through scan 20

Six corrections are durably recorded:

1. scan 9: `வயதுடையவனு அல்லது கிழவனு` → `வயதுடையவனா அல்லது கிழவனா` (`னா`), retrospectively reopened and re-passed after user correction;
2. scan 11: `அஞ்சல் மண்ணில்` → `அஞ்சல் மனையில்` (`னை`);
3. scan 12: `அஞ்சல் மண்` → `அஞ்சல் மனை` (`னை`);
4. scan 16: `அஞ்சல் மண்` → `அஞ்சல் மனை` (`னை`);
5. scan 17: `மருத்துவக் கிழவனூர்` → `மருத்துவக் கிழவனார்` (`னா`);
6. scan 18: `ஏன் வந்தேனு?` → `ஏன் வந்தேனா?` (`னா`).

These are character-identity corrections only. They do not authorize lexical, grammatical, spelling or punctuation modernization elsewhere.

## Exact next activity — scans 21–30

Process physical scans **21–30** as Batch 03:

1. create `works/iratha-kanneer/pages/0021.md` through `0030.md`;
2. transcribe each scan directly from source pixels;
3. perform initial visual verification;
4. after initial verification, run H-GATE on the full minimum family set;
5. promote only clean H-GATE-passed pages to final `verified`;
6. leave unresolved pages `needs-review` / `blocked` only as source evidence supports;
7. record every historical-glyph correction with scan, apparent reading, source-supported reading and family;
8. create `works/iratha-kanneer/BATCH_03_REVIEW.md` only after the batch gate is complete;
9. update page map, glyph audit, work/root README, this handover and `NEXT_CHAT_PROMPT.md`;
10. fetch final live `main` SHA.

Do not begin scene assembly or English translation merely because a page batch completes.

# CLOSED WORK SAFEGUARDS

The completed `ஒரே முத்தம்` Tamil + English workflows remain **CLOSED**. Also keep `திருவாளர் தேசீயம்பிள்ளை`, `காகிதப்பூ`, `மணிமகுடம்`, and closed `கலைஞரின் நான்மணி மாலை` components closed unless the user separately reopens them with new evidence / a named phase.